# Relational Databases

In a relational database system, data is stored in tables and these tables are related to each other. Tables consist of rows and columns.

## Relational Database Structure

- Each table is represents an object. (e.g., users, products, orders)
- Each row is a data record. (e.g., all informations of the user)
- Each column is a field/property. (e.g., name ,email, password)

* Sample Table:

**id** **name** **email**
1 Rumeysa rumeysa@gmail.com

2 Ali ali@gmail.com

## Relation Between Tables (Relational Logic)

The most important feature of a relational database is, its ability to create relationships between tables.

For example:

- A user can place multiple orders
  -> This is a **one-to-many** relationship

- Each order belongs to only one user
  -> This is a **many-to-one** relationship

Thanks to these relations, you can avoid data repetition and keep everything organized and consistent.

## Popular RDBMS Examples

- PostgreSQL
- MySQL
- Microsoft SQL Server
- Oracle

With these systems you can create databases, set up tables, add, delete or update data, and perform operations using SQL

## Advantages of Relational Databases

- Data is always well-organized
- You do not need to repeat the same data
- You can control who can access the data
- You can easily manage even large amounts of data

## Where Are Relational Database Use

- E-commerce systems
- Banking applications
- Social media platforms
- Blog platforms

In other words, relational databases are used wherever data needs to be consistent, connected, and professionally managed.
