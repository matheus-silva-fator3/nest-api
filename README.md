## Description

A small api using Nestjs that I made as a POC for my TCC
It has some features like

```bash
Validation with joi
Simple JWT Authentication
Security middlewares with helmet
Response compression with compression
ORM with prisma
```

## Installation

```bash
$ npm install
```

## Setting up Docker (use sudo if you're using linux)

```bash
docker compose up
```

## Iniciating database w/ Prisma

```bash
npx prisma migrate dev
```

## Running the app

```bash
$ npm run start
```
