# Preços de Imóveis Utilizando Regressão Linear

## Objetivo
Estimamos os preços de imóveis identificando aspectos que contribuem para a precificação dos imóveis. Além disso, entendemos qual aspecto é mais relevante e influencia mais no preço do imóvel, bem como precificamos um imóvel novo.

## Base de Dados
Utilizamos uma base de dados simplificada e inspirada em [House Prices](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

![Image](https://i.imgur.com/A8X79yq.jpeg)

## Estrutura do Projeto
O projeto foi desenvolvido com a tutoria de Ana Duarte da Alura.

### 1. Ajustando uma Reta

#### Conhecendo os Dados
Exploramos os dados para compreender suas características principais.

#### Correlação
Analisamos quais fatores estão relacionados ao preço da casa e como essa relação se apresenta. Utilizamos o coeficiente de Correlação de Pearson, que nos permite medir a relação linear entre variáveis, oferecendo uma escala que varia de -1 a 1:

- **-1**: Correlação negativa perfeita: à medida que uma variável aumenta, a outra diminui.
- **0**: Não há relação linear entre as variáveis.
- **1**: Correlação positiva perfeita: à medida que uma variável aumenta, a outra também aumenta.

### 2. Treinamento e Avaliação do Modelo de Regressão Linear

Utilizamos a biblioteca `scikit-learn` para criar e avaliar um modelo de regressão linear que estima os preços dos imóveis com base nas características disponíveis no dataset.

## Requisitos
Para rodar o projeto, você precisará das seguintes bibliotecas:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

Lenon Merlo
LinkedIn | GitHub
