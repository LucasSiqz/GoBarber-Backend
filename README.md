<h1 align="center">
  <img alt="GoBarber" src="https://github.com/LucasSiqz/GoBarber-Backend/blob/master/logo-purple.svg" width="100px" />
  <br/>
  <br/>
  GoBarber API
</h1>

## Descrição

Uma aplicação para agendamentos de horarios em barbearias desenvolvida em node.js utilizando Express, Sequelize, MongoDB, Redis, Yup, Sentry, Nodemailer, entre outras ferramentas.

## Dependencias

- Nodejs
- Yarn
- Docker

## Pre requisitos

Para rodar o servidor, são necessários containers do mongo, redis e postgres.

Para instalá-los rode:

> \$ docker run --name redisbarber -p 6379:6379 -d -t redis:alpine

> \$ docker run --name mongobarber -p 27017:27017 -d -t mongo

> \$ docker run --name postgresbarber -e POSTGRES_PASSWORD=docker -p 5433:5432 -d postgres

## Para executar o projeto

1. clone esse repositorio:
   > \$ git clone https://github.com/LucasSiqz/GoBarber-Backend
2. Acesse a pasta:
   > \$ cd GoBarber-Backend
3. Instale as dependencias:
   > \$ yarn
4. Crie uma copia do arquivo .env.example e renomeie para .env e adicione os valores
5. Execute os comandos:

   > \$ yarn dev

   > \$ yarn queue

6. O servidor estará rodando no endereço: http://localhost:3333

## Licença

Esse projeto utiliza a licença MIT. Para mais informações [clique aqui](https://github.com/LucasSiqz/GoBarber-Backend/blob/master/LICENSE)
