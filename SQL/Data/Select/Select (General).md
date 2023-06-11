# Selecting Data - General

To select / view Data in a Table, use the `SELECT` Keyword(s).

## Command

```sql
SELECT <column_name> FROM <table_name>;
```

## Example

```sql
SELECT firstname, lastname FROM Entities;
```

## Note

Now you may be wondering why the Columns swapped place, seeing that in the original Table the lastname comes first.

That's because the view is based on the order of the Columns in the `SELECT` Statement.

I'm not showing how to Select everything from a Table, because you can see that [here](../../Table/Select.md).

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/51ec3c7f-1f25-4393-8c97-9251163548e4)
