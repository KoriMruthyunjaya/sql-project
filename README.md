Overview
This database schema is designed for an online retail application, supporting customer management, employee management, order management, payment processing, and product management.

Getting Started
Create a new PostgreSQL database.
Run the provided SQL code to create the database schema.
SQL Code
The SQL code to create the database schema is provided in the online_retail_app.sql file.

Database Schema
The database schema consists of 9 tables:

User Login
Customers
Employment Type
Employees
Payment
Orders
Product Items
Order Items
Order Delivery
Table Descriptions
Please refer to the online_retail_app.sql file for detailed table descriptions.

Usage
Insert data into the tables as needed.
Use SQL queries to retrieve and manipulate data.

Example Use Cases
Retrieve all customer information: SELECT * FROM customers;
Retrieve all orders placed by a specific customer: SELECT * FROM orders WHERE ordered_by = 'customer_id';
Update the stock count of a product item: UPDATE product_items SET stock_count = 'new_stock_count' WHERE item_id = 'item_id';
