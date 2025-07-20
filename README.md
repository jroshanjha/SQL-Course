# SQL-Course

## 01-Feb
1.What is SQL or Why SQL ? <br>
2. What is different between Entity or attribute or tuples of records ? <br>
3. What is Database Schemas ?  <br>
4. What is Server or Database ? <br> 

## 02-Feb 

1. What is a primary key, and why is it important?
2. What is the difference between a primary key and a foreign key?
3. Explain the difference between DELETE, TRUNCATE, and DROP.
4. What are SQL constraints? Provide examples (e.g., NOT NULL, UNIQUE, CHECK).
5. suppose Amazon has stored much information about customers, products, orders, categories or more in the database tables. Customers want to change their information, which Sql commands should you use to solve this problem?
6. I have users or posts tables and I want a relationship between both tables and get information, so what is your approach, and how do you solve this problem ?

## 06-Feb
1. Write a sql query delete employees and posts tables from database.
2. what is the use case of ALTER TABLE and DROP TABLE?
3. write a sql query for DROP and TRUNCATE TABLE?
4. Let's suppose I have customers tables with customer_id, customer_name , salary, address, email, and phone and our clients need to change the customer_name columns what is your approach for solved these problems ?
5. Why we use  IF EXISTS or IF NOT EXISTS in SQL queries?
6. How do understand ADD and MODIFY Commands in Mysql?

## 07-Feb 
1. How to Create a Database abc if this database have already exists ?
2. Write a command to display all database name ?
3. Created Students table with id,s_name, age, email, phone and address attributes makes sure id is primary key and any columns have never store null values?
4. What is output of the code ( select * from students )
5. Explane this SQL query ( Truncate table ABC; )
6. What is the advantages or disadvantages of using drop commands ?
   
## 09-Feb
Mentions in your sql-day5 file at line numbers 48

## 13-Feb
1. What is Char or Varchar ?
2. What kind of data types should be defined for sotre name, email or phone number ?
3. How to store multiple records at a time ?
4. Write an SQL query for the created new column with datatypes varchar(30) and then changed this column into another names?
5. what do you understand about this query ( alter table employees to emp; )
6. what is output of this Sql query ( ADD COLUMN city VARCHAR(50) CHECK (city IN ('delhi', 'm')); )

## 22-Feb 
1. Write a SQL query to insert a new record into the "employees" table.
2. Write a SQL query to update the "quantity" column of the "products" table to 10 where the "product_id" is 5.
3. Write a SQL query to delete all records from the "orders" table where the "status" is 'cancelled'.
4. Write a SQL query to retrieve the names of all customers from the "customers" table in alphabetical order.
5. https://www.sqlzoo.net/wiki/SQL_Tutorial ( More practice ) 
6. https://www.w3schools.com/mySQl/mysql_create_db.asp ( DDL practice ) 

## 27-Feb 
1. null vs 'null'

## 28-Feb 
1. Write a SQL query to update the "price" column of the "course" table to 299 where the "course_id" is 5.
2. Write a SQL query to delete all records from the "orders" table where the "status" is 'cancelled'.
3. What is Filtering and Sorting?
4. Write a SQL query to retrieve all the columns from the "products" table where the "category" is 'Electronics' and the "price" is less than 1000.
5. Write a SQL query to retrieve the names of all customers from the "customers" table in alphabetical order.
6. Write a SQL query to retrieve the total number of course from the "course" table.
8. Write a SQL query to delete all records from the "customers" table where the "last_login_date" is older than 1 year. ( Optional ) 
9. Write a SQL query to insert new records into the "employees" table, selecting data from the "temp_employees" table.
10. Write a SQL query to update the "discount" column of the "orders" table by increasing it by 5% for all orders placed before a specific date.
11. What is different between Temporay table and View table ?

## 02-Mar
1. Let's suppose we have table structure like ,
   CREATE TABLE Persons (
    ID int NOT NULL,
    LastName varchar(255) NOT NULL,
    FirstName varchar(255) NOT NULL,
    Age int
);
  What is query for define the size of the dataset so what is your approach ?
## 16-Mar
1. https://leetcode.com/problems/recyclable-and-low-fat-products/?envType=study-plan-v2&envId=top-sql-50
2. https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true
3. https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true
4. https://www.hackerrank.com/challenges/weather-observation-station-1/problem?isFullScreen=true
5. https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true
6. https://leetcode.com/problems/big-countries/?envType=study-plan-v2&envId=top-sql-50

## 23-Mar 
1. What is the meaning of LIKE ‘%0%0%’ in SQL?
2. What do you mean by Data Sharing in DBMS?
Options: Pick one correct answer from below
a) Same data visible to everyone
b) Different data for everyone
c) Multiple versions of data
d) Anyone can access data
Solution description:- 
The act of sharing the same data resource with multiple applications or users is known as data sharing. In the case of DBMS when the same information is visible to everyone , it is called data sharing.

## 27-Mar
1. https://leetcode.com/problems/find-customer-referee/?envType=study-plan-v2&envId=top-sql-50
2. https://leetcode.com/problems/article-views-i/?envType=study-plan-v2&envId=top-sql-50
3. https://leetcode.com/problems/invalid-tweets/?envType=study-plan-v2&envId=top-sql-50
4. https://leetcode.com/problems/patients-with-a-condition/?envType=study-plan-v2&envId=top-sql-50
5. Which clause use for filter the records?
6. How can you remove or handle duplicated records from database tables?

## 26-April 
1. -- Retrieve each Product with the total,Maximum and average quantity of their sales.
2. -- Retrieve Product along with the total and average quantity of their purchases.
3. -- Retrieve product with an average sales quantity  whose sum is less than 2.

## 22-05-2025
## Notes ### 
FIND_IN_SET(str, str_list)	Position in comma list	SELECT FIND_IN_SET('B', 'A,B,C');	2 <br>
FORMAT(num, d)	Format number with commas	SELECT FORMAT(12345.6789, 2);	12,345.68  <br>
select person_income,format(person_income,0),format(person_income,2) , format(person_income,3)from quiz_app.loan_data <Br>

SELECT FIND_IN_SET(LOWER('manager'), LOWER('Engineer,Manager,Associate')); <Br> 
select position("manager" in "Engineer,Manager,Associate"); <Br> 

select distinct find_in_set(lower('Wired Headphones'),lower(Product)) from sales_data; <br>
select * from sales_data;  <br>

select find_in_set(lower('Wired Headphones'),lower(Product)) from sales_data;  <br>

## 01-06-2025 
1. https://leetcode.com/problems/last-person-to-fit-in-the-bus/?envType=study-plan-v2&envId=top-sql-50
2. https://leetcode.com/problems/primary-department-for-each-employee/?envType=study-plan-v2&envId=top-sql-50
3. https://leetcode.com/problems/game-play-analysis-iv/?envType=study-plan-v2&envId=top-sql-50
4. https://leetcode.com/problems/restaurant-growth/?envType=study-plan-v2&envId=top-sql-50


## 06-07-2025 
Valid email addresses must follow these rules:

1. It must have the username@websitename.extension format type.
2. The username can only contain letters, digits, dashes and underscores . [a-z],[A-Z],[0-9],[-_]
3. The website name can only have letters and digits . [a-Z],[A-Z],[0-9]
4. The extension can only contain letters . [a-z],[A-Z]
5. The maximum length of the extension is 3. 


# Notes ** 

End-to-end Data Analytics Projects
End-to-end projects are great for your resume and understanding of the data analytic project life cycle. 

In general, you will be:

1. Dealing with multiple datasets
2. Understanding the data distribution
3. Applying data cleaning and manipulation
4. Applying probability and statical techniques
5. Performing data analysis and visualization
6. Using machine learning model for predictive analysis
7. Creating the report or dashboard


# -- Worldquantuniversity



# SQL - Trigger 

In MySQL, a trigger is a named database object that automatically executes a set of SQL statements when a specific event occurs on a table. 
These events are typically INSERT, UPDATE, or DELETE operations. Triggers can be defined to execute either before or after the triggering event. 

# Key Concepts:
Associated Table: Each trigger is linked to a specific table within the database. 
Triggering Events: Triggers can be activated by INSERT, UPDATE, or DELETE statements on the associated table. 
Timing: Triggers can be set to execute BEFORE or AFTER the triggering event. 
Row vs. Statement: Triggers can be defined to execute for each row affected by the triggering statement (row-level) or once for the entire statement (statement-level). 
NEW and OLD: In UPDATE and INSERT triggers, you can reference the new row being inserted or updated using NEW.column_name. For UPDATE and DELETE triggers, OLD.column_name refers to the original row before the update or deletion. 

CREATE TRIGGER update_after
AFTER UPDATE ON customer
FOR EACH ROW
BEGIN
    INSERT INTO micro_statement (acc_no, avail_balance)
    VALUES(NEW.acc_no, NEW.avail_balance);
END;


This trigger, update_after, is activated after an UPDATE statement on the customer table. For each row updated, it inserts the new account number and available balance into the micro_statement table. 

# When to Use Triggers:
Data Validation: Enforce data integrity rules, such as ensuring that sell prices are not less than buy prices. 
Auditing: Automatically record changes to data, maintaining audit trails. 
Complex Business Logic: Implement intricate business rules that require multiple steps to be executed automatically. 
Data Synchronization: Keep data consistent across multiple tables. 
Incrementing Counters: Automatically update counters or other related values when data is modified. 

