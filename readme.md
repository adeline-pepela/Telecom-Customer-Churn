# Telecom Customer Churn Analysis

## Project Overview

This project aims to analyze customer churn in the telecom industry by identifying key factors that contribute to customer churn and developing a predictive model to help telecom companies proactively address churn risks. The dataset used in this study comprises telecom customer data collected over a period of one year, from January 2023 to December 2023.

## Background

The telecommunication industry has seen significant growth over the past few decades, becoming a cornerstone of modern society. With the rise of mobile and internet services, customer retention has become a critical challenge for telecom companies. High customer churn rates not only affect profitability but also reflect customer dissatisfaction. Understanding the factors leading to customer churn and developing strategies to mitigate it are crucial for sustaining growth and competitiveness.

## Research Problem

Despite various efforts by telecom companies to improve customer retention, high churn rates remain an issue. The challenge lies in identifying the key factors that influence a customer's decision to switch providers and predicting potential churners with high accuracy. This study aims to analyze customer data, identify significant churn predictors, and develop a predictive model to help telecom companies proactively address churn risks.

## Data Description

The dataset used in this study was sourced from a major telecom provider's customer database. Data collection was conducted under normal business conditions, ensuring the authenticity and reliability of the information. The dataset includes the following features:

- **Age**: Age of the customer
- **Number of Dependents**: Number of dependents the customer has
- **Zip Code**: Customer's zip code
- **Latitude**: Customer's latitude location
- **Longitude**: Customer's longitude location
- **Number of Referrals**: Number of referrals made by the customer
- **Tenure in Months**: Number of months the customer has been with the company
- **Avg Monthly Long Distance Charges**: Average monthly long-distance charges incurred by the customer
- **Avg Monthly GB Download**: Average monthly data download in GB
- **Monthly Charge**: Monthly charges incurred by the customer
- **Total Charges**: Total charges incurred by the customer
- **Total Refunds**: Total refunds issued to the customer
- **Total Extra Data Charges**: Total extra data charges incurred by the customer
- **Total Long Distance Charges**: Total long-distance charges incurred by the customer
- **Total Revenue**: Total revenue generated from the customer
- **Customer Status**: Whether the customer churned (True) or not (False)

## Hypotheses

Based on the dataset, we formulate the following hypotheses:

1. **Customers with higher monthly charges are more likely to churn.**
2. **Customers with shorter tenure are more likely to churn.**

## Methodology

1. **Data Preprocessing**:
   - Identify and handle missing values.
   - Encode categorical variables using one-hot encoding.
   - Normalize numerical features to ensure consistency and improve model performance.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of key features such as age, tenure, and monthly charges.
   - Analyze the relationship between different features and customer churn.

3. **Model Development**:
   - Split the dataset into training and testing sets.
   - Develop and evaluate various machine learning models to predict customer churn.
   - Select the best-performing model based on evaluation metrics.

4. **Model Evaluation**:
   - Evaluate the model using metrics such as accuracy, precision, recall, F1 score, and log loss.
   - Interpret the results and identify key factors contributing to customer churn.

## Results

### Confusion Matrix


### Key Metrics

- **Class 1 (Positive/Churn)**:
  - Precision: 52.4%
  - Recall: 61.1%
  - F1 Score: 56.4%

- **Class 2**:
  - Precision: 77.6%
  - Recall: 90.0%
  - F1 Score: 83.3%

- **Overall Accuracy**: 78.1%

## Conclusion

This project successfully identified key factors contributing to customer churn in the telecom industry. The developed predictive model provides telecom companies with valuable insights to proactively address churn risks. Further improvement can be achieved by incorporating additional data and refining the model.


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telecom-customer-churn.git
