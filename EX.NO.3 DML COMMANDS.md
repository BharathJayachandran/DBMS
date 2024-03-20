# EXP NO 3: Data Manipulation Language (DML) Commands and built in functions in SQL
### DATE : 23/08/23

## AIM:
To create a manager database and execute DML queries using SQL.

# THEORY
## DML(Data Manipulation Language)
*  The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements.
*  It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.

## List of DML commands: 
1. INSERT: It is used to insert data into a table.
2. UPDATE: It is used to update existing data within a table.
3. DELETE: It is used to delete records from a database table.
4. SELECT: The SELECT command shows the records of the specified table.

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![271174892-081ff76d-e743-4fee-993b-4fd367716f94](https://github.com/BharathJayachandran/DBMS/assets/122089525/d9172c1c-1f21-4336-83c3-6ab35b62fce9)

### OUTPUT:

![271174912-b667993b-d5b9-4197-be2c-ee7cab1c7d1e](https://github.com/BharathJayachandran/DBMS/assets/122089525/5119d9e8-1293-4f6b-b77b-f15c5c109757)

### Q2) Delete the records from manager table where the salary less than 2750.

### QUERY:

![271174961-c3469723-36d2-4488-ac58-b5c8683a0e93](https://github.com/BharathJayachandran/DBMS/assets/122089525/3886fd54-c7f1-4b5b-a106-ef22d6f90f51)

### OUTPUT:

![271174985-91233fd3-5dfa-4318-b62f-db528e31914c](https://github.com/BharathJayachandran/DBMS/assets/122089525/942c2551-b4bd-461f-85aa-ccf532d7cfd9)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![271175005-180d48fb-dd02-4d7e-991d-79e92d50f3ae](https://github.com/BharathJayachandran/DBMS/assets/122089525/a33f6a03-e032-4e4c-b654-2b0ff1b53ceb)

### OUTPUT:

![271175026-cbf1e6e9-9633-4cf9-ad85-341e7b03c613](https://github.com/BharathJayachandran/DBMS/assets/122089525/418ac555-075e-4310-bc77-c9f6da16bf6b)

### Q5)	List the names of Clerks from emp table.


### QUERY:

![271175071-feb4b41d-8428-440b-8961-078212a7e836](https://github.com/BharathJayachandran/DBMS/assets/122089525/14ea8e85-c7a4-4d5d-b61f-36f60f2fa267)

### OUTPUT:

![271175098-86f71191-94a7-45e6-b756-6020a06350b7](https://github.com/BharathJayachandran/DBMS/assets/122089525/680db43e-171e-4e2f-a4af-6d9340ed7a12)


### Q6)	List the names of employee who are not Managers.

### QUERY:

![271175146-a65b548c-2cd5-45c9-b21b-89cbdb1114c4](https://github.com/BharathJayachandran/DBMS/assets/122089525/953efa8b-2b86-45ae-a3fb-be3882368f31)


### OUTPUT:
![271175187-02933c79-0073-4274-9b90-2bc9f4814d8b](https://github.com/BharathJayachandran/DBMS/assets/122089525/6b56eba8-c0ed-40cf-8c5e-48ee56f531d0)


### Q7)	List the names of employees not eligible for commission.

### QUERY:

![271175220-6d3c980b-752e-4df5-9648-2a4bcf6e1962](https://github.com/BharathJayachandran/DBMS/assets/122089525/1b9447f3-4891-4dfc-bcc5-a542b4b0fdd5)

### OUTPUT:
![271175271-f4a825b1-ac41-4d65-9b0c-e59a55e4ca33](https://github.com/BharathJayachandran/DBMS/assets/122089525/552a9248-563d-440f-a61f-4e05764f5b80)


### Q8)	List employees whose name either start or end with ‘s’.

### QUERY:

![271175311-aec361f2-371a-43c0-8be2-7fae5ecfa2e8](https://github.com/BharathJayachandran/DBMS/assets/122089525/a303e2dc-8760-4bdf-95f8-c1ea7dd9c544)



### OUTPUT:

![271175346-6c098d6f-d039-4325-9810-93275772b07f](https://github.com/BharathJayachandran/DBMS/assets/122089525/1a636d60-0795-461a-a106-0aa27c519e74)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:

![271175362-89b37e50-40ad-42ab-9d4a-dbba66165238](https://github.com/BharathJayachandran/DBMS/assets/122089525/c9a45dce-ed85-47ec-a09e-772b21e7de58)


### OUTPUT:

![271175394-9bd94ed7-a460-4084-8ede-87fdaf6191cf](https://github.com/BharathJayachandran/DBMS/assets/122089525/2df24266-161b-42b1-834a-c5717561c54b)



### Q10) List the Details of Employees who have joined before 30 Sept 81.

### QUERY:

![271175413-a5349ed1-9a23-4d89-ad1f-4f1ea9cd63c0](https://github.com/BharathJayachandran/DBMS/assets/122089525/a2ccb688-9551-46e3-b4d6-2ef6d488fcc8)


### OUTPUT:

![271175439-85269e01-cc98-47d0-8e3a-18ca0b00d42e](https://github.com/BharathJayachandran/DBMS/assets/122089525/79b48a7e-ccc1-4a1b-9850-1c6c10f06de8)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.

### QUERY:

![271175474-faf3c43b-22f9-467b-ac0d-ce28c829d279](https://github.com/BharathJayachandran/DBMS/assets/122089525/59870fff-4dcc-49bd-b365-9a05c326ffe4)


### OUTPUT:

![271175517-4298c229-f964-4b6d-a0a2-a95cf3efb38c](https://github.com/BharathJayachandran/DBMS/assets/122089525/656d8070-13c6-4d61-8c4d-af788095c677)


### Q12) List the names of employees not belonging to dept no 30,40 & 10

### QUERY:

![271175548-b8bed764-1ff6-4925-a0e7-a6c41359274e](https://github.com/BharathJayachandran/DBMS/assets/122089525/0819e97c-a491-4cc3-8d24-476727289ece)


### OUTPUT:

![271175574-971930f3-b375-4560-acfc-2319350f6264](https://github.com/BharathJayachandran/DBMS/assets/122089525/d2c23a07-e852-4e4d-8114-87774dfd3d52)

### Q13) Find number of rows in the table EMP

### QUERY:

![271175622-ddeee89b-b882-4857-b1b6-9d03bafb1db5](https://github.com/BharathJayachandran/DBMS/assets/122089525/0091ee72-0d28-43eb-b5ed-7e592749708e)

### OUTPUT:

![271175637-d33535ee-03c1-4985-a55c-a101cc7ee17b](https://github.com/BharathJayachandran/DBMS/assets/122089525/218b6789-ede9-4007-88a9-89ab8040ee3f)

### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![271175678-cf58aa29-f3fa-4c7f-8d1f-d6a59c8ea7dd](https://github.com/BharathJayachandran/DBMS/assets/122089525/8d32d702-fd81-4722-9663-38e415f118b0)


### OUTPUT:

![271175689-4b00eb99-b144-4f53-becb-39f06680a9f3](https://github.com/BharathJayachandran/DBMS/assets/122089525/457310f6-5816-4e20-8916-572553101df4)

### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![271175705-534963f4-9772-4bab-90ec-1ccef54fb3c5](https://github.com/BharathJayachandran/DBMS/assets/122089525/fc2cf83f-280c-4e06-8b9b-98a2c2b27c68)

### OUTPUT:

![271175721-c0e4cac3-dd5f-40df-84f2-d3126c560d40](https://github.com/BharathJayachandran/DBMS/assets/122089525/6278dc3d-fd06-4cab-a8ae-d7ef1ce3882d)


### RESULT:

Thus the basic DML commands are executed
