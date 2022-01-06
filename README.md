<p align="center">
  <img src=".github/capa-ignite-nodejs.png" alt="Ignite Node.js">
</p>

<br>

<h1 align="center">
  Desafio 3: corrigindo o código
</h1>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
</p>

## :computer: Descrição:
Esta API realiza o CRUD (Create, Read, Update and Delete) de repositórios de projetos. Além disso, é possível dar likes nos repositórios cadastrados.

## :hammer_and_wrench: Funcionalidades:
- Criar um novo repositório.
- Listar todos os repositórios.
- Alterar o `title`, a `url` e as `techs` de um repositório existente.
- Adicionar likes em um repositório.
- Excluir um repositório.

## :link: Rotas:
- GET `/repositories`: retorna uma lista contendo todos os repositórios cadastrados.
- POST `/repositories`: cria um novo repositório.
- PUT `/repositories/:id`: atualiza o `title`, a `url` e as `techs` de um repositório.
- DELETE `/repositories/:id`: remove um repositório da lista.
- POST `/repositories/:id/like`: atualiza a quantidade de likes de um repositório.

## :memo: Execução da API:
- Instalação das dependências:
  > yarn

- Execução da API:
  > yarn dev

- Execução dos testes:
  > yarn test
