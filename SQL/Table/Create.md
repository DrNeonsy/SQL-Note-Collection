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

## Note

You must be inside a Database using the [`USE`](../Databases/Use.md) Keyword(s) before you can create a Table.
Make sure that you have the correct data types for each Column. If you don't, you will get an error.

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/42b6e533-8a45-4368-856d-8d73d37ee6da)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/64264825-734d-466d-b5d3-260f1e0b4d44)
