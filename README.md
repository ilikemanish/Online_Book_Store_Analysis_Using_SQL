📚 Online Book Store — SQL Project

"PostgreSQL" (https://img.shields.io/badge/Tool-PostgreSQL-blue)
"SQL" (https://img.shields.io/badge/Language-SQL-orange)
"Data Analysis" (https://img.shields.io/badge/Project-Data%20Analysis-green)
"Business Analytics" (https://img.shields.io/badge/Domain-Business%20Analytics-purple)

---

📌 Project Overview

This project presents an Online Book Store Data Analysis developed using PostgreSQL and SQL.

The project analyzes books, customers, and orders to understand inventory, customer behavior, sales performance, revenue, popular books, genre performance, and stock availability.

The analysis includes both Basic SQL Analysis and Advanced SQL Analysis, transforming raw bookstore data into meaningful business insights.

---

🎯 Business Problem

An online bookstore needs to understand its sales performance, customer purchasing behavior, book inventory, popular genres, and revenue generation.

This project aims to answer key business questions such as:

- Which books belong to the Fiction genre?
- Which books were published after 1950?
- Which customers are from Canada?
- What orders were placed in November 2023?
- What is the total available book stock?
- Which is the most expensive book?
- Which orders contain more than one book?
- Which orders generated more than $20?
- What genres are available in the bookstore?
- Which book has the lowest stock?
- What is the total revenue generated?
- How many books were sold in each genre?
- What is the average price of Fantasy books?
- Which customers have placed at least two orders?
- Which book is ordered most frequently?
- What are the top 3 most expensive Fantasy books?
- How many books were sold by each author?
- Which cities have customers who spent more than $30?
- Which customer spent the most?
- How much stock remains after accounting for orders?

---

📁 Dataset Information

Attribute| Details
Industry| E-Commerce / Online Book Store
Dataset| Online Book Store
Database| PostgreSQL
Analysis Tool| SQL
Analysis Type| Sales, Customer & Inventory Analysis
Project Type| End-to-End SQL Data Analysis

📂 Main Tables

The project uses three main tables:

- 📚 Books — Book information, genre, author, price, publication year, and stock.
- 👥 Customers — Customer information including name, city, and country.
- 🛒 Orders — Order information including customer, book, quantity, order date, and total amount.

---

🛠 Tools & Techniques

- PostgreSQL
- SQL
- pgAdmin
- SELECT Statements
- Aggregate Functions
- WHERE
- GROUP BY
- ORDER BY
- HAVING
- JOINs
- LEFT JOIN
- DISTINCT
- LIMIT
- COALESCE
- Date Filtering
- Revenue Analysis
- Inventory Analysis
- Customer Analysis

---

📊 Key Business Metrics

The project focuses on the following major business metrics:

KPI| Analysis
📚 Total Stock| Total books currently available
💰 Total Revenue| Revenue generated from orders
🛒 Order Quantity| Quantity of books ordered
💵 Highest Book Price| Most expensive book
📉 Lowest Stock| Book with the lowest inventory
👥 Customer Orders| Customers with multiple orders
🏆 Top Book| Most frequently ordered book
📊 Genre Sales| Books sold by genre
✍️ Author Sales| Books sold by author
📦 Remaining Stock| Stock after accounting for orders

---

📚 Basic SQL Analysis

The project performs the following basic analyses:

1️⃣ Fiction Books

Retrieve all books belonging to the Fiction genre.

2️⃣ Books Published After 1950

Identify books published after 1950.

3️⃣ Customers from Canada

Retrieve customers whose country is Canada.

4️⃣ November 2023 Orders

Identify orders placed during November 2023.

5️⃣ Total Stock

Calculate the total number of books available in stock.

6️⃣ Most Expensive Book

Identify the book with the highest price.

7️⃣ Multiple-Quantity Orders

Find orders where customers ordered more than one book.

8️⃣ Orders Above $20

Identify orders where the total amount is greater than $20.

9️⃣ Available Genres

Retrieve all unique genres available in the bookstore.

🔟 Lowest Stock

Identify the book with the lowest available stock.

1️⃣1️⃣ Total Revenue

Calculate the total revenue generated from all orders.

---

📈 Advanced SQL Analysis

📚 Books Sold by Genre

Calculate the total quantity of books sold for each genre.

This helps understand which genres have higher sales volumes.

---

💰 Average Price of Fantasy Books

Calculate the average price of books belonging to the Fantasy genre.

---

👥 Customers with Multiple Orders

Identify customers who have placed at least two orders.

This helps identify customers with repeated purchasing activity.

---

🏆 Most Frequently Ordered Book

Identify the book that appears in orders most frequently.

This helps highlight popular books among customers.

---

💵 Top 3 Most Expensive Fantasy Books

Find the three highest-priced books within the Fantasy genre.

---

✍️ Books Sold by Author

Calculate the total quantity of books sold by each author.

This helps understand author-level sales performance.

---

🌎 Cities with Spending Above $30

Identify cities where customers have orders with spending above $30.

---

🏆 Highest-Spending Customer

Identify the customer who has spent the most based on total order value.

---

📦 Remaining Stock After Orders

Calculate the remaining stock for every book after accounting for the quantity ordered.

The analysis uses:

Remaining Stock = Available Stock − Ordered Quantity

"COALESCE()" is used to handle books that do not have any associated orders.

---

🧠 SQL Concepts Used

- "SELECT"
- "WHERE"
- "DISTINCT"
- "COUNT()"
- "SUM()"
- "AVG()"
- "MAX()"
- "GROUP BY"
- "ORDER BY"
- "HAVING"
- "JOIN"
- "LEFT JOIN"
- "LIMIT"
- "COALESCE()"
- Aggregate Functions
- Date Filtering
- Subqueries
- Customer Analysis
- Revenue Analysis
- Inventory Analysis
- Top-N Analysis

---

🔍 SQL Analysis Performed

Basic Analysis

- Retrieve Fiction books.
- Find books published after 1950.
- Find customers from Canada.
- Retrieve November 2023 orders.
- Calculate total stock.
- Find the most expensive book.
- Find orders with quantity greater than one.
- Find orders above $20.
- Identify available genres.
- Find the book with the lowest stock.
- Calculate total revenue.

Advanced Analysis

- Calculate books sold by genre.
- Calculate average Fantasy book price.
- Find customers with at least two orders.
- Identify the most frequently ordered book.
- Find the top 3 most expensive Fantasy books.
- Calculate books sold by author.
- Identify cities with spending above $30.
- Find the highest-spending customer.
- Calculate remaining stock after orders.

---

💡 Key Business Insights

The SQL analysis can be used to identify:

- 📚 Overall bookstore inventory levels.
- 💰 Total revenue generated from book sales.
- 🏆 The most expensive and frequently ordered books.
- 📊 Sales performance across different genres.
- 👥 Customers with repeated purchases.
- ✍️ Author-wise sales performance.
- 🌎 Customer spending across different cities.
- 📦 Books with low remaining inventory.
- 🔥 Popular books based on order activity.
- 📈 Overall sales and inventory performance.

---

💼 Business Recommendations

Based on the SQL analysis:

- 📦 Monitor books with low remaining stock to avoid stockouts.
- 🏆 Maintain sufficient inventory for frequently ordered books.
- 📚 Analyze high-performing genres for future inventory planning.
- 👥 Identify repeat customers for customer-retention strategies.
- ✍️ Monitor author-level sales to understand demand patterns.
- 💰 Track high-value customers and their purchasing behavior.
- 📊 Use revenue and order analysis to support bookstore decision-making.
- 🔄 Regularly compare available stock with ordered quantities.

---

📷 Project Documentation

The complete project documentation contains the business questions, PostgreSQL queries, and analysis performed throughout the project.

Project Documentation: "Online_Book_Store_SQL_Project.pdf"

---

📂 Repository Structure

Online-Book-Store-SQL/
│
├── README.md
│
├── SQL/
│   └── Online_Book_Store.sql
│
├── Dataset/
│   ├── Books.csv
│   ├── Customers.csv
│   └── Orders.csv
│
└── Documentation/
    └── Online_Book_Store_SQL_Project.pdf

---

🚀 Project Highlights

📚 20 Business Questions

🟢 11 Basic SQL Queries

🔵 9 Advanced SQL Queries

🐘 PostgreSQL Database

📊 Sales + Customer + Inventory Analysis

💡 Business-Oriented SQL Analysis

---

🎯 Project Objective

The main objective of this project is to demonstrate how PostgreSQL and SQL can be used to analyze an online bookstore's data and convert raw transactional data into useful business insights.

---

🙌 Thank You

⭐ If you find this project useful, feel free to explore the repository and the SQL analysis.