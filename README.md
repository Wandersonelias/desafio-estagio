## Desafio Estagio Tributei

Deverá ser implementado uma API  [node.js](https://nodejs.org) no padrão `RESTful` que possibilite a criação e listagem de posts e comentários. 
Sendo que cada comentário devem pertencer a um post.

## Instruções

- Utilizar **apenas JavaScript** puro para resolver o problema (**nodejs**);

- **Entrega:** todas as soluções devem estar em um único repositório (github, gitlab, bitbucket, etc…) de forma **pública**;

- Neste repositório deve haver, na raiz, um README.md, com as instruções de execução do código desenvolvido;

- Estilo fica ao critério do candidato, e não é o foco principal do teste;

- Só será aceito o uso de bibliotecas de estilo e clientes HTTP (axios, fetch, etc);

- Caso não consiga resolver todos os exercícios, não tem problema, envie mesmo assim;

- Prazo para conclusão 3 dias;

- Ao finalizar o teste, envie o link do seu repositório via whatapp (96) 99207-6582 - Wanderson Elias

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
