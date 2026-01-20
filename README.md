# Python Pandas: Manipulação de Dados e Planilhas

## Estrutura do Projeto

- **notebooks/** → Jupyter Notebooks com os códigos e análises  
- **data/** → Bases de dados brutas e processadas  
*A pasta `data` segue a convenção padrão em projetos de Data Science.*

## Conteúdo Técnico

### Análises em Python
- `aula1.ipynb`: Leitura de arquivos CSV, tratamento de delimitadores e exportação de dados.
Leitura e tratamento de arquivos CSV contendo dados de clientes de um supermercado.  
Inclui ajuste de delimitadores, seleção de colunas e exportação de uma base simplificada com **ID, ano de nascimento e renda**, pronta para análises de perfil de clientes.

- `Aula_2.ipynb`: Manipulação de arquivos Excel (.xlsx), seleção de abas (sheets) e engine `openpyxl`.
Manipulação de arquivos Excel com múltiplas abas contendo dados históricos de emissões de CO₂ por país.  
Inclui leitura de planilhas, seleção de sheets específicas e preparação de dados de **emissões totais e per capita**, aplicando técnicas de extração e organização de dados ambientais.

### Arquivos de Dados
- `clientes_mercado.csv` / `dados_mercado.csv`: Bases CSV de exemplo.
- `co2_percapita.xlsx`: Planilha Excel para exercícios de extração.

## Como utilizar
Certifique-se de ter o `pandas` e as dependências de IO (`openpyxl`) instaladas em seu ambiente Python.
