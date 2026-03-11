# Identifying Drivers of Customer Churn and Revenue Impact in a Telecom Company

## Overview
Customer churn represents a major challenge for subscription-based businesses because losing customers directly impacts recurring revenue. This project analyzes customer churn patterns within a telecommunications dataset to identify key factors associated with customer attrition and highlight potential strategies for improving customer retention. The analysis focuses on understanding how service usage, contract structure, and billing behavior relate to churn risk.

## Project Notebook
📊 View the full analysis here:  
[Open the Jupyter Notebook](notebook/churn_analysis.ipynb)

## Dataset

The dataset contains customer-level information for a telecommunications company. Each record represents an individual customer and includes demographic attributes, service subscriptions, billing details, and churn status. This dataset has been taken from Kaggle, and can be found [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Key Variables

| Variable        | Description                                             |
|-----------------|---------------------------------------------------------|
| tenure          | Number of months the customer has been with the company |
| MonthlyCharges  | Amount billed to the customer each month                |
| TotalCharges    | Total amount charged to the customer                    |
| Contract        | Type of contract (month-to-month, one year, two year)   |
| InternetService | Type of internet service subscribed                     |
| PaymentMethod   | Customer billing method                                 |
| Churn           | Whether the customer discontinued the service           |

## Analytical Workflow

The analysis follows a structured data analysis process:

1. Business understanding and problem framing  
2. Data overview and cleaning  
3. KPI calculation to quantify churn impact  
4. Exploratory Data Analysis (EDA)  
5. Identification of churn drivers  
6. Business recommendations based on insights

## Business Recommendations

Based on the analysis, several strategies may help reduce customer churn:

- Encourage customers to transition to longer-term contracts.
- Improve onboarding and early-stage customer engagement.
- Reevaluate pricing or communicate value more effectively for higher-tier plans.
- Investigate customer experience associated with fiber optic services.
- Promote automated billing methods to improve retention.
