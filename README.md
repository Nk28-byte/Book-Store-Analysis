# 📚 Book Store Analysis (SQL Project)

This project is a SQL-based data analysis of a fictional **online book store**. The database includes information about books, customers, and their orders. Various SQL queries are used to extract insights such as sales, inventory, and customer behavior.

---

## 📊 ER Diagram

Below is the Entity-Relationship Diagram (ERD) representing the structure of the database. It shows how the tables (Book, Customer, Orders) are related to each other.

![ER Diagram](schema.png)

---

## 🗂️ Database Tables

### 1. **Book**
- `Book_id` (Primary Key)
- `Title`
- `Author`
- `Genre`
- `Published_year`
- `Price`
- `Stock`

### 2. **Customer**
- `Customer_id` (Primary Key)
- `Name`
- `Email`
- `Phone`
- `City`
- `Country`

### 3. **Orders**
- `Order_id` (Primary Key)
- `Customer_id` (Foreign Key → Customer)
- `Book_id` (Foreign Key → Book)
- `Order_date`
- `Quantity`
- `Total_amount`

---

## 🧾 Key SQL Queries in This Project

### 📌 Basic Queries:
1. Retrieve all the books in the **fiction** genre  
2. Find books published **after 1950**  
3. List all customers from **Canada**  
4. Show orders placed in **November 2023**  
5. Find **total stock** of all books  
6. Get the **most expensive book**  
7. Customers who ordered more than **1 quantity**  
8. Orders where **total amount > $20**  
9. List all **distinct genres**  
10. Book with **lowest stock**  
11. Calculate **total revenue** from orders  

---

### 🔍 Advanced Queries:
1. Total number of books sold by **genre**
2. Average price of books in **Fantasy** genre
3. Customers with **2 or more orders**
4. **Most frequently ordered** book
5. Top 3 **most expensive books** in Fantasy
6. Total books sold by each **author**
7. Cities of customers who spent over **$30**
8. **Top-spending customer**

---

## 💻 Tools Used

- SQL (MySQL)
- Microsoft Excel (for ER Diagram)
- Any SQL client (e.g., MySQL Workbench / DBeaver)

---

## 📁 Project Files

| File Name                  | Description                             |
|---------------------------|-----------------------------------------|
| `book_store_analysis.sql` | SQL code with schema and all queries    |
| `schema.png`              | ER diagram image made using Excel       |
| `README.md`               | Project overview and documentation      |

---

## 👩‍💻 Author

**Nitesh Badwaiya**  
https://www.linkedin.com/in/nitesh-badwaiya/   

---

## 📌 How to Use This Project

1. Import the SQL file into your MySQL client  
2. Run the `CREATE DATABASE` and `USE` commands  
3. Execute the queries one by one to see the analysis  
4. Modify queries as per your learning needs

---

## ⭐ Project Purpose

This project was created as part of my learning journey in SQL and database design. It helps in understanding:

- Table relationships
- Writing meaningful queries
- Performing basic and advanced analysis using SQL

---

