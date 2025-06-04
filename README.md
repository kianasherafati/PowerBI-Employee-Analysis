# Employee Attrition & HR Analytics Dashboard 

This Power BI dashboard analyzes a dataset related to employee information, focusing on **attrition, salary distribution, hiring trends**, and other **HR metrics**.

## Dataset Description

The dataset contains employee-level information, including:

- `ID Unique`*: Unique employee identifier  
- `Education`: Education level (e.g., Bachelor, Master)  
- `Year Joining`: Year the employee joined  
- `City`: Work location  
- `Tier Payment`: Salary tier (1 = High, 2 = Medium, 3 = Low)  
- `Age`, `Gender`  
- `Domain Current in Experience`: Experience in the current domain (in years)  
- `LeaveOrNot`: Attrition (1 = Left, 0 = Still employed)  
- `Group_Age`*: Age category  
- `Department`: e.g., IT, Sales, HR  
- `Salary`: Annual salary

\* Starred columns were created during data cleaning & preprocessing.

## Project Objectives

- Understand **employee distribution** across cities, departments, education levels, age groups, and genders  
- Identify **attrition rates** across departments and demographic groups  
- Analyze **salary distributions** by city, gender, experience, and department  
- Visualize **hiring trends** by year and location  
- Provide **insights** to improve HR strategies

## Key Dashboard Metrics (KPIs)

- 🔹 Total Employees  
- 🔹 Employees Left  
- 🔹 Average Salary  
- 🔹 Gender Distribution  
- 🔹 Hiring Trends (by year & city)  
- 🔹 Attrition Rate (compared to 15% target)  
- 🔹 Salary vs. Experience  
- 🔹 Salary by Department  
- 🔹 Attrition by Age Group  
- 🔹 Employee Distribution by City

## Sample Insights

- **Total Employees**: 4653 — of which **1600 left** (~34% attrition rate)
- **Gender Split**: 59.7% Male, 40.3% Female
- **Highest Avg. Salary**: IT department (~$97K)
- **Lowest Avg. Salary**: Sales department (~$47K)
- **Highest Hiring City**: Bangalore (~2200 employees)
- **Most vulnerable group**: Age 18–25 has highest attrition rate
- **Attrition rate** is **significantly higher** than the 15% goal, especially in HR and younger age groups

## Tools Used

- **Power BI** for interactive data visualization
- **Python (optional preprocessing)** for data cleaning and transformation

## Files

- `Dashboard.pbix`: Power BI dashboard file  
- `Dataset.csv`: Cleaned employee dataset  
- `Notebook.ipynb`: Data preprocessing steps

> Designed to support **data-driven HR decisions** and improve **organizational performance**.
