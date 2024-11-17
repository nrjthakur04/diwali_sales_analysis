# Diwali Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Steps Taken](#steps-taken)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview

This project, titled Diwali Sales Analysis, explores customer purchasing patterns, regional trends, product performance, and seasonal sales insights using Python and Jupyter Notebook. By analyzing a dataset with over 11,251 records of Diwali sales, the project aims to uncover actionable insights that can help businesses improve customer targeting, optimize inventory, and maximize revenue during festive sales periods.
A data analysis project exploring customer purchasing behavior, regional sales trends, and product performance using Python and Jupyter Notebook. Analyzes 11,251 records to uncover actionable insights for better customer targeting, inventory optimization, and revenue maximization during festive sales.

### Steps Taken

In this project, I've created the sales report Diwali Sales across all over India. The process involved data cleaning, processing, and analysis using Python. Below are the detailed steps taken during the project.

1. Importing Libraries

Essential libraries such as pandas, numpy, matplotlib, and seaborn were imported to handle data manipulation, visualization, and statistical analysis.

2. Loading the Dataset and Reviewing Basic Details

The dataset was loaded into a Pandas DataFrame.

Basic details of the dataset were reviewed, including column names, data types, and null values, using methods like .info() and .describe().

3. Data Cleaning

Understanding Data with info()

Used the .info() method to get an overall understanding of the data, identifying columns with missing or irrelevant information.

Dropping Irrelevant Columns

The Status and Unnamed1 columns were found to be blank or irrelevant and were removed using the .drop() function.

Handling Missing Values

The Amount column contained missing values. These were filled with the column's mean value to maintain data consistency.

Changing Data Types

The Amount column's data type was changed from float to int to better align with the data requirements.

### Exploratory Data Analysis (EDA)

EDA involved exploring the sales data to answer key questions, such as:

- Customer Demographics Analysis

Q1: What is the gender distribution of customers?

Analyzed the proportion of male and female customers to understand gender-based participation.

Q2: What are the age group distributions?

Analyzed the proportion of age group to understand age-based participation.

- Purchase Behavior Analysis

Q3: What is the total amount spent by different age groups?

Identified the cumulative spending across various age groups.

Q4: What is the average amount spent by different age groups?

Calculated the mean spending of customers within each age group.

Q5: Which gender spends more?

Compared the spending patterns between male and female customers.

Q6: Identify Top 10 High-Value Customers

Found the top 10 customers based on their total spending.

- Regional Analysis

Q7: Top 10 states with the highest sales?

Ranked states based on total revenue.

Q8: Top 10 states with the highest orders?

Identified states with the largest number of orders.

Q9: How do sales vary across zones?

Analyzed sales distribution across different geographical zones (e.g., North, South, East, West).

- Product Analysis

Q10: What are the top 5 selling product categories?

Identified the most frequently purchased product categories.

Q11: Which product category generates the most revenue?

Determined which product categories contributed the most to overall sales.

Q12: What are the top 10 selling products?

Highlighted the individual products with the highest sales volume.

- Customer Engagement

Q13: How does marital status affect purchasing behavior?

Investigated whether marital status influences spending patterns or order frequency.

Q14: Which occupation has the highest sales?

Explored sales contributions by customers' occupations.

- Seasonal Trends

Q15: Are there any seasonal trends in sales based on this Diwali data?

Analyzed patterns in sales to understand seasonal spikes and variations during the Diwali festival.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "diwalisalesdata.csv" file, containing detailed information about each sale made by the user and is attached in this repo.

### Recommendations

Based on the analysis, we recommend the following actions:

- Target Marketing: Focus on high-spending age groups and genders with special campaigns. Create offers for regions with lower sales to boost performance.

- Optimize Inventory: Stock up on popular products to prevent shortages and maximize sales.

- Customer Retention: Reward loyal, high-value customers to keep them engaged and encourage repeat purchases.

- Seasonal Planning: Get ready for Diwali by analyzing past trends to ensure enough stock and smooth delivery.

- Demographic Insights: Use customer data (like age and occupation) to create ads that appeal to specific groups.
