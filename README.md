# NLW eSports Mission Ignite - NodeJS
__By Rocketseat__

## Tecnologias
- NodeJS
- Express
- Typescript
- Prisma
  - Prisma Client
  - Prisma Studio
- SQLite

# Backend

## Entidades

### Game

id
title
bannerUrl

### Ads

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createdAt

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar anúncio pelo ID do anúncio

## Instalações neste projeto
Criar o projeto em Node
```
npm init -y
```

Express
```
npm i express
```

Typescript
```
npm i typescript -D
```

Criar tsconfig
```
npx tsc --init
```

Types Express
```
npm i @types/express -D
```
Node Server
```
npm i ts-node-dev -D
```

Prisma
```
npm i prisma -D
```
Inicializar o Prisma com definição de DB
```
npx prisma init --datasource-provider SQLite
```
Controle de Versão DB
```
npx prisma migrate dev
```
Interface Gráfica Prisma Studio
```
npx prisma studio
```
Prisma Client
```
npm i @prisma/client
```
Cors
```
npm i cors
```
Types Cors
```
npm i @types/cors -D
```

### Documentações
- [Prisma ORM](https://www.prisma.io/docs/)
- [SQLite](https://www.sqlite.org/docs.html)