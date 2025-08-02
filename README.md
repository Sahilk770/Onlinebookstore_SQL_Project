# 📚 Online Bookstore – End-to-End SQL Project (Beginner Portfolio)

Welcome! I'm **Sahil Kadu**, an aspiring data analyst. This is a beginner-friendly yet practical SQL project that simulates an online bookstore business. It covers everything from database schema design and data import to generating business insights using SQL queries.

This project demonstrates my ability to work with relational databases, analyze data, and answer real business questions — a key skill for any data-driven role.

---

## 🚀 Project Overview

This SQL project was built using PostgreSQL and pgAdmin. It simulates a real-world e-commerce system for an online bookstore with the following goals:

- Store and manage books, customers, and orders
- Track inventory and sales performance
- Analyze revenue, customer behavior, and product trends
- Practice both beginner and advanced SQL queries

---

## 🛠️ Tools Used

- PostgreSQL
- pgAdmin 4
- SQL (DDL, DML, Aggregate Functions, Joins, Subqueries)

---

## 🧱 Database Schema

The database consists of the following tables:

| Table      | Description                                     |
|------------|-------------------------------------------------|
| `Books`    | Stores book details like title, author, genre, price, stock |
| `Customers`| Contains customer information including contact and location |
| `Orders`   | Tracks each book purchase, quantity, and total amount |

---

## 📂 Data Source

Sample data was imported into the database from three CSV files:
- `Books.csv`
- `Customers.csv`
- `Orders.csv`

---

## 🧠 SQL Concepts Demonstrated

- Table creation using `CREATE TABLE` and `FOREIGN KEY` constraints  
- Data import using `COPY` from CSV  
- Filtering with `WHERE`, `BETWEEN`, `IN`  
- Aggregations using `SUM`, `AVG`, `COUNT`, `GROUP BY`  
- Sorting and Limiting results  
- Joins (`INNER`, `LEFT`)  
- `HAVING`, `ORDER BY`, `DISTINCT`  
- Business logic using `COALESCE`, calculated fields  

---

## 📊 Sample Queries & Business Insights

Here are some key questions answered in the project:

### 🔹 Basic Queries:
- Find all books in the "Fiction" genre  
- Customers from Canada  
- Orders placed in November 2023  
- Total revenue generated  
- Book with the lowest stock  

### 🔹 Advanced Analysis:
- **Total books sold per genre**  
- **Top 3 most expensive Fantasy books**  
- **Customers with more than 1 order**  
- **Most frequently ordered book**  
- **Remaining stock after fulfilling all orders**  
- **Customer who spent the most**  
- **Cities where high-spending customers are located**


