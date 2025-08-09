## Introduction to SQL — Notes (No Syntax Yet)

### What is SQL?
**SQL (Structured Query Language)** is used to communicate with a database. You use it to create and manage databases and to add, change, delete, and retrieve data.

### Common Things You Do With SQL
- Create a database
- Create objects (tables, views, indexes)
- Change (alter) the structure of existing objects
- Insert data into tables
- Update existing data
- Delete data
- Query (retrieve) data from one or more tables

### Case Sensitivity & Formatting
- SQL keywords are **not case-sensitive** (`SELECT` = `select`).
- Statements can be written on one line or multiple lines for readability.

### Two Big Buckets of SQL Statements
1. **DDL — Data Definition Language**
   - Purpose: define and manage the database structure.
   - Typical commands: **CREATE**, **ALTER**, **DROP**.
   - Used for: making a new table, changing a column, removing a view.

2. **DML — Data Manipulation Language**
   - Purpose: work with the data inside tables.
   - Typical commands: **INSERT**, **UPDATE**, **DELETE**, **SELECT**.
   - Used for: adding rows, changing values, removing rows, retrieving data.

### How this helps you as a Data Analyst
- Most day-to-day work is DML (especially **SELECT**, **JOIN**, **GROUP BY**).
- Knowing DDL basics helps you understand the structure you’re querying.

### Placeholder for Future Examples
When you start learning syntax, add short examples here (or in a new `.sql` file):
- **DDL example**: create a table with a few columns.
- **DML example**: add a few rows and read them back with a simple query.

> Tip: Keep examples tiny (3–5 rows) so you can reason about results easily.
