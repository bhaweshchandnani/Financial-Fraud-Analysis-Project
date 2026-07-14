### Financial Fraud Analysis Project

-->> Project Overview
This project presents an interactive Power BI dashboard built to analyze financial transaction data and identify fraud patterns. The dashboard provides insights into transaction performance, transaction types, city-wise analysis, category trends, and fraud distribution to support business decision-making.

-->> Business Objectives
• Analyze overall transaction performance.
• Monitor monthly transaction trends.
• Compare transaction amount across cities and categories.
• Analyze transaction types usage.
• Identify fraud hotspots and fraud patterns.
• Generate data-driven business recommendations.

-->> Tech Stack
• Microsoft Excel
• Power BI
• Power Query
• DAX

-->> Data Preparation
The dataset was prepared in Microsoft Excel before importing it into Power BI.

-->> Data Cleaning
• Standardized transaction amount values and converted them to numeric format.
• Converted phone number columns to text format to preserve formatting.
• Checked for missing values and inconsistent records.
• Excluded the Country column from analysis due to inconsistent location data.
• Validated calculations using Excel Pivot Tables before building the dashboard.

-->> Dashboard Structure
* Page 1 — Executive Overview
  • KPI Cards
  • Monthly Transaction Trend
  • Transaction Amount by City
* Page 2 — Transaction Analysis
  • Transaction Amount by Category
  • Transaction Amount by Category
  • Total Transactions by City
  • Transactions by Transaction Type
* Page 3 — Fraud Risk Analysis
  • Fraud Amount by Category
  • Fraud Amount by Transaction Type
  • Fraud Amount by City
  • Fraud Transactions by Transaction Type
  • Fraud Rate by City
* Page 4 — Insights & Recommendations
  • Key Insights
  • Recommended Actions

-->> Key Insights
  • Total transaction amount reached its highest level in June.
  • March recorded the highest fraud rate.
  • Hyderabad generated the highest transaction value and recorded the highest fraud rate, while Kolkata had the highest transaction volume and the highest fraud amount.
  • Debit Card recorded the highest number of fraudulent transactions, while Credit Card accounted for the highest fraudulent transaction value.
  • Electronics generated the highest transaction amount among all categories.
  • Clothing recorded the highest fraud rate and fraud transaction count, while Education recorded the highest fraud amount.
* Additional Findings-
  • October recorded the highest fraudulent transaction amount.
  • Credit Card accounted for the highest fraud amount in 6 out of 10 cities and also recorded the highest fraudulent transaction value overall.
    • Debit Card consistently recorded the highest number of fraudulent transactions across all years (2023–2025).

-->> Business Recommendations
  • Add an extra verification step for high-value Credit Card transactions.
  • Review and update fraud detection rules before March.
  • Strengthen fraud monitoring for transactions in Hyderabad.
  • Prioritize detailed reviews for transactions in the Clothing category.
  • Review high-value transactions more closely during October.

-->> Dataset Information
Source: Kaggle
Original Records: 6,060
Final Records Used: 6,048
Domain: Financial Transactions
