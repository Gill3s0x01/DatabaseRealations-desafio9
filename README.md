# DatabaseRealations-desafio9
Desafio sobre Relacionamentos com banco de dados TypeORM no Node.js aplicado no Bootcamp GoStack 13

## DatabaseRealations-desafio9

  <h3 align="center">
    Uma aplicação que permite a criação de clientes, produtos e pedidos, onde o cliente pode gerar novos pedidos de compra de certos produtos, como um pequeno e-commerce.👨🏻‍🚀
  </h3>
  <p align="center">
      <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Gilles30/DatabaseRealations-desafio9?color=1db954">
      <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Gilles30/DatabaseRealations-desafio9?color=1db954">
      <img alt="Stars" src="https://img.shields.io/github/stars/Gilles30/DatabaseRealations-desafio9?color=1db954">
      <img alt="Repository Size" src="https://img.shields.io/github/repo-size/Gilles30/DatabaseRealations-desafio9?color=1db954">
  </p>
</h1>

<p align="center">
  <a href="#page_with_curl-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-começando">Começando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-iniciando-back-end">Node.js</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## :page_with_curl: Sobre
Uma aplicação desenvolvida para aprender novas coisas e treinar o que aprendi até agora no Node.js junto ao TypeScript, incluindo o uso de banco de dados com o TypeORM, e relacionamentos ManyToMany!.

Nela o usuário tem poderá realizar a criação de clientes, produtos e pedidos, onde o cliente pode gerar novos pedidos de compra de certos produtos, como um pequeno e-commerce.👨🏻‍🚀.

Nesse projeto tive como principal objetivo praticar o que aprendemos com backend e aprender relacionamentos Many-to-Many.

**Node.js**: realiza todas as chamadas a API e customizamos as respostas pra serem da forma que tem que ser. Serve todos os dados para um possivel front-end.

## :books: Requisitos
- Ter [**Git**](https://git-scm.com/) para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.
- Ter [**Yarn**](https://classic.yarnpkg.com/pt-BR/docs/install/) instalado.

## :rocket: 🎧🕹Começando
``` bash
  # Clonar o projeto:
  $ git clone https://github.com/Gilles30/DatabaseRealations-desafio9

  # Entrar no diretório:
  $ cd DatabaseRealations-desafio9
```

## :gear: Iniciando back-end 
```bash

# Criar o BD:

  # 🎲* Já com o Docker em funcionamento * 
   
  # Dentro do seu Client de conexção com banco de dados (Dbeaver, Beekeeper Studio entre outros...) criar dois BD com os nomes:
  $ gostack_desafio09_tests
  $ gostack_desafio09

  # Instalar as dependencias:
  $ yarn
  
  # Criar as Migrations:
  $ yarn typeorm migration:run
  
  # Executar o servidor:
  $ yarn dev:server

  # Rodar a aplicação, use um app para faciliatr o uso (exemplo: Insomnia):
  $ configure os parametros das rotas HTTP das requisições (POST, GET, DELETE, PUT)
  
  # Para rodar os testes:
  $ yarn test
```
:computer: 


Feito com 💜 por [Lorison Gilles](https://github.com/Gilles30) 🖖🏻👾☕
