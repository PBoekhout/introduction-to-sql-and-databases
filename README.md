# Introduction to SQL and Databases

**Author**: Palmer Boekhout

---

## Summary

This tutorial provides a simple introduction to SQL (Structured Query Language) and relational databases. It explains fundamental concepts and basic SQL commands used to create, retrieve, update, and delete data in a database.

## Target Audience

Beginners with no prior experience in SQL or databases who are interested in learning the basics of how data is stored and managed.

---

## Table of Contents

1. [What is a Database?](#what-is-a-database)
2. [Relational Databases](#relational-databases)
3. [What is SQL?](#what-is-sql)
4. [Basic SQL Commands](#basic-sql-commands)
   - [CREATE](#create)
   - [SELECT](#select)
   - [UPDATE](#update)
   - [DELETE](#delete)
5. [Conclusion](#conclusion)
6. [About the Author](#about-the-author)

----

## What is a Database?

A **database** is an organized collection of data that can be easily accessed, managed, and updated. Databases are used to store information such as customer records, product inventories, and transactional data.

## Relational Databases

A **relational database** stores data in tables, which are structured with rows and columns. Each table represents a specific entity (like 'Customers' or 'Orders'), and relationships can be established between tables.

**Key Concepts:**

- **Table**: A collection of related data entries.
- **Row (Record)**: A single data item in a table.
- **Column (Field)**: A set of data values of a particular type.

## What is SQL?

**SQL (Structured Query Language)** is a standard programming language used to communicate with relational databases. SQL allows you to create databases, add new data, retrieve existing data, update data, and delete data.

----

## Basic SQL Commands

### CREATE

The `CREATE` command is used to create a new database or table.

**Example:**

To create a table named `Users`:

```sql
CREATE TABLE Users (
  UserID INT,
  Name VARCHAR(100),
  Email VARCHAR(100)
);
