📊 Employee & Project Data Analysis

Uncovering workforce and project performance insights through structured data analysis in Python.

📝 Purpose

This project focuses on analyzing employee and project datasets to identify patterns, resolve missing values, and generate actionable insights. By applying Python-based data analysis techniques, it demonstrates how raw organizational data can be transformed into meaningful business intelligence.

🛠 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy

Data Handling: CSV Files

IDE/Environment: Jupyter Notebook / VS Code

📂 Data Source

Employee data (employees.csv)

Project data (projects.csv)

Note: Data has been prepared for educational purposes and simulates real-world organizational structures.

✨ Highlights

🔹 Business Problem
Organizations often struggle with consolidating employee and project data to understand performance, optimize workload, and make data-driven HR decisions. Disparate datasets make it difficult to measure productivity, project allocation, and workforce utilization.

🔹 Goal of the Dashboard / Analysis
The goal is to clean, merge, and analyze employee and project data to:

Provide a clear view of employee distribution and project allocations
Identify missing or inconsistent records and handle them systematically
Generate insights on employee performance, workload balance, and project efficiency

🔹 Walkthrough of the Analysis
Data Import & Exploration
Loaded multiple CSV files into Pandas DataFrames.
Checked for missing values, duplicates, and inconsistencies.
Data Cleaning & Imputation
Handled missing values using conditional imputation strategies.
Standardized formats for employee IDs, department codes, and project assignments.
Merging Datasets
Combined employee data with project assignments.
Ensured relational integrity between employees and projects.
Conditional Logic & Filtering
Identified employees working on multiple projects simultaneously.
Flagged underutilized or overutilized employees.
Segmented employees by department and project role.
Aggregation & Analysis
Calculated average project duration and employee workload.
Determined which departments contribute most to active projects.
Measured employee engagement rate across projects.

🔍 Key Insights

Certain departments were overloaded, while others had idle employees.
Project delays correlated with higher employee allocation mismatches.
Around 10–15% of employee records contained missing values, which were systematically resolved.
Employees working across multiple projects showed higher stress indicators, suggesting potential burnout risks.

Projects handled by cross-functional teams exhibited better completion rates.
