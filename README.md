# Insurance Fraud Detection – Vehicle Claims
## Author: Maryam Jaffer Alqassas

## Project Overview
This project analyzes a vehicle insurance dataset to detect patterns and indicators of fraudulent claims.
The goal is to help insurance companies reduce fraud, lower operational costs, and improve decision-making.
The dataset shows a 6% increase in suspicious claims from 1993 to 1996, prompting a deeper investigation.

## Dataset Description
The dataset includes records of vehicle accidents, customer demographics, policy details, and an indicator showing whether fraud was found.
Key Columns:
•	Accident details (Month, Day, Week of Month)
•	Vehicle attributes (Make, Price, Category, Age)
•	Policy information (Policy Type, Base Policy, Days to Claim)
•	Customer demographics (Age, Gender, Marital Status)
•	Fraud indicator: FraudFound_P (1 = Fraud, 0 = No Fraud)


## Data Notes:
•	No missing values
•	No duplicates
•	All data types were correct
•	New combined Date column created (Month + Year)

## Data Cleaning & Preparation
The following steps were completed before analysis:
•	Checked for nulls → none found
•	Checked for duplicates → none found
•	Created additional features (Month/Year → Date)
•	Standardized column names (added spacing only)
•	Kept all original columns (no deletions)
•	Verified correct data types

## Exploratory Data Analysis (EDA)
### Performed Analyses:
•	Fraud distribution across years
•	Monthly fraud trends
•	Day-of-week effect on claims
•	Comparison of Urban vs Rural fraud
•	Fraud rates by gender, marital status, and age group
•	Vehicle type & vehicle make fraud patterns
•	Impact of police reports on fraud probability
•	Policy type analysis (All Perils, Collision, Liability)
### Visualizations Included:
•	Line charts
•	Bar charts
•	Category comparisons
•	Fraud proportions per attribute

## Key Insights / Results
### Fraud Trends
•	Fraud cases decreased from 1994 to 1996
•	Highest fraud months: March, May, August
•	Lowest fraud month: November
### Day of Week
•	Fraud peaks on Monday
•	Lowest during weekends
### Policy Type
•	All Perils has the highest fraud (10.16%)
•	Liability has the lowest (0.72%)
### Vehicle Category
•	Sedans → highest fraud (57.56%)
•	Sports cars → second highest
•	Utility vehicles → lowest
### Location
•	Urban areas show significantly more fraud than rural areas.
### Customer Demographics
•	Males have much higher fraud counts than females.
•	Ages 31–40 show the highest fraud frequency.
•	Married individuals show the highest fraud rates.
### Vehicle Make
Fraud is most common among:
•	Pontiac
•	Toyota
•	Honda
•	Mazda
### Luxury brands (BMW, Mercedes, etc.) appear rarely.
Police Report
•	Fraud is more common when NO police report is filed.

## Recommendations
1. Strengthen Monitoring of High-Risk Groups
Focus on males and adults aged 31–40 to optimize investigation resources.
2. Improve Risk-Based Pricing
Adjust pricing and policy coding based on vehicle type and risk level.
3. Enhance Vehicle & Time-Based Monitoring
Track fraud trends across months, days, and high-risk car makes.

## Tools & Libraries
The analysis was performed using:
•	Python: pandas, numpy, matplotlib, seaborn
•	Jupyter Notebook
•	Excel (data overview)

## Future Improvements
•	Build a machine learning model to predict fraud probability
•	Add anomaly detection techniques
•	Expand dataset with recent years
•	Include more detailed incident reports
