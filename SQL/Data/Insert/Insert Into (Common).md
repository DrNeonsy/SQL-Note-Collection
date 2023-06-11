# Inserting Data - Common Way

To insert Data into a Table, use the `INSERT INTO` Keyword(s).

## Command

```sql
INSERT INTO table_name VALUES (column1, column2, column3, ...)
```

## Example

```sql
INSERT INTO Entities VALUES (1, 'Whitmore', 'Darzen', 'Neonlane', 'Neonsphere')
```

## Note

This is a very common approach, but it's not recommended because specifying is a much safer way of inserting data, seeing that for example you don't necessarily know all the columns and their types and you don't always have all the data for every column.

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/5528f941-399e-4979-8549-146ea04ad9c9)
