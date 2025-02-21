## Análise de Investimentos e Otimização de Carteiras



# Descrição

Este projeto realiza uma análise exploratória e otimização de carteiras de investimentos utilizando dados históricos de ações da bolsa de valores. Os principais objetivos incluem:

Coletar dados de preços ajustados de ações

Analisar o comportamento dos retornos diários

Visualizar o desempenho histórico das ações

Calcular risco e retorno anualizado

Estimar a correlação entre as ações

Simular carteiras de investimentos para encontrar a Fronteira Eficiente e maximizar o Índice de Sharpe



## Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

yFinance



## Estrutura do Projeto

Coleta de Dados: Os dados são obtidos através da biblioteca yfinance, selecionando ações específicas e um intervalo de tempo.

Análise Exploratória: Cálculo de estatísticas descritivas sobre os retornos diários.

Visualização dos Dados: Gráficos de preços das ações e retornos acumulados ao longo do tempo.

Análise de Risco e Retorno: Cálculo de risco anualizado (desvio padrão) e retorno esperado.

Correlação entre Ações: Matriz de correlação dos retornos para identificar relações entre os ativos.

Simulação de Carteiras: Geração de 10.000 carteiras aleatórias para identificar a Fronteira Eficiente.

Portfólio Ótimo: Determina a alocação de ativos com o maior Índice de Sharpe.



## Como Executar o Projeto

Dependências

Instale as bibliotecas necessárias executando:

pip install yfinance pandas numpy matplotlib seaborn



## Execução

Basta rodar o script principal:

python analise_investimentos.py



## Resultados Esperados

Gráficos de preço e retorno acumulado das ações.

Análise de risco e retorno anualizado.

Matriz de correlação entre os ativos.

Visualização da Fronteira Eficiente e identificação do portfólio ótimo.
