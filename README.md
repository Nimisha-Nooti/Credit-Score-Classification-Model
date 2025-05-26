# Credit Score Classification Model

Overview

This project presents a machine learning solution for classifying individuals based on their credit scores using the CatBoost algorithm. The primary objective is to determine whether a person falls into categories such as "Good", "Standard", or "Poor" creditworthiness based on a set of financial and behavioral attributes. The model is built with scalability and practical deployment in mind, making it suitable for use in financial institutions and fintech applications. A web API is also included to make predictions easily accessible.

### Features
The pipeline implemented in this project is comprehensive and encompasses all essential stages of a machine learning workflow. It includes thorough data cleaning, extensive feature engineering, and robust model training using the CatBoost classifier, known for its efficiency with categorical data. Post-training, the model undergoes evaluation using various classification metrics. For deployment, a Flask-based API is provided to allow real-time predictions through HTTP requests.

- End-to-end pipeline: data cleaning, feature engineering, model training

- Gradient boosting using CatBoost

- Classification reporting and evaluation

- Model deployment using Flask API

### Dataset

- Source: Kaggle (custom credit scoring dataset)

- Attributes include: Age, Annual Income, Monthly Salary, Outstanding Debt, Loan Counts, Delayed Payments, Spending Score, Payment Behavior and Credit Utilization

### Files

- notebook.ipynb: Complete analysis, model building, and evaluation

- credit_model.cbm: Serialized CatBoost model (exported)

- app.py: Flask API for model deployment

- README.md: Project documentation
