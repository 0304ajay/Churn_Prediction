# **Telecom Customer Churn Prediction**

This project focuses on predicting customer churn in the telecom industry using machine learning techniques. The dataset used for this project is obtained from Kaggle and can be found [here](https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction).

## **Overview**

Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. Predicting customer churn is crucial for businesses, especially in highly competitive industries such as telecommunications, as it allows companies to identify at-risk customers and take proactive measures to retain them.

In this project, we use machine learning algorithms to analyze historical customer data and predict whether a customer is likely to churn or not. Specifically, we employ logistic regression, a commonly used classification algorithm, to build a predictive model.

## **Dataset**

The dataset used for this project contains information about telecom customers, including demographic information, usage patterns, and whether they churned or not. The dataset is provided in CSV format and consists of the following columns:

- `customerID`: Unique identifier for each customer
- `gender`: Customer's gender (male or female)
- `SeniorCitizen`: Whether the customer is a senior citizen (1: yes, 0: no)
- `Partner`: Whether the customer has a partner (yes or no)
- `Dependents`: Whether the customer has dependents (yes or no)
- `tenure`: Number of months the customer has been with the company
- `PhoneService`: Whether the customer has phone service (yes or no)
- `MultipleLines`: Whether the customer has multiple lines (yes, no, or no phone service)
- `InternetService`: Customer's internet service type (DSL, fiber optic, or no)
- `OnlineSecurity`: Whether the customer has online security (yes, no, or no internet service)
- `OnlineBackup`: Whether the customer has online backup (yes, no, or no internet service)
- `DeviceProtection`: Whether the customer has device protection (yes, no, or no internet service)
- `TechSupport`: Whether the customer has tech support (yes, no, or no internet service)
- `StreamingTV`: Whether the customer has streaming TV (yes, no, or no internet service)
- `StreamingMovies`: Whether the customer has streaming movies (yes, no, or no internet service)
- `Contract`: Customer's contract type (month-to-month, one year, or two year)
- `PaperlessBilling`: Whether the customer has paperless billing (yes or no)
- `PaymentMethod`: Customer's payment method
- `MonthlyCharges`: Customer's monthly charges
- `TotalCharges`: Customer's total charges
- `Churn`: Whether the customer churned (yes or no)

## **Methodology**

We use the scikit-learn library in Python to train a logistic regression model on the provided dataset. Logistic regression is a popular algorithm for binary classification tasks, making it suitable for predicting customer churn (a binary outcome).

After training the logistic regression model, we evaluate its performance using metrics such as accuracy, precision, recall, and F1-score. These metrics provide insights into how well the model predicts customer churn and can help identify areas for improvement.

## **Usage**

To run the code for this project, follow these steps:
1. Clone the repository or download the file and Unzip the file.
2. Then just run the `main.py` File. 

## **Results**

The results of the logistic regression model are as follows:

- Accuracy: 82%

These metrics indicate how well the model performs at predicting customer churn. Further analysis and fine-tuning of the model may be necessary to improve its performance.

## **Conclusion**

Predicting customer churn is a critical task for telecom companies to retain customers and maintain profitability. By leveraging machine learning techniques, such as logistic regression, businesses can gain insights into customer behavior and take proactive measures to prevent churn.
