# Bike-Sales
A Walkthrough of Bikes Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the bike company's sales performance by demographic over the past year. Through thorough analysis of buyer data, we aim to identify trends, offer data-driven recommendations, and understand sales performance using demographic KPIs.

### Data Sources

Bike Buyers Data: The primary dataset used for this analysis is the ["Excel Data Set.xlsx"](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx) file, containing detailed information about each customer`s demographics.

### Tools

- Excel
  -  Data Cleaning
  -  Data Analysis
  - Visualization

### Data Cleaning/Preparation

In the initial data preparation phase, which includes data loading and inspection, the following tasks are carried out:
1. Removing Duplicates.
2. Handling missing values.
3. Data cleaning and formatting values.

### Exploratory Data Analysis

EDA process of this project involved exploring the data to answer critical questions, such as:

- What is the overall purchase by age group, location, and occupation?
- What is the average income of customers based on gender?
- Does owning a home have an impact on bike purchases?

### Data Analysis

Data analysis is done in Excel, and it includes the following steps;
- Getting the age bracket of customers and categorizing them into adolescent, middle and Old.
  - =IF(L2<=25,"Adolescent",IF(L2<50,"MiddleAge","old"))
- Pivot table to give insight into the processed data
### Findings

The analysis results are summarized as follows:
1. The highest purchase by demographics includes:
    -By Age group- The Middle Age group (26-50) has the bike purchase
2. Product Category A is the best-performing category in sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:
- The highest purchase by demographics includes:
    -By Age group- The Middle Age group has the 
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

### Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References
