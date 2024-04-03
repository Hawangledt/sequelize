# Semana 10 - Introdução ao Sequelize

## Rodar o repositório:

### Na primeira vez é necessário instalar as dependencias:
1. `npm install`
2. `cp .env_example .env`

### Para rodar o repositório em ambiente local
1. `npm start:dev`

## Trabalhando com migrations:

### Criar uma migration
1. `sequelize migration:generate --name NomeDaMigration`
### Rodar uma migration. Opções:
1. Opção nº 1: `sequelize db:migrate`
2. Opção nº 2: `npx sequelize db:migrate`

## Novas Bibliotecas utilizadas:

### instalar o sequelize
`npm install sequelize` 
### instalar o driver do PostgreSQL
`npm install pg` 
### instalar o CLI do sequelize
`npm install -g sequelize-cli` 
### instalar o dotenv
`npm install dotenv`
