# Crud-Produtos

CRUD de Produto com Angular, TypeScript, Laravel e
PostgreSQL

Neste projeto CRUD (Create, Read, Update, Delete) de produtos, utilizando uma arquitetura desacoplada entre o frontend e o backend. O frontend será desenvolvido em Angular, utilizando TypeScript como linguagem de programação, enquanto o backend será desenvolvido em PHP Laravel. O banco de dados utilizado será o PostgreSQL.

Versoes utilizadas no projeto:
Laravel versão 8 (API PHP Back-end)
Angular versão 16.1.2 (Framework Front-endo)
Banco de dados Postagresql

Para inicialização do Front-end use os seguintes comandos:

> npm install (ira instalar as dependências do pojeto)
> 
> ng serve (subindo um servido local para acessar projeto)
> 

Para inicialização do Back-end use os seguintes comandos:

> composer install
> 
> copy .env.example .envse estiver usando o prompt de comando do Windows ou cp .env.example .envse estiver usando o terminal, Ubuntu
> 
> Abra seu .envarquivo e altere o nome do banco de dados ( DB_DATABASE) para o que você tiver, os campos nome de usuário ( DB_USERNAME) e senha ( DB_PASSWORD) correspondem à sua configuração.
> 
> php artisan key:generate
> 
> php artisan serve
> 

Banco de dados:

> use o arquivo localizado na pasta DB e faça importação das tabelas em seu banco.
