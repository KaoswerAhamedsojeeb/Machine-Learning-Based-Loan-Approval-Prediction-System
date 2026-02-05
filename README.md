**Machine Learning Based Loan Approval Prediction System**
**Overview**

This project focuses on building an end-to-end supervised machine learning pipeline to predict loan approval outcomes based on applicant information. The goal is to assist financial institutions in making data-driven loan approval decisions using classification models.
The project covers the complete workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

**Problem Statement**

Loan approval is a critical decision-making process for financial institutions. Manual evaluation can be time-consuming and prone to bias. This project aims to automate loan approval prediction using machine learning techniques based on historical applicant data.

**Dataset**

The dataset contains structured applicant information such as 'Applicant_Income', 'Coapplicant_Income', 'Age',
       'Dependents', 'Credit_Score', 'Existing_Loans', 'DTI_Ratio', 'Savings',
       'Collateral_Value', 'Loan_Amount', 'Loan_Term', and other relevant features.
The target variable represents whether a loan is approved or not (binary classification).

**Methodology**

The project follows a standard machine learning pipeline:

-> Data cleaning and preprocessing

-> Exploratory Data Analysis (EDA)

-> Feature engineering and encoding

-> Train-test split and feature scaling

-> Model training and comparison

-> Model evaluation using classification metrics

**Machine Learning Models Used**

-> K-Nearest Neighbors (KNN)

-> Logistic Regression

-> Naive Bayes

**Model Evaluation Metrics**

Models are evaluated using the following metrics:

-> Accuracy

-> Precision

-> Recall

-> F1-score

These metrics help assess model performance, especially in handling class imbalance.


**How to Run the Project**

Clone the repository:

git clone <https://github.com/KaoswerAhamedsojeeb/Machine-Learning-Based-Loan-Approval-Prediction-System>
cd Machine-Learning-Based-Loan-Approval-Prediction-System


Create and activate a virtual environment:

python -m venv venv
venv\Scripts\activate   # Windows


Install dependencies:

pip install -r requirements.txt


Run Jupyter Notebook:

python -m notebook
