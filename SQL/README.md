# 🗄️ SQL Exploratory Data Analysis (EDA) - Master's Activity

This repository contains the database script and queries developed for the SQL practical activity as part of my Master's degree program for a fictional bookshop database.

---

## 📂 File Structure
* `SQL_Activity_Script.sql`: The main SQL file containing all the queries, structural commands, and analysis.
* `README.md`: This file, documenting the assignment overview.

---

## 🛠️ Tech Stack & Database Environment
* **Language:** SQL
* **RDBMS used:** MySQL
* **Core Concepts Applied:** 
  * Aggregation functions ("SUM", "AVG", "COUNT", "GROUP BY")
  * Data filtering ("WHERE", "HAVING", "LIKE", "BETWEEN")
  * Joins and relationships ("INNER JOIN`, "LEFT JOIN")
  * Conditional logic ("CASE WHEN")
  * Advanced functions (Subqueries, CTEs...)

---

## 🗄️ Database Schema
Four related tables modelling a bookshop's catalogue and lending system:

_autores_: author details (id, first name, last name)
_categorias_: book categories (id, name)
_libros_: book catalogue (title, author, category, price, stock, publication date)
_prestamos_: lending records (book, client, loan date, return date)

---

## ▶️ How to Run

1. **Open MySQL Workbench** (or any MySQL client)
2. **Run the full SQL_activities.sql file**. This creates the schema, inserts sample data and runs all queries sequentially

---

## 📬 Contact
* **LinkedIn:** [linkedin.com/in/jesusonievapalomar](https://www.linkedin.com/in/jesusonievapalomar)
