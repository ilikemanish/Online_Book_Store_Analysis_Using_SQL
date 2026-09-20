📚 Online Book Store Analysis — SQL Project

"PostgreSQL" (https://img.shields.io/badge/Tool-PostgreSQL-blue)
"SQL" (https://img.shields.io/badge/Language-SQL-orange)
"Data Analysis" (https://img.shields.io/badge/Project-Data%20Analysis-green)
"Business Intelligence" (https://img.shields.io/badge/Domain-Business%20Analytics-purple)

---

📌 Project Overview

This project presents an end-to-end Online Book Store Analysis developed using PostgreSQL and SQL.

The project analyzes book information, customer details, orders, quantities, prices, genres, authors, revenue, and inventory to generate meaningful business insights.

The analysis contains 20 practical SQL business questions, divided into Basic SQL Analysis and Advanced SQL Analysis.

The project demonstrates how SQL can be used for data retrieval, filtering, sorting, aggregation, joins, grouping, ranking, customer analysis, revenue analysis, and inventory analysis.

---

🎯 Business Problem

An online bookstore needs to understand its books, customers, sales, revenue, and inventory to make better business decisions.

This project aims to answer key business questions such as:

- Which books belong to the Fiction genre?
- Which books were published after 1950?
- Which customers are from Canada?
- What orders were placed in November 2023?
- What is the total stock of books available?
- Which is the most expensive book?
- Which customers ordered more than one quantity of a book?
- Which orders have a total amount above $20?
- What genres are available?
- Which book has the lowest stock?
- What is the total revenue generated?
- How many books were sold for each genre?
- What is the average price of Fantasy books?
- Which customers have placed at least 2 orders?
- Which book is ordered most frequently?
- What are the top 3 most expensive Fantasy books?
- How many books were sold by each author?
- Which cities have customers who spent over $30?
- Which customer spent the most?
- How much stock remains after fulfilling orders?

---

📁 Dataset Information

Attribute| Details
Industry| E-Commerce / Online Book Store
Dataset| Online Book Store
Database| PostgreSQL
Analysis Tool| SQL
Analysis Type| Sales, Customer & Inventory Analysis
Project Type| End-to-End SQL Data Analysis

📂 Dataset Tables

The project uses three main tables:

Table| Information
📚 Books| Book information, price, genre, author & stock
👥 Customers| Customer identity and location details
🛒 Orders| Purchase, quantity, date & total amount

The tables are connected using common identifiers such as Book_ID and Customer_ID.

---

🛠 Tools & Techniques

- PostgreSQL
- SQL
- pgAdmin
- SELECT Statements
- Filtering
- Sorting
- Aggregate Functions
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
- Customer Analysis
- Inventory Analysis

---

📊 Key Business Metrics

The project focuses on the following key business metrics:

KPI| Analysis
📚 Total Stock| Total available books
💰 Total Revenue| Revenue generated from all orders
🛒 Order Quantity| Quantity of books ordered
💵 Highest Book Price| Most expensive book
📉 Lowest Stock| Book with the lowest stock
👥 Customer Orders| Customers with multiple orders
🏆 Most Ordered Book| Most frequently ordered book
📊 Genre Sales| Books sold by genre
✍️ Author Sales| Books sold by author
📦 Remaining Stock| Stock remaining after orders

---

📚 Basic SQL Analysis

1️⃣ Fiction Books

Retrieve all books belonging to the Fiction genre.

2️⃣ Books Published After 1950

Find all books published after the year 1950.

3️⃣ Customers from Canada

List all customers whose country is Canada.

4️⃣ November 2023 Orders

Show all orders placed during November 2023.

5️⃣ Total Book Stock

Calculate the total stock of books available.

6️⃣ Most Expensive Book

Find the details of the book with the highest price.

7️⃣ Multiple-Quantity Orders

Show customers/orders where more than 1 quantity of a book was ordered.

8️⃣ Orders Above $20

Retrieve all orders where the total amount exceeds $20.

9️⃣ Available Genres

List all unique genres available in the Books table.

🔟 Lowest Stock Book

Find the book with the lowest stock.

1️⃣1️⃣ Total Revenue

Calculate the total revenue generated from all orders.

These basic queries focus on core retrieval, filtering, sorting, and aggregation tasks.

---

📈 Advanced SQL Analysis

📚 Books Sold by Genre

Retrieve the total number of books sold for each genre.

This helps analyze genre-level sales performance.

---

💰 Average Fantasy Book Price

Calculate the average price of books belonging to the Fantasy genre.

---

👥 Customers with Multiple Orders

Identify customers who have placed at least 2 orders.

---

🏆 Most Frequently Ordered Book

Find the book that has been ordered most frequently.

---

💵 Top 3 Most Expensive Fantasy Books

Retrieve the top 3 most expensive books from the Fantasy genre.

---

✍️ Books Sold by Author

Calculate the total quantity of books sold by each author.

---

🌎 Cities with Spending Above $30

List the cities where customers have spent more than $30.

---

🏆 Highest-Spending Customer

Find the customer who spent the most on orders.

---

📦 Remaining Stock After Orders

Calculate the stock remaining after fulfilling all orders.

The calculation uses:

Remaining Quantity = Stock − Ordered Quantity

The query also uses "COALESCE()" to handle books without associated orders.

---

🔍 SQL Analysis Performed

Basic Analysis

- Retrieve Fiction books.
- Find books published after 1950.
- Find customers from Canada.
- Retrieve November 2023 orders.
- Calculate total stock.
- Find the most expensive book.
- Find orders with quantity greater than 1.
- Find orders above $20.
- List available genres.
- Find the book with the lowest stock.
- Calculate total revenue.

Advanced Analysis

- Calculate books sold by genre.
- Calculate average Fantasy book price.
- Find customers with at least 2 orders.
- Find the most frequently ordered book.
- Find the top 3 expensive Fantasy books.
- Calculate books sold by author.
- Find cities with spending above $30.
- Find the highest-spending customer.
- Calculate remaining stock after orders.

---

🧠 SQL Concepts Used

- "SELECT"
- "WHERE"
- "DISTINCT"
- "COUNT()"
- "SUM()"
- "AVG()"
- "GROUP BY"
- "ORDER BY"
- "HAVING"
- "JOIN"
- "LEFT JOIN"
- "LIMIT"
- "COALESCE()"
- Aggregate Functions
- Date Filtering
- Sorting
- Filtering
- Customer Analysis
- Revenue Analysis
- Inventory Analysis
- Top-N Analysis

---

💡 Key Business Insights

The SQL analysis helps identify:

- 📚 Books available across different genres.
- 💰 Total revenue generated through book orders.
- 🏆 The most expensive book.
- 📉 Books with low inventory levels.
- 📊 Genre-wise book sales.
- 👥 Customers with repeated orders.
- 🏆 The most frequently ordered book.
- ✍️ Author-wise quantity of books sold.
- 🌎 Cities associated with higher customer spending.
- 📦 Remaining inventory after accounting for orders.

---

💼 Business Recommendations

Based on the SQL analysis:

- 📦 Monitor books with low stock to avoid inventory shortages.
- 🏆 Maintain sufficient stock for frequently ordered books.
- 📚 Analyze genre-wise sales to support inventory planning.
- 👥 Monitor customers with multiple orders for customer-retention analysis.
- ✍️ Analyze author-wise sales to understand customer demand.
- 💰 Monitor high-spending customers and their purchasing activity.
- 📊 Track total revenue and order values regularly.
- 🔄 Compare available stock with ordered quantities to manage inventory effectively.

---

📷 Project Documentation

The complete project documentation contains the 20 business questions and their SQL queries, along with the database analysis.

Project Documentation: "Online_Book_Store.pdf"

The PDF includes the project introduction, database structure, basic questions, advanced questions, SQL queries, and a final Thank You page.

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
    └── Online_Book_Store.pdf

---

🚀 Project Highlights

📚 20 Practical SQL Questions

🟢 11 Basic SQL Questions

🔵 9 Advanced SQL Questions

🐘 PostgreSQL Database

📊 Sales & Revenue Analysis

👥 Customer Analysis

📦 Inventory Analysis

💡 Business-Oriented SQL Project

---

🎯 Project Objective

The main objective of this project is to demonstrate how PostgreSQL and SQL can be used to analyze an online bookstore database and transform raw book, customer, and order data into meaningful business insights.

---

🙌 Thank You

⭐ If you find this project useful, feel free to explore the repository and SQL analysis.