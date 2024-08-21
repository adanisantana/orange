Projeto de Ciência de Dados com Orange Data Mining

Este projeto apresenta o desenvolvimento de um processo de ciência de dados utilizando a ferramenta Orange Data Mining. O objetivo é explorar e analisar dados, aplicar algoritmos de aprendizado de máquina e avaliar as métricas dos experimentos realizados. Abaixo, detalhamos cada etapa do processo, incluindo imagens que evidenciam o trabalho realizado.

1. Exploração dos Dados
Durante a exploração dos dados, realizamos várias análises para entender melhor o conjunto de dados disponível:

Verificação de Outliers: Utilizamos gráficos para identificar valores atípicos nos dados.
Cálculo de Médias: Com a ferramenta Feature Statistics, calculamos a média do valor de venda, que foi de 6, com um mínimo de 4 e máximo de 9 no primeiro semestre de 2023.
Matriz de Confusão: Aplicamos a Matriz de Confusão para identificar erros na classificação, com o alvo sendo o Produto. Observamos uma quantidade significativa de falsos positivos e negativos.
Imagens:
Gráficos de outliers
Tabela de médias
Matriz de Confusão com destaque para os erros de classificação

2. Análise de Boxplot
Analisamos a distribuição dos combustíveis por região utilizando gráficos de Boxplot:

Gás Natural: Observamos que há um uso quase inexistente em diversas regiões.
Gasolina e Etanol: A gasolina está presente em todas as regiões, enquanto o etanol é mais utilizado no sudeste do que no norte.
Imagem:
Boxplot de combustíveis por região
3. Modelagem com Algoritmos de Aprendizado
Escolhemos três algoritmos para a modelagem:

KNN (K-Nearest Neighbors): Escolhido por sua simplicidade e capacidade de interpretar os dados após o pré-processamento.
Tree: Utilizado para classificar o tipo de combustível mais consumido e as regiões onde são utilizados.
Justificativa:
KNN: Efetivo na classificação com base em proximidade.
Tree: Oferece uma boa visualização e interpretação das regras de decisão.
Imagens:
Visualização dos modelos KNN e Tree
4. Preparação dos Dados
Os dados foram preparados de acordo com as necessidades de cada algoritmo:

Acurácia: Registramos uma acurácia entre 20% e 25%. Não houve grande evolução na acurácia após ajustar o nível de proximidade no KNN.
Imagem:
Gráfico de acurácia para diferentes níveis de proximidade
5. Execução dos Experimentos e Coleta das Métricas
Após a execução dos experimentos:

Resultados: Observamos que a mudança nos parâmetros dos algoritmos não resultou em melhorias significativas na acurácia.
Lições Aprendidas: A necessidade de explorar mais profundamente os parâmetros e talvez considerar outros métodos de pré-processamento de dados.
Imagem:
Tabela de métricas de desempenho

6. Reflexões Finais
Este projeto proporcionou uma valiosa experiência prática na exploração de dados e aplicação de algoritmos de aprendizado de máquina. Apesar dos desafios com a acurácia, o processo destacou a importância da preparação dos dados e da escolha correta dos algoritmos para cada tipo de análise.



