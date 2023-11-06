# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a database studentdb
### SQL QUERY:
```
Create database studentdb;
```
### OUTPUT:
![image](https://github.com/DrUmaRaniV/DBMS/assets/93427248/6df46966-3442-4252-9fa7-e8a6df36c399)

### 2) Create a table student  and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
```
 create table student(rollno int,name char(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:
![image](https://github.com/DrUmaRaniV/DBMS/assets/93427248/9c966cfb-5438-4b34-99ff-19bf2350b3a8)

### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![image](https://github.com/DrUmaRaniV/DBMS/assets/93427248/cd2181c8-608b-4d44-aa7e-33c0ff727723)

### 4) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```
### OUTPUT:
![image](https://github.com/DrUmaRaniV/DBMS/assets/93427248/5b492a77-7962-4143-ba36-6460ce376e61)

### 5) Delete the mystudent rows using truncate keyword

### SQL QUERY: 
```
truncate table mystudent;
```
### OUTPUT:
![image](https://github.com/DrUmaRaniV/DBMS/assets/93427248/71b47179-7c56-4aa1-ab96-518edda3eb7a)

### 4) Drop the mystudent table
 
### SQL QUERY: 
```
drop table mystudent;
```
### OUTPUT:
![image](https://github.com/DrUmaRaniV/DBMS/assets/93427248/94e6ab79-7441-48f5-9d58-96c082412afa)

## Result:
         Thus the basic DDL commands in SQL are executed. 


