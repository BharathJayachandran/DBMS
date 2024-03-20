# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE : 20/03/23

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
create database studentdbb;
```

### OUTPUT:
![281072399-58fc5109-3fe3-4b71-adfa-c8de97a3eb0c](https://github.com/BharathJayachandran/DBMS/assets/122089525/0499e573-d393-4037-a183-e7403d8a0601)


### 2) Create a table student  and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
```
 create table student(RegisterNumber int,Name varchar(100),Age int,Address varchar(250),PhoneNumber int) ;
```

### OUTPUT:
![281076398-2ed4d00e-5741-4f71-a0d2-0384650e6dae](https://github.com/BharathJayachandran/DBMS/assets/122089525/9e71e4e7-2c4e-4e22-96df-553b99b952cb)


### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
```
 alter table student add dept varchar(20);
```

### OUTPUT:
![281076826-0d709df7-9e80-4b2c-a358-dac94a29b6fa](https://github.com/BharathJayachandran/DBMS/assets/122089525/a616203a-5ff1-4b33-b6e1-1a3d24b659cb)


### SQL QUERY: 
```
rename table student to mystudent;
```

### OUTPUT:
![281077173-331990e2-babb-47a7-8576-d71ef8928eb3](https://github.com/BharathJayachandran/DBMS/assets/122089525/21a1840c-59e4-45e4-8ba8-bb1e41f69ac5)


### 5) Delete the mystudent rows using truncate keyword

### SQL QUERY: 
```
 truncate table mystudent;
```
### OUTPUT:
![281077364-73984590-23c6-4463-bb92-bfd6325824df](https://github.com/BharathJayachandran/DBMS/assets/122089525/5cf039f1-3799-4f34-ad82-a73624e4f4df)

### 4) Drop the mystudent table
 
### SQL QUERY: 
```
 drop table mystudent;
```

### OUTPUT:
![281077611-f798b751-c946-4215-83de-d22ebf9c9d73](https://github.com/BharathJayachandran/DBMS/assets/122089525/ea11a062-def2-435c-af35-be5524710847)



## Result:
<div align="justify">
       Thus the basic DDL commands in SQL are executed.
</div>
