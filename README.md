📚 Online Bookstore Management & Data Analysis (SQL)
Project Overview:
This project involves designing and analyzing an Online Bookstore database system. It manages data for customers, books, and orders to help understand sales trends, monitor inventory levels, and analyze customer purchasing behavior.

Tech Stack:
Database: PostgreSQL
Tool: pgAdmin 4
Language: SQL (DDL, DML, DQL)

Database Schema:
The project is built on three primary tables:
Books: Stores details such as Title, Author, Genre, Price, and Stock.
Customers: Contains buyer information including Name, Email, City, and Country.
Orders: Records transaction details like Order Date, Quantity, and Total Amount.

Key Business Questions Solved:
I have written queries to solve 20 real-world business problems, including:
Inventory Management: Calculating remaining stock after fulfilling orders using COALESCE.
Revenue Analysis: Calculating total revenue and sales performance by genre.
Customer Insights: Identifying top-spending customers and their geographic locations.
Sales Trends: Finding the most frequently ordered books and popular authors.

Advanced SQL Concepts Applied:
Joins: Linking multiple tables (Books, Orders, Customers) to retrieve comprehensive datasets.
Aggregations: Using SUM(), AVG(), and COUNT() for reporting.
Filtering & Sorting: Efficiently using WHERE, BETWEEN, ORDER BY, and LIMIT.
Data Integrity: Implementing Primary Key and Foreign Key constraints.
Null Handling: Using COALESCE() to ensure accurate calculations when data is missing.

How to Use:
Download the OnlineBookstore.sql file.
Create a new database in PostgreSQL/pgAdmin.
Run the provided SQL script to create tables and insert data.
Update the file path in the COPY command to match the location of your local CSV files.
