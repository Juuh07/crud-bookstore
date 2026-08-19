# BookStore

Sistema em console desenvolvido para gerenciamento de acervo de livros, realizando operações completas de CRUD (Create, Read, Update, Delete) integrado a um banco de dados relacional.

<div align="center">
  <a href="https://docs.oracle.com/en/java/"><img src="https://img.shields.io/badge/JAVA-000000?style=for-the-badge&logo=openjdk&logoColor=orange" alt="Java"></a>
  <a href="https://www.postgresql.org/docs/"><img src="https://img.shields.io/badge/POSTGRESQL-000000?style=for-the-badge&logo=postgresql&logoColor=326393" alt="PostgreSQL"></a>
  <a href="https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc/"><img src="https://img.shields.io/badge/JDBC-000000?style=for-the-badge&logo=java&logoColor=white" alt="JDBC"></a>
  <a href="https://maven.apache.org/ref/3.9.9/"><img src="https://img.shields.io/badge/MAVEN-000000?style=for-the-badge&logo=apachemaven&logoColor=C71A36" alt="Maven"></a>
</div>

O projeto segue o padrão de arquitetura **DAO (Data Access Object)** para separar as regras de acesso ao banco de dados da regra de negócio:

* `Conexaodb.java`: Gerencia a conexão com o banco PostgreSQL.
* `Livro.java`: Modelo/Entidade representando a tabela de livros.
* `LivroDAO.java`: Contém os métodos para executar `INSERT`, `SELECT`, `UPDATE` e `DELETE`.
* `Main.java`: Interface de menu interativo via terminal.
