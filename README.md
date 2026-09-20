# 📚 Online Book Store — SQL Project

![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/Language-SQL-orange?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Project-Data%20Analysis-green?style=for-the-badge)
![Business Analytics](https://img.shields.io/badge/Domain-Business%20Analytics-purple?style=for-the-badge)

---

# 📌 Project Overview

This project presents an end-to-end **Online Book Store Analysis** developed using **PostgreSQL and SQL**.

The project analyzes **book information, customer details, orders, quantities, prices, genres, authors, revenue, and inventory** to generate meaningful business insights.

The project contains **20 practical SQL business questions**, divided into **11 Basic SQL Questions** and **9 Advanced SQL Questions**.

---

# 🎯 Business Problem

An online bookstore needs to understand its **sales, customers, books, revenue, and inventory** to support better business analysis.

This project answers important business questions such as:

- Which books belong to the **Fiction** genre?
- Which books were published after **1950**?
- Which customers are from **Canada**?
- What orders were placed in **November 2023**?
- What is the **total stock** available?
- Which is the **most expensive book**?
- Which orders contain more than **1 quantity**?
- Which orders have a total amount above **$20**?
- What genres are available?
- Which book has the **lowest stock**?
- What is the **total revenue**?
- How many books were sold in each genre?
- What is the average price of **Fantasy** books?
- Which customers have placed at least **2 orders**?
- Which book is ordered most frequently?
- What are the **Top 3 most expensive Fantasy books**?
- How many books were sold by each author?
- Which cities have customers who spent over **$30**?
- Which customer spent the most?
- How much stock remains after fulfilling orders?

---

# 📁 Dataset Information

| Attribute | Details |
|---|---|
| 🏢 Industry | E-Commerce / Online Book Store |
| 📊 Dataset | Online Book Store |
| 🗄️ Database | PostgreSQL |
| 💻 Analysis Tool | SQL |
| 📈 Analysis Type | Sales, Customer & Inventory Analysis |
| 🚀 Project Type | End-to-End SQL Data Analysis |

## 📂 Database Tables

| Table | Description |
|---|---|
| 📚 **Books** | Book information, price, genre, author & stock |
| 👥 **Customers** | Customer identity and location details |
| 🛒 **Orders** | Purchase, quantity, date & total amount |

---

# 🛠 Tools & Techniques

- 🐘 PostgreSQL
- 💻 SQL
- 🖥️ pgAdmin
- 🔎 Data Filtering
- 📊 Data Aggregation
- 🔗 SQL JOINs
- 📈 Business Analysis
- 📦 Inventory Analysis
- 💰 Revenue Analysis
- 👥 Customer Analysis

---

# 📊 Key Business Metrics

| KPI | Analysis |
|---|---|
| 📚 **Total Stock** | Total available books |
| 💰 **Total Revenue** | Revenue generated from orders |
| 🛒 **Order Quantity** | Quantity of books ordered |
| 💵 **Highest Book Price** | Most expensive book |
| 📉 **Lowest Stock** | Book with the lowest stock |
| 🏆 **Most Ordered Book** | Most frequently ordered book |
| 📊 **Genre Sales** | Books sold by genre |
| ✍️ **Author Sales** | Books sold by author |
| 👥 **Customer Orders** | Customers with multiple orders |
| 📦 **Remaining Stock** | Stock after fulfilling orders |

---

# 📚 Basic SQL Analysis

## 1️⃣ Retrieve Fiction Books

Find all books belonging to the **Fiction** genre.

## 2️⃣ Books Published After 1950

Find books published after the year **1950**.

## 3️⃣ Customers from Canada

List all customers whose country is **Canada**.

## 4️⃣ Orders in November 2023

Retrieve orders placed during **November 2023**.

## 5️⃣ Total Book Stock

Calculate the total stock of books available.

## 6️⃣ Most Expensive Book

Find the details of the most expensive book.

## 7️⃣ Multiple-Quantity Orders

Find orders where the ordered quantity is greater than **1**.

## 8️⃣ Orders Above $20

Retrieve orders where the total amount exceeds **$20**.

## 9️⃣ Available Genres

List all unique genres available in the Books table.

## 🔟 Lowest Stock Book

Find the book with the lowest stock.

## 1️⃣1️⃣ Total Revenue

Calculate the total revenue generated from all orders.

---

# 📈 Advanced SQL Analysis

## 1️⃣2️⃣ Books Sold by Genre

Calculate the total number of books sold for each genre.

## 1️⃣3️⃣ Average Fantasy Book Price

Calculate the average price of books belonging to the **Fantasy** genre.

## 1️⃣4️⃣ Customers with At Least 2 Orders

Identify customers who have placed **at least two orders**.

## 1️⃣5️⃣ Most Frequently Ordered Book

Find the book that is ordered most frequently.

## 1️⃣6️⃣ Top 3 Most Expensive Fantasy Books

Retrieve the **Top 3 most expensive books** from the Fantasy genre.

## 1️⃣7️⃣ Books Sold by Author

Calculate the total quantity of books sold by each author.

## 1️⃣8️⃣ Cities with Spending Above $30

List cities where customers have spent more than **$30**.

## 1️⃣9️⃣ Highest-Spending Customer

Find the customer who spent the most on orders.

## 2️⃣0️⃣ Remaining Stock After Orders

Calculate the stock remaining after fulfilling all orders.

**Remaining Stock = Available Stock − Ordered Quantity**

---

# 🔍 SQL Analysis Performed

## 🟢 Basic Analysis

- Retrieve Fiction books
- Find books published after 1950
- Find customers from Canada
- Retrieve November 2023 orders
- Calculate total stock
- Find the most expensive book
- Find orders with quantity greater than 1
- Find orders above $20
- List available genres
- Find the lowest-stock book
- Calculate total revenue

## 🔵 Advanced Analysis

- Calculate books sold by genre
- Calculate average Fantasy book price
- Find customers with at least 2 orders
- Find the most frequently ordered book
- Find Top 3 expensive Fantasy books
- Calculate books sold by author
- Find cities with spending above $30
- Find the highest-spending customer
- Calculate remaining stock after orders

---

# 🧠 SQL Concepts Used

- `SELECT`
- `WHERE`
- `DISTINCT`
- `COUNT()`
- `SUM()`
- `AVG()`
- `GROUP BY`
- `ORDER BY`
- `HAVING`
- `JOIN`
- `LEFT JOIN`
- `LIMIT`
- `COALESCE()`
- Aggregate Functions
- Date Filtering
- Sorting
- Filtering
- Customer Analysis
- Revenue Analysis
- Inventory Analysis
- Top-N Analysis

---

# 💡 Key Business Insights

The SQL analysis helps identify:

- 📚 Book inventory across different genres.
- 💰 Total revenue generated from book orders.
- 🏆 The most frequently ordered books.
- 📉 Books with low inventory levels.
- 📊 Sales performance across genres.
- 👥 Customers with repeated purchases.
- ✍️ Author-wise book sales.
- 🌎 Customer spending across cities.
- 📦 Remaining inventory after orders.

---

# 💼 Business Recommendations

Based on the SQL analysis:

- 📦 Monitor books with low remaining stock.
- 🏆 Maintain sufficient inventory for frequently ordered books.
- 📚 Analyze genre-wise sales for inventory planning.
- 👥 Monitor repeat customers for customer-retention analysis.
- ✍️ Analyze author-wise sales to understand demand.
- 💰 Monitor high-spending customers.
- 📊 Track revenue and order performance regularly.
- 🔄 Compare stock levels with ordered quantities.

---

# 📷 Project Documentation

The complete project documentation contains the **20 business questions and SQL queries** used in this project.

📄 **Documentation:** `Online_Book_Store.pdf`

---

# 📂 Repository Structure

```text
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