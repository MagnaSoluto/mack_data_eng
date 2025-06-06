# Documentation for Jupyter Notebooks

## Visão Geral
Esta documentação fornece uma visão geral dos processos e fluxos de trabalho implementados nos Jupyter Notebooks associados ao projeto `mack_data_eng`. Cada notebook tem um propósito específico na pipeline de engenharia de dados.

## Notebook 1: Análise de Dados
### Propósito
- O primeiro notebook tem como objetivo realizar uma análise exploratória dos dados coletados, identificando padrões e tendências que podem informar decisões futuras.

### Processos Chave
- **Processo 1**: Carregamento e limpeza dos dados, onde os dados brutos são importados e as inconsistências são tratadas.
- **Processo 2**: Análise estatística descritiva, que inclui a geração de estatísticas resumidas e visualizações iniciais para entender a distribuição dos dados.
- **Processo 3**: Modelagem preditiva, onde algoritmos de machine learning são aplicados para prever resultados com base nas variáveis analisadas.

### Saídas
- As saídas incluem gráficos de dispersão, histogramas e um relatório com as principais descobertas da análise, além de um modelo preditivo salvo em formato `.pkl`.

## Notebook 2: Limpeza e Transformação de Dados
### Propósito
- O segundo notebook foca na limpeza e transformação dos dados, preparando-os para análise posterior e garantindo que estejam em um formato adequado.

### Processos Chave
- **Processo 1**: Remoção de duplicatas e tratamento de valores ausentes, assegurando a integridade dos dados.
- **Processo 2**: Normalização e padronização dos dados, aplicando técnicas para garantir que todas as variáveis estejam na mesma escala.
- **Processo 3**: Criação de novas variáveis, onde novas colunas são derivadas de dados existentes para enriquecer a análise.

### Saídas
- As saídas incluem um conjunto de dados limpos em formato `.csv` e um relatório que documenta as transformações realizadas.
