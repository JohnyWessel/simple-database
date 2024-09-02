# WesSQL Library #
*library for easy use sqlite3*

## Quick Guide ##

Using this library is very easy:

First, we need to setup database direcroty
For this we use `setdirecritry` it's look like that:

    import wessql as s

    s.setdirecritry("path//database.db")


Examples how to use all operations:

Creating table with `CreateTable(name: str, collumn: str)`:

    s.table.CreateTable("table_name", "int_values INT, str_values STR")


Adding to table items with `AddToTable(table: str, items: list)`:

    s.table.AddToTable("table_name", [1,"str"])


Deleting items from table with `DeleteFromTable(table: str, collumn: str, target: list)`:

    s.table.DeleteFromTable("table_name", "int_values" [1])


Getting data from table with `search.item(table: str, target: list)`:

    print(s.search.item("table_name", "str")) or print(s.search.item("table_name", 1))

Editing data with `Edit(table_name: str, collumn: str, target: list, item)`:

    s.table.Edit("table_name", "collumn_name", "old_values", "new_values")

----------


## Creator ##
site:  [*click*](https://johnywessel.github.io/) 
