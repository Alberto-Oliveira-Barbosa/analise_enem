# Projeto de Conclusão do curso de Big Data Science oferecido por [Semantix Academy](https://semantix.com.br/academy/)

[Autor](https://www.linkedin.com/in/alberto-oliveira-barbosa/)
---



---

## Introdução:

  O objetivo do projeto é fazer uma análise dos dados coletados do Enem 2019, e disponibilizados pelo site do [Inep](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem).

Para o desenvolvimento resolvi abordar o problema como um projeto End-to-End e dividi-lo em partes, desde a extração dos dados (ETL), passando pelos conceitos de aplicação de ciência de dados para a extração de insights até a entrega do produto (neste caso o relatório com as informações).

## Parte 1 - Engenharia de dados

Nessa parte é feita a extração e a transformações dos dados para melhor entendimento nos próximos passos. 

No notebook deixei algumas formas de acesso aos dados, como o acesso via biblioteca [Requests](https://docs.python-requests.org/en/latest/) para o download dos dados e o acesso via [Google Drive](https://www.google.com/intl/pt/drive/), aproveitando a integração do Google Colaboratory.(método usado no projeto)

Para o ambiente de desenvolvimento foi escolhido o [Google Colaboratory](https://colab.research.google.com/), ele já fornece uma interface via browser para desenvolvimento python, o que poupa o trabalho de instalação de ambientes locais de desenvolvimento.

Para manipulação dos dados foi usado o Apache Spark, usando a interface [PySpark](https://spark.apache.org/docs/latest/api/python/) o que nos permite tratar grandes quantidade de dados, e junto com o Google Colaboratory, nos permite a configuração de modo mais simplificado.


## Parte 2 - Análise Exploratória

Nessa parte é feita a busca por padrões, entendimento dos dados e extração de insights.

As tecnologias usadas atualmente são: a biblioteca [Pandas](https://pandas.pydata.org/) e [Numpy](https://numpy.org/) para modelagem dos dados, junto da biblioteca [Seaborn](https://seaborn.pydata.org/) para o desenvolvimento dos gráficos da análise.
