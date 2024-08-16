# Data Cleaning Project: Data Science Job Listings

The full project [is here](https://eyowhite.com/how-to-clean-a-job-postings-dataset-using-python/).

# Project Overview
This project focuses on cleaning a dataset containing job postings for data science positions. The dataset originally contained several inconsistencies, unnecessary columns, and missing values. The goal of this project was to clean and preprocess the dataset to make it suitable for further analysis.

# Files Included
•	Uncleaned_DS_jobs.csv: The original dataset containing job postings for data science positions.
•	data_cleaning_script.py: The Python script used to clean the dataset.
•	Cleaned_DS_jobs.csv: The cleaned and processed dataset, ready for analysis.
•	Data_Cleaning_Tutorial.docx: A Word document providing a step-by-step tutorial on how the dataset was cleaned.

# Data Cleaning Process
The data cleaning process involved the following key steps:
1.	Loading the Dataset: Importing the dataset into a Pandas DataFrame for easy manipulation.
2.	Dropping Unnecessary Columns: Removing columns that were not required for analysis, such as the index and Job Description columns.
3.	Separating Embedded Data: Extracting company ratings from the Company Name column into a new Rating column.
4.	Cleaning the Salary Estimate: Removing extraneous text and splitting the salary range into Min Salary and Max Salary columns.
5.	Handling Missing Values: Replacing placeholder values in the Competitors column with None.
6.	Standardizing Formats: Ensuring consistent formatting in the Founded and Revenue columns.
7.	Saving the Cleaned Dataset: Exporting the cleaned data to a new CSV file.

# How to Use
1.	Run the Script: Use the data_cleaning_script.py file to clean a similar dataset. Ensure the dataset path is correctly specified in the script.
2.	Analyse the Data: Once cleaned, the dataset can be used for various data analysis tasks, such as salary trends, company ratings, and more.
3.	Review the Tutorial: The Data_Cleaning_Tutorial.docx file provides a comprehensive guide on the cleaning process, which can be helpful for educational purposes or for replicating the process on other datasets.

# Requirements
•	Python 3.x
•	Pandas library

