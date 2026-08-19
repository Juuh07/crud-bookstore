# BookStore

Sistema em console desenvolvido para gerenciamento de acervo de livros, realizando operações completas de CRUD (Create, Read, Update, Delete) integrado a um banco de dados relacional.

## 🚀 Tecnologias Utilizadas



## 🗂️ Estrutura do Projeto

O projeto segue o padrão de arquitetura **DAO (Data Access Object)** para separar as regras de acesso ao banco de dados da regra de negócio:

* `Conexaodb.java`: Gerencia a conexão com o banco PostgreSQL.
* `Livro.java`: Modelo/Entidade representando a tabela de livros.
* `LivroDAO.java`: Contém os métodos para executar `INSERT`, `SELECT`, `UPDATE` e `DELETE`.
* `Main.java`: Interface de menu interativo via terminal.
