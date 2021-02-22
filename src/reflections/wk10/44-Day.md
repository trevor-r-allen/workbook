# Day 44
__02/18/2020__

## Thoughts on SQL

### In a SQL table, what is the difference between information in a row and information in a column?
Information in an SQL table row represents an instance of a class, or an object. An SQL table column represents all the values of a specific property on all the instances of a class.

### Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
`CREATE TABLE characters(
  name VARCHAR(255) NOT NULL,
  age VARCHAR(255),
  description VARCHAR(255),
  id INT NOT NULL AUTO_INCREMENT,

  PRIMARY KEY (id)
);`

### What is the difference between the following statements:
### `DELETE FROM table_name;`
### `DROP TABLE table_name;`
`DELETE FROM` will delete all rows from a table but the table itself will remain.
`DROP TABLE` will delete the table entirely.


#### Afternoon Lab: [C# BurgerShack Code](https://github.com/trevor-r-allen/csharp-burgershack)