📌 Project: Layoffs Data Cleaning & Exploratory Data Analysis (MySQL)
🔍 Overview

This project is my first end-to-end data cleaning and exploratory analysis project using MySQL.
The goal was to clean a real layoffs dataset, remove duplicates, fix inconsistent data formats, normalize fields, and perform initial exploratory analysis to extract insights.

🧹 Data Cleaning Steps

✔ Created staging tables to preserve raw data
✔ Used ROW_NUMBER() window functions to detect duplicates
✔ Converted inconsistent date formats using STR_TO_DATE()
✔ Normalized industry and country fields
✔ Removed rows with missing key values
✔ Propagated missing industry values using company grouping
✔ Trimmed whitespace and fixed inconsistent text fields

📊 Exploratory Analysis

Performed a ranked analysis to identify:

Top companies with the highest layoffs each year

Trends of layoffs over time

Industry-level effects

Included SQL window functions such as:

ROW_NUMBER()

DENSE_RANK()

GROUP BY aggregations

🛠️ Tech Stack

MySQL 8+

SQL Window Functions

Data Cleaning & EDA Techniques

🚀 Why This Project Matters

This project shows my ability to:

Clean messy real-world datasets

Apply advanced SQL window functions

Perform exploratory analytics

Build reproducible and well-structured data workflows

