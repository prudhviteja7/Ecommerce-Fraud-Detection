# E-Commerce Fraud Detection Analysis

This project analyses e-commerce transaction data to identify patterns associated with fraudulent activities and builds machine learning models to detect fraud.

## Objective
The goal of this project is to explore transaction behavior and identify key indicators of fraud using data analysis and predictive modeling.

## Dataset
Synthetic e-commerce transaction dataset containing information about:
- transaction amount
- payment method
- device used
- customer age
- account age
- transaction time

## Key Insights
Several patterns were identified during analysis:

• Higher-value transactions show significantly higher fraud risk  
• Fraud is more common among newly created accounts  
• Fraudulent transactions occur more frequently during late-night hours  

## Feature Engineering
New behavioral features were created to improve fraud detection:

- High value transaction flag
- New account indicator
- Night transaction indicator

## Machine Learning Models
Two models were implemented:

**Logistic Regression**
- Used as a baseline model

**Random Forest Classifier**
- Captures complex fraud patterns
- Improved fraud detection performance

## Model Performance
The Random Forest model achieved:

- **Accuracy:** ~95%
- **AUC Score:** 0.74

indicating a reasonable ability to distinguish between fraudulent and legitimate transactions.

## Key Fraud Indicators
Feature importance analysis showed that the most influential variables are:

1. Transaction Amount
2. Account Age
3. Transaction Hour

## Conclusion
The analysis demonstrates that transaction value, account age, and transaction timing are strong indicators of fraud risk. These insights can support fraud monitoring systems and help prioritize high-risk transactions for investigation.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
