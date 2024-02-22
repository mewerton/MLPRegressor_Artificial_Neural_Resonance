# MLPRegressor_Artificial_Neural_Resonance

Este código realiza o treinamento de nove modelos de Regressão com uma Rede Neural Artificial (RNA) utilizando a biblioteca MLPRegressor do scikit-learn em Python. Cada modelo possui uma configuração diferente de número de neurônios na camada oculta e função de ativação. Os modelos são treinados utilizando um dataset específico carregado do Google Drive, com as entradas normalizadas usando StandardScaler.

Após o treinamento, são apresentadas informações sobre cada modelo, como o número de neurônios na camada oculta, a função de ativação, a perda final e o número de épocas de treinamento. Além disso, são exibidos gráficos de curva de perda para alguns dos modelos e métricas de avaliação, como o Erro Médio Absoluto (MAE), o Erro Quadrático Médio (MSE), o Erro Quadrático Médio da Raiz (RMSE), o Erro Percentual Absoluto Médio (MAPE) e o Coeficiente de Determinação (R2 Score).

Por fim, os resultados dos treinamentos são organizados em uma tabela, que inclui informações sobre o número de neurônios, a função de ativação, a perda final, o número de épocas e um ranking da melhor configuração com base na perda final.

Este código pode ser útil para experimentar diferentes configurações de RNAs em problemas de regressão e comparar seu desempenho usando métricas de avaliação.
