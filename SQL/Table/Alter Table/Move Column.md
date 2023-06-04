# Moving a Column from a Table

To move a Column, use the `AFTER` or `FIRST` Keyword(s).

## Command

```sql
ALTER TABLE table_name MODIFY column_name datatype AFTER column_name (TO PUT AFTER);
```

## Example

```sql
ALTER TABLE Entities MODIFY PersonID INT AFTER LastName;
```

## Note

I'm undoing this change in the example, because I don't want to mess up the order of the columns in the Table.

## Position To First Column

```sql
ALTER TABLE Entities MODIFY PersonID INT FIRST;
```

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/d7f6b48c-bb42-4af5-9364-fe2d2110a503)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/b998689b-7982-449d-b87e-f5cec95b0fc5)
