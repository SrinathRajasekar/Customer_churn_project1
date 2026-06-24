#Customer Churn Prediction Using Machine Learning

Project Overview

This project analyzes customer churn behavior using Machine Learning techniques. The objective is to identify customers who are likely to leave the service and segment customers into meaningful groups for targeted retention strategies.

#Dataset

- Dataset: Telco Customer Churn Dataset
- Total Records: 7043 Customers
- Features include customer demographics, account information, services subscribed, tenure, and billing details.

#Project Workflow

1. ##Data Cleaning

- Handled missing values in Total Charges
- Converted data types where necessary
- Removed irrelevant columns

2. ##Data Preprocessing

- Encoded categorical variables using One-Hot Encoding
- Created a machine-learning-ready dataset

3. ##Machine Learning Implementation

- Train-Test Split (80:20)
- Random Forest Classifier

4. ##Class Imbalance Handling

- Used balanced class weights to improve minority class prediction

5. ##Hyperparameter Tuning

- Tested multiple combinations of:
  - Number of Trees
  - Maximum Tree Depth

6. ##Feature Importance Analysis

- Identified the most influential features affecting customer churn

7. ##Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

8. ##Customer Segmentation

- Generated churn probabilities
- Standardized customer features
- Applied K-Means Clustering

9. ##Customer Segments

- Budget Loyal Customers
- High Risk New Customers
- Loyal Premium Customers

##Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

##Results

The Random Forest model successfully identified customers at risk of churn. K-Means clustering further segmented customers into meaningful groups, helping businesses design personalized retention strategies.

##Future Improvements

- XGBoost Implementation
- Advanced Hyperparameter Optimization
- Deployment using Streamlit
- Real-time Customer Churn Prediction
