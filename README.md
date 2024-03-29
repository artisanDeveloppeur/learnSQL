
# Learn SQL

[SQLite](https://www.sqlite.org/)

## Discover

- What is SQL?
- Getting started with SQLite on VSCode
- Starting with SQLite in the terminal
- Starting SQLite on TablePlus

## TABLE
- CREATE TABLE
https://www.sqlite.org/lang_createtable.html
- Datatypes 
https://www.sqlite.org/datatype3.html
- ALTER TABLE
https://www.sqlite.org/lang_altertable.html

## Manipulating 
- Manipulating rows with SELECT, UPDATE & INSERT
- INSERT
https://www.sqlite.org/lang_insert.html
- Date TIMESTAMP
https://www.timestamp.fr/
- SELECT
https://www.sqlite.org/lang_select.html
- DELETE
https://www.sqlite.org/lang_delete.html
- UPDATE
https://www.sqlite.org/lang_update.html
- DROP TABLE
https://www.sqlite.org/lang_droptable.html

## Data Constraints
- Primary keys
id INTEGER PRIMARY KEY AUTOINCREMENT 
- Indexes
`idx_tableNamePlural_fieldName`
- EXPLAIN QUERY PLAN
https://www.sqlite.org/eqp.html
- CREATE UNIQUE INDEX (idx_)
https://www.sqlite.org/lang_createindex.html
- DROP INDEX
https://www.sqlite.org/lang_dropindex.html
- LIST INDEX PRAGMA Statements
https://www.sqlite.org/pragma.html
- The NULL value
```SQL example with URL
slug NOT NULL UNIQUE
```


## JOIN Queries
- Foreign keys 
https://www.sqlite.org/foreignkeys.html

`tableNameSingular_id INTEGER`

```SQL
FOREIGN KEY (tableNameSingular_id) 
REFERENCES tableNamePlural (id)
```

- Enabling Foreign Key Support
```SQL
PRAGMA foreign_keys = ON;
```
- Schema joins
https://www.sqlite.org/syntax/join-clause.html

- Visual https://www.diffen.com/difference/Inner_Join_vs_Outer_Join
 
## Diagramming
- Diagramming with MCD & MLD
- Practical work: MLD conversion

## Advanced notions
- Aggregating data
- Order and Limit
- Nested queries
- Transactions

# MySQL

[Documentation](https://linktodocumentation)