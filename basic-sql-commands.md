# Basic SQL Commands

## CREATE

The `CREATE` command is used to create a new database or table.

**Example:**

To create a table named `Users`:

```sql
CREATE TABLE Users (
  UserID INT,
  Name VARCHAR(100),
  Email VARCHAR(100)
);
```
## SELECT

The `SELECT` command retrieves data from a database.

**Example:**

To select all records from the `Users` table:

```sql
SELECT * FROM Users;
```
## UPDATE

The `UPDATE` command modifies existing data in a table.

**Example:**

To update the email of a user:

```sql
UPDATE Users
SET Email = 'newemail@example.com'
WHERE UserID = 1;
```

## DELETE

The `DELETE` command removes records from a table.

**Example:**

To delete a user from the `Users` table:


```sql
DELETE FROM Users
WHERE UserID = 1;
```

[← Previous: What is SQL?](what-is-sql.md) | [Back to Home](README.md) | [Next: Conclusion](conclusion.md)
