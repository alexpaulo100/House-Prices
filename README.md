# House Prices - Advanced Regression Techniques- Kaggle

Este projeto visa prever os preços de venda de casas em Ames, Iowa, com base em características como o número de quartos, tamanho da casa, localização, etc. O conjunto de dados utilizado é o famoso **"House Prices: Advanced Regression Techniques"** do **Kaggle**.

## Objetivo

O objetivo principal deste projeto é treinar modelos de aprendizado de máquina para prever o preço de venda de casas com base em um conjunto de variáveis de entrada. O modelo utiliza técnicas de regressão, como Árvores de Decisão, para fazer as previsões.

## Dados

Os dados utilizados neste projeto são provenientes do **Kaggle**, e podem ser encontrados no link abaixo:

[Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

**Descrição do Dataset**

O dataset contém as seguintes colunas principais:

   - **SalePrice**: Preço de venda da casa (variável alvo).
   - **OverallQual**: Qualidade geral da casa.
   - **GrLivArea**: Área da casa acima do nível do solo.
   - **TotRmsAbvGrd**: Total de cômodos acima do nível do solo.
   - **YearBuilt**: Ano de construção.
   - **GarageCars**: Número de carros que a garagem pode acomodar.
   - **BsmtFinSF1**: Área do porão que foi finalizada.
E muitas outras variáveis que representam diferentes aspectos das casas.

O dataset contém diversas variáveis sobre as casas, incluindo:
- **Número de quartos**
- **Área útil**
- **Ano de construção**
- **Tipo de garagem**
- **Entre outros**

O conjunto de dados é dividido em duas partes principais:
- **Treinamento**: Conjunto de dados usado para treinar o modelo.
- **Teste**: Conjunto de dados usado para fazer previsões, cujos preços de venda são desconhecidos.

## Tecnologias e Bibliotecas Utilizadas

- **Python**: Linguagem de programação utilizada.
- **pandas**: Biblioteca para manipulação de dados.
- **numpy**: Biblioteca para operações numéricas.
- **scikit-learn**: Biblioteca para machine learning, utilizada para construir e treinar os modelos.
- **matplotlib**: Biblioteca para visualização de dados.


## Treinamento de Modelos: O treinamento de modelos foi realizado utilizando três algoritmos:

  - **Regressão Linear**: Modelo simples de regressão linear para prever o preço de venda com base nas características das casas.
  - **Árvore de Decisão (Decision Tree)**: Modelo de árvore de decisão para prever o preço das casas com base em uma série de decisões binárias.
  - **K-Nearest Neighbors (KNN)**: Algoritmo baseado na proximidade de dados para prever o preço de casas.


## Como Executar

Para começar a trabalhar com o projeto localmente, siga os passos abaixo:

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/alexpaulo100/House-Prices.git

2. **Crie e ative um ambiente virtual (opcional, mas recomendado):**

``python3 -m venv .venv
source .venv/bin/activate  # Para sistemas Unix
.\.venv\Scripts\activate   # Para Windows

