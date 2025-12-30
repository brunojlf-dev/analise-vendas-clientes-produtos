# Análise de Vendas, Clientes e Produtos

Este projeto realiza a análise de dados de vendas, clientes e produtos utilizando Python, com bibliotecas como **pandas, numpy, matplotlib e seaborn**.  
O objetivo é entender o faturamento por categoria, identificar os principais clientes e visualizar tendências mensais, permitindo insights estratégicos para o negócio.

## Estrutura do Projeto

O repositório está organizado da seguinte forma:

- `notebooks/` : Notebook com a análise completa.
- `data/` : Arquivos CSV contendo os dados brutos.
- `requirements.txt` : Bibliotecas necessárias para rodar o projeto.
- `README.md` : Este arquivo.

## Funcionalidades Implementadas

- Importação e limpeza de dados: remoção de inconsistências, conversão de tipos e padronização de colunas.  
- Cálculo de faturamento: multiplicação da quantidade vendida pelo preço unitário.  
- Padronização de categorias: transformando nomes para maiúsculas, removendo caracteres especiais e aplicando mapeamento consistente.  
- Análise por categoria: agregação do faturamento por categoria de produto, identificando as mais lucrativas.  
- Top clientes: identificação dos 10 clientes com maior faturamento.  
- Análise temporal: agrupamento de faturamento por mês para visualizar tendências.  
- Visualização gráfica: gráficos de linha e barras com matplotlib e seaborn.

## Insights do Projeto

- Algumas categorias concentram a maior parte do faturamento, mostrando quais segmentos são mais estratégicos.  
- Poucos clientes representam uma fatia significativa da receita, importante para estratégias de fidelização.  
- A análise temporal revela picos de vendas em determinados meses, possivelmente ligados a sazonalidade ou promoções.

## Como Usar

1. Clone o repositório:  
   `git clone https://github.com/brunojlf-dev/analise-vendas-clientes-produtos.git`  
2. Entre na pasta do projeto:  
   `cd analise-vendas-clientes-produtos`  
3. Instale as dependências:  
   `pip install -r requirements.txt`  
4. Abra o notebook em `notebooks/analise_vendas.ipynb` para explorar a análise.

## Tecnologias e Bibliotecas

- Python  
- pandas, numpy  
- matplotlib, seaborn  

## Estrutura do Notebook

1. Importação de bibliotecas.  
2. Carregamento dos dados: leitura dos CSVs de clientes, produtos e vendas.  
3. Limpeza dos dados: funções específicas para remover inconsistências e tratar valores nulos.  
4. Merge dos datasets: união de vendas, clientes e produtos em um único dataframe.  
5. Cálculo do faturamento: criação da coluna `faturamento`.  
6. Padronização de categorias: conversão para maiúsculas, remoção de caracteres especiais e mapeamento.  
7. Análise por categoria: agrupamento e soma do faturamento por categoria.  
8. Top clientes: identificação dos principais clientes.  
9. Análise temporal: agrupamento de faturamento por mês e plotagem de gráfico de linha.

## Contato

- Autor: Bruno José Lucas Ferreira  
- GitHub: [brunojlf-dev](https://github.com/brunojlf-dev)
