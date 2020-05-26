<h1 align="center">
    <img alt="Gobarber" src="https://ik.imagekit.io/hwyksvj4iv/gofinances_FtYnL5e0v.svg" width="250px" />
</h1>

<p align="center">
  <a href="#page_with_curl-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-começando">Começando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-iniciando-back-end">Node.js</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-iniciando-front-end">ReactJS</a><!-- &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#iphone-iniciando-mobile">React Native</a> -->
</p>

<h1 align="center">
    <img alt="GoBarber" src="https://res.cloudinary.com/matheuspires/image/upload/v1587663201/gofinances_m4poam.gif" />
</h1>

## :page_with_curl: Sobre
Este repositório contém um API REST em Node.js como back-end, uma aplicação em ReactJS como front-end e um app mobile em React Native, todos utilizando TypeScript.

Essa é a aplicação GoFinances, de gestão de transações no qual o usuário consegue ter acesso ao seu saldo total, bem como todo o valor ja feito em depósito e saque. O usuário também consegue visualizar todas as suas transações já feitas.

**Node.js**: é uma API REST que faz todo o CRUD da aplicação, persistência de dados, tratativa de exceções e que serve dados tanto ao front-end quanto ao mobile.

**ReactJS**: é uma página Web em que o usuário consegue ter acesso as informações das usas trasações e também importar um arquivo do tipo CSV contendo várias transações.

**React Native**: em breve...

## :books: Requisitos
- Ter [**Git**](https://git-scm.com/) para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.
- Ter [**Docker**](https://www.docker.com/) rodando um container PostgreSQL.
<!-- - Um dispositivo ou emulador iOS ou Android -->

## :rocket: Começando
``` bash
  # Clonar o projeto:
  $ git clone https://github.com/rafaelkorz/go-stack-go-finance.git

  # Entrar no diretório:
  $ cd gofinances
```

## :gear: Iniciando back-end
```bash
  # Entrar no diretório do back-end:
  $ cd backend

  # Instalar as dependências:
  $ yarn

  # Rodar as migrations:
  $ yarn typeorm migration:run

  # Rodar a aplicação:
  $ yarn dev:server
```

## :computer: Iniciando front-end
```bash
  # Entrar no diretório do back-end:
  $ cd frontend

  # Instalar as dependências:
  $ yarn

  # Rodar a aplicação:
  $ yarn start
```
