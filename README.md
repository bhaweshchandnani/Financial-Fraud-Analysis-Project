### Financial Fraud Analysis Project

-->> Project Overview
Financial fraud is a major challenge for businesses, as identifying suspicious transactions while minimizing unnecessary friction for genuine customers requires a better understanding of transaction patterns and risk indicators.

This project analyzes financial transaction data to identify fraud patterns, examine risk across payment methods and cities, and understand how transaction amounts relate to fraudulent activity.

Using Excel, Power Query, DAX, and Power BI, I cleaned and analyzed transaction data and developed an interactive dashboard to convert raw transaction records into actionable business insights.

-->> Business Objectives

• Understand the overall distribution of fraudulent and non-fraudulent transactions.

• Analyze monthly transaction amounts and fraud-related amounts.

• Identify categories, payment methods, and cities with higher fraud activity.

• Examine fraud patterns across transaction amount ranges and days of the week.

• Evaluate whether high-value transactions are necessarily associated with fraud.

• Develop data-backed recommendations to improve transaction monitoring and fraud prevention.


-->> Tech Stack

• Excel

Initial data inspection, data cleaning and analysis

• Power Query

Data transformation

• Power BI

Interactive dashboard development

• DAX

KPI calculations and analytical measures


-->> Data Preparation

The dataset was prepared in Microsoft Excel before importing it into Power BI.


-->> Data Cleaning

• Standardized transaction amount values and converted them to numeric format.

• Converted phone number columns to text format to preserve formatting.

• Checked for missing values and inconsistent records.

• Excluded the Country and currency column from analysis due to inconsistent location data.

• Validated calculations using Excel Pivot Tables before building the dashboard.


-->> Dashboard Structure

Page 1 — Executive Overview

Objective: Understand the overall transaction and fraud situation.

Key metrics and visualizations:

• Total Transactions

• Fraud Transactions

• Fraud Rate

• Unknown Transactions

Fraud Status Distribution

• Total Transaction Amount by Month

• Fraud Amount by Month

Page 2 – Fraud Risk Analysis

Objective: Identify where fraud activity is concentrated.

Key analysis:

• Fraud Transactions by Category

• Fraud Rate by Payment Method

• Fraud Rate by City

• Fraud Transactions by City

Page 3 – Transaction Behaviour

Objective: Examine transaction-level patterns associated with fraudulent activity.

Key analysis:

• Fraud Transactions by Amount Range

• Fraud Transactions by Day of the Week

• Top 10 Highest-Value Transactions

• Fraud Amount by Amount Range

Page 4 – Insights & Recommendations

Objective: Translate analytical findings into practical business recommendations.

This page summarizes the key findings and proposed actions for improving transaction monitoring and reducing unnecessary verification friction.

Key Insights

1. Fraud is relatively rare

Fraudulent transactions account for approximately 1% of all transactions with known fraud labels.

2. Payment methods show different fraud patterns

Debit cards have the highest number of fraud cases, whereas credit cards have the highest fraud rate.

This highlights the importance of analyzing both fraud count and fraud rate rather than relying on transaction volume alone.

3. Most fraud cases occur in the low-value range

56 out of 63 fraud cases fall within the low-value transaction range. However, approximately 4,874 transactions also fall into this range, and its fraud rate is close to the overall fraud rate.

Therefore, the higher fraud count is largely associated with the higher volume of low-value transactions.

4. High transaction value does not automatically indicate fraud

9 out of the 10 highest-value transactions were genuine.

This suggests that transaction amount alone is not a reliable indicator for identifying fraudulent activity.

Business Recommendations

Based on the observed patterns, the following actions are recommended:

1. Risk-based verification for high-value credit card transactions

Introduce an additional verification step for unusually high-value credit card transactions instead of applying extra checks to every transaction.

2. Context-based checks for debit card transactions

Strengthen monitoring when multiple risk indicators occur together, such as unusual transaction type combined with an unusual amount.

3. Monitor fraud rate alongside fraud count

Evaluate both metrics when identifying high-risk payment methods, categories, and cities, as fraud counts can largely reflect differences in transaction volume.

4. Use multiple fraud indicators

Combine transaction amount with other risk signals instead of relying on amount alone. This can help minimize unnecessary friction for genuine high-value transactions.

These are analytical recommendations based on observed dataset patterns, not tested or proven fraud-prevention interventions.


-->> Dataset Information Source:

Kaggle Original Records: 6,060

Final Records Used: 6,048

Domain: Financial Transactions
