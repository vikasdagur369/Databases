## Databases:

organised collection of structured information or data. data can be easily managed, updated, read and delete.

## characterstic:

1. persistence
2. structured and organised
3. easily retrivable
4. concurrent access
5. security and integration.

## DBMS

DBMS is a software that manages databases.
acts as a interface or layer b/w database and end user.

### examples of DBMS:

1. RDMS - stores data in tables (MySQL, PostgreDSQL, Oracle, SQL Server)
2. NoSQL (MongoDb, DynamoDb)
3. in-memory DBMS -stores data in RAM (Redis, Memcached)

## Relational data models:

organises data into one or more tables (also known as relations) with rows and coloumns.

### tables :

type of data stored. for e.g :- product table containing price and quantity.

columns are also known as Attributes.
and rows are known as Records.

### Primary Key:

a coloumn or set of coloumn that uniquely indentify each row in a table. for e.g :- student_id

### foreign key:

a column in one table that refers to the primary key in another table.

### relationships :

#### One-to-One :

Student can be a student of only one Branch.

#### One-to-Many :

department can have a multiple students associated with it.

#### Many-to-Many :

multiple students can be associated with multiple projects.

## Why Relational Model :

1. Data Integrity :- no orphaned record can exist.

2. Reduced Redundany :- using normalisation, is minimses duplicacy.

3. Flexiblity in querying :-
   SQL querying is flexible.

## Main categories of SQL commands:

1. DDL (Data definition Language)
2. DML (Data Manipulation Language)
3. DCL (Data Control Language)
4. TCL (transaction control language)

### DDL :-

provides command to define structure of database.
CREATE -> used to create db, tables, indexes and more

    ALTER -> used to modify

    DROP -> used to delete entire database, tables or objects.

### DML :-

SELECT,INSERT, UPDATE, DELETE

### DCL :-

these commands control access to the data in the databses.

GRANT -> gives a user access privileges to db objects.

REVOKE -> removes access privileges from a user.

### TCL :-

COMMIT -> saves all changes mode during the current tranactions.

ROLLBACK -> undoes changes made during the current transaction.

SAVEPOINT -> set a point within a transactions to which you can roll back.

SET TRANSACTION -> configures transaction properties.

## Basic termonologies :-

1. Shema :
   defines -> tables ,
   relationship b/w those tables,
   attributes (col) within each table,
   constraints and rules that govern the data,
   the data type for each field .

types :

Database Schema : the complete structure of entire db.

Table Schema : entire structure of table.

Sub Schema : A portion of the database visible to specific users/applications.

## Query :

it is a request to manipulate a database.
