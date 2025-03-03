# 🍷 Avaliação de Qualidade de Vinhos  
*Projeto de Análise Exploratória de Dados (EDA) - Felipe V. Sousa*

Bem-vindo(a)! Este repositório apresenta uma **Análise Exploratória de Dados (EDA)** no conjunto de dados de vinhos tintos, explorando características físico-químicas e sua relação com a qualidade.

🔗 [Visualizar o Notebook](https://github.com/benzerinsio/WineQuality-EDA/blob/main/EDA-WineQuality.ipynb)

## 🎯 Objetivo da Análise

Analisar um conjunto de dados com 11 características físico-químicas de vinhos tintos (como `alcohol`, `volatile acidity` e `pH`) e a nota de qualidade (`quality`), para entender distribuições, identificar padrões e explorar associações que influenciam o sabor, gerando insights práticos e preparando uma base para futuros projetos.

## 📊 Fonte de Dados

Os dados vêm do arquivo `winequality-red.csv` (UCI Machine Learning Repository), contendo 1.599 registros de vinhos tintos. Utilizamos duas versões: `vinhos` (bruto) e `vinhos_alterado` (tratado com remoção de duplicatas e transformação logarítmica).

## 🛠️ Bibliotecas Utilizadas

- **Pandas**: Manipulação e análise de dados.  
- **NumPy**: Cálculos numéricos e transformações (ex.: log).  
- **Seaborn**: Visualizações estatísticas como histogramas e scatters.  
- **Matplotlib**: Criação de gráficos lado a lado.  
- **Scikit-learn**: Normalização com StandardScaler.

## 💬 Conclusão

Este projeto realizou uma **Análise Exploratória de Dados (EDA)** no dataset de vinhos tintos, tratando duplicatas (15% removidos) e aplicando transformação logarítmica para suavizar outliers. A análise revelou que maior teor alcoólico (`alcohol`) e menor acidez volátil (`volatile acidity`) estão associados a melhor qualidade, embora com correlações moderadas (0.48 e -0.39). Os dados tratados em `vinhos_alterado` oferecem uma base sólida para futuros estudos, como Machine Learning, e sugerem ajustes químicos pra melhorar o sabor dos vinhos.