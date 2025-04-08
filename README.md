# Books_SQL-Analysis

Books Database Project

Overview : This project is designed to manage and analyze a books store database. The database contains information related to books, customers, and orders. The primary purpose of the project is to help you perform various SQL queries such as filtering books by genre or publication year, retrieving customer or order details, calculating revenue, and more.

Project Structure : 

- Database Initialization: The project begins by creating a database called books.
- SQL Queries: The file sql_queries.txt contains a collection of SQL queries used for different operations on the database:
  - Retrieve books of a specific genre.
  - Find books based on publication years.
  - List customers based on location.
  - Analyze orders according to time or amount.
  - Calculate totals and averages for sales and stock.
  - Perform joins across tables (e.g., customers, orders, and books) to fetch combined data.

How to Use : 

1. Database Setup:
   - Start by executing the query create database books; to set up your database.
   - Ensure that you have the required tables (books, customers, and orders) created within this database. (Table definitions are assumed to be created prior to running these queries.)

2. Running the SQL Queries:
   - Open the sql_queries.txt file to view the full list of queries.
   - Run each SQL query in your SQL client (e.g., MySQL, MariaDB) to retrieve or manipulate the data as needed.
   - Modify the queries if necessary to match your specific table structure or schema differences.

3. Key Queries Included:
   - Filter Queries: Retrieve all books in a specific genre (e.g., Fiction) or books published after a certain year.
   - Join Queries: Combine information across customers, books, and orders to list detailed records (such as customers who placed high quantity orders).
   - Aggregation Queries: Calculate total stock, revenue, and average book prices by genre.
   - Sorting and Limiting: Identify the most expensive or most frequently ordered book.

Additional Considerations: 

- Make sure your SQL environment supports functions like month() used in the queries.
- The project is aimed at being easily extendable, so feel free to modify or add new queries based on your needs.
- Regularly back up your database before performing any updates or deletions.

Conclusion : This repository provides a starting point for managing and analyzing a books database. The queries provided can be used as-is or modified for additional functionality as you further develop your project.
