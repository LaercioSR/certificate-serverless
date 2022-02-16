<p align="center">
  <a href="https://www.rocketseat.com.br/">
    <img src="https://raw.githubusercontent.com/LaercioSR/certificate-serverless/main/assets/rocketseat-logo.png" height="120" width="auto" alt="Rocketseat Logo" />
  </a>
</p>

Repositório contendo o projeto desenvolvido durante a trilha Ignite de Node.Js da [Rocketseat](https://www.rocketseat.com.br/).

<h4 align="center">
 ✅  Projeto Concluído  ✅
</h4>

<p align="center">
 <a href="#sobre-o-projeto">Sobre</a> •
 <a href="#como-executar">Como executar</a> •
 <a href="#tecnologias">Tecnologias</a>
</p>

## Sobre o Projeto

Aplicação para geração de certificados, sendo desenvolvida em Node.Js utilizando a arquitetura serverless.

## Como Executar

### Pré Requisitos

Para executar o projeto você precisá ter o [NodeJs](https://nodejs.org/en/) e o [Serverless](https://www.serverless.com/) instalados em sua máquina.

### Executando

```bash
# Clone este repositório
$ git clone https://github.com/LaercioSR/certificate-serverless

# Acesse a pasta do projeto no terminal/cmd
$ cd certificate-serverless

# Instale as dependências
$ npm install

# Instale e execute o DynamoDB para executar localmente
$ npm run dynamodb:install
$ npm run dynamodb:start

# Em um outro terminal execute a aplicação
$ npm run dev
# Se tudo estiver correto, a aplicação será executada no http://localhost:3000
```

## Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- **[TypeScript](https://www.typescriptlang.org/)**
- **[NodeJs](https://nodejs.org/en/)**
- **[Serverless](https://www.serverless.com/)**
