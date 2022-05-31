# Ford-Cars-Price-Prediction

Esse projeto foi desenvolvido por mim. Outros projetos podem ser encontrados [aqui](https://github.com/mvsampaio98).

#### Status do Projeto: [Desenvolvimento]

## Introdução/Objetivo
A ideia central desse projeto é prever o preço de carros da marca Ford baseado em suas características como o ano de fabricação, as milhas rodadas, entre outros. Isso irá ajudar pessoas que desejam adquirir um veículo usado ou até mesmo negociantes que gostariam de adquirir o bem para revender.
### Agradecimentos
* Agradecimento ao Kaggle por fornecer o [Dataseet utilizado](https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction)

### Métodos Utilizados
* Estatística
* Machine Learning
* Vizualização de Dados
* Tratamento de dados
* Modelo Preditivo

### Tecnologias
* Python
* Pandas
* Jupyter Notebook

## Descrição do Projeto

Com a importação das bibliotecas que serão utilizadas (Pandas, numpy, seaborn, sklearn e etc), estamos aptos a começar o nosso projeto. A primeira tarefa é importar a base de dados e analisar cada coluna que temos.

<p align="center"><img src="https://github.com/mvsampaio98/Ford-Cars-Price-Prediction/blob/main/img/Figura1.PNG" alt="Tabela1"></p>

* model -> Nos informa os modelos de carro da marca FORD;
* year -> Nos informa o ano em que o carro foi produzido;
* price -> Nos informa o preço desse carro;
* transmission -> Nos diz se o câmbio é automático ou manual;
* mileage -> Quantas milhas o carro já rodou;
* fuelType -> Qual o tipo de combustível o carro utiliza;
* tax -> Taxa Anual do veículo;
* mpg -> É a razão entre as milhas e a quantidade de galões de combustível (consumo médio);
* engineSize -> "Medição em relação as cilindradas do motor".

Depois de preparar os dados que iremos utilizar, vamos partir para a análise exploratória desses dados. Achamos algumas inconsistências para serem tratadas:

1. Uma linha apontava que existia um carro superior ao ano que estamos, logo essa linha foi removida da análise.
2. Analisando os gráficos obtidos via Seaborn, as colunas de 'tax' e 'mpg' parecem ter valores fora do padrão, foi feito um filtro para remover esses dados da análise.

Após isso criamos um mapa de calor para analisar se existe forte correlação entre os dados do nosso DataFrame.

<p align="center"><img src="https://github.com/mvsampaio98/Ford-Cars-Price-Prediction/blob/main/img/Figura2.PNG" alt="Figura2"></p>

## Fale comigo !
* Entre em contato comigo pelo meu [LinkedIn](https://www.linkedin.com/in/marcelo-victor-sa-coqueiro-sampaio/).
* Me envie um [E-mail](mailto:mvsampaio98@gmail.com) !
