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

We found that 69.7% of the customers are female, and 30.3% are male.

Q2: What are the age group distributions?

Analyzed the proportion of age group to understand age-based participation.

The majority of Diwali sales customers are in the 26-35 age group (39.2%), followed by 36-45 (19.2%) and 18-25 (16.6%).

- Purchase Behavior Analysis

Q3: What is the total amount spent by different age groups?

Identified the cumulative spending across various age groups.

The highest total spending during Diwali sales comes from the 26-35 age group, with ₹42,632,348, followed by 36-45 age group with ₹22,173,353.

Q4: What is the average amount spent by different age groups?

Calculated the mean spending of customers within each age group.

On average, the 51-55 age group spent the most per customer, with ₹9,952.38, followed by the 36-45 group at ₹9,699.63.

Q5: Which gender spends more?

Compared the spending patterns between male and female customers.

Female customers spent more during Diwali sales, with a total of ₹74,430,383 compared to ₹31,932,182 spent by male customers.

Q6: Identify Top 10 High-Value Customers

Found the top 10 customers based on their total spending.

The top 10 high-value customers by spending are identified by their User_IDs, with the highest spender being User_ID 1001680, who spent ₹281,034.

- Regional Analysis

Q7: Top 10 states with the highest sales?

Ranked states based on total revenue.

The top 10 states with the highest Diwali sales are Uttar Pradesh (₹19,393,874), Maharashtra (₹14,436,996), and Karnataka (₹13,532,993).

Q8: Top 10 states with the highest orders?

Identified states with the largest number of orders.

The top 10 states with the highest number of Diwali orders are Uttar Pradesh (4,813), Maharashtra (3,811), and Karnataka (3,241).

Q9: How do sales vary across zones?

Analyzed sales distribution across different geographical zones (e.g., North, South, East, West).

Sales during Diwali are highest in the Central zone with ₹41,667,043, followed by the Southern zone with ₹26,625,573.

- Product Analysis

Q10: What are the top 5 selling product categories?

Identified the most frequently purchased product categories.

The top 5 selling product categories during Diwali are Clothing & Apparel (2,655), Food (2,493), and Electronics & Gadgets (2,087).

Q11: Which product category generates the most revenue?

Determined which product categories contributed the most to overall sales.

From above graph we can see that food, clothing & Apparel and electronics footwear&Shoes and Furniture category generates the most revenue.

Q12: What are the top 10 selling products?

Highlighted the individual products with the highest sales volume.

The top 10 selling products during Diwali are led by Product_ID P00265242 with 127 orders, followed by P00110942 with 116 orders.

- Customer Engagement

Q13: How does marital status affect purchasing behavior?

Investigated whether marital status influences spending patterns or order frequency.

Married customers (Marital Status 0) have a slightly higher average spending of ₹9,531.31 compared to unmarried customers (₹9,346.45).

Q14: Which occupation has the highest sales?

Explored sales contributions by customers' occupations.

The IT sector generates the highest sales during Diwali, with ₹14,802,344 in revenue.

- Seasonal Trends

Q15: Are there any seasonal trends in sales based on this Diwali data?

Analyzed patterns in sales to understand seasonal spikes and variations during the Diwali festival.

Zones such as Central and Northern have the highest sales.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "diwalisalesdata.csv" file, containing detailed information about each sale made by the user and is attached in this repo.

### Recommendations

Based on the analysis, we recommend the following actions:

- Target Female Consumers: Women contribute more to sales. Tailor marketing campaigns and promotions to appeal to female shoppers, especially for Clothing & Apparel and Food.

- Focus on High-Spending Age Groups: Age groups 26-35 and 36-45 are top spenders. Target these segments with premium offers and loyalty programs.

- Customer Retention: Retain top spenders with rewards, personalized deals, early access, and exclusive offers. to keep them engaged and encourage repeat purchases.

- Gender-Specific Strategies: Women (F) outspend men (M). Offer exclusive promotions for female customers, particularly in top-selling categories like Clothing & Apparel.

- Demographic Insights: Prioritize High-Performing States like Uttar Pradesh, Maharashtra, and Karnataka where sales are highest by creating ads that appeal to specific groups.

- Optimize Product Categories: Focus on high-revenue categories (Food, Clothing & Apparel, Electronics) and create bundles to increase average order value.

- Boost Sales in Low-Performing States: Run targeted campaigns in regions like Rajasthan and Punjab to increase engagement during Diwali.

- Leverage Zone Data: Central and Northern zones perform best. Allocate resources to high-performing zones and explore opportunities in underperforming zones like Eastern.

- Maximize Top Categories: Focus on Food, Clothing & Apparel, and Electronics for future campaigns to capitalize on high revenue-generating categories.

- Leverage Marital Status: Personalize offers for married and single customers based on purchasing behavior differences.


