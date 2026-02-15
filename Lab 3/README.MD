Lab 3: Exploratory Data Analysis (EDA)
Introduction

In this lab, I performed Exploratory Data Analysis (EDA) on a chocolate sales dataset.
The goal was to understand the structure of the data, detect patterns, and analyze relationships between variables before building any machine learning model.

Dataset Information

The dataset contains 300 rows of sales data and includes the following columns:

Date

Country

Product

Sales Person

Boxes Shipped

Amount

The dataset was provided as an Excel file.

Steps I Performed
1. Data Understanding

Loaded the dataset using pandas

Checked the number of rows and columns

Examined data types

Converted the Date column to datetime format

2. Data Cleaning

Checked for missing values (none found)

Checked for duplicate rows

Verified numeric columns are correctly formatted

3. Descriptive Statistics

Used describe() to view summary statistics

Observed average shipment size and revenue range

4. Univariate Analysis

Plotted histogram for Boxes Shipped

Plotted histogram for Amount

From the distribution, I noticed that revenue has a right skew, meaning there are a few high sales values.

5. Bivariate Analysis

Calculated total revenue by country

Calculated revenue by product

Created scatter plot between Boxes Shipped and Amount

Generated correlation matrix

I observed a strong positive relationship between Boxes Shipped and Amount, which is expected since revenue increases when more boxes are sold.

6. Time-Based Analysis

Extracted month from the Date column

Calculated total revenue per month

Plotted monthly revenue trend

The monthly revenue fluctuates across the year, showing variation in sales performance.

Conclusion

This EDA helped me understand the dataset and identify important patterns.
The data appears clean and suitable for future machine learning tasks such as sales prediction.