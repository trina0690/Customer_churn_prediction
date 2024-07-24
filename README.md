# 📊 **Customer Churn Prediction** 📊

Welcome to the **Customer Churn Prediction** project! This repository contains the code for predicting customer churn in a subscription-based service. Utilizing historical customer data, we apply various machine learning algorithms to predict whether customers will leave the service.

## 📝 **Project Overview**

In this project, we develop a predictive model to forecast customer churn. We use a dataset from Kaggle (`churn_Modelling.csv`) that includes features related to customer demographics and usage behavior. The models explored include Logistic Regression, Random Forest, and Gradient Boosting.
Also used Ensemble Method.
### 🔍 **Dataset Description**

The dataset `churn_Modelling.csv` consists of the following features:

- **RowNumber:** Index of the row.
- **CustomerId:** Unique identifier for the customer.
- **Surname:** Customer’s surname.
- **CreditScore:** Credit score of the customer.
- **Geography:** Country of residence.
- **Gender:** Gender of the customer.
- **Age:** Age of the customer.
- **Tenure:** Number of years the customer has been with the service.
- **Balance:** Account balance of the customer.
- **NumOfProducts:** Number of products the customer is using.
- **HasCrCard:** Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember:** Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary:** Estimated salary of the customer.
- **Exited:** Target variable indicating churn (1 = Churned, 0 = Not Churned).

- DATASET LINK: https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

## 🛠️ **Implementation Steps**

### 1. **Data Cleaning and Preparation**

- **Loading the Dataset:** Import the data and examine its structure.
- **Handling Missing Values:** Address any missing values in the dataset.
- **Feature Encoding:** Convert categorical variables into numerical format.
- **Feature Scaling:** Normalize features to improve model performance.

### 2. **Model Building**

- **Logistic Regression:** Train and evaluate the logistic regression model.
- **Random Forest:** Train and tune the random forest model using hyperparameter optimization.
- **Gradient Boosting:** Train and evaluate the gradient boosting model.

### 3. **Ensemble Method**

- **Combining Models:** Use a Voting Classifier to combine the predictions from Logistic Regression, Random Forest, and Gradient Boosting.

### 4. **Model Evaluation**

- **Performance Metrics:** Assess the models using accuracy, precision, recall, and F1 score.
- **Confusion Matrix:** Visualize the performance to understand model effectiveness.




🤝 Acknowledgements:

Kaggle for the dataset.

Encryptix for giving me this opportunity.


 **Clone the Repository:**

 ```bash
 git clone https://github.com/trina0690/Encryptix-Task-3-Customer_churn_prediction.git
