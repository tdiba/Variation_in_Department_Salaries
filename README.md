# Variation_in_Department_Salaries


### Table of Contents:

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Query Breakdown](#query-breakdown)
- [SQL Functions](#sql-functions)
- [Results](#results)
- [References](#references)
  

### Project Overview

In this project, we will identify departments with salaries above and below average within each department. 


### Data Sources:

The data was in a CSV file called Employee_Salaries


### Tools

- CSV
- SQL


### Data Preparation

1. Getting Data from source
2. Data formatting
3. Importing data into SQL
4. Data Exploration


### Query Breakdown

- Calculate statistics by department
- Create and Outlier table
- Filter and sort results by variation score


### SQL Functions

- CTEs
- Case Statement
- Joins
- Aggregate Functions
- Outliers, Standard Deviation and Variation


### Results

These are the top 5 departments with discrepancies based on CV, Outliers and Standard Deviation:

1. CMD: High Cv, High Standard Deviation, Some Outliers
2. AGR: High CV, failrly high Standard Deviation, some Outliers
3. CCC: High CV, fair number of outliers
4. PWD: High number of outliers, fair CV
5. CWA: fairly high Standard Deviation, high CV, fair number of Outliers


### References

Data for the project was obtained here: [Employee Salaries](https://github.com/Gaelim/youtube/blob/master/Employee_Salaries.csv)

