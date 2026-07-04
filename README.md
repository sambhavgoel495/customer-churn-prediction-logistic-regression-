# Customer Churn Prediction using Logistic Regression

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom companies. Losing existing customers directly impacts revenue and business growth.

In this project, a **Logistic Regression** model is developed to predict whether a customer is likely to churn based on demographic information, account details, and the services they use.

The project focuses on proper data preprocessing, feature engineering, exploratory data analysis (EDA), model evaluation, and improving Logistic Regression without using more advanced algorithms.

---

## 🎯 Objective

Build a machine learning model that predicts customer churn and helps businesses identify customers who are at risk of leaving.

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer demographics
- Account information
- Subscription details
- Services used
- Monthly and total charges
- Customer churn status

**Target Variable**

- **0** → Customer did not churn
- **1** → Customer churned

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Missing value analysis
- Data type inspection
- Categorical feature analysis
- Correlation Heatmap
- Feature Engineering

---

## ⚙ Data Preprocessing

The preprocessing pipeline included:

- Handling missing values
- Converting categorical variables into numerical values
- One-Hot Encoding
- Feature Scaling using StandardScaler
- Train-Test Split

---


## 🤖 Model Used

**Logistic Regression**

The model was trained using Scikit-learn after preprocessing and feature scaling.

Experiments were also performed with:

- Feature Engineering
- Class Weight Balancing
- Feature Importance Analysis

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix


---

## 📷 Visualizations

This project includes:

- Correlation Heatmap
- Confusion Matrix
- Feature Importance Plot

---

## 📌 Key Learnings

Through this project I learned:

- Binary Classification using Logistic Regression
- Data Cleaning and Preprocessing
- One-Hot Encoding
- Feature Scaling
- Feature Engineering
- Handling Class Imbalance
- Understanding Precision, Recall and F1 Score
- Feature Importance using Logistic Regression Coefficients

---

🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Recursive Feature Elimination (RFE)
- Cross Validation
- Threshold Optimization
- Compare Logistic Regression with other classification algorithms (Decision Tree, Random Forest, SVM, XGBoost)

---

## 📌 Results

The Logistic Regression model achieved competitive performance on the Telco Customer Churn dataset and demonstrated the trade-off between Accuracy, Precision and Recall. Different preprocessing and feature engineering techniques were explored to improve model performance while maintaining interpretability.
Accuracy: 0.7320540156361052
Precision: 0.49747899159663866
Recall: 0.7914438502673797
F1 Score: 0.6109391124871001
---

## 📜 License

This project is intended for educational and portfolio purposes.
