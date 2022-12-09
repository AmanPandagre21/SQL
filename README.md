
# SQL [STRUCTURED QUERY LANGUAGE]

SQL is a standard language for storing, manipulating and retrieving data in databases.

## What is SQL?
- SQL stands for Structured Query Language
- SQL lets you access and manipulate databases
- SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987

## What Can SQL do?
- SQL can execute queries against a database
- SQL can retrieve data from a database
- SQL can insert records in a database
- SQL can update records in a database
- SQL can delete records from a database
- SQL can create new databases
- SQL can create new tables in a database
- SQL can create stored procedures in a database
- SQL can create views in a database
- SQL can set permissions on tables, procedures, and views

## SQL Query Looks Like
 
![image](https://user-images.githubusercontent.com/80267318/204763077-68928869-8128-4d64-bbf5-4ed9817f9f8e.png)

<details>
 <summary><h2>ER Diagram</h2></summary><br>
 
## ER Diagram
An Entity Relationship Diagram is a diagram that represents relationships among entities in a database. It is commonly known as an ER Diagram.

## What is an ER Model?
 
An Entity-Relationship Model represents the structure of the database with the help of a diagram. ER Modelling is a systematic process to design a database as it would require you to analyze all data requirements before implementing your database.

## Symbols Used in ER Diagrams
- Rectangles: This Entity Relationship Diagram symbol represents entity types
- Ellipses: This symbol represents attributes
- Diamonds: This symbol represents relationship types
- Lines: It links attributes to entity types and entity types with other relationship types
- Primary key: Here, it underlines the attributes 
- Double Ellipses: Represents multi-valued attributes


 ### Components of ER Diagram
You base an ER Diagram on three basic concepts:

![image](https://user-images.githubusercontent.com/80267318/204767802-a6bbeca7-7367-45c6-9632-9bceb1136c46.png)

 #### Entities
 <details>
 <summary><b> An entity can be either a living or non-living component.</b></summary><br>

![image](https://user-images.githubusercontent.com/80267318/204769508-7fd77101-3bc7-488e-bd23-5e6aad504737.png)

- Weak Entity => An entity that makes reliance over another entity is called a weak entity

![image](https://user-images.githubusercontent.com/80267318/204769770-4c696309-3c18-4188-8e95-cc5e512f34f4.png)
 </details
 


#### Attributes
 
 <details>
 <summary><b>An attribute exhibits the properties of an entity.</b></summary><br>
 
- Key Attribute => Key attribute uniquely identifies an entity from an entity set. It underlines the text of a key attribute.

![image](https://user-images.githubusercontent.com/80267318/204770087-ffa276a7-3e50-41f9-98e4-6f135e044199.png)

- Composite Attribute => An attribute that is composed of several other attributes is known as a composite attribute.

![image](https://user-images.githubusercontent.com/80267318/204770241-30994b89-3e6b-49d5-8e58-2642428ade8e.png)

- Multivalued Attribute => Some attributes can possess over one value, those attributes are called multivalued attributes.

![image](https://user-images.githubusercontent.com/80267318/204770436-8626c951-4474-4a48-81a6-1f4a3e308609.png)

- Derived Attribute => An attribute that can be derived from other attributes of the entity is known as a derived attribute.

![image](https://user-images.githubusercontent.com/80267318/204770552-730e7206-a005-4e2b-b0f6-8aad7d39609d.png)

</details>

#### Relationships

 <details>
 <summary><b>There are 4 types of relationship they are </b></summary><br>

- One-to-One Relationships

![image](https://user-images.githubusercontent.com/80267318/204770991-763da9ee-ba4b-41d7-a713-6fe4e4323290.png)

- One-to-Many Relationships

![image](https://user-images.githubusercontent.com/80267318/204770683-acf089dd-edfc-4dc8-b2f4-ec5bd52de838.png)

- Many-to-One Relationships

![image](https://user-images.githubusercontent.com/80267318/204770738-c47d2079-8092-460c-9400-7d0336fb3755.png)

- Many-to-Many Relationships

![image](https://user-images.githubusercontent.com/80267318/204770783-1c9cec05-f695-4705-ae9b-30c0cbaf29a8.png)

</details>

 </details>

## Types of Sql 

### DDL - Data Defination Language
- create
- alter
- drop
- truncate

### DML - Data Manupilation Language
 - Select [DQL - DATA QUERY LANGUAGE] 
 - Update
 - Delete
 - Insert
 
 ### DCL - Data Control Language
  - Grant
  - Revoke
  
 ### TCL - Transaction Control Language
  - commit
  - rollback
  
## SQL Datatypes

<details>
<summary><b>Image</b></summary><br>

![image](https://user-images.githubusercontent.com/80267318/204773960-369b5193-5193-4390-9f44-8c03e53f0a19.png)

</details>

## Operators in Sql 
 
<details>
 <summary><b> Arithmetic Operators</b></summary><br>
<ul>
 <li>[+]</li> 
 <li>[-]</li>
 <li>[/]</li> 
 <li>[*]</li> 
 <li>[%}</li>
</ul>
 </details>
 
<details>
 <summary><b> Comparison Operators </b></summary><br>
 <ul>
 <li><, <=</li> 
 <li> >, >=</li>
 <li> =, !=</li> 
 <li>!<, !></li> 
</ul>
 </details>
  
<details>
 <summary><b> Logical Operators</b></summary><br>
 <ul>
 <li>Any</li> 
 <li>All</li>
 <li>And</li> 
 <li>OR/IN </li> 
 <li>Between</li>
 <li>Exists</li>
  <li>Not</li>
</ul>

 </details>
 
 ## SQL built in functions 
<details>
 <summary><h3> Functions </h3></summary><br>
 <details>
 <summary><b>Show Databases </b></summary><br>
 
 This is used for listing all present databases.
 
  #### Syntax => 
  ```sql 
     show databases;
  ```
</details>

 <details>
 <summary><b>use [db_name]  </b></summary><br>
 
This command is used for selecting the database for futher operations
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
  ````
 </details>

<details>
 <summary><b> show tables  </b></summary><br>
  
  this command is used for listing all the tables present in a database 
  
  #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
  show TABLES:
 ```
</details>
  
<details>
 <summary><b> Describe [table name] </b></summary><br> 
 
 this command is used for getting the structure/schema of table present in a database
 
 #### Syntax =>
  ```sql
  // let db name = employee and table name => emp_data
  use Employee
  describe emp_data;
  ```
  </details>
 
<details>
 <summary><b> Distinct  </b></summary><br>
 
 this keyword is used for fetch unique data of the selected attribute
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
 
 SELECT DISTINCT <attribute name> FROM <table name>;
 
 // example
  SELECT DISTINCT city FROM emp_data;
  ```
   </details>
 
<details>
 <summary><b> count()  </b></summary><br>
 
 this function is used for getting the total count of the row from  selected attribute
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
 
 SELECT COUNT(<attribute name>) FROM <table name>;
 
 // example
  SELECT COUNT(name) FROM emp_data;
  ```
  </details>
  
<details>
 <summary><b> AS </b></summary><br>
 
 SQL aliases are used to give a table, or a column in a table, a temporary name.
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
 
 SELECT COUNT(<attribute name>) AS <temp_name> FROM <table name>;
 
 // example
  SELECT COUNT(name) AS total_name FROM emp_data;
  ```
  </details>
 
<details>
 <summary><b> SUM()</b></summary><br>
 
 The SUM() function returns the total sum of a numeric column. 
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
 
 SELECT SUM(<attribute name>) AS <temp_name> FROM <table name>;
 
 // example
  SELECT SUM(salary) AS totalSalary FROM emp_data;
  ```
  </details>
  
 <details>
 <summary><b> AVG() </b></summary><br>
 
 The AVG() function returns the avrage of a numeric column. 
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
 
 SELECT AVG(<attribute name>) AS <temp_name> FROM <table name>;
 
 // example
  SELECT AVG(salary) AS avgsalary FROM emp_data;
  ```
   </details>
   
<details>
 <summary><b> WHERE CLAUSE </b></summary><br>
 
 The Where Clause is used for applying conditions in a query.
 
 #### Syntax =>
  ```sql
  // let db name = employee
  use Employee
 
 SELECT * FROM <Table Name> WHERE <condition>;
 
 // example
 1. SELECT * FROM emp_data WHERE age>22;
 
 2. SELECT Name, Gender, City FROM emp_data WHERE Gender = 'F';
  ```
  
  </details>
 
<details>
 <summary><b> OR/IN </b></summary><br>
 
 The OR operator displays a record if any of the conditions separated by OR is TRUE. The IN operator allows you to specify multiple values in a WHERE claus
 
 example - 
 ```sql 
 // Both work as same
   SELECT Name, Gender, City FROM emp_data WHERE city = 'indore' OR city='pune';
 
   SELECT Name, Gender, City FROM emp_data WHERE city IN ('indore', 'pune');
 ```
  </details>
 
<details>
 <summary><b> Between </b></summary><br>
 
 The BETWEEN operator selects values within a given range. The values can be numbers, text, or dates. The BETWEEN operator is inclusive: begin and end values are included. 
 
 example - 
 ```sql 
 SELECT * FROM emp_data WHERE doj BETWEEN '2001-01-01' AND '2010-01-01';
 ```
  </details>
 
<details>
 <summary><b> AND </b></summary><br>
 
 The AND operator displays a record if all the conditions separated by AND are TRUE.
 
 example - 
 ```sql 
 SELECT * FROM emp_data WHERE age>23 AND gender='M';
 ```
  </details>
  
 <details>
 <summary><b> NOT </b></summary><br>
 
 The NOT operator displays a record if the condition(s) is NOT TRUE.
 
 example - 
 ```sql 
 SELECT name, age, salary FROM emp_data WHERE NOT city = 'indore';
 ```
 
  </details>
 
<details>
 <summary><b> Combine Query of AND,OR and NOT </b></summary><br>
 
example - 
```sql
 SELECT name, age, salary , city FROM emp_data WHERE Not city='Mumbai' AND ( city = 'Banglore' OR city ='ujjain');
```
  </details>
  
<details>
 <summary><b> Order By  </b></summary><br>

The ORDER BY keyword is used to sort the result-set in ascending or descending order.The ORDER BY keyword sorts the records in ascending order by default. To sort the records in descending order, use the DESC keyword.

example - 
 ```sql 
 //ascending order
 SELECT * FROM emp_data  WHERE age>23 AND gender='M' ORDER BY salary ASC;
 
 //descending order
SELECT * FROM emp_data  WHERE age>23 AND gender='M' ORDER BY salary DESC;
 ```
 
  </details>
  
  
  <details>
 <summary><b> MIN/MAX  </b></summary><br>

The MIN() function returns the smallest value of the selected column.
The MAX() function returns the largest value of the selected column.

example - 
 ```sql 
 //min
 SELECT name, MIN(age) as min_age from emp_data;
 
 SELECT name, age as min_age from emp_data WHERE age = (SELECT MIN(age) from emp_data);

 //max
SELECT name, MAX(age) as max_age from emp_data;

SELECT name, age as max_age from emp_data WHERE age = (SELECT MAX(age) from emp_data);
 ```
 
  </details>
  
  
   <details>
 <summary><b> Repeat  </b></summary><br>
 
 it is used for repeation.

example - 
 ```sql 
 //syntax
  SELECT REPEAT(<repeat_name>, how many times you want to repeat) as repeated_name;
 
 SELECT REPEAT("aman", 10) as repeated_name;
 ```
 
  </details>
  
  
<details>
 <summary><b> Date  </b></summary><br>

<details>
 <summary><b> curDate() / CURRENT_DATE </b></summary><br>
 
 this is used for getting the current date.
 
example - 
 ```sql 
 //syntax
SELECT CURRENT_DATE as date;

SELECT curDate() as date;
 ```
  </details>
  
  <details>
 <summary><b> curTime() / CURRENT_TIME </b></summary><br>
 
 this is used for getting the current Time.
 
example - 
 ```sql 
 //syntax
SELECT CURRENT_TIME as date;

SELECT curTime() as date;
 ```
  </details>
  
  <details>
 <summary><b> now() / CURRENT_TIMESTAMP </b></summary><br>
 
 this is used for getting the current date and time.
 
example - 
 ```sql 
 //syntax
SELECT CURRENT_TIMESTAMP as date;

SELECT now() as date;
 ```
  </details>
 
  </details>
  
  <details>
 <summary><b> Math Operation  </b></summary><br>

example - 
 ```sql 
 // addition
 SELECT (10+80) AS Addition;
 
 //subtraction
SELECT (10-80) AS Subtraction;

//divide
SELECT (80/10) AS division;

//mutiply
SELECT (10*80) AS Multiplication;

 ```
  </details>
 

### Strings Function
  
<details><summary><b>upper()/ucase()</b></summary><br> 
 Convert words into uppercase
 
 ```sql 
 
      SELECT UPPER("aman pandagre") as adminName;
      SELECT UCASE("aman pandagre") as adminName;
 
 ```
 
 </details>
<details><summary><b>lower()/lcase()</b></summary><br>
   Convert words into lowercase
 
 ```sql 
 
       SELECT LOWER("AMAN PANDAGRE") as adminName;
       SELECT LCASE("AMAN PANDAGRE") as adminName;
 
 ```
 
</details>
<details><summary><b>character_length()/char_length()</b></summary><br>
     Returns length of chracter
 
 ```sql 
 
      SELECT CHARACTER_LENGTH("AMAN PANDAGRE") as adminName;
      SELECT CHAR_LENGTH("AMAN PANDAGRE") as adminName;
 
 ```
 
 </details>
<details><summary><b>concat()</b></summary><br>
    
      Concat the two strings
 
 ```sql 
 
     SELECT CONCAT("AM", "AN") as adminName;
 
 ```
 
</details>
<details><summary><b>reverse()</b></summary><br>
    
  REVERSE the strings
 
 ```sql 
 
     SELECT REVERSE("AMAN PANDAGRE") as adminName;
 
 ```
 
 </details>
<details><summary><b>length()</b></summary><br>

  Return the length of String
 
 ```sql 
 
     SELECT LENGTH("I just grind it..") as Len;
 
 ```
 
</details>
<details><summary><b>ltrim()/rtrim()/trim </b></summary><br>

   ltrim means left trim its trims the left side of String.<br>
   rtrim means right trim its trims the right side of String.<br>
   trim  its trims the left and right both side of String
 
 ```sql 

 //ltrim
    SELECT LTRIM("         I just grind it..") as Len;
//rtrim
    SELECT RTRIM("         I just grind it..           ") as Len;
//trim
    SELECT TRIM("         I just grind it..           ") as Len;
 
 ```
 
</details>
<details><summary><b>position()</b></summary><br>
    
      Return the position of String
 
 ```sql 
 
     SELECT POSITION("21" IN "aman PANDAGRE21");
 
 ```
  </details>
 </details>

 <details>
  <summary><h3>Group By / Having</h3></summary><br>
  
 The GROUP BY statement groups rows that have the same values into summary rows, like "find the number of customers in each country".

The GROUP BY statement is often used with aggregate functions (COUNT(), MAX(), MIN(), SUM(), AVG()) to group the result-set by one or more columns.
  
  AND
  
 The HAVING clause was added to SQL because the WHERE keyword cannot be used with aggregate functions.
 
 ```sql
  
    use sql_learn;
  
  //Group By
  
    // get each departmant average age and total salary
    SELECT dept, ROUND(AVG(age)) AS avg_age, SUM(salary) AS sly FROM employees GROUP BY dept;
    
    //select how many employees work on each city
    SELECT COUNT(Emp_Id) AS total_Emp , city FROM employees GROUP BY city ORDER BY COUNT(Emp_Id) DESC;
  
    //select how many employees join on each year
    SELECT YEAR(doj) as year, COUNT(Emp_Id) as total_emp_join FROM employees GROUP BY YEAR(doj) ORDER BY YEAR(doj) DESC;
  
    SELECT product_id, SUM(sell_price * quantity) AS revenue FROM sales GROUP BY product_id;

  //Having
  
      // return the group of department whose average salary is greater then 75000
      SELECT dept, AVG(salary) AS avg_salary FROM employees GROUP BY dept HAVING AVG(salary) > 75000;
  
      // return the group of city whose total salary is greater then 200000
      SELECT city, SUM(salary) AS total_salary FROM employees GROUP BY city HAVING SUM(salary) > 200000;
  
      // return the group of department whose total employees is greater then 2
      SELECT dept, COUNT(*) AS total_emp FROM employees GROUP BY dept HAVING COUNT(*) > 2;
  
      // return the group of department whose total employees is greater then 2 and they not belong to houston city
      SELECT dept, COUNT(*) AS total_emp FROM employees WHERE city != "Houston" GROUP BY dept HAVING COUNT(*) > 2;
  
      // return the group of department whose average salary is greater then 75000 
     // using aggrigate function in having clause that is not used in select
      SELECT dept, COUNT(*) AS total_emp FROM employees GROUP BY dept HAVING AVG(salary) > 75000;
   
  ```
  
 </details>
 
<details>
  <summary><h3> JOINS </h3></summary><br>
   
   A JOIN clause is used to combine rows from two or more tables, based on a related column between them.
   We can join more than one tables 
   there are Five types of joins - 
   
   <ul>
    <li>Inner Join</li>
    <li>Right Join</li>
    <li>Left Join</li>
    <li>Full Join</li>
    <li>Self Join</li>
   </ul>
   
 <details><summary><h5>Inner Join</h5></summary>
   
   The INNER JOIN keyword selects records that have matching values in both tables.
   Note: The INNER JOIN keyword selects all rows from both tables as long as there is a match between the columns. If     there are records in the "table1" table that do not have matches in "table2", these orders will not be shown!

   ![image](https://user-images.githubusercontent.com/80267318/206286434-a2bc37c4-f152-49c0-9755-07b7dedda24b.png)

   ```sql
     
   //Syntax 
   
    SELECT column_name(s)
    FROM table1
    INNER JOIN table2
    ON table1.column_name = table2.column_name;
   
   //example
   
   SELECT * FROM cricket AS c INNER JOIN football AS f ON c.name = f.name;
   Or
   SELECT * FROM cricket AS c INNER JOIN football AS f  USING(name); 
   
   SELECT productcode, productname, textdescription FROM products INNER JOIN productlines USING(productline);
   
   //three table join
   SELECT o.ordernumber, o.status, p.productname, SUM(quantityordered * priceeach) AS revenue FROM orders AS o INNER JOIN orderdetails AS od ON o.ordernumber=od.ordernumber INNER JOIN products AS p ON p.productcode = od.productcode GROUP BY ordernumber;
   
   ```
    
 </details>
   
   
 <details><summary><h5>Right Join</h5></summary>
   
  The RIGHT JOIN keyword returns all records from the right table (table2), and the matching records from the left     table (table1). The result is 0 records from the left side, if there is no match.
     
   ![image](https://user-images.githubusercontent.com/80267318/206287406-8560bf45-27cf-43cd-a0db-591f2429f148.png)

     Note: The RIGHT JOIN keyword returns all records from the right table (table2), even if there are no matches           in the left table (table1).<br>
      In some databases RIGHT JOIN is called RIGHT OUTER JOIN.
     
   ```sql
     
   //Syntax 
   
    SELECT column_name(s)
    FROM table1
    RIGHT JOIN table2
    ON table1.column_name = table2.column_name;
   
   //example
   
   SELECT c.customername, c.phone, e.employeenumber, e.email FROM customers AS c RIGHT JOIN employees AS e ON salesrepemployeenumber=employeenumber ORDER BY              employeenumber;
   
   ```
    
 </details>
   
   
 <details><summary><h5>Left Join</h5></summary>
   
   The LEFT JOIN keyword returns all records from the left table (table1), and the matching records from the right      table (table2). The result is 0 records from the right side, if there is no match.
   Note: The LEFT JOIN keyword returns all records from the left table (Customers), even if there are no matches in      the right table (Orders).<br>
   In some databases LEFT JOIN is called LEFT OUTER JOIN.

   ![image](https://user-images.githubusercontent.com/80267318/206287983-af44dc67-a879-4280-b15f-f4ac0c2968ec.png)

   ```sql
     
   //Syntax 
   
     SELECT column_name(s)
     FROM table1
     LEFT JOIN table2
     ON table1.column_name = table2.column_name;
   
   //example
   
   SELECT c.customernumber, c.customername, status, ordernumber FROM customers AS c LEFT JOIN orders AS o ON c.customernumber = o.customernumber WHERE o.ordernumber IS null;   
   
   ```
    
 </details>
   
 <details><summary><h5>Full Join</h5></summary>
   
   The FULL OUTER JOIN keyword returns all records when there is a match in left (table1) or right (table2) table        records. FULL OUTER JOIN and FULL JOIN are the same.
   Note: The FULL OUTER JOIN keyword returns all matching records from both tables whether the other table matches or    not. So, if there are rows in "Customers" that do not have matches in "Orders", or if there are rows in "Orders"      that do not have matches in "Customers", those rows will be listed as well.<br>
   FULL OUTER JOIN can potentially return very large result-sets!

   ![image](https://user-images.githubusercontent.com/80267318/206288426-f93fcd0a-b6cc-4deb-b00a-c8de33a1a37c.png)
     
   ```sql
     
   //Syntax 
   
    SELECT column_name(s)
    FROM table1
    FULL OUTER JOIN table2
    ON table1.column_name = table2.column_name
    WHERE condition;
   
   //example
   
   SELECT Customers.CustomerName, Orders.OrderID FROM Customers FULL JOIN Orders ON Customers.CustomerID=Orders.CustomerID ORDER BY Customers.CustomerName;
   
   ```
    
 </details>
   
 <details><summary><h5>Self Join</h5></summary>
   
   A self join is a regular join, but the table is joined with itself.

   ```sql
     
   //Syntax 
   
    SELECT column_name(s)
    FROM table1 T1, table1 T2
    WHERE condition;
   
   //example
   
   SELECT concat(m.lastname, ',' , m.firstname) as manager , concat(e.lastname, ',' , e.firstname) as employees FROM employees AS e INNER JOIN employees AS m ON m.employeenumber =  e.reportsto ORDER BY manager;
   
   ```
    
 </details>
    
 </details>
 
  <details><summary><h2>Su Queries </h2></summary>
   
   <h5> A subquery is select query that is enclosed inside other query. The inner select query is usually used to determine the results of the outer select query</h5>
   
   ![image](https://user-images.githubusercontent.com/80267318/206678672-f22f4f26-16d9-4b9f-b4f3-9cfa32a60992.png)
   
   ```sql
   
   // Subquery with select statement //
   
   // Write a sql query to display department with maximum salary from employees table //
   
   SELECT dept FROM employees WHERE salary = (SELECT MAX(salary) FROM employees);
   
   SELECT emp_name, dept, salary FROM employees WHERE salary < (SELECT AVG(salary) FROM employees);
                                                                      
   // Subquery with insert statement //
   
    INSERT INTO orders
    SELECT prod_id, item, sell_price 
    FROM products 
    WHERE prod_id IN (SELECT prod_id FROM products WHERE sell_price > 1000);   
   
   // Subquery with Update statement //
   
   UPDATE employees SET salary = salary *0.45 WHERE age IN (SELECT age from employees where age >27);
   
   // Subquery with Delete statement //
   
    Delete FROM employees WHERE age IN (SELECT age from employees where age >= 27);
   
   // two different tables //
   
   SELECT productcode, productname, msrp from products WHERE productcode in (SELECT productcode from orderdetails where priceeach <100);
   
   ```

   <details>
 
 
