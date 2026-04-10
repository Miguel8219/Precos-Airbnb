# Predição de Preços de Aluguel - Airbnb Rio de Janeiro
Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever os preços de dormidas de imóveis listados no Airbnb na cidade do Rio de Janeiro. O modelo serve como uma ferramenta de auxílio tanto para proprietários (para precificação competitiva) quanto para locatários (para identificação de oportunidades).

# Dataset
Os dados utilizados neste projeto foram extraídos do Kaggle:
https://www.kaggle.com/datasets/allanbruno/airbnb-rio-de-janeiro

O conjunto de dados original contém informações detalhadas sobre as propriedades, incluindo localização, tipos de quarto, comodidades, número de avaliações e outras variáveis que influenciam diretamente o valor da estadia.

# Etapas do Projeto
O desenvolvimento do projeto seguiu as seguintes etapas fundamentais:

Exploração e Limpeza de Dados (EDA): Análise estatística inicial, tratamento de valores ausentes, remoção de outliers e análise de correlação entre as variáveis.

Engenharia de Funcionalidades (Feature Engineering): Transformação de variáveis categóricas (como bairros e tipo de imóvel) e seleção das características mais relevantes para o modelo.

Desenvolvimento do Modelo: Implementação e comparação de diferentes algoritmos de regressão da biblioteca Scikit-learn.

Avaliação: Validação do desempenho do modelo utilizando métricas como o R² (Coeficiente de Determinação) e MSE (Raiz do Erro Quadrático Médio).

# Modelos Utilizados
Modelo de Regressão Linear

Modelo Random Forest Regressor

Modelo Extra Trees Regressor

# Resultados Obtidos
O modelo final alcançou um desempenho sólido, com um R² superior a 0.91, demonstrando uma elevada capacidade de explicar a variação dos preços com base nas características fornecidas. Entre os fatores de maior impacto no preço, destacaram-se a localização geográfica (proximidade com a orla), o tipo de propriedade e a capacidade de hóspedes
