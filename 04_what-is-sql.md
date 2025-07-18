# What is SQL

SQL (Structured Query Language) is a database language used to create, modify, delete, and query data in a database.
It allows us to communicate with the database.

## What Can We Do With SQL

- Creating new tables
- Adding, updating, deleting, and querying data
- Defining data types for tables
- Creating relationships between tables using foreign keys

## Fundamental SQL commands

### CREATE TABLE

Creates new table

```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(150)
);
```

### INSERT INTO

Adds data to the table

```sql
INSERT INTO users (name, email)
VALUES ('Rumeysa', 'rumeysa@gmail.com');
```

### SELECT

Retrieves data (shows)

```sql
SELECT * FROM  users;
-- Lists all users and all columns
```

(lists all users)

### UPDATE

Updates a data

```sql
UPDATE users
SET email = 'rumeysa123@gmail.com'
WHERE id = 1;
```

### DELETE

Deletes data

```sql
DELETE FROM users
WHERE id = 1;
-- Deletes the user with ID 1
```

## SQL Data Types

In SQL, data types are defined for columns

| **Data type** | **Explanation**   |
| ------------- | ----------------- |
| Integer       | Integer           |
|               |                   |
| Varchar       | Character string  |
|               |                   |
| Boolean       | true/false        |
|               |                   |
| Date          | Date              |
|               |                   |
| Serial        | Auto increment ID |

- SQL allows us to create relations between tables

* **PRIMARIY KEY** -> A unique identifier for each row in a table. Usually the ID. Only one per table.
* **FOREIGN KEY** -> A column that refers to the PRIMARY KEY of another table. Used to create relationships.

```sql
CREATE TABLE orders (
    id SERIAL PRIMARY KEY,
    user_id INTEGER REFERENCES users(id),
    total_price INTEGER
);
-- user_id is a FOREIGN KEY pointing users(id)
```

In this example, the orders table is linked to the users table.

## What Is SQL Used For

- Keeping user information on websites
- Managing data in order and payment systems
- Displaying data with queries in admin panels
- Content management in social media applications

SQL is used when we need to keep data in order and get it back when we need it
