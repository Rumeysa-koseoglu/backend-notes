# What Is ORM (OBJECT RELATIONAL MAPPING)

ORM is a bridge between databases and programming languages.  
Normally, we write SQL to work with a database. But thanks to ORM, we can perform database operations without writing SQL just by using the syntax of our programming language

## What Is The Use Of ORM

- Allows database tables to be used as objects.
- Automatically generates SQL commands for us.
- It makes coding easier, cleaner and easier to maintain.

For example, we have a "users" table. To add a user by using SQL, you would write:

```sql

INSERT INTO users (name, email) VALUES ('Ali', 'ali@gmail.com');

```

But when you use an ORM (like Sequelize in JavaScript), you can write:

```sql

User.create({name: 'Ali', email: 'ali@gmail.com'})

```

The ORM takes this code and converts it into SQL query behind the scenes So you do not need to know SQL, ORM handles this for you.

## Advantages Of ORM

- Codes become shorter and more readable
- You do not have to write SQL
- Provides a safer and more organized structure
- Easier to manage changes in the database
- Useful for large projects
