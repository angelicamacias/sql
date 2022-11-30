What is data?

Highly used in software and IT industries. 

What is data?
Any information is known as data. Any facts of figures, or information that's
stored in or used by a computer:
-Number
-Facts
-Informatin
-Graphs
-Observations
etc 

What is a database? 

A database is an organised collection of data stored which can be accessed electronically 
Small databases can be stored on a file system, while large databases 
are hosted on computer clusters or cloud storage.

This is so importan because: 
Organized collection of data is sotred in a computer system which can be accessed
electronically means through remote you can access that is nothing but databasese.

Examples to database: 
- MySQL
- SQL Server
- MongoDB
- Oracle Database
- PostgreSQL
etc 

but...

==> How to fetch those data our form this servers?

We will use a SQL. 

SQL is the place where we are storing the data. So for storing the data, we have 
to use database server and to fetch this information from database we have to 
use a database language which is nothing but SQL.

==> How data is stored in database? 
Data is sotred in database in a row and column in the table format. 

==> Why do we need database?
We need to store our data in a secure place so that nobady else can access it. 
proof
You can store the data securely and you can access remotely electronically from 
any remote location and that your data will be very safe within database because
it will be highly configured. 

==> Why DBMS and SQL? 

Databases can store very large numbers of records efficiently
It is very quick and easy to find information 
It is easy to add new data and to edit or delete old data.
Data can be searched easily. 

SQL: SQL (DB language) lets your access and mnipulate databases. 
- It is widely used in the business intelligence tool 
- Data manipulation and data testing are donde through SQL
- Data science tools depend highly on SQL.Big data tools such as spark, impala 
are dependent on SQL.

==> How to access data from databases? 
We first need to connect to the database by giving username and password. 
SQL is used to communicate with a database.


==> To use database? 
- Need to install DB Server(SQL/Qracle etc) with sufficient memory and internet connection.
- Adatabase user should be granted all required permissions.
Once database intalled we can:
 - Creat multiple tables and link relation between tables 
 - Insert data into tables 
 - Manipulate the data 
 - Retrieve tha data
 etc. 

==> What is SQL?

SQL is a satandard language for accessing and manipulating databases 
- SQL stands for Structured Query Language (structured = sequel)
- SQL lets you access and manipulate databases


Retrieving those information in this case and displaying to the user. 


==> Where are ue using database in software? 

- Understanding importance of DB, here all the app sata will be sotred in the DB
- Which can be acessed via App server and based on the programing sql query will be
formed and fetch the data and display in the UI. 

Example: searching flights / Train / Signup 

==> Use of SQL?
Un tipo de lenguaje de programación que te permite manipular y descargar datos de una 
base de datos. 
Te ahorra mucho tiempo. Puedes descargarte datos con consultas ya codificadas para 
automatizar procesos

- SQL can execute queries against a database
- SQL can retrieve data from a database
- SQL can insert records in a database
- SQL can updata records in a database
- SQL can dalete recrods from a database
- SQL can create new databases
- SQL can create new tables in adatabase
- SQL can create stored procedures in a database
- SQL can create views in a database
- SQL can set permissions on tables, procedures and views

==> Use of SQL in software?

 
Developer will write a SQL query in the program, writing the program, fetch 
those informtaion and use those information page by the skill query in the program.

==> Use of SQL as a QA?

The main objective is like sql is also widely used as in machine learning
analytics and data scientist. 
So as a data, dta scientist, what you have to do is you have to fetch those 
information and retrieve those information and put it into the website. 
You have to order to try and maniulate those data into multiple platform.

-accent from the UI and then retrieving the data from the database using
a sql query in the same way data scientist also they will be, you know, all
the data will be ther into the database, they will just
query those information and display it to the user dased on the logic and
design pattern

==> What is RDVMS? 

The data in an RDBMS is stored in database objects which are called tables. This 
table is basically a collection of related data entries and it consists of 
numerous columns and rows.

relaciona information with tables. 
 
 Advantages of SQL?
 - Faster query procesing
 - Standardiesd language
 - Multiple data views
 - Interactive language
 - Portable
 - No coding skills 

Disabanages of SQL?
- Poor interface
- Cost inefficient
- Partial control
- Security 

SQL queries types? 
Data definition language(DDL)
  DDL -- create, alter, drop, truncate, rename 
Data manipulation language (DML)
  DML -- insert, update, delete
Data retrieval language (DRL)
  DRL--select
Transaction control language 
  TCL -- commit, rollback, savepoint
Data control language (DCL)
  DCL-- grant, revoke 

What is a Query? 
A request for data from single or multiple tables in the databases. 
password postgres: posgt123
==> Create tables syntax
CREATE TABLE is a keyword, telling the database system to create a new table.

syntax
```
CREATE TABLE table_name(
  column1 datatype,
  column2 datatype,
  ...
  columnN datatype
  (PRIMATY KEY (one or more columns))
);


==> Primary key?
A primary key is used to ensure data in the specific column 
is unique. It is a column can not have null values. 
It's a combination of 
UNIQUE and NOT NULL constraints. 

==> Foreign key?
A foreign key is a column or group of columns 
in a relationl database table that provides a link between 
data in two tables. 
It is a column (or columns) that references a column (most often the primary key) of another table. 

A table can have multiple foreign keys based on the requirement, primaty key just one time. 

quiz:

What allows us to define how various tables are related to each other formally in a database?  Foreing key
Which statement is false for a FOREIGN KEY constraint?
Foreing key is automatically created when two tables are joined.
---------------------------- INSERT -----------------------------
'INSER': means how we can insert the data into database tables.

The postgreSQL INSERT INTO statement allows one to insert new rows into a table. One can isert a signel row at a time or serveral roes as a result of a query. 
We have two methods to insert. 
 - By INSERTING DATA INTO SPECIFIED COLUMNS USING VALUE METHOD
 - By value METHOD 

1 ==> Inserting data into specified columns using value method 

-Syntax: 
INSERT INTO TABLE_NAME(column1, column2,... columnN)
VALUES(value1, value2,... valueN);

example
INSERT INTO COMPANY (ID,NAME,AGE,ADDRESS,JOIN_DATE) VALUES (1'Angelica',23,'MEXICO','2022-11-21');
INSERT INTO COMPANY (ID,NAME,AGE,ADDRESS,SALARY,JOIN_DATA) VALUES(2,'Juan',34,'USA',900000,'2022-11-21');

Here column1, column2... columnN are the names of the columns 
in the table into which you want to inser data 
The target column names can be listed in any order. 

=> Multiple data - insertion:
-Syntax: 

INSERT INTO TABLE_NAME(column1, column2,... columnN)
VALUES(value1, value2,... valueN),(2value1, 2value2,... valueN)

the second values are separate by coma

example:
INSERT INTO COMPANY(ID,NAME,AGE,ADDRESS,SALARY,JOIN_DATA)
VALUES(4,'Blanquito',3,'Alemania,789000,'2022-11-21),(5,'Gris',6,'Canada',452000,'2022-11-21');

refrech the database and see the table or use select querty to see the tables --->     select * from company; 

2 ==> Without value method 

You may not need to specify the column(s)  names in th SQL query if you are adding vales for all the columns of the table. However, make sure the order of the values is in the same order as the columns in the table

-Syntax:

INSERT INTO TABLE_NAME(vale1,value2,...valueN);

exampl:
INSERT INTO COMPANY VALUES(3,'Billy',8,'Rusia',541000,'2022-11-21');

refrech the databases and see the table or use select query to see the tables --> select * from table_name

------------------- SELECTING / FETCHING DATA --------------------
-syntax Select all column
select * from <table_name>    --here * indicates all columns 
 
 exampple:
 select * from COMPANY;

                       OR

-syntax select specific column 
select col1, col2,... coln form <table_name>;

 example:
 select ID,NAME,SALARY form COMPAYN;

------------------------------------------------------------------
QUIZ 
What is the name of the component that requests data to the PostgreSQL server? CLIENt
-------------------------------------------------------------------

==> CONDITIONAL SELECTIONS AND OPERATORS

We have two clauses used in this
 1.- Where: we can put some condition like where if is greater than 20 salary's grater that 50. 
 2.- Order by: Is used where we have to sort the record like ascending order, descending order. 

1) Using Where
syntax:

slect * from <table_name>where<condition>;

The following are the differtent types of operators used in where clauses. 
    - Arithmetic operators
    - Comparison operators
    - Logical operators
 -Arithmetic operators
  +,-,*,/

  select name,salary+32 form company;
  select name,salary-32 form company;
  select name,salary*2 form company;
  select name,salary/10 form company;
  select name,salary+32 form company where id = 1;
  select name,salary+salary*50/100 from company; #increase salary by 5% for all 
  select name as Employee_Name,salary+salary*50/100 as increased_Salary from company;




 -Comparison operators:
  =, !=, <,>, >=, <=, <>

  = --> select*from COMPANY where ID=4;
        select ID,Name,salary from COMPANY where ID=4;

  < --> select*from COMPANY where ID < 3;
  
  > --> select*from COMPANY where ID > 2;

  => --> select*from COMPANY where ID >= 2;

  =< --> select*from COMPANY where ID <= 3;

  != --> select*from COMPANY where ID != 2; todos exepto el 2

  <> --> select*from COMPANY where ID <> 2;
        
  between, not between 
  in , not in 
  null, not null
  like 
 
 between 
  This will give the output based on the column and its lower bound, upper bound. 

  syntax:
   select*from<table_name>where<col>between<lowe bound>and<upper bound>;
  example:
   select*from COMPANY where SALARY between 90000 and 100000;
 
 Not between 
  This will give the output based on the column wich values are not in its lower bound, upper bound.
  syntax:
  select*from<table_name>where<col>not between<lowe bound>and<upper bound>;
  example:
  select*from COMPANY where SALARY not between 90000 and 100000;
 
 IN 
  This will give the output based on the column and its list of values specified. 
  syntax:
  select*from<table_name>where<col>in (value1, value2, valueN);
  example:
  select*from COMPANY where ID in (1,3,4);
  select Name,Salary from COMPANY where Age in (28,29,30);

NOT IN 
 This will give the output bases on the column which values are not in the list of values specified. 
 syntax:
 select*from<table_name>where<col> not in (value1, value2, valueN);
 example:
 select*from COMPANY where ID NOT IN (1,3,4);

NULL
 This will give the output based on the null values in the specified column. 
 syntax:
 select*from <table_name>where<col>is null;
 example:
 select*from COMPANY where SALARY is NULL;

NOT NULL 
 This will give the output based on the not null values in the specified column.
 syntax:
 select*from <table_name>where<col> is NOT NULL;

LIKE
 This will be used to search through the rows of the database column based on the pattern you specify.
 Wildcatd characters are used with the LIKE operator. The LIKE operator is used in a WHERE clause to serach for specified pattern in a column. 

 syntax:
 select*from<table_name>where<col>like<pattern>;
 
 example:
 This will give the rows whose name starts with 'R'.
 - select*from COMPANY where NAME like 'R%';    #(start with R)
   select*from COMPANY where NAME like '%R';    #(ends with R)
   select*from COMPANY where NAME like '_R';    #(Second letter start with R)
   select*from COMPANY where NAME like '__R%';   #(Third letter starts with R)
   select*from COMPANY where NAME like '%_R%';   #(Second letter onwards start with R from ending)
  select*from COMPANY where NAME like '%__R%';   #(Third letter start with R from ending)
  select*from COMPANY where NAME like '%R%R%';   #(Whose name contains two R's) 
  select * from comany where name like '%ri%'; #(whose contains "ri" in the name)

 -Logical operators
  And 
  Or
  not 

  And 
  This will give the output when all the conditions become true. 
  syntax:
  select*from <table_name>where<condition1>and<condition2>and<conditionN>
  example:
  select*from COMPANY where ID < 5 and SALARY >= 8000;

  OR
  This will give the output when either of the conditions become true.
  syntax:
  select*from <table_name>where<condition1>or<condrionN>;

2) ORDER BY

This will be used to otder the column data (ascending or descending)
The ORDER BY statement in sql is used to sort the fetched data in either ascending or descending according to one or more columns. 
 -By default ORDER BY sorts the data in ascending order. 
 -We can use the keyword DESC to sort the data in descending order and the keyword ASC to sort in ascending order. 

Sort according to one column: To sort in asecending or descending order we can use the keyword ASC or DESC respecively. 

Sort according to multiple columns: To sort according to multiple columns, separate the names of columns by (,) operator. 

syntax:
SELECT * FROM table_name ORDER BY column1 ASC|DESC, column2 ASC|DESC

syntax:
Select*from <table_name>order by <col> desc;

by default oracie will use ascending order. 
If you wanto output in descending order you have to use desc keyword after the column. 

example:
select*from COMPANY order by ID;
select*from COMPANY order by SALARY desc; #for descending 
select*from COMPANY order by ID asc, SALARY desc;  #ID will be acending and SALARY will be descending


---------------------- SQL GROUP BY STATEMENT---------------------
The GROUP BY statment groups rows that have the same values into summary rows, like "find the number of employees in each departament"

The GROUP BY statement os often used with aggregate functions (COUNT, MAX, MIN, SUM, AVG) to group the result-set by one or more columns. 

-Aggregate functions:
An aggregate function performs a calculation on a ser of values, and returns a single value. 
OR 
Aggrefate function is a function where the values of multiple rows are grouped together as input on certain criteria to form a single value of more significant meaning. 

Except for COUNT(*), aggregate functions ignore null values. Aggregate functions are often used with the GROUP BY clause of the SELECT statement.
 
 Count():
  1. count(*): Returns total number of records .i.e 5
  2. count(salary): Return number of non null values over the column salary i.e 4
  3. connt(Distinct salary): Return number of distinct Non Null values over the column salary .i.e
 Sum():
  1. sum(salary): Sum all Non Null values of column salary .i.e, 310
  2. sum(Distinct salary): Sum of all distinct Non-Null values .i.w, 250
 Avg():
  1. Avg(salary)= sum(salary)/count(salary)= 310/5
  2. Avg(distinct salary)= sum(Distinct salary) / count(Distinct salary) = 250/4
 Min()/Max():
  1. Min(salary): Minimun value in the salary solumn except NULL .i.e 40
  2. Max(salary): Maximum value in the salary .i.e, 80.
examples:

select COUNT(SALARY) from COMPANY;
select MAX(SALARY) from COMPANY;
select MAX(SALARY),address from COMPANY group by address;
select MIN(SALARY) from COMPANY;
select MIN(SALARY),address from COMPANY group by address;
select SUM(SALARY) from COMPANY;
select SUM(SALARY),addreess from COMPANY group by address;
select AVG(SALARY) from COMPANY;
select AVG(SALARY),address from COMPANY group by address;

------------------------- GRUOP BY SYNTAX ------------------------

SELECT column_name(s)
FROM table_name
WHERE condition
GROUP BY column_names(s)
ORDER BY column_name(s);

1examples: Gives address and it's repeated counts

select COUNT(ID),address
from COMPANY
group by address;
#it will create a multiples groups from the address.

select address,COUNT(ID)
from COMPANY
group by address;

2example; 
The following SQL statment lists the number of employe in each departments sorted high to low:

Gives address and it's repeated counts in descending order

select address, COUNT(ID)
from COMPANY
group by address
order by COUNT(ID) DESC;
#With this we will create a grupos depending for the address, and the order of the data will be descending. 

--------------------- The SQL HAVING clause ----------------------
The HAVING clause was added to SQL because the WHERE keyword coluld not be used with aggregate functions. 

HAVING SYNTAX
SELECT column_name(s)
FROM table_name
WHERE condition
GROUP BY column_name(s)
HAVING condition
ORDER BY column_name(s);

The following SQLstatement lists the number of ID COUNT each address. Only include address with mor than 2 adn equals employee ID count:

example:

select address,count(ID)
from COMPANY 
where ID>=1
group by ADDRESS
Having count(ID)>=2;
#select the columns address and count from the table company where the ID are equal or greater that 1 createing groups for the address having count id equal or greter that 2.

select address,count(ID)
from COMPANY 
group by Address
Having count(ID)>=2
order by count(ID) DESC;

---------------------------USING DML------------------------------
==> Using update
The can be used to modify the table data. 
syntax:
update<table_name> set <col1>=value1, <col2>= value2 where <condition>;

example:
list:
select * from COMPANY order by ID;
want to update soun age from 30 to 32
 1.- By ID, name, salary, address and joining date
 2.- Why by ID - PK

syntax:
update company set AGE = 32 where ID =3;
 age will be updated 
if you are no specifying any condition this will update the entire table data. 

update company set AGE = 33, SALARY = 95000 where ID = 3;
 age and salary will be updated

==> USING DELETE
This can be used to delete the table data TEMPORARILY

syntax
DELTE FROM table_name WHERE condition;
example:
 delete student;
 if you are not specifying any condition this will delete the entire table 
inserting a dta to ve delted:
insert into company values (9, 'AK, 22, 'USA', 785000, '2022-03-02');

delet from COMPANY where ID = 9;
ID = 9 will be deleted. 

----------------------------USING DDL-----------------------------
==> Using alter
This can be used to add or remove xolumns and to modify the precision/structure of the data type. 

a) ADDING COLUMN 
syntax:
alter table <talbe_name> add <col data type>;

example:
alter table COMPANY add edob date;

b) Removing column 
syntax:
alter table <table_name> drop <col datatype>;

example:
alter table COMPANY drop edob;
-edob will be removed

c) Increasing or decresing precision of a column 

syntax:
 alter table<table_name> modify <col datatype>;
example:
 alter tabel COMPANY alter column address TYPE CHAR(60);

d) Renaming column 

syntax 
alter table<table_name> rename column <old_col_name> to <new_col_name>
example:
alter table company rename column edob to empdob;
column name will be changed fromn edob to empodob 

------------------------- USING TRUNCATE -------------------------
The SQL TRUNCATE TABLE command is used to delete complete data permanently from an existing table.
syntax:
 truncate table <table_name>;

example:
creating a dummy table and adding few data into it

CREATE TABLE DEPARTAMENT(
  ID INT PRIMERY KEY NOT NULL,
  DEPT CHAR (50) NOT NULL,
  EMP_ID INT NOT NULL
);
INSERT INTO DEPARTAMENT (ID,DEPT,EMP_ID)values (1,'IT', 25), (2,'CS',29);
select * from DEPARTEMENT;

truncate table DEPARTEMENT;
#table structure is there, buT data is not there.

--------------------------- USING DROP ---------------------------

The DROP TABLE statement is used to drop an existing table in a database. 
This will be used to drop the database object;

syntax:
 drop table <table_name>;
example:
 drop table DEPARTAMENT;

IT WILL DELTE THE DATA AND TABLE

------------------------------ JOINS -----------------------------

The purpose of a join is to combine the data across tables.
A join is actually performed by th where clause which combines the specified rows of tables. 
If a join involves more than two tables then oracle joins the first two tables based on the joins condition and then compars the result with the next tablw and so on. 

understanding pk and fk 

creating another table along with company - for clear understanding 
we have already created three different tables to practice: Let's insert the data into tables
==============> EJERCICIO 2

CREATE TABLE EMPLOYEE_COURSE(
  ID INT,
  COURSE_NAME CHAR(50) NOT NULL,
  COURSE_ID INT,
  COURSE_JOIN_DATE DATE,
  FOREIGN KEY(ID)
  REFERENCES COMANY(ID),
  FOREIGN KEY (COURSE_ID)
  REFERENCES COURSE (COURSE_ID)
);

CREATE TABLE COMANY(
  ID INT PRIMARY KEY NOT NULL,
  NAME TEXT NOT NULL,
  AGE INT NOT NULL, 
  ADDRESS CHAR(50),
  SALART REAL, 
  JOIN_DATA DATE
);

CREATE TABLE COURSE(
  COURSE_ID INT NOT NULL,
  COURSE_NAME CHAR(50) NOT NULL,
  DURATION INT NOT NULL,
  PRIMARY KEY(COURSE_ID)
);

INSERT INTO COMANY vALUES (1,'Angelica Macias',23,'Mexico',230000,'2021-11-22'),
(2,'Juan Carrillo',34,'Canada',950000,'2021-11-22'),
(3,'Blanquito Kumar',25,'Alemania',452000,'2021-11-22'),
(4,'Krity Gupta',36,'India',323000,'2021-11-22'),
(5,'Gris Kumar',23,'Mexico',230000,'2021-11-22'),
(6,'Billy Carrillo',38,'Japon',430000,'2021-11-22');
select * from COMANY;

INSERT INTO COURSE VALUES (30,'Java',28),(31,'Python',5),(32,'SQL',4),(33,'ML',30),(34,'AL',25),(35,'Testing',10);
select*from COURSE;

INSERT INTO EMPLOYEE_COURSE VALUES(1,'Java',30,'2021-11-22'),(1,'Python',31,'2021-11-22'),(2,'Java',30,'2021-11-22'),(4,'ML',33,'2021-11-22'),(4,'AL',34,'2021-11-22'),(5,'Testing',35,'2021-11-22'),(6,'Java',30,'2021-11-22'),(6,'SQL',32,'2021-11-22');
select * from EMPLOYEE_COURSE;

--Inserting some null values 
INSERT INTO COMANY VALUES(7, 'Manchitas Ramirez' , 28, 'Mexico',630000);
INSERT INTO COURSE VALUES (36,'Introduction',1)
INSERT INTO EMPLOYEE_COURSE VALUES(2,'Introduction',36)

=======> SQL Joins 

A SQL Join statement is used to comine data or rows from two or more tables based on a common field between them.
-The pourpose of a join is to combine the data across tables. 
-If a join involves more than two tables then oracle joins the first two tables based on the joins condition and then comparse the result with the next table and so on.
-A query can contain zero, one, on multiple JOIN operations. 
-Minimum required condition for joining table, is (n-1) where n, is number of tables. 
To join 3 tables -2 Joins are required (n-1=3-1=2 condition)

By using joins, we can retrieve data from two or more tables based on logical relationships between the tables. 
 - Joins indicate how database server should use data from one table to select the rows in another table. 
 - Based on our requirement we use joins. 

 --> Left join
 --> Right join
 --> Inner join
 --> Full outer join 
 --> Natural join
 --> Self join
 --> croos join 

--> Inner join

The INNER JOIN keyword select all rows from both the tables as long as where is match between the columns in both the tables 
We can also write JOIN instead on INNER JOIN 

- Syntax 

SELEC table1.column1, table1.column2, table2.column1,...
FROM table 1
INNER JOIN table2
ON table1.matching_cloumn= table2.matching_column 

table1: First table
table2: Second table
matching_column: Column common to both the tables 


-example

List all the matching data from both the table
SELECT COMANY.ID,COMANY.NAME,
EMPLOYEE_COURSE.COURSE_NAME,EMPLOYEE_COURSE.COURSE_JOIN_DATE
FROM COMANY #left table
INNER JOIN EMPLOYEE_COURSE #rigth table
ON COMANY.ID = EMPLOYEE_COURSE.ID; #this two tables have a comun ID


SELECT COMANY.ID,COMANY.NAME,
EMPLOYEE_COURSE.COURSE_NAME,EMPLOYEE_COURSE.COURSE_JOIN_DATE
FROM COMANY
INNER JOIN EMPLOYEE_COURSE
ON COMANY.ID = EMPLOYEE_COURSE.ID 

--> Righ join 

The RIGTH join keyword returns all the rows from the RIGTH table (table2), with matching rows in the LEFT table(tabl1)
The result is NULL in the LEFT side when there is no match 
RIGTH join is also known as RIGHT outer join 

#join means it will fetch all the data from the righ table on only matching dara from the left table. 

SELEC table1.column1, table1.column2, table2.column1,...
FROM table 1
RIGH JOIN table2
ON table1.matching_cloumn= table2.matching_column 

#Right means whenever you are doing right, join means you will get all the data from the right table, and only the match of the left table.

table1: First table
table2: Second table
matching_column: Column common to both the tables 

example:
SELECT COMANY.ID,COMANY.NAME,
EMPLOYEE_COURSE.COURSE_NAME,EMPLOYEE_COURSE.COURSE_JOIN_DATE
FROM COMANY
RIGTH JOIN EMPLOYEE_COURSE
ON COMANY.ID = EMPLOYEE_COURSE.ID;

all the data from the left table means company table and matching data on ly from the right table.

--> Full join 
The FULL JOIN keyword returns all the rows from the lef table(table1) and from the right table (table2)
FULL JOIN is also known as FULL OUTER JOIN 

syntax:
SELEC table1.column1, table1.column2, table2.column1,...
FROM table 1
FULL JOIN table2
ON table1.matching_cloumn= table2.matching_column 

table1: First table
table2: Second table
matching_column: Column common to both the tables 

example:
SELECT COMANY.ID,COMANY.NAME,
EMPLOYEE_COURSE.COURSE_NAME,EMPLOYEE_COURSE.COURSE_JOIN_DATE
FROM COMANY
FULL JOIN EMPLOYEE_COURSE
ON COMANY.ID = EMPLOYEE_COURSE.ID;

--> Natural join 
Similar to INNER JOIN and if we don't apply any join by default it takes as INNER Joins. 
A natural join can be a inner join,left, righ join however the default is inner join.
so, we don't need to put the join condtion for natural join
also, it avoids duplicate column names if any 

syntax:

SELECT*FROM table1
NATURAL join table2

example:

SELECT ID,DEPT FROM company
NATURAL JOIN EMPLOYEE;

adding duplicate record - INSERT INTO EMPLOYEE_COURSE VALUE (2,'Introduction',36)

if we want all the data use below:
example:    
SELECT * FROM COMPANY
NATURAL JOIN EMPLOYEE_COURSE;
#ALL THE MATCHING DATA FROM ALL THE TABLES

We have lef, rigth and full join on natural joins too:

SELECT * FROM COMPANY
NATURAL LEFT JOIN EMPLOYEE_COURSE;

SELECT * FROM COMPANY
NATURAL RIGTH JOIN EMPLOYEE_COURSE;

SELECT * FROM COMPANY
NATURAL FULL JOIN EMPLOYEE_COURSE;

Inner join vs natural join 

Using natural join we don't need to give the condition (bcz by default it's inner join) whereas for inner join we need to specify the conditions. 

--> CROSS/BARTESIAN JOIN 
It returns cartesian products. 

List all from both the tables 
 SELECT * FROM COMPANY 
 CROSS JOIN EMPLOYEE_COURSE;

If we want all the data use below:
 SELECT * FROM COMPANY 
 CROSS JOIN EMPLOYEE_COURSER;

it retruns cartesian products 

 SELECT * FROM company 
 CROSS join Employee_course;

--> SELF JOIN
It's similar to cross join on the same table.
Joining tables with the same tables 

List all data from the same tables afte salf join 
 
 SELECT COMPANY.ID,COMPANY.NAME
 FROM COMPANY
 SELF JOIN COMPANY
 ON COMPANY.ID = COMPANY.ID;

If we want all tha data using slef join use below:
  SELECT*
  FROM COMPANY
  SELF JOIN COMPANY
  ON COMPANY.ID = COMPANY.ID

------------------HOW TO JOIN MORE THAN 2 TABLES-------------------
Need employee ID, name, course name and course duration from all three tables??
Refer ERdiagram to understand the joins between tables. 

syntax:

SELECT table1.column1,table1.column2,table3.column1,..
FROM table1
INNER JOIN table2
ON table1.matching_column = table2.matching_column
INNER JOIN table3
ON table2.matching_column = table3.matching_column 

example:
SELECT
company.ID,COMPANY.NAME,EMPLOYEE_COURSE.COURSE_NAME,COURSE.DURATION
FROM COMPANY
INNER JOIN EMPLOYEE_COURSE
ON COMPANY.ID = EMPLOYEE_COURSE.ID
INNER JOIN COURSE
ON EMPLOYEE_COURSE.COURSE_ID = COURSE.COURSER_ID

------------------------- USE OF ALIAS ----------------------------

Temporay name of a table to avoid bigger names. 
- SQL aliases are used to five a table, or a column  in a table, a temporaly name. 
-An alias only exists for the duration of that query.
-An alias is created with the AS keyword. 

syntax:

SELEC column1,column2...FROM tabel_name AS alias_name 
WHERE [condition];

 SELECT t1.ID,t1.NAME,t2.DEPT,t2.EMP_ID
 FROM COMPANY as t1
 FULL JOIN EMPLOYEE as t2
 ON t1.ID = t2.ID;

BEFORE the ALIAS:

SELECT COMANY.ID,COMANY.NAME,
EMPLOYEE_COURSE.COURSE_NAME,EMPLOYEE_COURSE.COURSE_JOIN_DATE
FROM COMANY
RIGTH JOIN EMPLOYEE_COURSE
ON COMANY.ID = EMPLOYEE_COURSE.ID;

AFTER the ALIAS:

SELECT t1.ID,t1.NAME,
t2.COURSE_NAME,t2.COURSE_JOIN_DATE
FROM COMANY as t1
RIGTH JOIN EMPLOYEE_COURSE as t2
ON COMANY.ID = EMPLOYEE_COURSE.ID;

-----------SELECT FORM MULTIPLE TABLE WITHOUR USING JOINS----------

If you don't know will keeep thinking 

SELECT * FROM COMPANY c, EMPLOYEE_COURSE e
WHERE c.ID = e.ID;

---------------JOIN MULTIPLE TABLE WITH CONDITION -----------------
Fetch the employee whose salary is greater than 2 lac?

SELECT.t1.ID,t1.NAME,t1.SALARY,
t2.COURSER_NAME,t2.COURSER_JOIN_DATE
FORM company as t1
FULL JOIN EMPLOYY_COURSER as t2
ON t1.ID = t2.ID
WHERE t1.SALARY>200000;
**Salary is anailable in company table not in employee table, that's why taking t1 as reff.

--------------SUBQUERIES WITH THE SELECT STATEMENT-----------------

A subquery or inner query on nested query is a query within another postgreSQL query and embedded within the WHERE clause. 

A subquery is used to return data that will be used in the main query as a condition to futher restrict the data to be retrived, subqueries can be used with the SELECT, INSERT, UPDATE and DELETE statements along with the operators like =,>,<,>=,<=, IN, etc. 
There are a few rules that subqueries must follow:
   - Subqueries must ve enclosed within parentheses. 
   - A subqueries can have only one column in the SELECT clause, unless multiple columns are in the main query for the subquery to compare its selected columns. 
   -An ORDER BY can not be used in a subquery, although the main query can use an ORDER BY. The GROUP BY can be used to perform the same function as the ORDER BY in a subquery. 
   -Subqueries that return more than on row can only be used with multiple value operators, such as the IN, EXISTS, NOT IN, ANY/SOME, ALL operator. 
   - The BETWEEN operator can not be used with a subquery; however, the BETWEEN can be used within the subqueryr.

==> within same table

SELECT*FROM COMPANY WHERE ID IN (SELECT ID FORM COMPANY WHERE SALARY > 200000);

=> from two different table 

SELECT * FROM COMPANY WHERE ID IN (DELECT ID FROM EMPLOYEE_COURSE WHERE COURSE_NAME= 'Java');

-------------------------LIMIT AND OFFEST--------------------------
The linmit oprion allows you to limit the number of rows returned from a query. 
To limit the data to ve displayed
SELECT * FROM COMPANY LIMIT 4;--> display firest 4 added records 

Offest allows you to omit a specified number of rows before the beginning of the results set. 
Select * from company limit 4 offset 4; --> next 4 records

It will display next 4 record after 1st 4 records - It's like i have already view first 4 records and now i ant to scroll the page and view another next 4 recrods.

selec distinct(salay) from company order by salary desc;
select * from company order by salar desc limit 1; --> 1st highest salary  
select * from company order by salar desc limit 1 offset 1; --> 1st highest salary  
select * from company order by salar desc limit 1 offset 2; -->3rd highest salary  
select * from company order by salar desc limit 1 offset 3; --> 4th highest salary 


======================== SIMPLE QUERIES =====================

1.- List all the available course:
    select * from course;

2.- List course name and duration from the available course.
    select course_name,duration from course;
    
3.- List course_name and duration from course and rename course_name as "Name of the course", duration as "Course duration in hour"
    select course_name as "Name of the courser",duration as "Course duration in hour" from course;

4.- List name, annual slary from company
    select Name, SALARY*12 as "Annal salary" from COMANY;

    #We are multiplay for 12 because the salary is for a month.

===================== WHERE CONDITIONS ======================
--1.- List the details about "Juan Carrillo"
select * from comany where name = 'Juan Carrillo';
--2.- List out the emplouess whose age is greater than 28 years. 
select * from comany where age > 28;
--3.- List out the employess who are earing salary between 20lac and 40 la
select * from comany where salart between 200000 and 500000;
--4.- List outr the employess who joined on 05-jan-2022 or 07-jan-2022
select * from comany where join_data = '2021-11-22';
--5.- Lis out the emlopyess whose name start with "B"
select * from comany where name like 'B%';
--6.- List out the employess whose name contains "ir"
select * from comany where name like '%ri%';
--7.- List out the employess whose name length is 10 and start with "r"
select * from comany where name like '_________r%';
--8.- List out the employess who are working in Bangalore and draw the salaries more than 2000000
select * from comany where address = 'Mexico' and salart > 200000;

====================== ORDER BY CLAUSE =======================
--1.- List out the employee id, name in desecending order based on the employee id. 
select * from comany order by ID desc;
--2.- List out the employee id, name in ascending order based on salary column. 
select * from comany order by salart asc;
--3.- List out the employee details according to their id in asecending order and salary in descending order.
select * from comany order by id asc, salart desc;

=================== GROUP BY AND HAVING ======================

--1.- How many employees who are there in different address wise in the company. 

SELECT count(id),address 
from comany 
group by address;


--2.- List out the address wise maximum slary, minimun slary, avarage salary of the employess. 

select address,max(salart),min(salart),avg(salart) from comany group by address;

select * from comany

--3.- List out the no.of employees joined in every month in ascending order. 
select join_data,count(*) from comany group by join_data order by join_data asc;

--4.- List out the address having at least three employees.
select address, count (*) from comany group by address having count(*)>3;

--5.- How many employees who are joined in 2021.
select to_char(join_data, 'YYYY') as "Year", count(*) from comany group by to_char(join_data, 'YYYY');

=================== CORRELATED SUBQUERIES ====================
--1.- List out all the employees who earn more than all employee from Mexico. 
select max(salart) from comany where address='Mexico'; --> 630000
select * from comany where salart > (select max(salart) from comany where address='Mexico');
select * from comany where salart > (630000);
--2.- List out the mexico employees who earn more than the lowest slary from Mexico 
select min(salart) from company where address = 'Bangalore';
select * from comany where address = 'Mexico' and salart > (select
min(salart) from comany where address = 'Mexico'); -- only from bangalore
--3.- Find out whose location is not Mexico
select * from comany where address!='Mexico';



============================ JOINS ==========================


 1List all employees with their courses details

select * from comany full join employee_course on
comany.id=employee_course.id;

2.-Display the employees with their course name and course duration.

select * from company full join employee_course on
company.id=employee_course.id full join COURSE on
employee_course.course_id=course.course_id;
select company.name,employee_course.course_name,course.duration from
company full join employee_course on company.id=employee_course.id full join
COURSE on employee_course.course_id=course.course_id;
 
3 Display the employee details with their address names - using self join
Select c.name Employee_Name, m.address Employee_Address
from company c, company m where c.id=m.id;
