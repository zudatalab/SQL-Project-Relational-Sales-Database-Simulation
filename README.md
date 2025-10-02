Project Overview: SalesDB – Relational Sales Database Simulation & SQL Querying
---
💻 Tech Stack: MySQL (SQL)
---
🧩 Description

SalesDB is a hands-on SQL project where I built a relational database from scratch to simulate a real-world sales environment. 
This includes creating a normalized schema, populating realistic sample data, and writing SQL queries to extract meaningful business insights.
The project was designed to strengthen my understanding of database design,relational modeling and query optimization 
— essential skills for data-centric roles such as Data Analyst, BI Developer and Data Engineer.
---
📦 Core Tables

➤ Customers– Stores customer details, country, and score
➤ Employees – Includes employee details with manager hierarchy (self-referencing FK)
➤ Products– Product catalog with category and price
➤ Orders – Live sales orders with foreign keys to customers, employees, and products
➤ Orders_archive`** – Archived historical order data for analysis
---
🔍 Features & Highlights

 ✅ Database creation with foreign keys, indexes, and referential integrity
 ✅ Simulated real-world transactional data across departments and customers
 ✅ Used JOINs, subqueries, **GROUP BY**, HAVING, UNION and aggregates
 ✅ Time-based analysis using `DATEDIFF()` and `BETWEEN`
 ✅ Compared live (`orders`) and archived (`orders_archive`) datasets
---

 📊 Sample Business Queries

➤ Total sales per customer
➤ Number of orders per salesperson
➤ Employees earning above the average salary
➤ Orders shipped in February 2025
➤ Orders that took more than 10 days to ship
➤ Customers with more than 2 purchases
➤ Order IDs common to both active and archive tables
➤ Combined customer and employee directory (with/without duplicates)
➤ Total sales from live vs. archived data
---
 🎯 Skills Gained

➤ Relational database design & normalization
➤ Writing efficient SQL queries
➤ Aggregations & business metric extraction
➤ Self-joins and foreign key constraints
➤ Data manipulation and reporting logic
---
📌 Why This Project Matters

This project is more than just practice — it reflects real-world scenarios faced in sales, CRM, and BI systems. 
It showcases how raw data can be structured, related, and queried for insightful analysis — a critical skill in any data role.
---
