# Welcome to my Telco Customer Churn Prediction Project


In this project I analyzed a dataset of Telco Customers which contains various informations about the customers in order to predict whether the customers will stop using the service or not. The dataset used is a simplified version of this dataset found in Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customer-churn


The main objective of this project is to make a Machine Learning model to predict customers churn status. This project will be focused on testing a Random Forest model with Hyperparameter Tuning and Cross Validation to create a more robust model with optimized result.


# Data Overview


The Dataset is comprised of 7,046 entry with 12 features.


CustomerID: ID of a customer


Gender: Gender of a customer


SeniorCitizen: Whether the customer is a senior citizen or not


Partner: Whether the customer has a partner or not


Dependents: Whether the customer has dependents or not


Tenure: How many months has a customer used the company's service


Contract: Type of the contract (Month-to-Month, 1 Year, 2 Years)


PaperlessBilling: Whether the customer has paperless billing or not


PaymentMethod: PaymentMethod used (Electronic Check, Mailed Check, Bank Transfer, Credit Card)


MonthlyCharges: The amount charged to customer monthly


TotalCharges: The amount charged to customer in total


Churn: Whether a customer stop using the service or not / Customer's Churn Status


# Modelling


The dataset is split into Training Data and Test Data with 80:20 ratio


The Machine Learning model used in this project is Random Forest, further optimized with Hyperparameter Tuning to obtain the optimized result. Cross Validation is used during training process to create a more robust model.


The Evaluation Metrics used are Recall and F1-Score.


Further details can be viewed directly in the Python Notebook.
