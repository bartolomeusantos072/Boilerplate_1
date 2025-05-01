# Projeto Backend Boilerplate

Este é um boilerplate para um projeto backend utilizando **Node.js**, **TypeScript**, **PostgreSQL** e **Docker**.

## Estrutura do projeto

A estrutura do projeto é a seguinte:

```
/projeto
├── src
│   ├── app.ts
│   ├── config
│   ├── controllers
│   ├── database
│   ├── models
│   ├── routes
│   ├── services
│   ├── middlewares
│   ├── utils
│   └── tests
├── .env
├── .env.dev
├── .env.test
├── docker-compose.yml
├── docker-compose.dev.yml
├── docker-compose.test.yml
├── package.json
├── tsconfig.json
├── tsconfig.build.json
└── jest.config.js
```

## Como rodar o projeto

### Docker
Este projeto usa Docker para rodar tanto no ambiente de desenvolvimento quanto em produção.

### Produção
Para rodar o ambiente de produção, use o comando:
```
docker-compose -f docker-compose.yml up --build
```

### Desenvolvimento
Para rodar o ambiente de desenvolvimento, use o comando:
```
docker-compose -f docker-compose.dev.yml up --build
```

### Testes
Para rodar os testes, use o comando:
```
docker-compose -f docker-compose.test.yml up --build
```

## Variáveis de ambiente

As variáveis de ambiente podem ser configuradas nos arquivos ,  e .

