
![README](https://github.com/saidatascience2023/DataScienceGuidedProject/blob/main/Classification%20Projects/Customer%20Churn%20Project/images/churn.jpeg)

## Customer Churn Prediction Project

This project aims to predict customer churn using machine learning techniques. Churn refers to customers who stop doing business with a company. By identifying such customers in advance, businesses can take proactive steps to retain them.

### Data Dictionary
The data set includes information about:

Customers who left within the last month – the column is called Churn

Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges

Demographic info about customers – gender, age range, and if they have partners and dependents

### Problem Statement or Goal 

Telecom and subscription-based companies often face the challenge of losing customers. This project builds a predictive model that classifies customers as **churned** or **not churned** based on their behavior and demographic data.

### Strategy to Solve the Problem

1. **Data Cleaning and Preprocessing**  
  Handle missing values, correct data types, encode categorical variables, and scale features.

2. **Exploratory Data Analysis (EDA)**  
  Understand distributions, spot trends, visualize churn behavior, and identify outliers.

3. **Model Training**  
  Train multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost) and perform hyperparameter tuning.

4. **Model Evaluation**  
  Assess performance using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

5. **Feature Importance**  
  Identify which features contribute most to customer churn using model insights.

6. **Deployment**  
  Export trained model and build a simple script or web app for real-time prediction.

### How to Run

1. Clone the repository  
2. git clone https://github.com//saidatascience2023/customer-churn-prediction.git
3. cd customer-churn-prediction

### Model Performance

1. Model Used: Random Forest Classifier:

2. Accuracy: 85%

3. Precision: 81%

4. Recall: 78%

5. ROC-AUC: 0.88

### Technologies Used

1. Python

2. Pandas, NumPy, Matplotlib, Seaborn

3. Scikit-learn

4. Jupyter Notebook

5. Streamlit or Flask (optional, for web deployment)

### Future Enhancements

1. Add deep learning models (e.g., ANN with TensorFlow)

2. Build an interactive dashboard

3. Automate retraining with new data

4. Integrate feedback loop for model improvement

