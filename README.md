# 📊 Desafio Alura Store

<p>O objetivo do desafio é ajudar o Senhor João a identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados para decidir qual loja da sua rede Alura Store vender para iniciar um novo empreendimento. Para isso, realizei analise e gráficos de dados de vendas, desempenho, avaliações das 4 lojas fictícias da Alura Store. 

Esta atividade é uma etapa do programa Oracle Next Education (ONE), oferecendo a chance de aplicar, na prática, conhecimentos relevantes como:

- Carregar e manipular dados CSV com a biblioteca Pandas.

- Criar visualizações de dados com biblioteca Matplotlib.

- Analisar métricas como faturamento, avaliações e desempenho de vendas.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido no Google Colab com as técnologias:

- Python: Linguagem principal utilizada para manipulação e visualização dos dados.
- pandas: Tratamento e análise de dados tabulares.
- matplotlib: Geração de gráficos estáticos.


## ✅ Como executar o notebook

- Abra o notebook no Google Colab.
  
📄 O notebook está dividido nas seguintes partes, execute as células na ordem:

- Importação dos dados
  Os dados são carregados automaticamente das seguintes URLs:
````
import pandas as pd

url = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv"
url2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv"
url3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv"
url4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv"

loja1 = pd.read_csv(url)
loja2 = pd.read_csv(url2)
loja3 = pd.read_csv(url3)
loja4 = pd.read_csv(url4)

loja1.head()
````

- Análise do faturamento;
- Vendas por Categoria;
- Média de Avaliação das Lojas;
- Produtos Mais e Menos Vendidos;
- Frete Médio por Loja;
- Relatório de análise

## 📍 Conclusão:
Após uma análise dos dados de faturamento, avaliações de clientes, vendas por categoria, desempenho de produtos e frete médio conclui-se que a Loja 1 é a mais indicada para ser vendida, pois ela representa a operação menos eficiente da rede atualmente.

Os principais fatores que levam a essa decisão são:

- Menor média de avaliação dos clientes (3,98), indicando menor satisfação e possível dificuldade em fidelizar compradores.

- Desempenho abaixo da média em categorias importantes, como instrumentos musicais e utilidades domésticas.

- Desempenho apenas mediano nas demais categorias, sem grande destaque competitivo.

## 
**Desafio do programa Oracle Next Education (ONE), por Poliany Guimarães.**

