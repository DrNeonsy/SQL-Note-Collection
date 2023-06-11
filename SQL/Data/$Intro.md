# Introduction to Data

Data in SQL is stored in Tables, while A Table is a collection of related Data, consisting of Columns and Rows.

## Columns

A Column is a set of Data values of a particular type, one value for each Row of the Table.
The values in a Column are all of the same type.
A Column may contain text values, numbers, or even pointers to files in the operating system.
A Column can also be called an attribute.

## Rows

A Row is a single set of values in a Table.
A Row is also called a record.
A Row is a horizontal entity in a Table.
A Row contains all the information about one entity in a Table.
For example, in a Table called customer list, each Row would represent a single customer.

## Note

The [Insert](./Insert) examples will use this [Database](../Database/Create.md) and this [Table](../Table/Create.md).

[Select](./Select), [Update](./Update.md) and [Delete](./Delete.md) use the following Data:

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
