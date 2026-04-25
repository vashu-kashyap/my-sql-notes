# Database and DBMS Notes

Simple, beginner-friendly notes on **Database**, **DBMS**, **SQL**, and **RDBMS** for study, revision, and GitHub reference.

These notes are useful for:

- College exams and interview preparation
- Beginners learning SQL and DBMS
- Office and operations work involving data
- Quick revision before practice

## Table of Contents

- [1. What is a Database?](#1-what-is-a-database)
- [2. What is DBMS?](#2-what-is-dbms)
- [3. Types of DBMS](#3-types-of-dbms)
- [4. What is SQL?](#4-what-is-sql)
- [5. How to Create a Database](#5-how-to-create-a-database)
- [6. How to Delete a Database](#6-how-to-delete-a-database)
- [7. Important Concepts](#7-important-concepts)
- [8. Keys in DBMS](#8-keys-in-dbms)
- [9. Advantages of DBMS](#9-advantages-of-dbms)
- [10. Disadvantages of DBMS](#10-disadvantages-of-dbms)
- [11. Normalization](#11-normalization)
- [12. Real-Life Use](#12-real-life-use)
- [13. Final Summary](#13-final-summary)

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
- Update data
- Control access to data

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
- Oracle
- SQL Server

**Note:** This is the type most commonly used in companies and the one you should focus on first.

### 4. NoSQL DBMS

- Stores non-tabular data
- Works with JSON, key-value, document, or similar formats
- Used for big data and fast modern applications

**Example:** MongoDB

## 4. What is SQL?

**SQL** stands for **Structured Query Language**.

It is used to:

- Create databases and tables
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

## 7. Important Concepts

### Table

Data inside a database is stored in tables.

Example:

| id | name  | age |
|-----|-------|-----|
| 1   | Rahul | 25  |

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

## 8. Keys in DBMS

Keys are used to identify records and connect tables.

### Primary Key

- Uniquely identifies each row in a table
- Cannot contain duplicate values

### Foreign Key

- A column that links one table with another table
- Helps create relationships between tables

### Candidate Key

- A column that can become a primary key

### Composite Key

- A key made using two or more columns together

## 9. Advantages of DBMS

- Reduces data duplication
- Improves data security
- Makes data sharing easier
- Supports backup and recovery
- Helps maintain data accuracy
- Makes searching and reporting faster

## 10. Disadvantages of DBMS

- Software can be costly
- Requires training
- Setup can be complex
- Needs regular maintenance

## 11. Normalization

**Normalization** is the process of organizing data to reduce duplication and improve consistency.

### Simple Meaning

It helps keep the database clean and avoids repeated data.

### Main Benefit

- Reduces redundancy
- Improves accuracy
- Makes updates easier

## 12. Real-Life Use

Since you work in operations, databases can help you:

- Store branch-wise data
- Compare monthly performance
- Track insurance claims
- Reduce heavy Excel work
- Create reports faster

**SQL + Excel** is a powerful combo for operations, reporting, and analysis work.

## 13. Final Summary

- **Database** -> stores organized data
- **DBMS** -> manages the database
- **SQL** -> communicates with the database
- **RDBMS** -> stores data in table format and uses SQL

## Quick Revision

- Database = collection of organized data
- DBMS = software that manages the database
- SQL = language used to work with databases
- RDBMS = table-based database system using SQL
- Primary Key = unique identifier
- Foreign Key = connects tables
- Normalization = reduces duplicate data
