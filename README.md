# Database & DBMS Notes

## 1. What is a Database?

A **database** is a collection of organized data that can be easily accessed, managed, and updated.

### Simple Meaning

A database is a place where data is stored in a structured way.

### Examples

- Bank system: customer details, accounts, transactions
- Instagram: users, posts, followers
- Office system: branch data, claims data

## 2. What is DBMS?

**DBMS** stands for **Database Management System**.

It is software that helps users:

- Store data
- Manage data
- Retrieve data

### Simple Meaning

DBMS acts as a middle layer between the user and the database.

### Examples of DBMS

- MySQL
- Oracle Database
- Microsoft SQL Server
- MongoDB

## 3. Types of DBMS

### 1. Hierarchical DBMS

- Data is stored in a tree structure
- Follows parent-child relationship
- Supports one-to-many relationship

**Example:** File system

### 2. Network DBMS

- Data is stored in graph form
- Supports many-to-many relationships

**Example:** Complex telecom systems

### 3. Relational DBMS (RDBMS)

- Data is stored in tables
- Tables contain rows and columns
- Uses SQL
- This is the most important type of DBMS

**Examples:**

- MySQL
- PostgreSQL

**Note:** This is the type you are mainly learning.

### 4. NoSQL DBMS

- Stores non-tabular data
- Works with JSON, key-value, document, or similar formats
- Used for big data and fast modern applications

**Example:** MongoDB

## 4. What is SQL?

**SQL** stands for **Structured Query Language**.

It is used to:

- Create databases
- Insert data
- Update data
- Delete data
- Fetch data

### Simple Meaning

SQL is the language used to communicate with a database.

## 5. How to Create a Database

```sql
CREATE DATABASE company;
```

This command creates a new database named `company`.

### Use the Database

```sql
USE company;
```

## 6. How to Delete a Database

```sql
DROP DATABASE company;
```

### Important

- This permanently deletes the database
- All data will be lost

## 7. Extra Important Concepts

### Table

Data inside a database is stored in tables.

Example:

| id | name | age |
|----|------|-----|
| 1  | Rahul | 25 |

### Row and Column

- **Row:** One complete record
- **Column:** One field or attribute such as name or age

### Primary Key

A **primary key** is a unique identifier for each record.

**Example:** `id`

### CRUD Operations

CRUD means the four basic database operations:

- **Create** -> `INSERT`
- **Read** -> `SELECT`
- **Update** -> `UPDATE`
- **Delete** -> `DELETE`

These operations are used regularly in real jobs.

## 8. Real-Life Use

Since you work in operations, databases can help you:

- Store branch-wise data
- Compare monthly performance
- Track insurance claims
- Reduce heavy Excel work

**SQL + Excel** is a very powerful combo for operations and reporting work.

## Final Summary

- **Database** -> stores data
- **DBMS** -> manages data
- **SQL** -> communicates with database
- **RDBMS** -> the most important type for learning and jobs

## Quick Revision

- Database = collection of organized data
- DBMS = software that manages the database
- SQL = language used to work with databases
- RDBMS = table-based database system using SQL
