# 1.Regressão e classificação

## Bibliotecas

### NumPy
Biblioteca que utiliza Arrays de N dimensões(na-arrays) e inúmeras operações matemáticas visando a velocidade e eficiência.

### Scikit-learn (sklearn)
Biblioteca fundamental para machine learning, construída sobre NumPy, SciPy e Matplotlib e fornece um conjunto consistente de ferramentas para a construção e avaliação de modelos de aprendizado de máquina.


## Funções

### Mean squaded error(Erro quadrático médio)
uma métrica de avaliação usada para medir o desempenho de um modelo de regressão. Ela quantifica a média dos quadrados das diferenças entre os valores previstos pelo modelo e os valores reais. Um valor de MSE menor indica que o modelo está fazendo previsões mais precisas.

A fórmula do Erro Quadrático Médio (MSE) é:

<img width="366" height="137" alt="image" src="https://github.com/user-attachments/assets/080f9dbe-85df-4852-adc1-7127dc8a0f27" />

 
Onde:

n é o número de pontos de dados.

Y 
i
​
  é o valor real (verdadeiro).

Y 
i
​
 
^
​
  (lê-se "Y-chapéu") é o valor previsto pelo modelo.

### train_test_split
Função que  recebe como entrada os dados a serem divididos (X, as características, e y, os rótulos) e os divide aleatoriamente de acordo com uma proporção especificada.

### Accuracy_score
Função de métrica de avaliação para problemas de classificação. Ela mede a precisão geral de um modelo, calculando a proporção de previsões corretas em relação ao número total de previsões.

A fórmula da acurácia é:
<img width="559" height="90" alt="image" src="https://github.com/user-attachments/assets/d95452f4-cf99-4326-9d47-05f3111ccff3" />


## Classes

### StandardScale
Tem a função de pré-processamento de dados.Padroniza as características transformando os dados de modo que cada característica tenha uma média de 0 e um desvio padrão de 1. Isso é feito subtraindo a média e dividindo pelo desvio padrão.

-fit(): Este método calcula a média e o desvio padrão de cada coluna nos dados de treinamento

-transform(): Este método aplica a transformação aos dados, usando a média e o desvio padrão calculados anteriormente.

## Modelos

### Regressão linear (LinearRegression)
Modelo de regressão usado para prever um valor contínuo com base em uma ou mais variáveis de entrada independentes. A relação entre as variáveis de entrada e a variável de saída pode ser representada por uma equação linear "y = ax + b", a qual busca encontrar os melhores valores para os coeficientes a e b que minimizem a distância entre a linha e os pontos de dados reais, geralmente usando o método dos mínimos quadrados.


### Regressão logística (LogisticRegression)
Modelo tipicamente usado em problemas de classificação, a qual é usada para prever resultados binários a partir de variáveis de entrada, a partir da aplicação da função sigmoide (ou logística) para transformar uma combinação linear de variáveis independentes numa probabilidade entre 0 e 1.


# 2. Métodos baseados em distância
