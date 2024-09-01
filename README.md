# Simple DB Library #

## Quick Guide ##

### Using ###

Using this library is very easy:

First, we need to setup database direcroty
For this we use `setdirecritry` it's look like that:

    import simpledb as s

    s.setdirecritry("path//database.db")


Examples how to use all operations:

Creating table with `CreateTable`:

    s.table.CreateTable("table_name", "int_values INT, str_values STR")


Adding to table items with `readlines()`:

    s.table.AddToTable("table_name", [1,"str"])


Deleting items from table with `DeleteFromTable()`:

    s.table.DeleteFromTable("table_name", "int_values" [1])


Getting data from table with `search.item`):

    print(s.search.item("table_name", "str")) or print(s.search.item("table_name", 1))



----------


## Creator ##
My site: [link](https://johnywessel.github.io/) 
