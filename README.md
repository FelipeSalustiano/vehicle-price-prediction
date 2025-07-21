# 🚗 Vehicle Price Prediction

Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever o preço de veículos com base em diversas características, como marca, modelo, ano de fabricação, tipo de motor, quilometragem, entre outras. O trabalho foi desenvolvido em Python com foco em análise exploratória, pré-processamento e aplicação de diferentes algoritmos de regressão.

## 📊 Problema

Os preços de veículos podem variar bastante, e compreender os principais fatores que influenciam esses preços pode ser útil tanto para consumidores quanto para empresas do setor automotivo. Neste projeto, criamos um modelo preditivo para estimar o preço de um carro a partir de um conjunto de atributos.

---

## 🧠 Técnicas Utilizadas

- 📦 **Bibliotecas**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost.
- 🔍 **Análise Exploratória de Dados (EDA)**:
  - Verificação de nulos e outliers
  - Correlação entre variáveis
  - Visualizações com gráficos de dispersão, boxplots e heatmaps
- 🧹 **Pré-processamento de Dados**:
  - Codificação de variáveis categóricas (`LabelEncoder`)
  - Tratamento de nulos
  - Escalonamento de variáveis
- 🔨 **Modelos de Regressão**:
  - Regressão Linear
  - Ridge Regression
  - Random Forest Regressor
  - Gradient Boosting
  - XGBoost Regressor
- 📈 **Avaliação dos Modelos**:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Comparativo de desempenho entre os modelos

---


# 🔎 Resultados
Após testar diferentes modelos, o XGBoost Regressor foi o que apresentou o melhor desempenho, obtendo:

R² Score: 79.73

MAE: 4814.09

MSE: 62.230.090

Esses resultados mostram que o modelo é eficaz na tarefa de prever o preço dos veículos com boa precisão.


## 📌 Observações
Os dados utilizados foram obtidos do Kaggle e passaram por etapas de limpeza e transformação.
Link do Kaggle: https://www.kaggle.com/datasets/khwaishsaxena/vehicle-price-prediction-dataset



