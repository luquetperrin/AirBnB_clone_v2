# AirBnB Clone - MySQL
## Table of Contents
1. Project Overview
2. Environment Variables
3. Resources
4. General Concepts
5. Python Scripts
6. Python Unit Tests
7. SQL Scripts
8. Testing with MySQL
9. Authors

## Project Overview
The AirBnB Clone - MySQL project is part of a larger effort to build a full web application similar to AirBnB. This segment of the project focuses on transitioning from file storage to database storage using MySQL, adding new functionalities and optimizing the existing codebase. This involves setting up a database, creating tables, and modifying the storage engine to use SQLAlchemy as an Object-Relational Mapping (ORM) tool.

The project also emphasizes the importance of testing, particularly unit testing, and handling environment variables effectively to manage different configurations, such as development and testing environments.

## Environment Variables
To run this project successfully, you will need to configure several environment variables:

a. HBNB_ENV: Specifies the running environment. It can be dev for development or b. test for testing.
c. HBNB_MYSQL_USER: Your MySQL username.
d. HBNB_MYSQL_PWD: Your MySQL password.
e. HBNB_MYSQL_HOST: The hostname of your MySQL server.
f. HBNB_MYSQL_DB: The name of your MySQL database.
g. HBNB_TYPE_STORAGE: The type of storage to use. It can be either file (using FileStorage) or db (using DBStorage).

## Resources
To complete this project, the following resources may be helpful:

https://docs.python.org/3/library/cmd.html
https://docs.python.org/3/library/cmd.html
https://docs.python.org/3/library/unittest.html
https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/
https://docs.sqlalchemy.org/en/13/orm/tutorial.html
https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql
https://docs.python.org/3/library/os.html?highlight=env#os.getenv
https://docs.sqlalchemy.org/en/13/
https://dev.mysql.com/doc/refman/8.0/en/sql-statements.html

## **args and **kwargs
Understanding *args and **kwargs is essential for writing flexible and reusable functions in Python.

## Object-Relational Mapping (ORM)
ORM is a technique for converting data between incompatible type systems using object-oriented programming languages. In this project, SQLAlchemy is used as the ORM to interact with the MySQL database.

## Environment Variables
Environment variables allow you to manage different configurations easily, such as switching between development and production environments.

## Python Scripts
1. Your scripts will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.8.5.
2. Follow the PEP8 style guide for your code.
3. Ensure all your Python scripts are executable and well-documented.

## Python Unit Tests
1. Write your unit tests using the unittest module.
2. Organize your test files in a directory named tests.
3. Ensure all tests pass with every storage engine (file and DB).

## SQL Scripts
1. Write your SQL scripts following best practices such as using comments and uppercase keywords.
2. Ensure all scripts end with a newline and are executable on Ubuntu 20.04 LTS
using MySQL 8.0.

## Testing with MySQL
To test with MySQL, follow these steps:

1. Create a specific database for testing.
2. Assert the current state of the database.
3. Execute the desired action (e.g., create a new record).
4. Validate the outcome by comparing the state before and after the action.
For example, to validate that creating a new state works as expected, compare the number of records in the states table before and after the action.

## Authors
This project was developed by:

Perrin Letembet 
