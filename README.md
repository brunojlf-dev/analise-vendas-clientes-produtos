Análise de Vendas, Clientes e Produtos

Este projeto realiza a análise de dados de vendas, clientes e produtos utilizando Python, com bibliotecas como pandas, numpy, matplotlib e seaborn.
O objetivo é entender o faturamento por categoria, identificar os principais clientes e visualizar tendências mensais, permitindo insights estratégicos para o negócio.

Estrutura do Projeto

O repositório está organizado da seguinte forma:

analise-vendas-clientes-produtos/
│
├── notebooks/
│   └── analise_vendas.ipynb       # Notebook com a análise completa
├── data/
│   ├── clientes.csv                # Dados de clientes
│   ├── produtos.csv                # Dados de produtos
│   └── vendas_com_data.csv         # Dados de vendas
├── requirements.txt                # Dependências do projeto
└── README.md                       # Este arquivo

Funcionalidades Implementadas

Importação e limpeza de dados: remoção de inconsistências, conversão de tipos e padronização de colunas.

Cálculo de faturamento: multiplicação da quantidade vendida pelo preço unitário.

Padronização de categorias: transformando nomes para maiúsculas, removendo caracteres especiais e aplicando mapeamento consistente.

Análise por categoria: agregação do faturamento por categoria de produto, identificando as mais lucrativas.

Top clientes: identificação dos 10 clientes com maior faturamento.

Análise temporal: agrupamento de faturamento por mês para visualizar tendências.

Visualização gráfica: gráficos de linha e barras com matplotlib e seaborn para facilitar interpretação.

Insights do Projeto

Algumas categorias concentram a maior parte do faturamento, mostrando quais segmentos são mais estratégicos.

Poucos clientes representam uma fatia significativa da receita, importante para estratégias de fidelização.

A análise temporal revela picos de vendas em determinados meses, possivelmente ligados a sazonalidade ou promoções.

Como Usar

Clone o repositório:

git clone https://github.com/brunojlf-dev/analise-vendas-clientes-produtos.git


Entre na pasta do projeto:

cd analise-vendas-clientes-produtos


Instale as dependências:

pip install -r requirements.txt


Abra o notebook em notebooks/analise_vendas.ipynb para explorar a análise.

Tecnologias e Bibliotecas

Python

pandas: manipulação de dataframes

numpy: operações numéricas

matplotlib: gráficos básicos

seaborn: gráficos estatísticos avançados

Estrutura do Notebook

Importação de bibliotecas: pandas, numpy, matplotlib e seaborn.

Carregamento dos dados: leitura dos CSVs de clientes, produtos e vendas.

Limpeza dos dados: funções específicas para remover inconsistências e tratar valores nulos.

Merge dos datasets: união de vendas, clientes e produtos em um único dataframe.

Cálculo do faturamento: criação da coluna faturamento.

Padronização de categorias: conversão para maiúsculas, remoção de caracteres especiais e mapeamento.

Análise por categoria: agrupamento e soma do faturamento por categoria.

Top clientes: identificação dos principais clientes.

Análise temporal: agrupamento de faturamento por mês e plotagem de gráfico de linha.

Contato

Autor: Bruno José Lucas Ferreira

GitHub: brunojlf-dev