
# Bank Customer Churn Driver Analysis Dashboard

## Project Overview
This project analyzes customer churn behavior in a banking dataset to identify the key drivers influencing customer attrition.

The dashboard focuses on understanding how demographic factors, financial characteristics, engagement levels, and product usage impact churn rates.

The goal of this analysis is to uncover actionable business insights that can support customer retention strategies.

---

## Business Objective

This analysis aims to answer:

- Which customer segments have the highest churn rate?
- Does engagement reduce churn?
- Are certain products associated with higher attrition?
- Does customer balance influence churn behavior?
- Are there geographical differences in churn patterns?

---

## Dataset Description

The dataset contains 10,000 bank customers with the following key features:

- Age  
- Gender  
- Country  
- Account Balance  
- Product Ownership  
- Active Membership Status  
- Credit Card Ownership  
- Churn Status  

---

## Dashboard Features

### KPI Indicators
- Total Customers: 10,000  
- Overall Churn Rate: 20.4%  

### Analytical Visualizations (Combo Charts: Customers + Churn Rate)

1. Customers & Churn Rate by Age Group  
2. Customers & Churn Rate by Balance Group  
3. Customers & Churn Rate by Product  
4. Customers & Churn Rate by Country  
5. Customers & Churn Rate by Active Member Status  
6. Customers & Churn Rate by Gender  

### Interactive Filters
- Country  
- Product  

---

## Key Insights

### Age Is a Strong Churn Driver
- Customers aged 51–60 have the highest churn rate.
- Customers aged 41–50 have the second highest churn rate with larger volume.

### High Balance Customers Show Elevated Risk
- Customers with balance >200K have the highest churn rate despite smaller population.
- Customers in the 100K–200K range combine high volume with elevated churn.

### Product 1 Has a Significant Retention Issue
- Product 1 churn rate: 27.7%
- Product 2 churn rate: 7.6%
- Similar customer volumes, but large churn gap.

### Germany Has the Highest Churn Rate
- Germany: 32.4%
- France: 16.2%
- Spain: 16.7%

### Engagement Significantly Reduces Churn
- Active members: 14.3%
- Inactive members: 26.9%

### Gender Difference Observed
- Female: 25.1%
- Male: 16.5%

---

## Business Recommendations

1. Target customers aged 41–60 with retention programs.
2. Create loyalty strategies for high-balance customers (>100K).
3. Investigate Product 1 experience and pricing structure.
4. Conduct deeper regional analysis for Germany.
5. Increase engagement initiatives for inactive customers.

---

## Tools Used

- Power BI  
- DAX  
- Data Modeling  
- Data Cleaning & Transformation  

---

## Conclusion

This dashboard highlights high-risk customer segments by combining customer volume with churn rate analysis.

It demonstrates multi-factor churn driver investigation to support data-driven retention strategies.
