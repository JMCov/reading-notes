# Data Modeling

## nosql vs sql

**What type of database is the best fit for the complex query intensive environment?**

SQL

**What type of database is the best fit for hierarchical data storage?**

NoSQL

**Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.**

SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable. SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.

From [SQL vs NoSQL Database Differences](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

## sql modeling techniques

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**

In some cases an entry in one table can be related to more than one entry in another.  This is called a one-to-many relationship.

From [Easy To Understand Data Modeling Concepts](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

Create a diagram

**Explain the difference between a primary and foreign key.**

The Primary Keys.  Remember the primary keys uniquely identify each row in a table.  A table typically has one primary key, but can have more.  When the key has more than one column, it is called a compound key.

Foreign Key – This is a column or set of columns which match a primary key in another table.

From [Easy To Understand Data Modeling Concepts](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

## sql vs nosql

**How do we treat keywords and parameters differently in SQL syntax?**

We have to use caps for keywords and the parameters are defined in the tables.

**Define normalization within the context of schemas and data.**

Normalized schemas avoid storage of duplicate data so that stored data can't become inconsistent

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

In a one to one relationship one record of the first table will be linked to zero or one record of another table.

In a one to many relationship one record of the first table will be linked to zero or many records of another table

In a many to many relationship each row of the first table will be linked to many records of another table and vice versa.


## Reflection

What are your learning goals after reading and reviewing the class README?

Understanding models and routers in more detail.

## Things I want to know more about

I just need to review and understand what we have learned about so far and apply more from the upcoming classes.

[Back to Home](../README.md)