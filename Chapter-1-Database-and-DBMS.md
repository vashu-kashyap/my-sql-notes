# Database Notes

## What Is a Database?

A **database** is an organized collection of data that is stored in a way that makes it easy to access, manage, and update.

### Examples

- Student records
- Employee details
- Bank account information
- Product lists in an online store

## What Is DBMS?

**DBMS** stands for **Database Management System**.

It is software used to create, store, manage, and control databases.

### Examples of DBMS

- MySQL
- Oracle
- PostgreSQL
- MongoDB

## Types of DBMS

There are two common types of DBMS:

### 1. Relational DBMS (RDBMS)

In a relational database, data is stored in the form of **tables** with **rows and columns**.

#### Examples

- MySQL
- PostgreSQL
- Oracle
- SQL Server

### 2. Non-Relational DBMS (NoSQL)

In a non-relational database, data is stored in flexible formats such as:

- Documents
- Key-value pairs
- Graphs
- Column-based structures

#### Examples

- MongoDB
- Cassandra
- Redis

## Relational vs Non-Relational Database

| Relational Database | Non-Relational Database |
| --- | --- |
| Stores data in tables | Stores data in flexible formats |
| Uses rows and columns | Uses documents, key-value, graph, or column models |
| Mostly uses SQL | May not use standard SQL |
| Best for structured data | Best for semi-structured or unstructured data |

## What Is CRUD Operation in Database?

**CRUD** refers to the four basic operations performed on data in a database:

- **Create**: Add new data
- **Read**: View or fetch data
- **Update**: Modify existing data
- **Delete**: Remove data

### CRUD Example in SQL

```sql
INSERT INTO students VALUES (1, 'Rahul');
SELECT * FROM students;
UPDATE students SET name = 'Ravi' WHERE id = 1;
DELETE FROM students WHERE id = 1;
```

## What Is SQL?

**SQL** stands for **Structured Query Language**.

It is the standard language used to communicate with relational databases. SQL is used to:

- Create databases and tables
- Insert data
- Read data
- Update data
- Delete data

## What Is MySQL?

**MySQL** is a popular **Relational Database Management System (RDBMS)** that uses SQL.

It is widely used in web applications to store and manage data.

## How to Create a Database in MySQL

```sql
CREATE DATABASE school;
```

## How to Delete a Database in SQL

```sql
DROP DATABASE school;
```

> Be careful: `DROP DATABASE` permanently deletes the database.

## How to Use a Database in SQL

To select a database before working with it, use:

```sql
USE school;
```

After selecting the database, you can create tables and insert data into it.

## Full Example

```sql
CREATE DATABASE school;
USE school;

CREATE TABLE students (
    id INT,
    name VARCHAR(50)
);

INSERT INTO students VALUES (1, 'Aman');
SELECT * FROM students;
```

## Short Summary

- **Database**: Organized collection of data
- **DBMS**: Software used to manage databases
- **RDBMS**: Table-based database system
- **NoSQL**: Non-relational database system
- **CRUD**: Create, Read, Update, Delete
- **SQL**: Language used to manage relational databases
- **MySQL**: Popular relational database system
- `CREATE DATABASE`: Creates a database
- `DROP DATABASE`: Deletes a database
- `USE database_name`: Selects a database
