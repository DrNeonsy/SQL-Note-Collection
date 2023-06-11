# Updating Data

To update data in a Table, use the `UPDATE` Keyword(s).

## Command

```sql
UPDATE <table_name> SET <column_name> = <value> WHERE <condition>;
```

## Example

```sql
INSERT INTO Entities (PersonID, LastName, FirstName) VALUES (13, 'King', 'Loberius');

UPDATE Entities SET Address = 'Iceavenue' WHERE PersonID = 13;

UPDATE Entities SET City = 'Everfrost' WHERE lastname = 'King';

UPDATE Entities SET City = NULL, Address = NULL WHERE PersonID = 13;
```

## Note

For this example, I've created a new Entity to play with.

## Output

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/2873206b-7f99-471f-a8e5-e1168923eda2)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/4466f108-e002-4e4c-8f31-ebe6031dee4a)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/18ed84f6-02f4-4e9e-a55e-c9ff1226baad)

![image](https://github.com/DrNeonsy/SQL-Note-Collection/assets/118444485/0730ae1e-c56d-4b61-bfd0-778fb085f9db)
