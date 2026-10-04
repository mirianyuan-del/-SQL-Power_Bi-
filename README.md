# Customer Shopping Trends Analysis

SQL · Python · Power BI

## Overview

This project analyzes 3,900 customer purchase records to understand customer segments, purchasing behavior, product performance, promotion usage, and subscription conversion.

The analysis combines Python for data preparation, SQL for business questions, and Power BI for dashboard visualization.

## Business Questions

- Which customer segments contribute the most revenue?
- How are discounts and shipping methods related to purchase amount?
- Which products have the highest ratings and sales volume?
- What is the structure of new, returning, and loyal customers?
- Are repeat customers more likely to subscribe?

## Workflow

1. Cleaned missing values and standardized column names with Python.
2. Created `age_group` and `purchase_frequency_days` features.
3. Used SQL to answer 10 business questions.
4. Built a Power BI dashboard to present the findings.
5. Translated the results into marketing and customer-retention recommendations.

## Key Findings

- The dataset contains 3,900 customer purchase records.
- In this sample, male customers contributed approximately `$157,890`, compared with `$75,191` from female customers.
- Loyal customers accounted for approximately 80% of the customer base, while new customers accounted for approximately 2%.
- Subscribers represented approximately 27% of customers, and their average purchase amount was similar to that of non-subscribers.
- Among repeat customers, only approximately 27.6% were subscribers, suggesting room to improve subscription conversion.
- Gloves, Sandals, Boots, Hat, and T-shirt received the highest average ratings.

## Project Files

- [SQL analysis](./Data%20Analysis_SQL.sql)
- [Python notebook](./Shopping%20Trend.ipynb)
- [Power BI dashboard](./Shopping%20Trend.pbix)
- Analysis report: see the report file in this repository.

## Tools

- Python
- Pandas
- SQL
- Power BI
- Jupyter Notebook

## Dashboard Preview

<img width="605" height="338" alt="Shopping Trend" src="https://github.com/user-attachments/assets/1fe286e5-e0a6-4431-89e3-5ee02ea5cbe5" />


## Limitations

This is an exploratory analysis based on a portfolio dataset. The results describe relationships in the sample and should not be interpreted as causal conclusions.
