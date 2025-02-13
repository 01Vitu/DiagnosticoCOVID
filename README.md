# DiagnosticoCOVID
Este repositório contém um notebook Jupyter que implementa um modelo de aprendizado profundo para o diagnóstico de COVID-19 a partir de imagens de raios-X de tórax. O objetivo é automatizar o processo de identificação de padrões característicos de infecção pulmonar causada pelo vírus SARS-CoV-2, utilizando técnicas de redes neurais convolucionais.
Estrutura do Projeto
O notebook está organizado nas seguintes seções:

1-Explicação do Problema: Contextualiza o problema e o objetivo do projeto.

2-Importações Necessárias: Importa as bibliotecas e ferramentas necessárias para a execução do código.

3-Definição dos Caminhos das Pastas: Define os caminhos para as pastas contendo as imagens de COVID-19 e normais.

4-Carregamento das Imagens: Carrega as imagens e converte as listas para arrays numpy.

5-Divisão do Dataset: Divide o dataset em conjuntos de treino (80%) e teste (20%).

6-Normalização das Imagens: Normaliza as imagens para o intervalo [0, 1].

7-Exibição das Imagens de Treino e Teste: Exibe exemplos de imagens de treino e teste.

8-Construção do Modelo: Define e compila o modelo de rede neural convolucional.

9-Treinamento do Modelo: Treina o modelo usando o conjunto de treino.

10-Avaliação do Modelo: Avalia o modelo usando o conjunto de teste e calcula métricas de desempenho.

11-Visualização dos Resultados: Exibe gráficos e métricas de desempenho do modelo.

Conjunto de Dados:
O conjunto de dados utilizado neste projeto está organizado em duas pastas: covid e normal, contendo imagens de raios-X de tórax de pacientes com e sem COVID-19, respectivamente. O dataset é dividido em conjuntos de treino e teste para avaliação do modelo.

Resultados:
O modelo é avaliado usando métricas como acurácia, precisão, recall e F1-score. Além disso, são exibidos gráficos de perda e acurácia durante o treinamento, bem como a matriz de confusão para o conjunto de teste.
