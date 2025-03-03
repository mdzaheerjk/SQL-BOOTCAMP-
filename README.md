# 🚀 SQL Bootcamp  

Welcome to the **SQL Bootcamp** repository! This repo contains **notes, mind maps, and important SQL queries** to help you master SQL from beginner to advanced levels.  

## 📌 Table of Contents  

- [📖 Overview](#-overview)  
- [🧠 Mind Maps](#-mind-maps)  
- [📋 Notes](#-notes)  
- [⚡ Important Queries](#-important-queries)  
- [💡 Projects & Practice](#-projects--practice)  
- [📚 Resources](#-resources)  
- [🤝 Contributing](#-contributing)  

---

## 📖 Overview  

This bootcamp covers:  
✅ Database Basics  
✅ SQL Syntax & Queries  
✅ Joins & Subqueries  
✅ Indexing & Optimization  
✅ Stored Procedures & Triggers  
✅ Advanced Topics (CTE, Window Functions, etc.)  

---

## 🧠 Mind Maps  

Find all mind maps in the `mind_maps/` directory.  

📌 Topics Covered:  
- SQL Basics & Commands  
- Database Relationships  
- Joins & Subqueries  
- Normalization & Indexing  

---

## 📋 Notes  

Structured **topic-wise notes** are available in the `notes/` directory.  

### Topics Covered:  
- SQL Basics  
- Data Types & Constraints  
- Joins (Inner, Left, Right, Full)  
- Subqueries & CTEs  
- Transactions & ACID Properties  
- SQL Performance Optimization  

---
## 💡 Projects & Practice

The projects/ directory contains real-world SQL projects for hands-on practice.

🔹 Example Projects:

1️⃣ E-commerce Database Analysis

Analyze customer orders, revenue, and trends.

Use GROUP BY, JOINS, and WINDOW FUNCTIONS.


2️⃣ Employee Management System

Create and manage employee records.

Implement CRUD operations and INDEXING.


3️⃣ Hotel Booking Database

Store and retrieve hotel booking details.

Optimize QUERY PERFORMANCE.


4️⃣ Library Management System

Track books, borrowers, and due dates.

Use TRANSACTIONS for database consistency.


5️⃣ Social Media Analytics

Analyze user engagement and post interactions.

Utilize ADVANCED SQL FUNCTIONS.



---

## 📚 Resources

Here are some helpful resources to boost your SQL learning:

## 📖 Books:

SQL for Data Analysis - Cathy Tanimura

SQL in 10 Minutes - Ben Forta

Practical SQL - Anthony DeBarros

SQL Performance Explained - Markus Winand


## 🤝 Contributing

Contributions are welcome! Feel free to:
✅ Improve the notes

✅ Add new SQL queries

✅ Share additional resources

To contribute, fork the repo, make changes, and submit a pull request.


---

⭐ Star this repository if you found it helpful! Happy coding! 🚀

## ⚡ Important Queries  

A collection of **handy SQL queries** is available in the `queries/` directory.  

```sql
-- Retrieve all employees with salary greater than 50,000
SELECT * FROM employees WHERE salary > 50000;

-- Find the total number of orders per customer
SELECT customer_id, COUNT(*) FROM orders GROUP BY customer_id;

-- Get the top 5 highest-paid employees
SELECT * FROM employees ORDER BY salary DESC LIMIT 5;


