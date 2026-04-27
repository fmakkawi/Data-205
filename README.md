# Data 205 Capstone Project

**Analysis of Income, Education, Population, and Internet Access in Maryland Counties**

## Overview

This project analyzes socioeconomic differences across counties in Maryland using data from the U.S. Census Bureau (American Community Survey). The focus is on understanding how education, income, population, and internet access are related, with a comparison between Montgomery County and Prince George’s County.

## Research Question

How are education level, income, population, and internet access related across Maryland counties, and how do these factors differ between Montgomery County and Prince George’s County?

## Data Sources

The datasets used in this project come from the U.S. Census Bureau (ACS 5-Year Estimates):

* **S1901** – Median Household Income
* **S1501** – Educational Attainment
* **DP05** – Population (Demographic Data)
* **S2801** – Internet Access

All datasets were downloaded from: https://data.census.gov/

## Tools Used

* Python
* Google Colab
* pandas (data cleaning and merging)
* matplotlib (data visualization)

## Project Workflow

### 1. Data Collection

Downloaded multiple ACS datasets for all Maryland counties.

### 2. Data Cleaning

* Removed unnecessary rows
* Selected relevant columns
* Renamed variables for clarity

### 3. Data Merging

Combined all datasets into a single dataframe using county names.

### 4. Analysis

* Compared income across counties
* Analyzed relationship between education and income
* Examined internet access vs income
* Compared Montgomery County and Prince George’s County

### 5. Visualization

Created:

* Bar charts (income comparison)
* Scatter plots (education vs income, internet vs income)
* Top 10 counties by income

### 6. Statistical Analysis

* Linear regression (education vs income)
* Correlation analysis

## Key Findings

* There is a strong positive relationship between education and income.
* Counties with higher percentages of bachelor’s degrees tend to have higher median household incomes.
* Internet access is also positively associated with income.
* Montgomery County shows higher income and education levels compared to Prince George’s County.

## Conclusion

This project demonstrates that education and access to resources play an important role in income differences across Maryland counties. The analysis highlights regional disparities and provides insight into socioeconomic patterns within the state.

## Author

Farah Makkawi
Data 205 – Montgomery College
