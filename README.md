Customer Churn Data Analysis
📌 Project Overview

This project analyses customer churn data to understand customer behaviour, identify factors associated with churn, and generate insights that can support customer retention decisions.
The project follows an end-to-end Data Analyst workflow, starting with data cleaning and exploration in Python, followed by SQL analysis and Power BI visualisation.

🎯 Business Problem

Customer churn can impact revenue and long-term business growth.
The objective of this project is to analyse customer information, subscription details, charges, service usage, and churn status to understand:

Which customer groups have higher churn
How contract and subscription types relate to churn
Whether pricing and tenure are associated with churn
Which customer characteristics may require further investigation
What insights can support customer retention strategies



🎯 Project Objectives
Clean and prepare the raw customer dataset
Handle missing and inconsistent values
Perform exploratory data analysis
Analyse customer churn using SQL
Identify important patterns and trends
Build an interactive Power BI dashboard
Present business insights through data visualisation


📊 Dataset
The dataset contains 542 customer records and 18 columns. 
Key fields include:

Customer ID
Customer Name
Gender
Age
State
City
Tenure
Subscription Type
Monthly Charges
Total Charges
Contract Type
Payment Method
Internet Service
Tech Support
Senior Citizen
Dependents
Churn

🔄 Project Workflow
Raw Excel Dataset
       ↓
Data Cleaning with Python
       ↓
Clean Dataset
       ↓
Exploratory Data Analysis
       ↓
SQL Analysis
       ↓
Power BI Dashboard
       ↓
Business Insights


🧹 Data Cleaning

The raw dataset was cleaned using Python and Pandas.
The cleaning process included:
Checking missing values
Converting numeric columns to appropriate data types
Converting interaction dates into datetime format
Handling missing categorical values
Handling missing numerical values
Checking data consistency
Exporting the cleaned dataset as a CSV file



📈 Exploratory Data Analysis

The analysis will explore customer churn across different dimensions, including:

Churn by gender
Churn by age group
Churn by contract type
Churn by subscription type
Churn by payment method
Churn by internet service
Churn by tech support availability
Churn by tenure
Churn by monthly charges
Churn by customer demographics

🗄️ SQL Analysis

SQL Server will be used to perform business-focused analysis on the cleaned customer data.
Example analysis areas include:

Overall churn rate
Churn by contract type
Churn by subscription type
Average monthly charges by churn status
Customer tenure analysis
Churn by payment method
Customer segment analysis

📊 Power BI Dashboard

An interactive Power BI dashboard will be developed to provide a visual overview of customer churn.
The dashboard will include metrics and visualizations such as:

Total Customers
Churned Customers
Churn Rate
Average Monthly Charges
Average Tenure
Churn by Contract Type
Churn by Subscription Type
Churn by Payment Method
Churn by Customer Segment


📁 Project Structure
Churn-Data-Analysis/
│
├── README.md
├── Churn_Dataset_Cleaning.ipynb
├── Churn_Unclean_Project.xlsx
├── Clean_Churn_Data.csv
│
├── SQL/
│   └── churn_analysis.sql
│
├── PowerBI/
│   └── Churn_Dashboard.pbix
│
└── images/
    └── dashboard.png


👩‍💻 Author

Nikita Dey

Data Analyst | Research Analyst

Last Interaction Date

The original dataset was intentionally unclean and required preprocessing before analysis.
