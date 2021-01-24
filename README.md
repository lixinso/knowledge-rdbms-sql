# Relational Database (SQL) Basics

# Basics

- Structured Query Language (SQL)

# SQL Operations

- **Data Definition Language (DDL)**

- Create DB
- Drop DB

- Create Table
- Drop table
- Modify Table

- Insert
- Delete
- Update

- **Data Query Language (DQL)**

- SELECT

- JOIN

- 

- **Data Control Language (DCL)**

- **Data Manipulation Language(DML)**

## History

- SQL-92
- SQL:1999
- SQL:2003
- SQL:2006
- SQL:2008
- SQL:2011
- SQL:2016
- SQL:2019

# Transaction

# Consistance

# SQL DB Design

# CAP Theorem

- Consistancy

Every read receives the most recent write or error.

- Availability

Every request receives a (non-error) response, without the guarantee that it contains the most recent write.

- Partition Tolerance

The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes.

# ACID

ACID is a set of properties of relational database transactions.

- Atomicity

Each transaction is all or nothing

- Consistency

Any transactions will bring the database from one valid state to another.

- Isolation

Executing transactions concurrently has the same results as if the transactions were executed serially

- Durability

Once a transsaction has been committed, it will remain no.


# References

- https://en.wikipedia.org/wiki/SQL
- https://en.wikipedia.org/wiki/CAP_theorem
- https://docs.microsoft.com/en-us/sql/relational-databases/sql-server-transaction-locking-and-row-versioning-guide?view=sql-server-ver15
