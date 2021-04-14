# Data Base Normalization

Database normalization is a process used to organize a database into tables and columns.

## Why do we need DB Normalization

There are three main reasons to normalize a database:

1. to minimize duplicate data.

2. to minimize or avoid data modification issues

3. to simplify queries.

***
Duplicated information presents two problems:

1. It increases storage and decrease performance.
2. It becomes more difficult to maintain data changes

***

Duplicated information can cause many types of anomalies:

1. Insert Anomaly

2. Update Anomaly

3. Deletion Anomaly

***

## DB Normalization Forms

There are three common forms of database normalization: 1NF, 2NF, and 3NF .

The forms are progressive, meaning that to qualify for 3rd normal form a table must first satisfy the rules for 2nd normal form, and 2nd normal form must adhere to those for 1st normal form.

* First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
* Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
* Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key.
