
![README](https://github.com/saidatascience2023/DataScienceGuidedProject/blob/main/Classification%20Projects/Customer%20Churn%20Project/images/churn.jpeg)

## Customer Churn Prediction Project

This project aims to predict customer churn using machine learning techniques. Churn refers to customers who stop doing business with a company. By identifying such customers in advance, businesses can take proactive steps to retain them.

### Data Dictionary
The data set includes information about:

Customers who left within the last month – the column is called Churn

Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges

Demographic info about customers – gender, age range, and if they have partners and dependents

## 🔍 Problem Statement or Goal 

Telecom and subscription-based companies often face the challenge of losing customers. This project builds a predictive model that classifies customers as **churned** or **not churned** based on their behavior and demographic data.

## 📦 Strategy to Solve the Problem

- **Data Cleaning and Preprocessing**  
  Handle missing values, correct data types, encode categorical variables, and scale features.

- **Exploratory Data Analysis (EDA)**  
  Understand distributions, spot trends, visualize churn behavior, and identify outliers.

- **Model Training**  
  Train multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost) and perform hyperparameter tuning.

- **Model Evaluation**  
  Assess performance using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

- **Feature Importance**  
  Identify which features contribute most to customer churn using model insights.

- **Deployment**  
  Export trained model and build a simple script or web app for real-time prediction.

## 🛠️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com//saidatascience2023/customer-churn-prediction.git
   cd customer-churn-prediction

### Model Performance

Model Used: Random Forest Classifier:

Accuracy: 85%

Precision: 81%

Recall: 78%

ROC-AUC: 0.88
