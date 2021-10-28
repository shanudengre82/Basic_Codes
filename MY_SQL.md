
## In this file I am going to write basic SQL commmads also few important notes. This effort is to enhance my SQL skills as well as to write a nice readme file. 

## Table of contents
* [Important notes for SQL](#Important-notes-for-SQL)
* [Basic SQL queries](#Basic-SQL-queries)
* [Adavanced SQL queries](#Basic-SQL-queries)

## Important notes for SQL
#### In SQL, the data is stored in the form of tables. The type of data remains same in a column of a table. Like for example, all the column values are a float Some data types are
1. varchar: represented as varchar(max_character_length)
2. int

#### SQL is a relational database, I believe that it basically means that a schema is hidden within the database.

## Basic SQL queries 

1. To show all the databases use:
    <div align="center">
    <h3>SHOW DATABASES;</h3>
    </div>
    
2. To select a databases, use:
    <div align="center">
    <h3>USE database_name;</h3>
    </div>

3. To know which database we are in, use:
    <div align="center">
    <h3>SELECT DATABASE() FROM DUAL;</h3>
    </div>

4. To delete a database, use:
    <div align="center">
    <h3>DROP DATABASE;</h3>
    </div>

5. To create a database, use: 
    <div align="center">
    <h3>CREATE DATABASE_NAME;</h3>
    </div>

6. Adding a table to a dataframe, use:
    <div align="center">
    <h3>CREATE TABLE TABLE_name (name varchar(100), surname varchar(100));</h3>
    </div>

7. How to  get column names from a table? 
    <div align="center">
    <h3>DESCRIBE table_names;</h3>
    </div>

8. Inserting data into columns of a table.
    <div align="center">
    <h3>INSERT INTO table_names(column_name_1, column_name_2)</h3>
    <h3>VALUES (Value_1, Value_2)</h3>
    </div>

9. Selecting columns from a table.
    <div align="center">
    <h3>SELECT * FROM table_name</h3>
    </div>

