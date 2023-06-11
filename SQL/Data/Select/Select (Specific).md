# Selecting Data - Specific Condition

To select / view Data in a Table, use the `SELECT` Keyword(s).

## Command

```sql
SELECT <column_name> FROM <table_name> WHERE <condition>;
```

## Example

```sql
SELECT firstname, lastname FROM Entities WHERE personid = 1;

SELECT firstname, lastname FROM Entities WHERE City = 'Pyrothorn';

SELECT * FROM Entities WHERE PersonID % 2 = 0;
```

## Note

The `WHERE` Keyword is used to specify a condition.

The Modulus Operator `%` can be used to find the remainder of a division.

So in this case, the Modulus Operator `%` is used to find the remainder of the `personid` divided by `2`.

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/cf820335-d2d2-4e92-a3f8-d4fa5177aea7)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/0d81cb58-99c4-4977-ae64-7302cd1e03b6)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/3d800013-4ffb-4ae2-ab9d-6b6922a4c626)
