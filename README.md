# Online Book Store Sales & Inventory Analysis

## Project Overview

This project analyzes an online bookstore database using PostgreSQL to understand customer purchasing behavior, book sales trends, revenue generation, and inventory management. The project includes relational database design, CSV data import, and analytical SQL queries to solve real-world business problems.

---

## Database Tables

### Books Table

Contains information about books including:

* Book ID
* Title
* Author
* Genre
* Published Year
* Price
* Stock Availability

### Customers Table

Contains customer information including:

* Customer ID
* Customer Name
* Email
* Phone Number
* City
* Country

### Orders Table

Stores transaction details including:

* Order ID
* Customer ID
* Book ID
* Order Date
* Quantity
* Total Amount

---

## Entity Relationship Diagram (ERD)

Customers → Orders → Books

* One customer can place multiple orders
* One book can appear in multiple orders
* Orders table connects customers and books

---

## Dataset Handling

* Imported CSV datasets using PostgreSQL COPY command
* Managed relational database structure
* Applied primary and foreign key constraints

---

## SQL Concepts Covered

* SELECT Statements
* WHERE Clause
* GROUP BY
* HAVING
* ORDER BY
* LIMIT
* Aggregate Functions
* JOINS
* LEFT JOIN
* DISTINCT
* COALESCE()
* Revenue Analysis
* Inventory Analysis
* Customer Analysis

---

## Business Problems Solved

### Book Analysis

* Retrieve books by genre
* Find books published after a specific year
* Identify highest and lowest priced books
* Find books with lowest stock availability

### Customer Analysis

* Customers placing multiple orders
* Customers spending above a threshold
* City-wise customer spending analysis

### Revenue Analysis

* Total revenue generated
* Revenue by genre
* Revenue by author
* Highest spending customers

### Order Analysis

* Orders placed during specific periods
* Most frequently ordered books
* Quantity sold analysis

### Inventory Analysis

* Remaining stock after order fulfillment
* Total stock availability
* Book demand analysis

---

## Advanced Features Implemented

* Multi-table joins
* Aggregate analysis
* Inventory tracking
* Revenue computation
* Customer spending insights
* Relational database design

---

## Tools Used

* PostgreSQL
* pgAdmin
* CSV Data Import

---

## Features Implemented

* Relational Database Design
* CSV File Integration
* SQL Query Optimization
* Inventory & Revenue Tracking
* Business-Oriented Data Analysis

---

## Project Outcome

Enhanced SQL querying, database management, analytical thinking, and business problem-solving skills through real-world bookstore sales and inventory analysis.
