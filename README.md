
# Customer Churn Prediction Using Predictive Analytics

# Project Overview
Customer churn is a major challenge for businesses, especially in the banking and financial sectors. This project focuses on analyzing customer behavior and building a machine learning model to predict whether a customer will leave the bank.

Using predictive analytics techniques, the project explores patterns in customer data, performs feature engineering, and builds a classification model to detect churn risk.

# Project Objectives

- Analyze customer data to identify patterns related to churn.
- Perform exploratory data analysis (EDA).
- Clean and preprocess the dataset.
- Create engineered features to improve prediction.
- Build a classification model to predict customer churn.
- Generate insights that can help businesses reduce churn.

# Dataset Description
The dataset contains information about bank customers including demographic details, financial attributes, and transaction behavior.

## Key features include:

- Customer Age
- Gender
- Income Category
- Credit Limit
- Total Transaction Amount
- Total Transaction Count
- Credit Utilization Ratio

## The target variable is:

`Attrition_Flag`

- `0` → Existing Customer
- `1` → Attrited Customer (Churn)

# Project Workflow

## Day 1 — Exploratory Data Analysis

- Understanding the dataset
- Checking missing values
- Generating summary statistics
- Creating visualizations (histograms, boxplots, heatmaps)

## Day 2 — Data Cleaning & Preprocessing

- Handling missing values
- Removing duplicate records
- Encoding categorical variables
- Preparing the dataset for modeling

## Day 3 — Feature Engineering

New features were created to capture customer behavior patterns:

- Activity Rate
- Credit Usage Ratio
- Average Transaction Value

## Day 4 — Modeling

A Logistic Regression classification model was built to predict customer churn.

### Evaluation metrics used:

- Accuracy
- Precision
- Recall
- Confusion Matrix

## Day 5 — Insights & Conclusion

Business insights were generated based on analysis and model results.

# Model Performance

**Model used:** Logistic Regression

## Evaluation results:

- Accuracy ≈ 83.9%
- Precision ≈ 83.9%
- Recall = 1.0

The model successfully identified churned customers and provides a useful early warning system for customer retention strategies.

# Key Insights

- Customers with lower activity rates tend to have higher churn probability.
- High credit utilization may indicate increased churn risk.
- Customers with higher transaction frequency are generally more loyal.
- Customer tenure plays an important role in retention.
- Spending amount alone is not a strong churn indicator.

# Recommended Actions

- Identify and target high-risk customers using churn predictions.
- Increase customer engagement through reward programs.
- Monitor customers with high credit utilization.
- Implement retention campaigns for inactive customers.

# Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

# Future Improvements

- Implement advanced models such as Random Forest or XGBoost.
- Perform hyperparameter tuning.
- Incorporate additional customer behavior features.
- Use cross-validation for more robust evaluation.

# Author

**MOHAMMAD ALTHAF**
