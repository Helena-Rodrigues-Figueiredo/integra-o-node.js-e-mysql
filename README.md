# Node.js: Express e MySQL

Este repósitorio contém um exercício realizado no aprendizado de como integrar uma aplicação com o Express com o banco de dados MySQL.

## O que foi feito?

* Configuração de um container docker com MySQL;
* Utilização do mysql2 para acessar um servidor MySQL através de uma aplicação Express;
* Aplicação o conceito de variáveis de ambiente para separar os parâmetros de configuração do código;
* Consultas SQL utilizando prepared statements;
* Desenvolvimento de um CRUD com Express integrado ao MySQL;
* Testes de integração com mock do banco de dados.

## Porque isso é importante?

Manipular dados é uma das atividades mais comuns do desenvolvimento de software. Geralmente esses dados são inseridos através de formulários pelas pessoas que utilizam sua aplicação ou de forma estruturada, através de um JSON, por meio de uma requisição a um endpoint de uma API REST.


Na maioria das vezes, esses dados necessitam ser armazenados para, posteriormente, serem utilizados pela aplicação com o intuito de realizar alguma ação ou fornecer algum tipo de serviço. O banco de dados é uma das ferramentas de armazenamento de dados mais utilizada em aplicações web. Portanto uma das atividades mais recorrentes no desenvolvimento de software é o de armazenar e consultar dados em um banco de dados.


Um CRUD (Create, Read, Update e Delete) é uma operação fundamental em um Sistema Gerenciador de Banco de dados (SGBD).
