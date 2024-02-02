# regress-olinear_case_house_USA

Este repositório contém um modelo de regressão linear desenvolvido para prever os preços de casas nos Estados Unidos com base em diversas variáveis. O conjunto de dados foi tratado adequadamente para garantir a eficácia do modelo, incluindo a remoção da coluna de endereço, que não é numérica e, portanto, não contribui para a modelagem.

Passos do Processo:

Pré-processamento dos Dados:
Remoção da coluna de endereço para simplificar a análise.
Exploração e comparação de todas as variáveis para identificar possíveis correlações.
Análise de correlação específica entre cada variável e o preço das casas.

Divisão da Base de Dados:
Separação da base de dados em conjuntos de treino e teste, utilizando 70% dos dados para treino e 30% para teste.

Regressão Linear:
Implementação da regressão linear utilizando a biblioteca LinearRegression do scikit-learn.
Treinamento do modelo com o conjunto de treino.

Avaliação do Modelo:
Utilização do conjunto de teste para avaliar a acurácia do modelo.
Cálculo do coeficiente de determinação (R²) usando a biblioteca r2_score do scikit-learn.

Visualização dos Resultados:
Plotagem de gráficos comparativos entre as variáveis nos conjuntos de treino e teste.
Apresentação de um exemplo prático de utilização do modelo, fornecendo valores arbitrários para as variáveis e obtendo uma previsão de preço.
