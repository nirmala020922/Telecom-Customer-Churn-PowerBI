Telecom Customer Churn Analysis Dashboard
📊 Project Overview

This project analyzes customer churn for a telecommunications company using Power BI. The dashboard identifies key churn drivers, high-risk customer segments, contract patterns, customer value segments, tenure trends, and service-level churn patterns.

The goal is to convert customer data into actionable business insights that can support customer retention and churn reduction strategies.

🎯 Business Objectives

Analyze overall customer churn performance.
Identify customer segments with high churn risk.
Understand the impact of contract type on churn.
Analyze churn by customer value and tenure.
Identify internet-service segments contributing to churn.
Provide actionable insights for customer retention.
Build an interactive dashboard for business decision-making.

🛠️ Tools & Technologies
Power BI
DAX
Power Query
Microsoft Excel
Data Cleaning & Transformation
Data Visualization
KPI Analysis
Business Intelligence

📂 Dataset

The project uses the Telco Customer Churn dataset, containing customer demographics, services, contract information, tenure, monthly charges, payment methods, and churn status.

Key fields analyzed
Customer ID
Gender
Senior Citizen
Partner
Dependents
Tenure
Contract
Internet Service
Payment Method
Monthly Charges
Total Charges
Churn

📑 Dashboard Pages

1. Executive Summary

Provides a high-level overview of customer churn performance.

Key KPIs:
Total Customers: 7,043
Churned Customers: 1,869
Churn Rate: 26.54%
Month-to-Month Churned: 1,655
High Charge Churned: 1,267
High Value + Month-to-Month Churned: 1,105

Key visualizations include:
Churned Customers by Contract
Churn Rate by Customer Value
Churned Customers by Tenure
Churned Customers by Risk Segment
Churn Rate by Risk Segment
Churned Customers by Internet Service

2. Customer Details

Provides customer-level analysis with interactive filters.

Filters
Contract
Churn Status
Tenure Group
Customer Value
Internet Service
Customer-level information
Customer ID
Contract
Tenure Group
Monthly Charges
Internet Service
Customer Value
Risk Segment

3. Churn Insights

Focuses on identifying major churn drivers and customer segments requiring attention.

Key analysis includes:

Risk Segment Churn Rate
Churned Customers by Customer Value
Churned Customers by Contract
Short-Tenure Churn by Customer Value
Month-to-Month Short-Tenure Churn

📸 Screenshots
Executive Summary

Customer Details

Churn Insights

🔍 Key Business Insights
1. Month-to-Month Contracts Have the Highest Churn

Month-to-month customers account for 1,655 churned customers, making this the largest contract-based churn segment.

2. High-Risk Customers Have the Highest Churn Rate

The high-risk segment has a churn rate of approximately 69%, indicating a strong concentration of churn within this segment.

3. High-Value Customers Show Higher Churn

High-value customers have a churn rate of approximately 35.36%, compared with:

Medium Value: 23.94%
Low Value: 10.86%
4. Short-Tenure Customers Are a Major Churn Segment

Customers with tenure of 0–12 months account for 1,037 churned customers.

5. Fiber Optic Customers Contribute the Highest Churn Volume

Fiber optic customers account for approximately 1,297 churned customers, representing the largest churn volume among internet-service categories.

💡 Business Recommendations

Based on the analysis, the following retention strategies can be considered:

Introduce retention offers for month-to-month customers.
Focus early engagement programs on newly acquired customers.
Develop targeted retention strategies for high-risk customers.
Review pricing and service experience for high-value customers.
Investigate customer experience issues within the fiber-optic segment.
Encourage suitable customers to move from month-to-month contracts to longer-term plans.

📐 DAX & Analytics

The project uses DAX measures and calculated columns for KPI and segmentation analysis.

Customer Value Segmentation

Customers were segmented using monthly charges:

Low Value: Monthly Charges < 35
Medium Value: Monthly Charges 35–70
High Value: Monthly Charges > 70

Key DAX Measures

Examples of measures created include:

Churned Customers
Overall Churn Rate
Month-to-Month Churned
Month-to-Month Churn %
One Year Churned
Two Year Churned
Customer Value Churn %
High Value Month-to-Month Churn Rate

🧠 Skills Demonstrated
Power BI Dashboard Development
DAX Measures
Power Query
Data Cleaning
Data Transformation
KPI Reporting
Customer Segmentation
Churn Analysis
Trend Analysis
Risk Analysis
Business Insights
Data Visualization
Interactive Slicers
Dashboard Navigation
Business Recommendations

📁 Repository Structure
Telecom-Customer-Churn-PowerBI/
│
├── README.md
│
├── screenshots/
│   ├── executive-summary.png
│   ├── customer-details.png
│   └── churn-insights.png
│
├── PowerBI/
│   └── Telecom-Customer-Churn.pbix
│
└── Dataset/
    └── Telco-Customer-Churn.csv
    |
📈 Project Outcome

The dashboard transforms raw telecom customer data into an interactive business intelligence solution that helps identify:

Who is churning
Which customer segments are at higher risk
Which contract types contribute most to churn
Which customer-value segments require attention
Which service categories have high churn volume
Where customer retention efforts can be focused

👩‍💻 Author

Nirmala N

Data Analyst | Power BI | SQL | Excel | Python | Tableau

Bachelor of Engineering – Electronics & Communication Engineering
