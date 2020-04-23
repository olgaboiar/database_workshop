# database_workshop

## Exercise 1 - Restore a database from a backup

* Clone this repo and navigate to this folder
* Using `psql` create a database:
```
CREATE DATABASE db_name;
```
* Restore a database from `sqlc` file to the one you've just created:
```
pg_restore --dbname=db_name dental_appointments.sqlc
```

## Exercise 2 - Find possible ways to normalize database

* Analyze the data existing in the restored database and the database schema.
* Discuss with your group possible ways to normalize database.
* Create a diagram to illustrate your solution using [DB-Diagram tool](https://dbdiagram.io/home).
* The initial code for DB-Diagram can be found in `db_diagram.md`.
