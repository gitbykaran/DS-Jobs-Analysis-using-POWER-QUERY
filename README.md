# ETL and EDA on Data Science Jobs Dataset

## Overview

This repository contains a Power Query script and associated resources for performing ETL (Extract, Transform, Load) and EDA (Exploratory Data Analysis) on a dataset of data science job postings. The dataset is provided in CSV format and includes various attributes related to job postings, such as job titles, companies, locations, and required skills.

The primary objectives of this project are to:

1. **Extract**: Load the raw data from the CSV file into Power Query.
2. **Transform**: Clean and preprocess the data, including handling missing values, formatting issues, and creating calculated columns.
3. **Load**: Load the transformed data into a format suitable for analysis and visualization.
4. **Analyze**: Perform exploratory data analysis to uncover insights and trends within the dataset.

## Files

- `Uncleaned DS_jobs.csv`: The raw dataset containing information about data science job postings.
- `PowerQueryScript.m`: The Power Query script used for ETL processes. This script contains the queries and transformations applied to the dataset.
- `Clean Sheet with insights.xlsx`: An Excel file with the results of exploratory data analysis, including charts and summary statistics.

## EDA Focus Areas

The EDA process covered the following aspects:

### 1. Jobs per U.S. City

- **Objective**: Determine the number of job opportunities available in each U.S. city.
- **Approach**:
  - Aggregated job postings by city to count the number of available positions.
  - Created visualizations (e.g., bar charts) to display the distribution of job postings across different cities.

### 2. Role Type Analysis

- **Objective**: Analyze the distribution of different role types within the dataset.
- **Approach**:
  - Examined the prevalence of various role types (e.g., Data Scientist, Data Analyst).
  - Generated summary statistics and visualizations to illustrate the distribution and frequency of each role type.

### 3. Company Size and Salary Analysis

- **Objective**: Compare salaries based on company size categories.
- **Approach**:
  - Categorized job postings by company size (e.g., Small, Medium, Large).
  - Calculated the minimum and maximum salaries for each company size category.
  - Created visualizations to compare salary ranges across different company sizes.

### 4. Salary Distribution Analysis

- **Objective**: Understand the typical salary range and identify any trends or anomalies.
- **Approach**:
  - Examined the overall distribution of salaries within the dataset.
  - Used histograms and box plots to visualize salary distributions and highlight any notable trends or anomalies

### Prerequisites

- [Microsoft Power Query](https://powerquery.microsoft.com/) (usually available through Excel or Power BI)
- [Excel](https://www.microsoft.com/en-us/microsoft-365/excel) or [Power BI](https://powerbi.microsoft.com/) for data visualization
- Basic understanding of ETL processes and EDA techniques

