# DATA-201 – Data Pipelines

This repository contains my weekly assignments for the DATA-201 Data Pipelines course.

## Week 2 – SQL Exercises

In this week, I practised basic SQL queries.

Topics covered:
- SELECT statements
- SQL JOINs
- GROUP BY and ORDER BY
- Aggregate functions like COUNT, SUM, AVG, MIN, and MAX
- HAVING clause
- Self JOIN

**Files:**
- `select_exercise.sql`
- `joins_aggregations.sql`

## Week 3 – Retail Data ELT Lab

In this assignment, I worked on a retail data pipeline using Python, Pandas, and SQLite in Google Colab.

### Tools Used
- Python
- Pandas
- SQLite
- Google Colab
- SQL

### Work Completed
1. Loaded four CSV files using Pandas.
2. Inspected the datasets and their columns.
3. Created a SQLite database.
4. Loaded customers, products, and raw orders into SQLite tables.
5. Created staging views using SQL.
6. Performed data quality checks.
7. Used SQL queries to analyse sales, products, customers, and monthly performance.
8. Compared the raw dataset with the reference dataset.

### Data Quality Findings
- The raw dataset contains 5,100 rows and 5,000 unique order IDs.
- There are 100 exact duplicate rows.
- There are 173 missing customer IDs.
- The reference dataset contains 5,000 rows with no missing values or duplicate rows.
- All 5,000 order IDs are present in both datasets.

### Week 3 Files
- `Copy_of_Retail_ELT_SQLite_Lab_Starter.ipynb` – Completed Google Colab notebook.
- `retail_lab.db` – SQLite database containing the loaded tables and staging views.

## Repository Purpose

This repository is used to store my weekly Data Pipelines assignments and practise SQL, Python, data loading, data cleaning, and data analysis.
