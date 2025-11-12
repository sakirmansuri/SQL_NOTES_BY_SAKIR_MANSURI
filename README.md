# SQL_NOTES_BY_SAKIR_MANSURI
Comprehensive SQL notes for data science/ data analysis learners — from basics to advanced joins, subqueries, and case studies. Includes syntax, commands, solved examples, and assignments for real-world database practice using MySQL.
# 🗄️ SQL Masterclass — Notes, Queries & Assignments  

**Trainer:** Sakir Mansuri | *Data Science & AI Educator*  
Master SQL from basics to real-world applications — through clear notes, solved examples, and interview-level practice queries.

---

## 🎯 Objectives
- Understand core SQL concepts — Database, Table, Keys, Constraints  
- Learn DDL, DML, DCL, and TCL Commands  
- Explore Filtering, Sorting, Aggregations  
- Master Joins, Subqueries, Views, and Indexes  
- Apply concepts on real datasets and interview questions  

---

## 🧩 Topics Covered
| Section | Topics | Level |
|----------|---------|--------|
| 1️⃣ Basics | CREATE, ALTER, DROP, Data Types, Constraints | Beginner |
| 2️⃣ Clauses | WHERE, LIKE, BETWEEN, IN, ORDER BY | Beginner |
| 3️⃣ Aggregations | COUNT, SUM, AVG, GROUP BY, HAVING | Intermediate |
| 4️⃣ Joins | INNER, LEFT, RIGHT, FULL, SELF | Intermediate |
| 5️⃣ Subqueries | Nested Queries, EXISTS, CTE | Intermediate |
| 6️⃣ Advanced | Views, Indexes, Normalization, Keys | Advanced |

---

## 💡 Example — One Solved DDL Query  

### 🧾 Task: Create a `students` table  
**Goal:** Store student details including ID, Name, and Marks.  

```sql
CREATE DATABASE my_uni;

USE my_uni;

CREATE TABLE students (
    student_id INT PRIMARY KEY AUTO_INCREMENT,
    student_name VARCHAR(50) NOT NULL,
    course VARCHAR(30),
    marks INT CHECK (marks >= 0 AND marks <= 100)
);
```
✅ Explanation:

PRIMARY KEY → ensures each student has a unique ID

AUTO_INCREMENT → automatically assigns the next ID

CHECK → validates marks are between 0–100

📚 Practice Exercise
Try it yourself 👇

Create a departments table with dept_id, dept_name, and location.
Add a UNIQUE constraint to dept_name and ensure location is not null.

Save your answer as departments_table.sql inside /Practice.

🧾 Tools Used
MySQL (primary)

Compatible with PostgreSQL / SQLite / MS SQL

📬 Connect with Me
Sakir Mansuri — Data Science & AI Trainer
📧 sakir.mansuri2103@gmail.com
🔗 LinkedIn

“Write SQL like you speak data — clear, structured, and logical.”
