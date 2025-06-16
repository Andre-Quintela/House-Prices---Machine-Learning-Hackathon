# 🏠 House Prices - Machine Learning Hackathon

Este projeto foi desenvolvido como parte da Avaliação C3 da disciplina **Data Analysis and Machine Learning** na FAESA, sob orientação do Prof. Howard Roatti. O desafio consistiu em realizar uma análise completa de dados de preços de casas nos Estados Unidos e aplicar diferentes técnicas de Aprendizado de Máquina, tanto supervisionadas quanto não supervisionadas.

## 🎯 Objetivo

Explorar um conjunto de dados públicos de preços de casas com o objetivo de prever o valor de venda utilizando modelos de regressão. Além disso, foram exploradas técnicas de classificação e agrupamento de dados, com foco no desenvolvimento das habilidades práticas em Data Science.

## 📁 Dataset

O dataset utilizado está disponível no Kaggle:

🔗 [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

O conjunto de dados contém características detalhadas das casas (como número de quartos, área, ano de construção, entre outras) e seus respectivos preços de venda.

## 🧪 Etapas Realizadas

### 1. 🔍 Análise Exploratória de Dados (EDA)
- Análise das variáveis numéricas e categóricas
- Verificação e tratamento de valores ausentes
- Identificação de outliers
- Visualizações com gráficos de dispersão, histograma, heatmap de correlação, etc.

### 2. 🛠 Feature Engineering
- Criação de novas variáveis
- Transformações logarítmicas
- Codificação de variáveis categóricas
- Normalização e padronização de dados

### 3. 📈 Aprendizado Supervisionado
- **Regressão Linear Múltipla**: utilizada para prever o preço de venda da casa.
- **Classificação Binária**: os preços foram transformados em "alto" ou "baixo" com base na mediana, e foram testados modelos como:
  - KNN
  - Random Forest
  - Regressão Logística

### 4. 📉 Aprendizado Não Supervisionado
- **Clusterização**: aplicação do algoritmo KMeans para agrupar casas com características semelhantes.
- **Redução de Dimensionalidade**: uso do PCA (Principal Component Analysis) para visualização dos dados em 2D.
- **Análise de Outliers**: identificação de pontos fora do padrão utilizando o algoritmo Local Outlier Factor (LOF).

### 5. 📊 Métricas e Avaliação
- R², MAE, RMSE para regressão
- Acurácia, matriz de confusão, F1-score para classificação
- Visualização dos clusters e dos componentes principais

## 🖼 Visualizações

Foram utilizadas bibliotecas como `Matplotlib`, `Seaborn` e `Plotly` para construção de gráficos que ilustram os resultados dos modelos e insights da análise.

## 🗃 Estrutura do Projeto
Hackathon/ <br>
│ <br>
├── Hackathon.ipynb # Jupyter Notebook principal com todo o desenvolvimento <br>
├── README.md # Este arquivo <br>
└── train.csv

## 👥 Autoria

Este projeto foi desenvolvido por:

- [André Quintela]
- [Guilherme Ambrosio]
