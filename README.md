# Student Performance Data Analysis

## Objective
The objective of this project is to explore student performance data, clean it, and find useful information from it using Python.

## Project Overview
In this project, I used Pandas and NumPy to understand the dataset, check for missing values and duplicates, and handle incorrect or impossible values. I also calculated basic statistics and created charts to understand student performance.

## Dataset Source
The dataset was obtained from Kaggle:

**Student Performance Predictions**  
https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression

Please refer to the Kaggle dataset page for the original dataset description, licensing information, and any usage conditions.

## Tools and Libraries
- **Python** – to write and run the analysis.
- **Pandas** – to load, inspect, and clean the data.
- **NumPy** – to handle numerical values and missing data.
- **Matplotlib** – to create charts and graphs.
- **Jupyter Notebook** – to organize the code and view the results.

## Project Workflow
1. Loaded the CSV dataset using Pandas.
2. Checked the number of rows and columns and reviewed the column data types.
3. Checked for missing values and duplicate rows.
4. Cleaned the data by handling missing, incorrect, and impossible values.
5. Calculated basic statistics to understand the data.
6. Created visualizations to explore student performance and their relationship with study hours and extracurricular activities.

## Data Cleaning
I checked the dataset for missing values and duplicate rows. I converted numerical columns to numeric format and treated values that did not make sense, such as negative study hours or previous scores outside the 0–100 range, as missing values. I then filled missing values where appropriate and checked the data again.

Some checks depend on what each column means. For example, grade limits should match the grading scale used in the dataset.

## Conclusion
This project helped me practise the basic steps of data analysis: loading data, checking its quality, cleaning it, summarizing it, and presenting useful patterns with charts. The visualizations make it easier to explore student grades and how they may relate to study habits and parental support.
