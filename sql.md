# SQL

* What is SQL ? SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.

* How to retrieve data from a SQL database? by using `SELECT` statements, which are often colloquially refered to as queries.

```SQL
SELECT column1,clumn_2 FROM mytable
```

* column contains the common properties while rows hold the unique instances.

* `WHERE` condition used to filter certain results. 

* First for lessons about sorting quires results 

* Logical Operator can be used in `Where` conditions.

* `DISTINCT` used to delete duplicate rows.

* `DISTINCT` keyword will blindly remove duplicate rows.

* `GROUP BY` is a controlled version of `DISTINCT`.

```SQL
SELECT DISTINCT column, another_column, …
FROM mytable
WHERE condition(s);
```

* `ORDER BY` will order the data base rows according to a certain criteria. 

```SQL

Select query with ordered results
SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC;

```


* `INSERT` to insert data into the table. 

```SQL
INSERT INTO mytable
VALUES (value_or_expr, another_value_or_expr, …),
       (value_or_expr_2, another_value_or_expr_2, …),
       …;
```

* `UPDATE` used to update columns value (rows data)that satsfiys a where condition in the query statement.

* `DELETE` used to delete rows from the table , `WHERE` condition is used to determine which rows to delete   in the query statement.

* `ALTER` used to add columns to my existing Table.

```SQL
ALTER TABLE mytable ADD column_extra FLOAT DEFAULT 3.33;
```

* `DROP TABLE IF EXISTS mytable` used to drop the table which differs from the `DELETE` statement in that it also removes the table schema from the database entirely.

