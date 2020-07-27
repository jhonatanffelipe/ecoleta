# ♻ Ecoleta
Projeto construído durante o Next Level Week #01 - Rocketseat. Todo o projeto foi denvolvido com a stack NodeJS, React e React Native.

O desenvolvimento desse projeto tem o intuito de auxilar no descarte de resíduos. O projeto é composto por uma aplicação Web, e uma aplicação mobile;

## Backend

Foi desenvolvida uma API REST desenvolvida em NodeJS utilizando Typescript. O Banco de dados utilizado foi o SQLite, utilizando o Knex;

## Frontend Web

A Aplicação web tem por responsabilidades cadastrar os pontos de coleta informando os dados de contato, entereço e quais os tipos de resíduos são coletados. Foi desenvolvida em Typescript utilizando o framework ReactJS 

<img alt="Ecoleta" src="https://raw.githubusercontent.com/jhonatanffelipe/ecoleta/master/assets/web-home.png" height="350px" />


## Mobile

A Aplicação mobile disponibiliaz um filtro em que deve ser informada a cidade, com essa informação serão apresentados os potos de coleta em sua região, de acordo com os tipos de resíduos selecionados. O desenvolvimento da aplicação mobile foi realizado em Typescript utilizando o framework React Native. Por se tratar de uma aplicação simples utilizamos o Expo para poder utilizar algumas funcionalidades de forma simplificada, como por exemplo os serviços dde geolocalização da aplicação.


<img alt="Ecoleta" src="https://raw.githubusercontent.com/jhonatanffelipe/ecoleta/master/assets/home.jpeg"  height="350px" />

## Como Executar a aplicação?

- O primeiro passo é clonar o repositório nossa base;
- Em seguida dentro de cada um dos diretórios server, web e mobile iremos executar no terminal o comando `yarn`, para baixar as dependências de nossas aplicação;
- Iremos começar executando nosso server, para isso devemos executar o camando `yarn dev`;
- Com nosso servidor executando podemos executar nossa aplicação web com o comando `yarn start`;
- Para executar nosssa aplicação mobile, precisamos ter instalado em nosso dispositivo mobile um Aplicativo chamado Expo, e estar conectado na mesma rede wi-fi do nosso servidor;
- Executaremos o comando `yarn start`, e iremos com nosso aplicativo, escanear o QRCode gerado em nosso terminal;



