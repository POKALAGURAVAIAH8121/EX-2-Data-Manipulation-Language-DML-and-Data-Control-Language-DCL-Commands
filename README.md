# EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands

# AIM:

To create a manager database and execute DML queries using SQL.

# DML(Data Manupulation Language)

The SQL commands that deal with the manipulation of data present in the database belong to DML or Data

Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that

controls access to data and to the database. Basically, DCL statements are grouped with DML statements.

# List of DML commands:

INSERT: It is used to insert data into a table.

UPDATE: It is used to update existing data within a table.

DELETE: It is used to delete records from a database table.

# Create the table as given below:

create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));

# insert the following values into the table

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/ceb86566-9637-44a0-a158-f867ad51a0ee)

# Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/219ec86c-bdad-494e-aea4-02ac3a952c75)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/4e0f0f89-f96a-4c39-99ab-633b2c899658)

# Q2) Delete the records from manager table where the salary less than 2750.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/f0784fcc-c049-4faa-90c2-049be9f8ca69)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/b771ad5b-95e0-41a0-99d1-84f4fa514def)

# Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/5982029a-4920-4bf0-8726-f1a4c4d9acfc)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/f8a2eb5f-0652-487e-8121-8a60b16b3fbe)

# Q5) List the names of Clerks from emp table.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/3d3177d9-f123-4dae-8cbd-6e2118615e3e)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/d7c79611-2320-4aae-93fa-c28ddfe8c26b)

# Q6) List the names of employee who are not Managers.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/460be39c-c13f-49a1-a504-dea23ab48d64)

OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/63de22d9-b75c-4106-a33e-aef1fe65577d)

# Q7) List the names of employees not eligible for commission.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/fa465def-ced0-4c5e-8074-cb8492dad27c)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/a9a45881-7b45-4dd8-b506-5e124b8550f3)

# Q8) List employees whose name either start or end with ‘s’.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/24ea8056-0815-4055-b60e-5a271e0b11b1)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/cd7f53ec-e016-458f-955b-7470fd0f5a3b)

# Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/834109c4-31b5-43df-b970-33c10edc1b3e)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/d45ee7ea-ffa1-4ed2-b469-41791a4e882c)

# Q10) List the Details of Employees who have joined before 30 Sept 81.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/44626ceb-4f24-42bb-9752-b8c56760e07d)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/60933210-811c-4f55-aef2-a6061f9d3242)

# Q11) List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/40f30ae9-e0cf-4568-a149-eef64584c5fe)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/d0631c7a-1e24-4535-ad9e-f1729faa5d22)

# Q12) List the names of employees not belonging to dept no 30,40 & 10

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/2c40d374-ff9f-4e33-92ea-bf2ada20df4d)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/47d72df3-1002-45dc-917e-0a47e276b363)

# Q13) Find number of rows in the table EMP

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/883285be-29aa-48b4-aadc-cad77d548145)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/48e8b9cd-dde0-4146-b555-90ad5b57cf7d)

# Q14) Find maximum, minimum and average salary in EMP table.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/bbd4832b-c078-4ed6-876b-69cd881cd898)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/4050b724-5c0d-4907-b258-0aafd7703b12)

# Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

# QUERY:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/9d778789-1ded-4dd3-97b4-e432d69007a4)

# OUTPUT:

![image](https://github.com/POKALAGURAVAIAH8121/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128034765/9c916518-b1bb-48fd-baa9-ae28b5151358)
