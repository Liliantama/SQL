# SQL

# EXCERCISE 1

### QUICK PRACTICLE ON DB
-- create database school
-- create table Students, firstname,stud_id,age
-- insert 4 students
-- add a column to the table Students, Subject
-- Update 2 records with a subject
-- drop a column from the table, Subject

# EXCERCISE 2
### WORKING ON CLASSICAL DB
-- Question 1 : What is the total number of orders placed in the year 2005?
-- Question 2 : Find the names and contact information (city, country)
-- of all customers from Germany who have placed orders with a total amount exceeding $500.
-- Question 3 : Find the product line with the highest average order quantity.
-- Question 4 : How many different employee offices are there in the database?
-- Question 5 : Find the names of all employees who manage at least one employee
-- who has completed more orders than the average number of orders per employee.
-- Question 6 : Find the total number of orders placed between the first day of the current month and today's date.
-- Question 7 : List all products with a price exceeding $100.
-- Include an additional column indicating "High Price" for these products and "Low Price" for products with a price of $100 or less.
-- Question 8 : Find the product with the most orders placed in total.
-- Question 9 : Find the top 5 customer cities (by city name) with the highest total order amounts.

# EXCERCISE 3
### CREATION OF BD
Question 1: Create a view named high_value_customers that lists the customer number, customer name, and total order amount for customers who have placed orders exceeding $10,000.

Question 2: Find the names of customers who have placed orders for products from the 'Classic Cars' product line.

Question 3: List the employees who work in the office with the maximum number of employees.

Question 4: Write a stored procedure named get_customer_orders that takes a customer number as input and returns the order numbers and order dates for that customer.

Question 5: Write a stored procedure named total_sales_by_employee that takes an employee number as input and returns the total sales amount for that employee.

Question 6: Use a CTE to find the top 3 employees by the number of customers they manage.

Question 7: Use a CTE to find the average payment amount for each customer and list those with an average payment greater than $2000.

Question 8: Create a union query that lists all customer names and employee names.

Question 9: Write a union query to list all office cities and customer cities, making sure there are no duplicates.

Question 10: Create a union query that lists all product codes from the orderdetails table along with the respective order number and indicates whether it is from the 'Classic Cars' or 'Motorcycles' product line.

# EXCERCISE 4
### SCENARIO 1 (PIZZA HOT)
Your client is a local fast food restaurant - PizzaHot. The background story is as below:
PizzaHot is a local restaurant serving the community and bringing people happiness. Recent years, PizzaHot is adopting a franchising strategy and is moving towards a chain-restaurant in the State. A database system for Inner Management is crucial for the expansion of the business.
The information needed is:
Stores: including ID, name, location, contact information.
Employees: including ID, SSN, name, gender, DoB, position, salary, AffiliateStore.
Vendors: including name, address, contactPerson
Products: including name, Vendor, price, quantity
Task:
Based on your understanding so far, what are the entities, attributes, identifiers, and relationships in the Entity Relationship Model? You can lay out the initial outline here, and the owner will meet with you to answer your questions.

### SCENARIO 2 (TRUE TRADE)
Your client is a stock-exchange company. The background story is as below:
TrueTrade provides excellent financial services to customers all over the world. Customers can buy/sell stock via TrueTrade easily and securely. TrueTrade also provides detailed information for every stock so customers can make the best decision.
The information needed for TrueTrade is:
Stocks: including stock#, companyName, ExchangeMarket, Description
Customers: including CustomerID, Name, Contact
Portfolio: including CustomerName, currentValue
Logs: including stock#, openPrice, closePrice, date
Transactions: CustomerID, Portfolio, stock, quantity, price, date, time.
Task:
Based on your understanding so far, what are the entities, attributes, identifiers, and relationships in the Entity Relationship Model? You can lay out the initial outline here, and the owner will meet with you to answer your questions.

# EXCERCISE 5
### SCENARIO
Read the following statements about a Database for Art Galleries and collections of drawings. Draw the Entity-Relationship Attribute Diagram with Crow’s Foot Notation. Make sure you have all entities, all attributes (and identifiers), all relationships etc.
A gallery must have one and only one location and each location must have one and only one gallery.
Galleries have attributes: GalleryNum(identifier), Name, Phone, Hours, and Intro.
Locations have attributes: ID(identifier), Country, State, City, Street, and ZipCode.
A gallery may have one or more drawings and each drawing may belong to one and only one gallery.
Drawings have attributes: DrawingNum(identifier), Title, Size, Material, and Date.
A drawing must be created by at least one artist and each artist must create at least one drawing.
Artists have attributes: ArtistNum(identifier), Name, Phone, Birthday, and Email.
An artist may have a bio statement and a bio statement must belong to one artist.
BioStatements have attributes: Citizenship, Education, Experience, MasterPiece(s)


## PIZZA HOT ERD

![PIZZA HOT drawio](https://github.com/Liliantama/SQL/assets/171235266/b1bf1135-a608-4949-9bfe-74d2be7cadd7)

## TRUE TRADE ERD

![TRUE TRADE](https://github.com/Liliantama/SQL/assets/171235266/759c0843-61f1-4916-bc38-ddcf6b99fd30)

## ART GALLERY ERD


![ART GALLERY drawio (1)](https://github.com/Liliantama/SQL/assets/171235266/bb2a22db-c66e-467f-877f-5a45242c1311)










