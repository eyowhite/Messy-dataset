# Warehouse Inventory Data Cleaning

Find the [project here](https://eyowhite.com/how-to-clean-a-messy-warehouse-data-using-python-a-step-by-step-tutorial/).

# Overview
This project focuses on cleaning and analysing a warehouse inventory dataset using Python. The dataset originally contained several issues, such as inconsistent formatting, missing values, and incorrect data types. The goal of this project is to transform the messy dataset into a clean and analysable form and then conduct a rigorous analysis to derive valuable insights.

# Project Structure
•	cleaned_warehouse_messy_data.csv: The cleaned version of the warehouse inventory dataset.
•	cleaning_script.py: Python script used for cleaning the messy dataset, which includes steps like stripping spaces, standardising text formats, correcting data types, and handling missing values.
•	analysis_script.py: Python script for conducting exploratory data analysis (EDA) and detailed analysis on the cleaned dataset. It includes visualisations and insights derived from the data.
•	README.md: This file, providing an overview and instructions for the project.

# Requirements
•	Python 3.x
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn

# Project Workflow

## 1.	Data Cleaning: 
      The cleaning_script.py processes the raw, messy dataset by performing operations such as:
o	Stripping leading and trailing spaces from string columns.
o	Standardizing text formats for consistency.
o	Correcting data types and handling missing values.
o	Saving the cleaned data to a new CSV file.

## 2.	Exploratory Data Analysis (EDA): 
      The analysis_script.py performs an initial EDA to understand the structure of the cleaned dataset. This includes:
o	Summarising data.
o	Visualising distributions of key variables.
o	Checking correlations between numeric variables.
o	Analysing categorical data distributions.

## 3.	Detailed Analysis: 
      The script then proceeds to a more rigorous analysis, including:
o	Correlation analysis.
o	Time-series analysis of restocking data.
o	Drawing insights and conclusions from the dataset.

# Results
•	The analysis provided insights into inventory levels, restocking patterns, and potential relationships between different variables such as price, quantity, and category. These insights can help optimise warehouse management and improve operational efficiency.

# Conclusion
This project demonstrates the importance of data cleaning in ensuring reliable analysis results. By following the outlined steps, you can transform a messy dataset into a valuable resource for decision-making.

