# desafio-estagio


## Desafio

Deverá ser implementado uma API [node.js](https://nodejs.org) no padrão `RESTful` que possibilite a criação e listagem de posts e comentários.
Sendo que cada comentário devem pertencer a um post.

## Observações

Sugestão de bibliotecas para montar a api:

- Koa ou express
- Alguma biblioteca para abstrair a camada de dados que preferir.
  - Knex
  - Bookshelf
  - Sequelize
  - Mongoose

Prefira o uso de um banco de dados relacional (postgresql, mysql, ...), sendo seu uso não obrigatório.<br>
Para organizar a estrutura de seu projeto prefira o uso do padrão `MVC` sendo seu uso não obrigátio.<br>
Será observado organização de código, legibilidade e melhor uso dos recursos da linguagem javascript.

## (BONUS) Exercício de Banco de Dados

Dado a seguinte estrutura do banco
<br><br>
![banco](https://nave-challenges.s3.amazonaws.com/Back-End-Interniship/Screenshot.png)

- **E.B.1** Crie um script de criação das tabelas.
- **E.B.2** Faça um script para popular as tabelas.
- **E.B.3** Faça uma querie que traga todos os `posts` ordenados por `title`.
- **E.B.4** Faça uma querie que traga todos os `posts` com seus respectivos `comments`.
- **E.B.5** Faça uma querie que traga todos os `posts` com sua quantidade de `comments`.
