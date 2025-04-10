
![README](https://github.com/saidatascience2023/DataScienceGuidedProject/blob/main/Classification%20Projects/Customer%20Churn%20Project/images/churn.jpeg)

## Customer Churn Prediction Project

This project aims to predict customer churn using machine learning techniques. Churn refers to customers who stop doing business with a company. By identifying such customers in advance, businesses can take proactive steps to retain them.

### Data Dictionary
The data set includes information about:

Customers who left within the last month – the column is called Churn

Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges

Demographic info about customers – gender, age range, and if they have partners and dependents

**customerID**A unique identifier for each customer.

**gender:** The gender of the customer (Male/Female).

**SeniorCitizen:** Indicates whether the customer is a senior citizen (1: Yes, 0: No).

**Partner:** Indicates whether the customer has a partner (Yes/No).

**Dependents:** Indicates whether the customer has dependents (Yes/No).

**tenure:** The number of months the customer has been with the company.

**PhoneService:** Indicates whether the customer has phone service (Yes/No).

**MultipleLines:** Indicates whether the customer has multiple lines (Yes/No).

**InternetService:** The type of internet service the customer has (DSL/Fiber optic/No).

**OnlineSecurity:** Indicates whether the customer has online security (Yes/No).

**OnlineBackup:** Indicates whether the customer has online backup service (Yes/No).

**DeviceProtection:** Indicates whether the customer has device protection (Yes/No).

**TechSupport:** Indicates whether the customer has tech support service (Yes/No).

**StreamingTV:** Indicates whether the customer has streaming TV service (Yes/No).

**StreamingMovies:** Indicates whether the customer has streaming movies service (Yes/No).

**Contract:** The type of contract the customer has (Month-to-month/One year/Two year).

**PaperlessBilling:** Indicates whether the customer has paperless billing (Yes/No).

PaymentMethod: The method the customer uses to pay (Electronic check/Mailed check/Bank transfer/credit card).

**MonthlyCharges:** The amount charged to the customer each month.

**TotalCharges:** The total amount charged to the customer during their tenure.

**Churn**Indicates whether the customer has churned (1: Yes, 0: No).

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

### Insights from Data Analysis

**Univariate Analysis :** Checking the Distribution of the Single Feature or Imbalance of the DataSet.

![README](https://github.com/saidatascience2023/DataScienceGuidedProject/blob/main/Classification%20Projects/Customer%20Churn%20Project/images/Random-Forest-Classifier-Customer_Churn-ipynb-Colab-04-10-2025_04_58_PM.png)

**Bivariate Analysis :** Check the relationship between the Churn and Tenure.Analyzing how the length of time a customer has been with a company (Tenure) affects the likelihood of that customer leaving the company (Churn).

![README](https://github.com/saidatascience2023/DataScienceGuidedProject/blob/main/Classification%20Projects/Customer%20Churn%20Project/images/Random-Forest-Classifier-Customer_Churn-ipynb-Colab-04-10-2025_05_27_PM.png)

### Model Performance

1. Model Used: Random Forest Classifier:

2. Accuracy: 85%

3. Precision: 81%

4. Recall: 78%

5. ROC-AUC: 0.88

### Confusion Matrix Explanation
This matrix summarizes the performance of your Customer Churn Prediction model, likely using a Random Forest Classifier.

![README](https://github.com/saidatascience2023/DataScienceGuidedProject/blob/main/Classification%20Projects/Customer%20Churn%20Project/images/Random-Forest-Classifier-Customer_Churn-ipynb-Colab-04-10-2025_05_31_PM.png)

**Interpretation of Each Cell**

True Negatives (TN): 887
Customers who did not churn, and the model correctly predicted No Churn.

False Positives (FP): 149
Customers who did not churn, but the model incorrectly predicted Churn.
⚠️ May lead to unnecessary retention efforts.

False Negatives (FN): 156
Customers who did churn, but the model predicted No Churn.
⚠️ These are risky, as the model misses customers who actually left.

True Positives (TP): 217
Customers who did churn, and the model correctly predicted Churn.

**Performance Insight**

The model is good at identifying non-churners (TN = 887) and a decent number of churners (TP = 217).
However, there are 149 false alarms (FP) and 156 misses (FN), which could be improved with further model tuning or better features.

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

