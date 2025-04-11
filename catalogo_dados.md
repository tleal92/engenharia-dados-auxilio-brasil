# Catálogo de Dados - Auxílio Brasil

Este catálogo descreve as colunas presentes no dataset "Auxílio Brasil" e fornece informações sobre os dados que compõem este conjunto.

## Colunas

- **ID**: Identificador único do beneficiário.
- **Faixa_Renda**: Faixa de renda do beneficiário, categorizada em diferentes valores.
- **Estado**: Estado onde o beneficiário reside.
- **Municipio**: Município onde o beneficiário reside.
- **Data_Cadastro**: Data de cadastro do beneficiário no sistema.
- **Situacao_Economica**: Situação econômica do beneficiário, podendo ser "Ativo", "Inativo", etc.
- **Municipio_Residencia**: Município onde o beneficiário reside.
- **Numero_Familiares**: Número de membros na família do beneficiário.
- **Data_Atualizacao**: Data da última atualização do cadastro do beneficiário.

## Tipos de Dados

- **Numéricos**: Faixa_Renda, Numero_Familiares.
- **Categóricos**: Estado, Municipio, Situacao_Economica.
- **Datas**: Data_Cadastro, Data_Atualizacao.

## Observações

- Dados faltantes ou inconsistentes foram identificados e tratados durante a análise de qualidade dos dados.
- O intervalo de valores de **Faixa_Renda** varia de 0 a 5000.
- **Situacao_Economica** contém categorias como "Ativo", "Inativo", "Em Análise", etc.

