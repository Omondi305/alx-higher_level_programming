0x0D. SQL - Introduction
0. List databases
mandatory
Write a script that lists all databases of your MySQL server.

1. Create a database
mandatory
Write a script that creates the database hbtn_0c_0 in your MySQL server.

If the database hbtn_0c_0 already exists, your script should not fail
You are not allowed to use the SELECT or SHOW statements

2. Delete a database
mandatory
Write a script that deletes the database hbtn_0c_0 in your MySQL server.

If the database hbtn_0c_0 doesn’t exist, your script should not fail
You are not allowed to use the SELECT or SHOW statements

3. List tables
mandatory
Write a script that lists all the tables of a database in your MySQL server.

The database name will be passed as argument of mysql command (in the following example: mysql is the name of the database)

4. First table
mandatory
Write a script that creates a table called first_table in the current database in your MySQL server.

first_table description:
id INT
name VARCHAR(256)
The database name will be passed as an argument of the mysql command
If the table first_table already exists, your script should not fail
You are not allowed to use the SELECT or SHOW statements

5. Full description
mandatory
Write a script that prints the full description of the table first_table from the database hbtn_0c_0 in your MySQL server.

The database name will be passed as an argument of the mysql command
You are not allowed to use the DESCRIBE or EXPLAIN statements

6. List all in table
mandatory
Write a script that lists all rows of the table first_table from the database hbtn_0c_0 in your MySQL server.

All fields should be printed
The database name will be passed as an argument of the mysql command

7. First add
mandatory
Write a script that inserts a new row in the table first_table (database hbtn_0c_0) in your MySQL server.

New row:
id = 89
name = Best School
The database name will be passed as an argument of the mysql command
8. Count 89
mandatory
Write a script that displays the number of records with id = 89 in the table first_table of the database hbtn_0c_0 in your MySQL server.

The database name will be passed as an argument of the mysql command

9. Full creation
mandatory
Write a script that creates a table second_table in the database hbtn_0c_0 in your MySQL server and add multiples rows.

second_table description:
id INT
name VARCHAR(256)
score INT

10. List by best
mandatory
Write a script that lists all records of the table second_table of the database hbtn_0c_0 in your MySQL server.

Results should display both the score and the name (in this order)
Records should be ordered by score (top first)
The database name will be passed as an argument of the mysql command
