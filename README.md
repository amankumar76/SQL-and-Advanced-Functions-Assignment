# 🧠 Introduction to SQL and Advanced Functions  
  
## 📘 Overview  
This repository showcases my structured approach to solving SQL-based analytical and database management tasks.  
The assignment demonstrates practical knowledge of **Database Design**, **Data Manipulation**, **Advanced SQL Queries**, and **Analytical Problem Solving**.  

It includes both **theoretical understanding** and **hands-on SQL execution** using databases such as **ECommerceDB** and **Sakila**.

---

## 🧩 Assignment Details  

### **Instructions**
- Read each question carefully before attempting.  
- Theoretical questions are explained using clear definitions and examples.  
- Practical questions are executed using **SQL Workbench / Google Colab**. 

---

## 🧱 Questions

### **Question 1**  
Explain the fundamental differences between **DDL**, **DML**, and **DQL** commands in SQL. Provide one example for each type of command.  

---

### **Question 2**  
What is the purpose of **SQL constraints**?  
Name and describe three common types of constraints, providing a simple scenario where each would be useful.  

---

### **Question 3**  
Explain the difference between **LIMIT** and **OFFSET** clauses in SQL.  
How would you use them together to retrieve the **third page of results**, assuming each page has 10 records?  

---

### **Question 4**  
What is a **Common Table Expression (CTE)** in SQL, and what are its main benefits?  
Provide a simple SQL example demonstrating its usage.  

---

### **Question 5**  
Describe the concept of **SQL Normalization** and its primary goals.  
Briefly explain the first three normal forms (**1NF**, **2NF**, **3NF**).  

---

### **Question 6**  
Create a database named **ECommerceDB** and perform the following tasks:  

#### Tables:
- **Categories**
  - CategoryID (INT, PRIMARY KEY)  
  - CategoryName (VARCHAR(50), NOT NULL, UNIQUE)
- **Products**
  - ProductID (INT, PRIMARY KEY)  
  - ProductName (VARCHAR(100), NOT NULL, UNIQUE)  
  - CategoryID (INT, FOREIGN KEY → Categories)  
  - Price (DECIMAL(10,2), NOT NULL)  
  - StockQuantity (INT)
- **Customers**
  - CustomerID (INT, PRIMARY KEY)  
  - CustomerName (VARCHAR(100), NOT NULL)  
  - Email (VARCHAR(100), UNIQUE)  
  - JoinDate (DATE)
- **Orders**
  - OrderID (INT, PRIMARY KEY)  
  - CustomerID (INT, FOREIGN KEY → Customers)  
  - OrderDate (DATE, NOT NULL)  
  - TotalAmount (DECIMAL(10,2))

#### Insert Records:
Populate each table with the provided sample data for Categories, Products, Customers, and Orders.

---

### **Question 7**  
Generate a report showing **CustomerName**, **Email**, and the **TotalNumberOfOrders** for each customer.  
Include customers who have not placed any orders (show `0` as their count).  
Order results by **CustomerName**.  

---

### **Question 8**  
Retrieve product information with category:  
Display **ProductName**, **Price**, **StockQuantity**, and **CategoryName** for all products.  
Order results by **CategoryName**, then **ProductName** alphabetically.  

---

### **Question 9**  
Write a SQL query that uses a **CTE** and a **Window Function** (`ROW_NUMBER()` or `RANK()`) to display  
**CategoryName**, **ProductName**, and **Price** for the **top 2 most expensive products** in each category.  

---

### **Question 10 – Sakila Database Analysis**  
You are hired as a **Data Analyst** by *Sakila Video Rentals*, a global movie rental company.  
Use the Sakila database to support the management team’s decision-making process.

#### Tasks:
1. Identify the **top 5 customers** based on total amount spent. Include customer name, email, and total amount.  
2. Find the **3 movie categories** with the highest rental counts.  
3. Calculate how many films are available at each store and how many have **never been rented**.  
4. Show **total revenue per month** for 2023 to analyze seasonality.  
5. Identify customers who have **rented more than 10 times** in the last 6 months.  

---

## ⚙️ Tools & Technologies Used  
- **SQL Workbench / MySQL / PostgreSQL**  
- **Google Colab (SQL Execution via Python)**  
- **Power BI (for Data Visualization Extensions)**  
- **Excel (Data Validation & Preprocessing)**  

---

## 💡 Skills Demonstrated  
- Database Design & Schema Creation  
- SQL Query Optimization  
- Use of Constraints, Joins, and CTEs  
- Aggregations, Window Functions, and Reporting Queries  
- Business Problem Solving through Data Analysis  

---

## 🧾 Deliverables  
- `SQL_Assignment.ipynb` → Google Colab SQL Implementation     

---

⭐ *This repository demonstrates my proficiency in SQL, analytical problem-solving, and database-driven business insights.*
