# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```sql
CREATE TABLE student(roll_no NUMBER(5), name VARCHAR(20), age NUMBER(2), address VARCHAR(50), phone_no NUMBER(10));
```
### OUTPUT:
![image](https://github.com/DHARINIPV/G2_DBMS/assets/119400845/71637e3e-872e-4fcc-b31f-5cfde84a1188)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
ALTER TABLE student ADD department VARCHAR(10);
```
### OUTPUT:
![image](https://github.com/DHARINIPV/G2_DBMS/assets/119400845/08526244-2f2a-4798-be2e-2be02e64570a)

### 3) Drop the student table
 
### SQL QUERY: 
```sql
DROP TABLE student;
```
### OUTPUT:
![image](https://github.com/DHARINIPV/G2_DBMS/assets/119400845/2c9fba5d-70f0-4a14-87b6-5c47ad7da5d5)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
TRUNCATE TABLE student;
```
### OUTPUT:
![image](https://github.com/DHARINIPV/G2_DBMS/assets/119400845/ed46e5e1-330a-44b8-813d-2eeb2b8feb88)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
ALTER TABLE student RENAME TO my_student;
```
### OUTPUT:
![image](https://github.com/DHARINIPV/G2_DBMS/assets/119400845/b13ed43d-cc43-4d3f-9536-08e2db2836b3)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
