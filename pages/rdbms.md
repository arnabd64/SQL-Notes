# Relational Database Management System

Before diving into RDBMS, first let's look into a Database Management System. A **Database** is an *organized collection of data* whereas a **Database Management System** is a piece of software that interacts with end users or applications, acting as an interface between them and the database.

Here are some popular DBMS used in today's world:

1. MySQL
2. PostgreSQL
3. MongoDB
4. Amazon RDS
5. Amazon DynamoDB
6. Oracle Database
7. Microsoft SQL Server
8. Hadoop HDFS

In 1970, at IBM, **Edgar F. Codd** created the first Relational Database System. He proposed data to be organized as *Tables*, which consists of rows and columns. Each Table is related to one other by a specified *Relation*. 

# Terminology

1. A `Database` is an organized collection of data.
2. A Collecton of related data, stored in a tabular format consisting of rows and columns is called a `Table`.
3. Each row in a Table is related to a distinct real life object or an individual and is called an `Entity`.
4. Every entity in a table has columns called `Fields` or `Keys` on which contain a single data point which is attached to that entity. Example, _name_, _age_, _wieght_ etc. are some fields for a table containing data on people at an hospital.
5. A `Relational Model` is a schematic of several tables that connected using some fixed relations.

# Structured Query Language

SQL is a _domain-specific programming language_ that is used to interface with a Relational Database Management System. It was standardized by _ANSI_ and _ISO_ and hence many RDBMS systems have more or less the same implementation of SQL.

## Syntax

The SQL syntax can grouped into the following:

1. _Clauses_ which form the primary components of a Query. Ex: `SELECT`, `UPDATE`, `WHERE`, `FROM`, etc.
2. _Expressions_ produce a scarlar value or a table upon execution.
3. _Queries_ are used to retrieve data from the database.
4. _Statements_ have a permanent effect on the Database schema or data contained in the database, they can also other aspects of the database like controlling data transactions, program flow or managing connections, sessions or diagnostics.
5. _Whitespaces_ are ignored by SQL which can be used by the users to improve the readability of Queries and Statements.
6. _Delimiter_, usually a semicolon (;) which is used to terminate a Query or a Statement.