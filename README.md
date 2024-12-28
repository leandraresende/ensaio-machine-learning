A empresa Data Money fornece serviços de consultoria de Análise e Ciência de Dados para grandes empresas no Brasil e no exterior. Seu principal diferencial está no treinamento e ajuste fino dos algoritmos de Machine Learning que faz com que a performance dos mesmos gere alto retorno financeiro.

Para continuar crescendo a expertise do time, os Cientistas de Dados acreditam que é extremamente importante realizar ensaios nos algoritmos de Machine Learning para adquirir uma experiência cada vez maior sobre o seu funcionamento e estudar a mudança de comportamento da performance para diferentes valores de hiperparâmetros.

A tarefa será realizar ensaios com algoritmos de Classificação, Regressão e Clusterização, a fim de extrair aprendizados sobre o seu funcionamento em determinados cenários. Cada algoritmo será treinado com os dados de treinamento e sua performance será medida usando três conjuntos de dados: treinamento, validação e teste. A performance de cada algoritmo será medida utilizando diferentes métricas. 

## 1. Os algoritmos e métricas do ensaio

Classificação:

    Algoritmos: KNN, Decision Tree, Random Forest e Logistic Regression

    Métricas de performance: Accuracy, Precision, Recall e F1-Score

Regressão:

    Algoritmos: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polinomial Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net, Polinomial Regression Lasso, Polinomial Regression Ridge e Polinomial Regression Elastic Net

    Métricas de performance: R2, MSE, RMSE, MAE e MAPE

Clusterização:

    Algoritmos: K-Means e Affinity Propagation
   
    Métricas de performance: Silhouette Score

## 2. Estratégia da solução
Os códigos foram escritos utilizando a linguagem Python e seus principais parâmetros de ajuste de overfitting foram variados observando a métrica final. O conjunto de valores que fizeram os algoritmos alcançarem a melhor performance, serão aqueles escolhidos para o treinamento final do algoritmo.

### 2.1 O passo a passo
Passo 1: Divisão dos dados em treino, validação e teste.

Passo 2: Treinar o algoritmo com os dados de treinamento alterando os valores dos principais parâmetros que controlam o overfitting do algoritmo.

Passo 3: Com o conjunto de dados de treinamento, medir a performance do algoritmo treinado com os parâmetros escolhidos.

Passo 4: Com o conjunto de dados de validação, medir a performance do algoritmo treinado com os parâmetros escolhidos.

Passo 5: Unir os dados de treinamento e validação.

Passo 6: Retreinar o algoritmo com a união dos dados de treinamento e validação, utilizando os melhores valores para os 
parâmetros de controle do algoritmo.

Passo 7: Medir a performance do algoritmo treinado com os melhores parâmetros, utilizando o conjunto de dados de teste.

## 3. Resultados
Classificação:

Regressão:

Clusterização:


## 4. Top insights

1 - Os algoritmos baseados em árvores possuem uma performance melhor em todas as métricas, quando aplicados sobre os dados de teste, no ensaio de Classificação.

2 - A performance dos algoritmos de classificação sobre os dados de validação ficou bem próxima da performance sobre os dados de teste.

3 - Os algoritmos de regressão não apresentaram boas métricas de performance, o que mostra uma necessidade de uma seleção de atributos e uma preparação melhor das variáveis independentes do conjunto de dados.


## 5. Conclusão

Algoritmos baseados em árvores são sensíveis quanto à profundidade do crescimento e do número de árvores, fazendo com que a escolha correta desses valores impeçam os algoritmos de entrar no estado de overfitting.

Os algoritmos de regressão são sensíveis ao grau do polinômio. Esse parâmetro controla o limite entre o estado de underfitting e overfitting desses algoritmos.

Esse ensaio de Machine Learning foi muito importante para aprofundar o entendimento sobre o funcionamento de diversos algoritmos de classificação, regressão e clusterização e sobre os principais parâmetros de controle entre os estados de underfitting e overfitting.

## 6. Próximos passos

Como próximos passos desse ensaio, pretendo estudar novos algoritmos de Machine Learning e usar diferentes conjuntos de dados para aumentar o conhecimento sobre os algoritmos e quais cenários são mais favoráveis para o aumento da performance dos mesmos.
