# Atliq Mart Promotional Campaign Analysis-Codebasics Resume Challenge 9
## Overview

This project focuses on analyzing the sales data from AtliQ Mart's Diwali 2023 and Sankranti 2024 sales events. The goal is to generate actionable insights that can be presented to the sales director, Bruce Haryali.

## Project Structure

- **Data Files:**
  - `dim_campaigns.csv`: Contains information about the marketing campaigns.
  - `dim_products.csv`: Contains details about the products sold.
  - `dim_stores.csv`: Contains data on store locations.
  - `fact_events.csv`: Holds transactional data related to the sales events.

- **Documents:**
  - `Recommended Insights.pdf`: Recommendations from the manager, Tony, to guide the analysis.
  - `ad-hoc-requests.pdf`: Contains business questions posed by senior executives that require SQL-based report generation.

- **Output:**
  - **Dashboard**: A Power BI dashboard that visualizes key metrics and insights from the analysis.

## Steps to Reproduce

1. **Data Import:**
   - Load the CSV files (`dim_campaigns.csv`, `dim_products.csv`, `dim_stores.csv`, and `fact_events.csv`) into a SQL database and directly into Power BI.

2. **Data Cleaning and Preparation:**
   - Perform necessary data cleaning to ensure data quality.
   - Join the tables based on common keys to prepare a unified dataset for analysis.

3. **SQL Queries:**
   - Refer to `ad-hoc-requests.pdf` for the SQL queries required to answer specific business questions.
   - Execute the queries in your SQL environment to generate the necessary reports.

4. **Dashboard Design:**
   - Design a Power BI dashboard incorporating the metrics and insights generated from the SQL queries and analysis.
   - Ensure the dashboard is self-explanatory, with clear labels, legends, and descriptions.


## Summary

1. **Diwali vs. Sankranti Campaigns:**
   - **Diwali Campaign:** The most successful, with a revenue increase of 94%, from Rs. 82.57M to Rs. 160.29M.
   - **Sankranti Campaign:** Achieved a 50.86% revenue increase, from Rs. 58.13M to Rs. 87.70M.

2. **Category Performance:**
   - **Home Appliances:** Had the highest ISU (Item Sold Units).
   - **Post-Offer Revenue:** Combo 1 and Grocery & Staples generated the most revenue after the offers, highlighting the strong impact of promotions.

3. **City Performance:**
   - **Top Contributors:** Bengaluru, Chennai, Hyderabad, Mysuru, and Coimbatore together contributed 70–75% of the total revenue.
   - **Growth Potential:** Vijayawada and Trivandrum, each with only 2 stores, saw revenue increase by 1.5x and 2x respectively, indicating potential for further expansion.

4. **Promotion Effectiveness:**
   - **BOGOF (Buy One Get One Free) and Cashback:** More popular compared to discounts.
   - **Best Promotion:** Cashback offers provided the best balance between sales growth and healthy margins.

