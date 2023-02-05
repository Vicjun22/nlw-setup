## CRIAÇÃO DE PROJETO

Criação do arquivo package.json
* npm init -y

Instalação do framework fastify
* npm install fastify

Instalando Typescript como dependência de desenvolvimento
* npm install typescript -D

Criação do tsconfig.json com todas as configurações do typescript
* npm tsc --init

Para executar o código basta instalar o tsx como dependência de desenvolvimento
* npm i tsx -D


## BANCO DE DADOS
ORM - Prisma

Instalação:
* npm i -D prisma

Dependência que será usada para acessar o banco de dados dentro da aplicação:
* npm i @prisma/client

Será utilizado o banco de dados do tipo SQLite pois cria um arquivo local de banco de dados.
Não precisa usar Docker ou banco local.
* npx prisma init --datasource-provider SQLite

Comando que lerá o arquivo schema.prisma e criará automaticamente o arquivo SQL que fará as alterações no banco de dados
* npx prisma migrate dev

Comando que irá abrir no navegador uma interface para navegar no banco de dados
* npx prisma studio


## CORS

Configurando CORS
* npm i @fastify/cors


## VITE

Criação do frontend com vite
* npm create vite@latest