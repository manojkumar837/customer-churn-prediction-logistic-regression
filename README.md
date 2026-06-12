Customer Churn Prediction Using Logistic Regression

Project Overview

Customer churn is one of the major challenges faced by telecom companies. This project uses Machine Learning to predict whether a customer is likely to leave a telecom service provider based on customer demographics, account information, and subscribed services.

The model is built using Logistic Regression and helps organizations identify at-risk customers and improve retention strategies.

Problem Statement

Predict whether a telecom customer will churn (leave the service) or stay with the company using historical customer data.

Target Variable:
- Churn

Classes:
- Yes (Customer will leave)
- No (Customer will stay)

---

Dataset

Dataset: Telco Customer Churn Dataset

Features include:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

Target:
- Churn

---

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Logistic Regression
- Joblib
- Jupyter Notebook

---

Project Workflow

1. Data Collection
Loaded the Telco Customer Churn dataset.

2. Data Preprocessing
- Handled missing values
- Removed unnecessary columns
- Converted categorical variables into numerical format
- Prepared features and target variable

3. Feature Engineering
- Label Encoding
- Data Transformation

4. Model Building
- Train-Test Split
- Logistic Regression Model Training

5. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

6. Model Deployment Preparation
- Saved trained model using Joblib
- Loaded saved model for future predictions

Model Performance

Evaluation Metrics:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

Project Structure

customer-churn-prediction-logistic-regression/

├── Churn_logistic.ipynb

├── Telco-Customer-Churn.csv

├── churn_model.pkl

├── README.md

└── requirements.txt

Installation

bash
pip install pandas numpy scikit-learn joblib

Run Project

```bash
jupyter notebook
```

Open:

```text
Churn_logistic.ipynb
```

Run all cells sequentially.

Business Impact

The model helps telecom companies:

- Identify customers likely to churn
- Improve customer retention
- Reduce revenue loss
- Support data-driven business decisions

Author

Manoj Kumar M

Aspiring Data Analyst | Machine Learning Enthusiast
