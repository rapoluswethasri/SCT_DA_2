Task 02: Data Cleaning and Preparation
Overview

This project focuses on cleaning and preparing a dataset using Python and Pandas. The objective is to identify and handle missing values, remove duplicate records, convert data types, and export the cleaned dataset for further analysis.

Dataset

Dataset Used: Titanic Dataset

Objectives
Load the dataset into a Python environment.
Identify and handle missing values.
Remove duplicate rows.
Convert data types where necessary.
Export the cleaned data to a new CSV file.
Tools and Technologies
Python
Pandas
Google Colab
Data Cleaning Steps
1. Loading the Dataset

The dataset was loaded using the Pandas library.

2. Handling Missing Values
Missing values in the Age column were filled using the median value.
Missing values in the Embarked column were filled using the mode value.
Missing values in the Cabin column were replaced with "Unknown".
3. Removing Duplicate Records
Checked for duplicate rows.
Removed duplicate entries to improve data quality.
4. Data Type Conversion
Converted the PassengerId column from integer to string format.
5. Exporting Cleaned Data
Saved the cleaned dataset as Titanic_Cleaned.csv.
Files Included
Titanic.csv – Original dataset
Titanic_Cleaned.csv – Cleaned dataset
Task_02_Data_Cleaning.ipynb – Google Colab notebook
README.md – Project documentation
Learning Outcomes
Data preprocessing using Pandas
Missing value treatment
Duplicate data removal
Data type conversion
Exporting cleaned datasets
Author

Rapolu Swethasri

Internship

Data Analyst Internship – SkillCraft Technology
