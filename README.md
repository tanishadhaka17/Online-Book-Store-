# 📚 Online Bookstore SQL Project  

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue?logo=postgresql)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![License](https://img.shields.io/badge/License-MIT-orange)  

## 📖 Table of Contents  
- [📌 Project Overview](#-project-overview)  
- [🗄️ Database Schema](#️-database-schema)  
- [📂 Dataset](#-dataset)  
- [📝 Practical SQL Queries](#-practical-sql-queries)  
- [🔍 Advanced SQL Queries](#-advanced-sql-queries)  
- [📊 Key Insights](#-key-insights)  
- [🛠️ Tech Stack](#️-tech-stack)  
- [🚀 How to Run This Project](#-how-to-run-this-project)  
- [📌 Future Improvements](#-future-improvements)  
- [🧑‍💻 Author](#-author)  

---

## 📌 Project Overview  
This project demonstrates the design and implementation of an **Online Bookstore Database** using SQL. It covers:  
- Database creation  
- Table design with relationships  
- Data import from CSV files  
- Practical SQL queries for analysis  
- Advanced queries for business insights  

The goal is to **analyze books, customers, and orders data** to extract meaningful insights like sales trends, customer behavior, and revenue generation.  

---

## 🗄️ Database Schema  
The project contains three main tables:  

1. **Books** – Stores details of books (title, author, genre, published year, price, stock).  
2. **Customers** – Contains customer information (name, email, phone, city, country).  
3. **Orders** – Tracks customer purchases with details (order date, quantity, total amount).  

**Relationships:**  
- Each order is linked to a customer (`Customer_ID`).  
- Each order refers to a book (`Book_ID`).  

---

## 📂 Dataset  
Data is imported from CSV files into the database:  
- `BOOKS_DATA.csv` → Books  
- `CUSTOMERS_DATA.csv` → Customers  
- `ORDER_DATA.csv` → Orders  

---

## 📝 Practical SQL Queries  
Some of the queries included:  
- Retrieve all books in the **Fiction** genre  
- Find books published after **1950**  
- List customers from **Canada**  
- Show orders placed in **November 2023**  
- Calculate total **stock** of books  
- Find the **most expensive book**  
- Get all orders where total amount > $20  
- Find the book with the **lowest stock**  
- Calculate total **revenue** from orders  

---

## 🔍 Advanced SQL Queries  
The project also covers deeper analysis, such as:  
- Total number of books sold for each genre  
- Average price of books in the **Fantasy** genre  
- Customers with **at least 2 orders**  
- Most frequently ordered book  
- Top 3 most expensive books in **Fantasy**  
- Total quantity of books sold by each author  
- Cities where customers spent more than **$300**  
- Customer who spent the **most on orders**  
- Remaining stock after fulfilling all orders  

---

## 📊 Key Insights  
- Ability to track **sales trends by genre, author, and customer**  
- Identify **high-value customers** and their spending behavior  
- Monitor **stock levels** and detect low-inventory books  
- Calculate overall **revenue and performance** of the store  

---

## 🛠️ Tech Stack  
- **SQL (PostgreSQL)**  
- **CSV files** for data import  
- **Relational database design** principles  

---

## 🚀 How to Run This Project  
1. Create a PostgreSQL database:  
   ```sql
   CREATE DATABASE OnlineBookstore;
2. Run the SQL script from this repository to create tables.

3. Import CSV data into the respective tables.

4. Execute queries to analyze the data.

📌 #Future Improvements

Add stored procedures and triggers

Create views for reporting

Build a dashboard in Power BI / Tableau / Excel using this database

Expand with more customer and sales datasets

🧑‍💻 #Author

Tanisha Dhaka
💡 Passionate about SQL, Data Analysis, and Database Design
