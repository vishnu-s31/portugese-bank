# Portuguese Bank Marketing Analysis

## 📌 Project Overview
Banks invest heavily in marketing campaigns for financial products such as term deposits. This project analyzes a Portuguese bank’s marketing dataset to predict whether a customer will subscribe to a term deposit, helping improve campaign efficiency and customer targeting.

The project combines Exploratory Data Analysis (EDA) and Machine Learning to uncover customer behavior patterns and build predictive models for better decision-making.

---

## 🎯 Problem Statement
The goal is to predict whether a client will subscribe to a term deposit based on demographic, financial, campaign-related, and macroeconomic attributes.

### Business Objectives
- Identify customers likely to respond positively to campaigns  
- Reduce unnecessary marketing calls and operational costs  
- Improve campaign success rates  
- Enhance customer targeting strategies  

This is a **binary classification problem** (`yes` / `no`).

---

## 📊 Dataset Information
- **Dataset Size:** 41,188 rows × 21 columns  
- **Target Variable:**  
  - `y` – Whether the client subscribed to a term deposit  

### Feature Categories
- **Customer Demographics:** age, job, marital status, education  
- **Financial Information:** default, housing loan, personal loan  
- **Campaign Details:** contact type, month, call duration, campaign count, previous outcomes  
- **Macroeconomic Indicators:** employment rate, consumer price index, Euribor rate, number of employees  

---

## 🔧 Data Preprocessing
- Handled missing and `unknown` values  
- Encoded categorical variables using Label Encoding and One-Hot Encoding  
- Scaled numerical features using StandardScaler  
- Addressed class imbalance using:
  - Class weight balancing  
  - SMOTE oversampling  

---

## 📈 Exploratory Data Analysis (EDA)
### Key Insights
- Most customers fall within the 30–50 age group  
- Longer call durations strongly increase subscription probability  
- Customers without housing or personal loans show higher subscription rates  
- Successful previous campaigns significantly boost conversions  
- Repeated calls in the same campaign reduce customer interest  

---

## 🤖 Model Building
- **Train-Test Split:** 80% training, 20% testing  

### Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  

### Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

## 🏆 Model Performance
- **Best Performing Model:** Gradient Boosting Classifier  
- High predictive performance on unseen data  
- Robust handling of nonlinear relationships  

---

## ⭐ Feature Importance
Top features influencing customer subscription:
- Call duration  
- Previous campaign outcome  
- Number of campaign contacts  
- Age  
- Housing loan status  
- Euribor 3-month rate  

---

## 💡 Business Insights & Recommendations
### Insights
- Customers with successful past interactions are more likely to subscribe  
- Longer and meaningful conversations increase conversion rates  
- Excessive calling negatively impacts customer response  

### Recommendations
- Focus marketing efforts on high-probability customers  
- Reduce unnecessary repeated calls  
- Improve agent training to optimize call duration  
- Use predictive analytics before launching campaigns  

---

## 🚀 Future Scope
- Deploy the model using Flask or FastAPI  
- Build a real-time dashboard with Power BI or Streamlit  
- Perform cost-benefit analysis of campaigns  
- Experiment with deep learning techniques  

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- Machine Learning Algorithms  

---
