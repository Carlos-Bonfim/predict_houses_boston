# Prevendo Valores de Imóveis

O Projeto prevê o preço de casas em Boston. Esse projeto foi para acompanhamento da Semana de Data Science do site Minerando dados.
Segue o passo a passo do Projeto:
- Definindo o Problema de Negócio;
- Análise dos dados e tratamento de dados missing e outras transformações, caso necessário;
- Análise exploratória e estatística com Pandas Profiling;
- Análise exploratória e visualizações com a biblioteca plotly;
- Definição da baseline;
- Machine Learning, comparando 4 modelos;
- Avaliação das performances do modelo;
- Tunning do melhor modelo, neste caso o Random Forest;
- Treinamento com todos os dados do conjunto;
- Criação de uma aplicação Web com Streamlit, framework para widgets dinâmicos em linguagem Python.
A semana foi até este ponto.

Com a aplicação pronta, fiz a publicação no site Heroku: https://boston-house-prices.herokuapp.com/
- Entrar no github.com;
- Criar um novo repositorio;

No terminal / prompt de comando:
- entrar na pasta dos arquivos do projeto
- git init
- git add .
- git commit -m "first commit"
- git remote add origin <caminho do seu repositorio criado no github>
- git push origin master

Ter uma conta no heroku e instalado o CLI heroku
No terminal / prompt de comando:
- heroku login
- heroku create boston-house-prices
- git push heroku master
- heroku open
