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

```sql
SELECT * FROM Users;
```
## UPDATE

The `UPDATE` command modifies existing data in a table.

**Example:**

```sql
UPDATE Users
SET Email = 'newemail@example.com'
WHERE UserID = 1;
```
## DELETE

The `DELETE` command removes records from a table.

**Example:**

```sql
DELETE FROM Users
WHERE UserID = 1;
```

