# Projeto de Engenharia de Dados - Auxílio Brasil

## Objetivo

O objetivo deste projeto é construir um pipeline de dados utilizando a plataforma Databricks, com foco na análise dos dados do programa Auxílio Brasil. O pipeline envolve a busca, coleta, modelagem, carga e análise dos dados. Este projeto visa responder às seguintes perguntas de negócio:

1. Qual é a distribuição geográfica dos beneficiários do Auxílio Brasil no estado do Rio de Janeiro?
2. Quais faixas de renda têm mais beneficiários no programa?
3. Existe uma correlação entre o número de beneficiários e a situação econômica das regiões?

## Dados Utilizados

Os dados utilizados neste projeto são provenientes do dataset "Auxílio Brasil", disponível publicamente. Eles contêm informações sobre os beneficiários do programa, incluindo dados como ID, faixa de renda, estado, município e outros atributos.

**Fonte dos Dados:** [GitHub - Auxílio Brasil Dataset](https://github.com/tleal92/engenharia-dados-clima-rj)

## Etapas do Projeto

### 1. Busca pelos Dados
O dataset "Auxílio Brasil" foi baixado diretamente do repositório do GitHub.

### 2. Coleta
O processo de coleta foi automatizado com um script Python que realiza o download dos dados e os armazena na nuvem.

### 3. Modelagem
A modelagem dos dados segue o formato de **Data Warehouse** utilizando o modelo de **Esquema Estrela**, o que facilita as consultas e a análise.

### 4. Carga
Foi criado um pipeline ETL que extrai, transforma e carrega os dados para o ambiente Databricks.

### 5. Análise
A análise foi dividida em duas partes:
- **Qualidade dos Dados**: Verificação de dados ausentes, duplicados ou inconsistentes.
- **Solução do Problema**: Respostas para as perguntas de negócio utilizando SQL e gráficos no Databricks.

## Tecnologias Utilizadas

- **Plataforma**: Databricks Community Edition
- **Linguagens**: Python, SQL
- **Ferramentas de Visualização**: Databricks, matplotlib, seaborn

## Autoavaliação

Neste projeto, foram seguidos todos os passos para construir um pipeline robusto e escalável, desde a coleta até a análise. A principal dificuldade foi garantir a qualidade dos dados e implementar o processo de ETL de maneira eficiente. No futuro, seria interessante incluir mais fontes de dados para enriquecer a análise.

## Licença

Este projeto está licenciado sob a Licença MIT.

