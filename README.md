# SQL Layoffs Dataset Analysis

## Project Overview

This project demonstrates data cleaning and exploratory analysis using SQL on a dataset containing global company layoffs information.

The objective of the project is to transform raw data into a structured dataset and extract insights regarding layoffs trends across companies, industries, and time periods.

## Tools Used

* MySQL
* SQL Window Functions
* Aggregation Functions
* Date Functions

## Data Cleaning

The dataset required preprocessing before analysis. The following steps were performed:

* Created staging tables for safe data transformation
* Identified and removed duplicate records using SQL window functions
* Standardized categorical fields such as company names and industries
* Converted text-based dates into SQL date format
* Handled missing values and removed incomplete records

## Data Analysis

Exploratory queries were written to analyze workforce reduction patterns across different dimensions.

### Analysis Performed

* Total layoffs by company
* Industry-wise layoffs analysis
* Yearly layoffs trends
* Monthly layoffs trends
* Companies with complete workforce layoffs

### SQL Techniques Used

* GROUP BY
* Aggregation functions (SUM, MAX)
* Date functions
* Filtering conditions

## Key Learnings

* Building SQL data cleaning workflows
* Using window functions to detect duplicates
* Handling inconsistent data formats
* Performing exploratory data analysis using SQL
