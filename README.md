
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

 [+], [-], [/], [*], [%]
 
 </details>
 
<details>
 <summary><b> Comparison Operators </b></summary><br>
 1. <, <=
 2. >, >=
 3. =, !=
 4. !<, !>
 </details>
  
<details>
 <summary><b> Logical Operators</b></summary><br>
 - Any
 - All
 - And
 - OR/IN 
 - Between
 - Exists
 - Not
 </details>
 
## SQL built in functions
 
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
 
