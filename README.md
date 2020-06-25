# Aplicação simulando um E-commerce


<h3 align="center">
    <b>🛒 Aplicação que permite a criação de clientes, produtos e pedidos, onde o cliente pode gerar novos pedidos de compra de certos produtos.</b>
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/gacl97/gostack-typeorm-relations?style=flat-square&color=%23e0a639">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gacl97/gostack-typeorm-relations?style=flat-square&color=%23e0a639">

  <a href="https://github.com/gacl97/Ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/gacl97/gostack-typeorm-relations?style=flat-square&color=%23e0a639">
  </a>

  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square&color=%23e0a639" alt="PRs Welcome">
  </a>

  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square&color=%23e0a639" alt="License MIT">
  </a>

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square&color=%23e0a639">
  </a>
  <a>
</p>


# :pushpin: Índice

  - [Funcionalidades](#funcionalidades)
  - [Sobre](#sobre)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Como usar](#como-usar)

<a id="funcionalidades"></a>

# :rocket: Funcionalidades

- Cadastro de clientes;
- Cadastro de produtos;
- Criação de pedidos informando os produtos que irá ser feito a encomenda;
- Visualizar algum pedido que foi feito;

<a id="sobre"></a>


# :clipboard:	Sobre

Desafio proposto pela rocketseat para uma mini simulação de e-commerce, onde o foi feita somente a api para gerenciamento de pedidos por clientes.

<a id="tecnologias-utilizadas"></a>

# :wrench: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando

- Node
- Express
- Typescript

<a id="como-usar"></a>

# :construction_worker: Como usar

Lembrando que é necessário ter instalado o banco de dados postgres na sua máquina e criar um novo banco com o nome para funcionar corretamente:

      gostack_desafio09

1. Faça um clone :

```sh
  $ git clone https://github.com/gacl97/gostack-typeorm-relations.git
```

2. Instalar as dependências:
```sh
  $ yarn
```

3. Executar migrations:
```sh
  $ yarn typeorm migration:run
```

4. Executando a Aplicação:
```sh
  $ yarn dev:server
```
