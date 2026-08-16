# Student Data Analysis Using Python

## Project Overview

This project focuses on analysing and cleaning a student dataset using Python. 
The analysis was performed using Pandas and NumPy, with Matplotlib used for 
basic data visualisation.

The project follows a practical data analysis workflow starting from importing 
a CSV dataset and understanding its structure to cleaning the data and 
performing basic exploratory analysis.

## Objectives

- Import a CSV dataset into Python
- Understand the structure and characteristics of the dataset
- Identify numerical and categorical variables
- Detect missing values
- Identify and remove duplicate records
- Handle missing data appropriately
- Perform basic statistical analysis
- Filter and sort data
- Perform grouped analysis
- Analyse correlations between numerical variables
- Create basic visualisations
- Export the cleaned dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Analysis Performed

### 1. Data Import

The student dataset was imported from a CSV file using Pandas.

### 2. Data Exploration

The dataset was examined using:

- `head()`
- `info()`
- `describe()`
- Dataset shape
- Column names
- Data types
- Unique values

### 3. Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Numerical columns
- Categorical columns

Missing numerical values were handled using the median, while missing 
categorical values were handled using the mode.

Duplicate records were removed from the dataset.

### 4. Exploratory Data Analysis

Basic analysis was performed using:

- Mean
- Median
- Minimum
- Maximum
- Standard deviation
- Filtering
- Sorting
- Grouping
- Correlation analysis

### 5. Data Visualisation

Basic visualisations were created to understand:

- Numerical data distributions
- Categorical data distributions
- Relationships between numerical variables

A correlation matrix was also generated for numerical variables.

## Project Workflow

```text
CSV Dataset
     ↓
Data Import
     ↓
Data Exploration
     ↓
Data Quality Check
     ↓
Missing Value Handling
     ↓
Duplicate Removal
     ↓
Exploratory Data Analysis
     ↓
Statistical Analysis
     ↓
Data Visualisation
     ↓
Cleaned Dataset
     ↓
Final Observations
