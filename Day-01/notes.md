1. Today's learning objectives
By the end of Day 1, you should be able to:
1. Explain SQL and databases.
2. Understand tables, rows and columns.
3. Differentiate SQL command categories.
4. Create a PostgreSQL database.
5. Create tables and insert records.
6. Execute your first SQL queries.
7. Upload your work to GitHub.
2. What is SQL?
SQL stands for Structured Query Language.

It is a language used to communicate with relational databases.

For example, imagine a college database:
Students table
ID	Name	Age	Department
1	Amaan	22	CSE
2	Rahul	23	ECE
3	Ahmed	21	IT

Example of a relational database table.

Understand these terms:
Term	Meaning
Database	Collection of organized data
Table	Structure that stores data
Row	One complete record
Column	Attribute of a record
Primary Key	Uniquely identifies a row
Foreign Key	Connects related tables

Python connection: Think of a database table as a structured collection of records, similar to a list of dictionaries in Python.

students = [
    {"id": 1, "name": "Amaan", "age": 22},
    {"id": 2, "name": "Rahul", "age": 23}
]

SQL databases store and manage this kind of structured information persistently.
3. SQL command categories
There are five important categories.
Category	Full form	Commands
DDL	Data Definition Language	CREATE, ALTER, DROP
DML	Data Manipulation Language	INSERT, UPDATE, DELETE
DQL	Data Query Language	SELECT
DCL	Data Control Language	GRANT, REVOKE
TCL	Transaction Control Language	COMMIT, ROLLBACK

Remember:
- DDL → Structure
- DML → Data modification
- DQL → Data retrieval
- DCL → Permissions
- TCL → Transactions