SQL Layoffs Analysis :

This project analyzes global layoffs data using SQL.
The goal of this project is to clean the raw dataset and perform exploratory data analysis (EDA) to understand layoffs trends across companies, industries, countries, and time.

---

Dataset

The dataset used in this project contains information about layoffs from different companies around the world.

Dataset includes columns such as:

- Company
- Location
- Industry
- Total Laid Off
- Percentage Laid Off
- Date
- Company Stage
- Country
- Funds Raised

File used:

- "layoffs.csv"

---

Project Workflow

The project was completed in two main steps:

1. Data Cleaning

The raw dataset was cleaned using SQL to make it suitable for analysis.

Cleaning steps performed:

- Removed duplicate records
- Standardized inconsistent text values
- Converted date column into proper format
- Handled missing values
- Removed unnecessary rows

SQL file:
"01_data_cleaning.sql"

---

2. Exploratory Data Analysis (EDA)

After cleaning the data, several SQL queries were used to explore layoffs trends.

Analysis performed:

- Total layoffs by company
- Companies with the highest layoffs
- Layoffs by industry
- Layoffs by country
- Layoffs by year
- Layoffs by month
- Rolling total layoffs over time
- Top 5 companies with the highest layoffs each year

SQL file:
"02_exploratory_data_analysis.sql"

---

Key SQL Concepts Used

This project uses several important SQL concepts including:

- GROUP BY
- ORDER BY
- Aggregate functions (SUM, AVG, MIN, MAX)
- Window functions
- DENSE_RANK()
- PARTITION BY
- Rolling totals
- Common Table Expressions (CTEs)
- Data cleaning techniques

---

Project Files

SQL-Layoffs-Analysis :
layoffs.csv
01_data_cleaning.sql
02_exploratory_data_analysis.sql

---

Tools Used

- MySQL
- SQL
- GitHub
- MySQL Workbench

---

Purpose of the Project

This project was created to practice SQL for real-world data analysis tasks including:

- Data cleaning
- Data exploration
- SQL analytical queries
- Window functions
- Business insight extraction
