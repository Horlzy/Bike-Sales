# Bike-Sales
A Walkthrough of Bikes Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the bike company's sales performance by demographic over the past year. Through thorough analysis of buyer data, we aim to identify trends, offer data-driven recommendations, and understand sales performance using demographic KPIs.
![dashboard](https://github.com/Horlzy/Bike-Sales/assets/74312225/9571b844-7fa5-4604-8e43-6bfbc295ea85)


### Data Sources

Bike Buyers Data: The primary dataset used for this analysis is the ["Excel Data Set.xlsx"](https://github.com/Horlzy/Bike-Sales/blob/main/Excel%20Project%20Dataset.xlsx) file, containing detailed information about each customer`s demographics.

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
1. The Middle Age group (26-50), North Americans and professionals have the highest bike purchase, respectively, 
2. The Male gender has the highest average income
3. House ownership has no significant impact on bike sales. 

### Recommendations

Based on the analysis, it is recommended that the following actions should be taken:
- Target marketing efforts towards the middle-aged demographic (26-50 age group), North American regions, and professional occupations, as they exhibit the highest bike purchase propensity.
- Focus marketing and product development strategies towards the male demographic, considering their higher average income and potential purchasing power.
- Recognise that house ownership does not significantly influence bike sales, suggesting that marketing efforts should not heavily rely on this demographic variable.


