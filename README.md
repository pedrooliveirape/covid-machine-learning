# dio-projeto-covid-machine-learning
Repositório criado no Desafio de Projeto DIO - Criando modelos com Python e Machine Learning para prever a evolução do COVID-19 no Brasil, no Bootcamp Geração Tech Unimed-BH - Ciências de Dados.

### Análise e previsão do preço médio das passagens aérias do do Aeroporto do Recife-Guararapes(SBSP) para o Aeroporte de Congonhas(SBSP).

A partir do projeto 'Análise Covid_19' criei uma análise de séries temporais e previsão dos preços médios de passagens aéreas partindo do aeroporto do Recife-Guararapes(SBRF) com destino ao aeroporto de Congonhas(SBSP).

A base de dados é composta por dados mensais no período de agosto de 2017 a julho de 2022. A previsão foi realizada com os meses faltantes do ano de 2022, compreendendo o período de agosto a dezembro de 2022. 

A análise preditiva foi realizada utilizando o método ARIMA com a biblioteca pmdarima e com a biblioteca fbprophet.

Observação: Os arquivos brutos para a extração dos dados de vendas de passagens de SBRF para SBSP não foram versionados no GitHub devido ao tamanho da base de dados. Esses dados podem ser baixados no endereço: [ANAC-DataSAS](https://sistemas.anac.gov.br/sas/downloads/view/frmDownload.aspx). Acesso em 03/11/2022.

- :open_file_folder: [__preco_passagens_sbrf_sbsp__](https://github.com/pedrooliveirape/dio-projeto-covid-machine-learning/tree/main/preco_passagens_sbrf_sbsp) - Pasta do projeto 'Preços de passagens aéreas'.
  - :page_facing_up: __extraindo_apenas_sbrf_sbsp.ipynb__ - Arquivo jupyter com códigos da extração dos dados de passagens de SBRF para SBSP a partir dos dados brutos.
  - :page_facing_up: __flights_sbrf_to_sbsp.csv__ - Arquivo csv contendo apenas os dados de vendas de passagens de SBRF para SBSP.
  - :page_facing_up: __prophet_sbrf_sbsp.ipynb__ - Arquivo jupyter da transformação dos dados e previsão usando __ARIMA__.
  - :page_facing_up: __transformando_sbrf_sbsp.ipynb__ - Arquivo jupyter da transformação dos dados e previsão usando __fbprophet__.
- :file_folder: [__projeto_covid_19__](https://github.com/pedrooliveirape/dio-projeto-covid-machine-learning/tree/main/projeto_covid_19) - Pasta do projeto original 'Análise Covid_19'
 
