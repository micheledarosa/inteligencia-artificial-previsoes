# Python IA: Inteligência Artificial e Previsões 🤖

## Case: Score de Crédito dos Clientes 💳

O objetivo foi analisar todos os clientes do banco e, com base nessa análise, criar um modelo que consiga ler as informações do cliente e dizer automaticamente o score de crédito dele: Ruim, Ok, Bom.

Isso vai definir se o banco vai emprestar dinheiro, se ele vai ter crédito entre outros benefícios dentro do banco.

## Base de Dados 🗃️

Foi utilizada a biblioteca [Pandas](https://pandas.pydata.org/docs/#) para trabalhar com os dados, ela pode ser instalada digitando _"pip install pandas"_ no terminal do editor de código.

![Imgur](https://i.imgur.com/cGQLQZW.png)


Após a importação da base de dados, foi realizado o tratamento da base, verificando se há valores vazios e transformando colunas com o tipo de informação _"object"_ para _"int32"_.

## Modelos de IA utilizados 🤖

### Modelo árvore de decisão ➜ Random Forest

<img height="400" src="https://i.imgur.com/IvNcatO.jpg" title="source: imgur.com" />

### Modelo KNN ➜ Kneighbors (Vizinhos próximos)

<img height="345" src="https://i.imgur.com/gLeifod.png" title="source: imgur.com" />

## Testes de modelos 🛡️

Tanto para a transformação dos dados, quanto os testes, foi utilizada a biblioteca [Scikit-learn](https://scikit-learn.org/stable/index.html), ela pode ser instalada digitando _"pip install –U scikit-learn"_ no terminal do editor de código.

![Imgur](https://i.imgur.com/vuLCvy1.png)

Ao fim dos testes o modelo de **Random Forest** apresentou melhores resultados, com acurácia de 82%, então foi utilizado ele para finalizar a ánalise e realizar novas previsões.

**Resultado das previsões:**

![Imgur](https://i.imgur.com/JiRbMwW.png)