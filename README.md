Análise de Vendas do E-commerce Brasileiro
Descrição
Este projeto tem como objetivo analisar as tendências de vendas de um e-commerce brasileiro utilizando o Brazilian E-Commerce Public Dataset by Olist. O projeto foi desenvolvido utilizando a plataforma Databricks para processamento e análise de dados, e o Power BI para visualização dos resultados.

Objetivos
As principais perguntas de negócio que este projeto busca responder são:

Quais são as tendências de vendas por região?
Quais produtos têm maior demanda em diferentes períodos do ano?
Qual é a correlação entre preço e demanda?
Quais produtos têm a maior variação de preço?
Quais são as categorias de produtos mais populares?
Qual é o efeito de promoções e descontos na demanda?
Estrutura do Projeto
O projeto é dividido nas seguintes etapas:

Busca pelos Dados
Fonte dos dados: Brazilian E-Commerce Public Dataset by Olist https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
Coleta dos Dados
Os dados foram baixados do Kaggle e armazenados na plataforma Databricks.
Modelagem dos Dados
Utilização de um modelo de dados em Esquema Estrela, incluindo tabelas de fato e dimensões.
Carga dos Dados
Processamento dos dados utilizando pipelines de ETL no Databricks.
Análise dos Dados
Realização de consultas SQL para responder às perguntas de negócio.
Visualização dos Dados
Criação de dashboards e gráficos no Power BI para visualizar os resultados.
Tecnologias Utilizadas
Databricks
Python
SQL
Power BI
Git
GitHub
Estrutura de Diretórios
data/
raw/ (Dados brutos)
processed/ (Dados processados)
notebooks/
etl_pipeline.ipynb (Notebook com o pipeline ETL)
powerbi/
dashboards.pbix (Arquivos do Power BI)
.gitignore
LICENSE
README.md

Configuração e Execução
Pré-requisitos
Conta no Kaggle
Conta no Databricks
Python instalado
Power BI instalado

Passos para Configuração
Clone o Repositório para o seu ambiente local:


git clone https://github.com/CraftingInsights00/MVP---Engenharia-de-dados.git
cd MVP---Engenharia-de-dados


Configuração do Databricks:
Faça o upload dos arquivos de dados para o Databricks.
Execute o notebook etl_pipeline.ipynb no Databricks para processar os dados.
Visualização no Power BI:
Abra o arquivo dashboards.pbix no Power BI.
Atualize as conexões de dados conforme necessário.
Resultados
Os resultados das análises realizadas foram visualizados no Power BI. Os dashboards incluem gráficos e visualizações que ajudam a entender as tendências de vendas, a demanda por produtos, a correlação entre preço e demanda, a variação de preço, as categorias mais populares e o efeito de promoções e descontos.

Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

Contato
Andres - andres.oliveira1995@gmail.com
