# Modifying a Column Datatype from a Table

To modify the Datatype of a Column, use the `MODIFY COLUMN` Keyword(s).

## Command

```sql
ALTER TABLE table_name MODIFY COLUMN column_name datatype;
```

## Example

```sql
ALTER TABLE Entities MODIFY COLUMN FavAnimal varchar(255);
```

## Note

I've [renamed](Rename%20Column.md) the Column `BirthPlace` to `FavAnimal` in the rename example.

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/285cd80f-62ee-42ec-a9d2-f087cbf7fa6e)
