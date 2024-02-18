# Database Migration and Rollback Instructions
These instructions will guide you through the process of migrating your PostgreSQL database schema according to the provided specifications and rolling back the changes if needed. The migration involves renaming columns, altering column lengths, and transforming data types.

# Prerequisites
Ensure that you have PostgreSQL installed and running.
Make sure you have necessary permissions to create and modify tables in your database.
Python Library "psycopg2" for 1st method: pip install psycopg2
Jupyter Notebook

## Step 1: Initialization
First, let's initialize the database tables and populate them with sample data.

### Using Python Script
Open your preferred terminal or command prompt.
Navigate to the directory containing the Python script (migrate.py).
Execute the script by running python migrate.py.
Verify that the tables students and interests are created and populated with sample data.

### Using SQL Script
Open your preferred terminal or command prompt.
Log in to your PostgreSQL database using psql or any other client.
Run the SQL script initTable.sql using the command \i 'path/to/initTable.sql'.
Verify that the tables students and interests are created and populated with sample data.



[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/JwSLLxUh)
