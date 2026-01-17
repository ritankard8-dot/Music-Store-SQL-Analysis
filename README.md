# 🎵 Digital Music Store Data Analysis

## 📌 Project Overview
This project analyzes a digital music store database (similar to iTunes) to derive insights into store performance, customer behavior, and sales trends. The analysis answers key business questions ranging from identifying top-paying customers to finding the most popular music genres by country.

**Key Goals:**
* Identify the Senior-most employees and top customers.
* Analyze genre popularity across different countries.
* Determine the best-selling artists and tracks.

## 🛠️ Tools & Technologies
* **Database:** PostgreSQL 16
* **SQL Client:** pgAdmin 4
* **Skills Applied:**
    * **Joins:** Inner Joins, Multi-table Joins (up to 5 tables).
    * **Aggregations:** `COUNT()`, `SUM()`, `AVG()`.
    * **Advanced Logic:** `CTE` (Common Table Expressions), Recursive Queries.
    * **Filtering:** `LIKE`, `IN`, `DISTINCT`.

## 📂 Project Structure
The SQL analysis is categorized into three levels of difficulty:

1.  **Beginner (Set 1):** Basic queries using `SELECT`, `ORDER BY`, and `LIMIT` to explore the dataset.
2.  **Intermediate (Set 2):** Joins and Grouping to analyze customer purchases and genre preferences.
3.  **Advanced (Set 3):** Complex queries using CTEs and Window Functions to find top sales per country and customer spending patterns.

## 📊 Sample Insights
* **Top Genre:** Rock makes up the majority of the store's track listings.
* **Best Selling Artist:** Analyzed invoice line items to determine the artist with the highest earnings.
* **Customer Demographics:** Identified key markets in the USA, Canada, and Brazil.

## 🚀 How to Run
1.  Install **PostgreSQL** and **pgAdmin**.
2.  Create a database named `Music_Store`.
3.  Restore the schema and data using the provided backup file.
4.  Open `Music_Store_Analysis.sql` in the Query Tool and run the queries.

---
*Author: [Your Name]*
