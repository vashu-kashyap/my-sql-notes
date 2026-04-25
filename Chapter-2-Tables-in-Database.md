# Chapter 2: Tables in Database

## What Is a Table in a Database?

A **table** is a structure in a database used to store data in an organized form.

It contains data in the form of:

- **Rows**
- **Columns**

A table is similar to a spreadsheet, where information is arranged in a grid format.

### Example Table: `students`

| id | name  | age |
| --- | --- | --- |
| 1 | Aman | 20 |
| 2 | Ravi | 21 |

## What Is a Row in a Database?

A **row** represents a single record in a table.

Each row contains complete information about one item or one person.

### Example

In the `students` table:

`1 | Aman | 20`

This is one row, and it represents one student's record.

## What Is a Column in a Database?

A **column** represents a specific field or attribute in a table.

Each column stores one type of information for all rows.

### Example

In the `students` table:

- `id` is a column
- `name` is a column
- `age` is a column

## How to Create a Table in MySQL

To create a table, use the `CREATE TABLE` statement.

```sql
CREATE TABLE students (
    id INT,
    name VARCHAR(50),
    age INT
);
```

### Meaning

- `id INT` stores numeric student ID
- `name VARCHAR(50)` stores student name
- `age INT` stores student age

## How to Delete a Table in Database

To delete a table, use the `DROP TABLE` statement.

```sql
DROP TABLE students;
```

> Be careful: `DROP TABLE` permanently deletes the table and its data.

## How to Insert Data into a Table

To add data to a table, use the `INSERT INTO` statement.

```sql
INSERT INTO students (id, name, age)
VALUES (1, 'Aman', 20);
```

### Insert More Than One Row

```sql
INSERT INTO students (id, name, age)
VALUES
    (2, 'Ravi', 21),
    (3, 'Sita', 22);
```

## How to Update Data in a Table

To change existing data, use the `UPDATE` statement.

```sql
UPDATE students
SET age = 23
WHERE id = 2;
```

### Meaning

- `SET` changes the value
- `WHERE` selects which row should be updated

## How to Read or Print a Table in MySQL

To display data from a table, use the `SELECT` statement.

```sql
SELECT * FROM students;
```

### Meaning

- `SELECT` is used to fetch data
- `*` means all columns
- `FROM students` means data is taken from the `students` table

## Full Example

```sql
CREATE DATABASE school;
USE school;

CREATE TABLE students (
    id INT,
    name VARCHAR(50),
    age INT
);

INSERT INTO students (id, name, age)
VALUES (1, 'Aman', 20);

INSERT INTO students (id, name, age)
VALUES (2, 'Ravi', 21);

UPDATE students
SET age = 22
WHERE id = 1;

SELECT * FROM students;
```

## Short Summary

- A **table** stores data in rows and columns
- A **row** is one complete record
- A **column** is one field of data
- `CREATE TABLE` creates a new table
- `DROP TABLE` deletes a table
- `INSERT INTO` adds data
- `UPDATE` changes data
- `SELECT` reads or prints data
