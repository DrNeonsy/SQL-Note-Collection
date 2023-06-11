# Introduction to Data

Data in SQL is stored in tables, while A table is a collection of related data, consisting of columns and rows.

## Columns

A column is a set of data values of a particular type, one value for each row of the table.
The values in a column are all of the same type.
A column may contain text values, numbers, or even pointers to files in the operating system.
A column can also be called an attribute.

## Rows

A row is a single set of values in a table.
A row is also called a record.
A row is a horizontal entity in a table.
A row contains all the information about one entity in a table.
For example, in a table called customer list, each row would represent a single customer.

## Note

The [Insert](./Insert) examples will use this [Database](../Database/Create.md) and this [Table](../Table/Create.md).

[Select](./Select), [Update](./Update) and [Delete](./Delete) use the following Data:

```sql
INSERT INTO `Entities` (`PersonID`, `LastName`, `FirstName`, `Address`, `City`) VALUES
(1, 'Whitmore', 'Darzen', 'Neonlane', 'Neonsphere'),
(2, 'Enderson', 'Timothy', 'Neonlane', 'Neonsphere'),
(3, 'Shadowthorn', 'Luna', 'Moonrise Way', 'Stellaris'),
(4, 'Silverbrook', 'Elysian', 'Silverbreeze Avenue', 'Eternia'),
(5, 'Ironhart', 'Valen', 'Forgemaster Lane', 'Hammerhold'),
(6, 'Stormrider', 'Aeris', 'Galewind Terrace', 'Zephyria'),
(7, 'Thornwood', 'Sylvan', 'Everleaf Lane', 'Verdantia'),
(8, 'Emberstrike', 'Ignis', 'Flamesong Avenue', 'Pyrothorn'),
(9, 'Nightshade', 'Raven', 'Shadowcrest Lane', 'Darkhollow'),
(10, 'Moonwhisper', 'Selene', 'Lunarglow Avenue', 'Eternia'),
(11, 'Frostfang', 'Wynn', 'Snowfall Lane', 'Pyrothorn'),
(12, 'Starweaver', 'Astra', 'Stardust Avenue', 'Celestalis');
```
