# Diwali Sales Data Analysis

This repository contains an analysis of the Diwali Sales Data, focusing on customer demographics, purchasing patterns, and product sales. The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to understand the trends and insights.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Cleaning](#data-cleaning)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Key Findings](#key-findings)
5. [Dependencies](#dependencies)
6. [Usage](#usage)
7. [Conclusion](#conclusion)

## Introduction

The dataset contains transaction details for various products sold during the Diwali season. The data includes customer demographics, product details, and sales figures. This analysis aims to identify key trends and insights, such as the most popular products, customer demographics, and purchasing behaviors.

## Data Cleaning

Several data cleaning steps were undertaken to ensure the dataset's integrity:
1. **Removal of Unrelated/Blank Columns**: The columns 'Status' and 'unnamed1' were dropped as they contained no useful information.
2. **Handling Missing Values**: Rows with missing values in the 'Amount' column were removed.
3. **Data Type Conversion**: The 'Amount' column was converted from float to integer for consistency.
4. **Column Renaming**: The 'Marital_Status' column was renamed to 'Shaadi' for better readability.

## Exploratory Data Analysis (EDA)

The EDA section covers various aspects, including:
1. **Gender Distribution**: Analysis of the distribution of buyers by gender and their respective purchasing amounts.
2. **Age Group Analysis**: Distribution and purchasing patterns across different age groups.
3. **State-wise Analysis**: Top states by the number of orders and total sales.
4. **Marital Status**: Examination of purchasing behavior based on marital status.
5. **Occupation Analysis**: Insights into purchasing behavior across different occupations.
6. **Product Category Analysis**: Identification of the most popular product categories.

### Key Visualizations

1. **Bar Charts**: Used to display the count and amount of purchases based on various demographics.
2. **Grouped Bar Charts**: Show purchasing patterns based on multiple factors, such as gender and marital status.

## Key Findings

- **Gender**: Most buyers are female, and they also exhibit higher purchasing power compared to males.
- **Age Group**: The 26-35 age group, particularly women, are the most frequent buyers.
- **State**: Uttar Pradesh, Maharashtra, and Karnataka are the top states in terms of orders and sales.
- **Marital Status**: Married individuals, especially women, tend to have higher purchasing power.
- **Occupation**: The IT, Healthcare, and Aviation sectors have the highest number of buyers.
- **Product Category**: Food, Clothing, and Electronics are the top-selling product categories.

## Dependencies

The analysis was performed using the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

## Conclusion

The analysis provides valuable insights into customer behavior during the Diwali season. It highlights the importance of targeting specific demographics, such as married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, particularly those working in IT, Healthcare, and Aviation sectors, with products in the Food, Clothing, and Electronics categories.

---

Feel free to customize this README file further to suit your specific needs!
