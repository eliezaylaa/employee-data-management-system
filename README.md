# Employee Data Management System (SQL)

This project demonstrates a set of SQL queries designed to manage and analyze employee data within an organization. It focuses on extracting meaningful insights such as department statistics, salary analysis, job history tracking, and managerial hierarchies.

## 📌 Features & Queries

The project includes the following SQL operations:

1. Display department names along with the number of employees in each department  
2. Calculate the average salary of employees per department  
3. Retrieve employees earning above the average salary within their department  
4. Identify the region with the highest employee salary  
5. List employees who have changed their jobs  
6. Show countries and the count of employees who changed jobs  
7. Display monthly count of managers in each department  
8. Show managers and the number of employees reporting to them  

## 🧩 Views

Each query is implemented as a SQL view to improve reusability, abstraction, and simplification of complex queries.

## ⚙️ Concepts Covered

- SQL Aggregation (COUNT, AVG, etc.)
- GROUP BY and filtering
- Subqueries and correlated queries
- Joins and relationships
- View creation and management

## 🔍 Advanced Topics

### Updatable Views
A view is considered updatable when it avoids:
- Aggregate functions (SUM, AVG, COUNT, etc.)
- DISTINCT, GROUP BY, HAVING
- UNION / UNION ALL
- Complex joins or subqueries referencing the same table
- Non-updatable base views

### WITH CHECK OPTION
Ensures data consistency when inserting/updating through views:
- CASCADED: Enforces conditions of the view and all underlying views  
- LOCAL: Enforces only the conditions of the current view  

### View Processing Algorithms
- MERGE: Combines view query with the main query (efficient & updatable)  
- TEMPTABLE: Uses a temporary table (not updatable, less efficient)  
- UNDEFINED: Default mode (MySQL decides the best approach)  

## 🚀 Purpose

This project is ideal for learning:
- Real-world SQL query design  
- Data analysis using relational databases  
- Best practices for using views and ensuring data integrity  

---
