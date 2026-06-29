# 📚 MySQL Normalization Mini Project

A practical MySQL project demonstrating **Database Normalization** up to **Third Normal Form (3NF)** using SQL. This project shows how to eliminate redundancy, improve data integrity, and organize relational databases following normalization principles.

---

## 📌 Project Objective

The objective of this project is to transform an unnormalized dataset into:

- ✅ First Normal Form (1NF)
- ✅ Second Normal Form (2NF)
- ✅ Third Normal Form (3NF)

by creating well-structured relational tables using MySQL.

---

## 🛠️ Technologies Used

- MySQL Server 8.0
- MySQL Workbench
- SQL (DDL & DML)

---

## 📂 Project Structure


Normalization-Mini-Project/
│
├── 📄 README.md
├── 📄 Normalization_Project.sql
│
└── 📁 screenshots
    │
    ├── 📁 1NF
    │   ├── create_table_member_hobbies.jpeg
    │   ├── insert_table_member_hobbies.jpeg
    │   └── output.png
    │
    ├── 📁 2 NF
    │   ├── create_table_employee.jpeg
    │   ├── create_table_employee_training.jpeg
    │   ├── insert_table_employee.jpeg
    │   ├── insert_table_employee_training.jpeg
    │   ├── 2NF(1).png.png
    │   └── 2NF(2).png.png
    │
    └── 📁 3 NF
        ├── create_table_member.jpeg
        ├── create_table_sports.jpeg
        ├── insert_table_member.jpeg
        ├── insert_table_sports.jpeg
        ├── 3NF(1).png.png
        └── 3NF(2).png.png
```
## 🏗️ Project Workflow

```
Input Data
     │
     ▼
Create Database
     │
     ▼
Create Tables
     │
     ▼
Insert Records
     │
     ▼
Apply 1NF
     │
     ▼
Apply 2NF
     │
     ▼
Apply 3NF
     │
     ▼
Execute SQL Queries
     │
     ▼
View Results in MySQL Workbench
```
---

## 📖 Database Normalization

### 🔹 First Normal Form (1NF)
- Removed repeating groups.
- Stored one value in each cell.
- Created the **Member_Hobbies** table.

### 🔹 Second Normal Form (2NF)
- Removed partial dependencies.
- Split data into separate tables.
- Created:
  - Employee
  - Employee_Training

### 🔹 Third Normal Form (3NF)
- Removed transitive dependencies.
- Created separate tables:
  - Member
  - Sports
- Linked data using relational design.

---

## 💻 SQL Operations Performed

- CREATE DATABASE
- USE DATABASE
- CREATE TABLE
- INSERT INTO
- SELECT
- PRIMARY KEY
- Normalization (1NF, 2NF, 3NF)

---

## 📸 Screenshots

The repository includes screenshots showing:

- SQL Queries
- Table Creation
- Data Insertion
- Query Execution
- Final Outputs

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Database Design
- SQL Programming
- Data Normalization
- MySQL Workbench
- Relational Database Concepts

---

## 🚀 How to Run

1. Install **MySQL Server** and **MySQL Workbench**.
2. Open **Normalization_Project.sql**.
3. Execute the SQL script.
4. Verify the output using the provided SELECT queries.

---

## 📌 Repository Features

✔ Clean SQL Scripts  
✔ Well-Structured Database Design  
✔ Practical Normalization Example  
✔ Easy to Understand  
✔ Beginner Friendly

---

## 👩‍💻 Author

**Ishita Pandey**

B.Tech (Artificial Intelligence & Data Science)

Passionate about Software Development, Databases, and AI.

---

⭐ If you found this project helpful, consider giving it a Star!
