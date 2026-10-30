# 🚗 SQL Subquery Case Study – Car Sales Orders Database

![SQL](https://img.shields.io/badge/SQL-MySQL-blue?logo=mysql)
![Project Type](https://img.shields.io/badge/Project-Data%20Analytics-orange)
![Records](https://img.shields.io/badge/Records-50-success)
![Queries](https://img.shields.io/badge/Business%20Questions-14-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project focuses on analysing a **Car Sales Orders Database** using SQL subqueries in MySQL.

The objective was to solve real-world business questions by applying SQL concepts such as **subqueries, correlated subqueries, aggregate functions, GROUP BY, HAVING, MAX(), MIN(), and AVG()**.

The project contains 50 car purchase records across different customers, cities, and car categories. I used these records to solve 14 business-oriented SQL questions and extract meaningful insights.

## 🎯 Project Objectives

- Practise SQL subqueries using real-world business scenarios.
- Identify high-value and low-value car purchases.
- Compare individual order prices with average prices.
- Find the highest-priced orders across cities and categories.
- Understand and implement correlated subqueries.
- Improve SQL problem-solving and analytical thinking.

## 🗄️ Database Information

**Database Name:** `orders`  
**Table Name:** `Orders`  
**Total Records:** 50  
**Total Business Questions:** 14

### Database Schema

| Column | Data Type | Description |
|---|---|---|
| Order_ID | INT | Unique order ID (Primary Key) |
| Customer_Name | VARCHAR(100) | Customer's name |
| Product_Name | VARCHAR(100) | Car model |
| Car_Category | VARCHAR(50) | SUV, Sedan, Hatchback, MPV |
| City | VARCHAR(50) | Customer's city |
| Price | DECIMAL(10,2) | Car purchase price |

## 🛠️ Tools & Technologies

- **MySQL** – Database management and query execution
- **SQL** – Data retrieval and analysis
- **MySQL Workbench** – Writing and executing SQL queries
- **GitHub** – Project documentation and version control

## 📊 SQL Concepts Covered

| SQL Concept | Application |
|---|---|
| Subqueries | Filtering records using another query |
| Correlated Subqueries | Comparing records within the same group |
| AVG() | Calculating average car prices |
| MAX() | Finding the highest purchase price |
| MIN() | Finding the lowest purchase price |
| GROUP BY | Grouping orders by category |
| HAVING | Filtering aggregated results |
| DISTINCT | Identifying unique cities |
| WHERE | Filtering records based on conditions |

## 🧠 Business Questions Solved

### 1. Correlated Subquery Problems

1. Find orders above the average price for their category.
2. Find the highest-priced SUV in each city.
3. Find customers with above-average purchases for their city and category.
4. Identify the highest-priced order for each city and car category.
5. Find customers whose purchase is the highest in their city.

### 2. General Subquery Problems

6. Identify the highest-value order.
7. Find orders above the overall average price.
8. Find orders above Ahmedabad's average price.
9. Find the cheapest SUV.
10. Identify cities with high-value sales.
11. Find orders more expensive than the average Sedan.
12. Find orders above the average price of cars costing more than ₹20 lakhs.
13. Find the city with the highest-priced order.
14. Identify categories with above-average order prices.

## 📈 Key Learning Outcomes

Through this project, I gained practical experience in:

- Writing nested SQL queries.
- Understanding the difference between simple and correlated subqueries.
- Using aggregate functions to solve analytical problems.
- Comparing individual records against grouped averages.
- Translating business requirements into SQL queries.
- Debugging and improving SQL query logic.

## 📂 Project Structure

```text
SQL-Subquery-Case-Study/
│
├── SQL SUBQUERY.sql
├── README.md
└── SQL_Subquery_Case_Study_Assignment.docx
```

*Keep the SQL and Word assignment files in your repository if you want visitors to access the complete database script and documentation.*

## ⚙️ How to Run This Project

1. Download or clone this repository.
2. Open MySQL Workbench.
3. Open the `SQL SUBQUERY.sql` file.
4. Execute the database creation and table creation statements.
5. Execute the INSERT statements to load the 50 records.
6. Run the SQL queries to explore the business questions.

## 💡 Conclusion

This SQL case study helped me strengthen my understanding of subqueries and correlated subqueries through practical business scenarios.

Rather than focusing only on writing SQL syntax, I learned how to approach business problems, analyse data, and retrieve meaningful insights using SQL.

**Project Status: Completed ✅**

---

## 👨‍💻 Author

**Ubaid Pathan**

Aspiring Data Analyst | SQL | MySQL | Excel | Power BI | Python


---

⭐ If you find this project useful, feel free to explore the SQL queries and share your feedback!
