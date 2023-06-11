# Creating a Table

To create a Table, use the `CREATE TABLE` Keyword(s).

## Command

```sql
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
);
```

## Example

```sql
CREATE TABLE Entities (
    PersonID int,
    LastName varchar(55),
    FirstName varchar(55),
    Address varchar(75),
    City varchar(36)
);
```

**FULL SQL**

```sql
CREATE TABLE `Entities` (
  `PersonID` int(11) DEFAULT NULL,
  `LastName` varchar(55) DEFAULT NULL,
  `FirstName` varchar(55) DEFAULT NULL,
  `Address` varchar(75) DEFAULT NULL,
  `City` varchar(36) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;
```

## Note

You must be inside a Database using the [`USE`](../Databases/Use.md) Keyword(s) before you can create a Table.
Make sure that you have the correct data types for each Column. If you don't, you might get an error in later examples.

## Brief Explanation

If you are interested in learning more about the code: The "DEFAULT NULL" means that if we don't specify a value for a column when adding a new row, it will be set to NULL.

The "ENGINE=InnoDB" means that we are using the InnoDB storage engine.

> InnoDB is a general-purpose storage engine that balances high reliability and high performance.
> In MySQL 8.0, InnoDB is the default MySQL storage engine.
> Unless you have configured a different default storage engine, issuing a CREATE TABLE statement without an ENGINE clause creates an InnoDB table.

The "DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci" means that we are using the UTF-8 character set.
CI stands for Case Insensitive, which means that the Database will ignore the case of the letters when comparing them.

My Server Config

```
Server type: MariaDB
Server version: 10.6.12-MariaDB-0ubuntu0.22.04.1 - Ubuntu 22.04
Server charset: UTF-8 Unicode (utf8mb4)
```

This will be handeled automatically by the Database, so you don't have to worry about it.

This is why we didn't type any of that when we created the Database or the Table.


## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/42b6e533-8a45-4368-856d-8d73d37ee6da)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/64264825-734d-466d-b5d3-260f1e0b4d44)
