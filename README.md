# Previsão de Preços de Imóveis usando Regressão

## 📌 Sobre o Projeto
O mercado imobiliário desempenha um papel crucial na economia global, sendo influenciado por diversos fatores, como localização, infraestrutura, tamanho das propriedades e condições socioeconômicas. A previsão precisa de preços de imóveis é essencial para compradores, vendedores e investidores, permitindo tomadas de decisão mais informadas e estratégicas.

Com o avanço das ferramentas de análise de dados, técnicas de regressão emergiram como soluções eficazes para modelar as relações entre variáveis preditoras e o preço final dos imóveis. Este projeto tem como objetivo explorar o **Boston Housing Dataset**, um dos datasets clássicos para estudo de previsão de preços, aplicando algoritmos de regressão para modelagem preditiva e análise de impacto das variáveis envolvidas.

## 🎯 Objetivos
- Construir modelos preditivos para prever o preço médio dos imóveis em diferentes regiões com base no **Boston Housing Dataset**.
- Aplicar algoritmos de regressão para identificar relações entre variáveis como taxa de criminalidade, proximidade ao rio Charles, número de quartos e preço final das casas.
- Avaliar a acurácia dos modelos utilizando métricas como **Mean Squared Error (MSE)** e **R² Score**.

## 📂 Estrutura do Repositório
```
📂 previsao-precos-imoveis
│── 📜 README.md              # Documentação do projeto
│── 📜 requirements.txt       # Dependências do projeto
│── 📂 data/                  # Conjunto de dados
    ├── processed_data.csv    # Base de dados processada
│── 📂 notebook/             # Notebooks para análise
    ├── 📜 boston.ipynb      # Notebook único do projeto
```

## 🛠 Tecnologias Utilizadas
- **Linguagem:** Python 🐍
- **Bibliotecas:**
  - `pandas` → Manipulação e análise de dados
  - `numpy` → Operações numéricas eficientes
  - `matplotlib` e `seaborn` → Visualização de dados e gráficos
  - `kagglehub` → Acesso a datasets do Kaggle
  - `scikit-learn` → Algoritmos de machine learning para regressão e seleção de atributos
  - `SimpleImputer` → Tratamento de valores ausentes
  - `SelectKBest` e `f_regression` → Seleção de atributos mais relevantes

### 🔍 Modelos Utilizados
- **Regressão Linear**
- **Ridge Regression**
- **Lasso Regression**
- **ElasticNet Regression**
- **Random Forest Regressor**

## 📊 Fonte dos Dados
O dataset utilizado no projeto é o [Boston Housing Dataset](https://www.kaggle.com/datasets/altavish/boston-housing-dataset), amplamente utilizado para estudos de regressão e machine learning. Ele contém 14 variáveis que representam diversos aspectos socioeconômicos e estruturais de diferentes bairros de Boston. A variável-alvo (**MEDV**) representa o preço médio das residências ocupadas pelos proprietários, medido em milhares de dólares.