# dio-projeto-covid-machine-learning
Repositório criado no Desafio de Projeto DIO - Criando modelos com Python e Machine Learning para prever a evolução do COVID-19 no Brasil, no Bootcamp Geração Tech Unimed-BH - Ciências de Dados.

### Prevendo a evolução do COVID-19 no Brasil com Python e Machine Learning.

A partir do projeto original e do acesso a dados mais atualizados crie uma comparação entre o que foi previsto através do método ARIMA utilizando as biblioteca pmdarima e o que de fato aconteceu. 

Da mesma forma criei um comparativo entre o previsto através da biblioteca fbprophet e os dados reais. Neste caso criei uma comparação com uma previsão de um milhão de infectados, dez milhões de infectatos e os mais de duzentos e onze milhões de brasileiros infectados.

A grande diferença do trabalho original foi a necessidade de fazer um agrupamento nos dados uma vez que a partir de uma determinada data o Brasil passou a ter dados por estados.

#### Conclusões

##### ARIMA

A conclusão que podemos chegar é que o previsto no ARIMA foi conservador uma vez que o número de infectados nos quinze dias posteriores foi maior que o método havia previsto.

#### Prophet

Já o observado na comparação com o Prophet é que as medidas tomadas desaceleraram a curva de contagem comparando com a previsão feita usando esta biblioteca.
