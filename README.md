# Data-Science-Interview-Guide

The Main goal of this Readme is 
- To help you Prepare for Data Science related Interview
- Some Basic Data Science Concept who wants to learn Data Science

- SQL
- Statistics & Probability
- Mathematics
- Machine Learning Concepts
- Deep Learning Concepts
- Supervised Learning
- Unsupervised Learning
- Computer Vision
- NLP




# Data Science Question Bank

- 


# SQL

* Finding Data Queries
* Data Modification Queries
* Reporting Queries
* View Queries
* Altering Table Queries
* Creating Table Query


### Finding Data Queries 


### **SELECT** : Used to Select Data From Database
* `SELECT` * `FROM` table_name;

#### **DISTINCT**: filters away duplicate values and returns rows of specified column
* `SELECT DISTINCT` column_name;

#### **WHERE**: used to filter records/rows
* `SELECT` column1, column2 `FROM` table_name `WHERE` condition;
* `SELECT` * `FROM` table_name `WHERE` condition1 `AND` condition2;
* `SELECT` * `FROM` table_name `WHERE` condition1 `OR` condition2;
* `SELECT` * `FROM` table_name `WHERE NOT` condition;
* `SELECT` * `FROM` table_name `WHERE` condition1 `AND` (condition2 `OR` condition3);
* `SELECT` * `FROM` table_name `WHERE EXISTS` (`SELECT` column_name `FROM` table_name `WHERE` condition);
