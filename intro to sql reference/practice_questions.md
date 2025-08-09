## Practice Questions — Introduction to SQL (No Syntax)

1. What does SQL stand for and what is it used for?

SQL stands for Structured Query Language and its used to communicate with databases.

2. List at least five activities you can perform using SQL.

Create databases


Create objects (tables, views, indexes, etc.)


Alter object structures


Insert data into tables


Update existing data


Delete data


Query (retrieve) data from one or more tables


3. Explain the difference between **DDL** and **DML** in your own words.

Data Definition Language (DDL). These statements are used to create, alter, and delete existing objects within a database.

Data Manipulation Language (DML). These statements are used to insert, update, delete and query data in database tables.

4. Give three examples of **DDL** commands and three examples of **DML** commands.

DDL - CREATE, ALTER, DELETE

DML - INSERT, UPDATE, SELECT

5. Are SQL keywords case-sensitive? Why might developers still write them in uppercase?

SQL is not case sensitive. SELECT is the same as select and can be written on single or multiple lines.

Developers write them in uppercase for readability and clarity.

6. Which category (DDL or DML) would you use to:
   - a) Create a new table - DDL
   - b) Add a new row of data - DML
   - c) Change a column’s definition - DDL
   - d) Retrieve data from a table - DML

7. As a data analyst, which SQL statements will you likely use most often and why?
You’ll mostly use DML statements, especially: SELECT, JOIN, WHERE, GROUP BY & HAVING, ORDER BY

Why? As a data analyst your job is to usualyy query, explore, and transform existing data rather than design or restructure the database.