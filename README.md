# **Customer Churn Prediction**

**Project Type:** End-to-End Batch Prediction & Business Insights  
**Tools & Technologies:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Kaggle  

---

## **Project Overview**

Customer churn—when a customer stops using a service—is a major challenge for subscription-based businesses. This project demonstrates an end-to-end approach to predicting customer churn using a real-world telecom dataset, generating actionable business insights, and creating batch risk predictions.

### **Objectives**
- Predict which customers are likely to churn (binary classification)
- Identify key drivers of churn
- Categorize customers into risk buckets for retention strategies

---

## **Dataset**

- **Source:** [Kaggle Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Description:** Customer demographic, account, and service usage data
- **Target Variable:** `Churn` (Yes = 1, No = 0)

---

## **Methodology**

### **1. Data Preprocessing**
- Handled missing values and converted columns to correct data types  
- Dropped irrelevant columns (`customerID`)  
- Encoded categorical variables using one-hot encoding  
- Converted target variable `Churn` to binary  

### **2. Exploratory Data Analysis (EDA)**
- Analyzed churn distribution across tenure, monthly charges, and contract types  
- Visualized patterns using boxplots, bar charts, and heatmaps  
- Identified high-risk customer segments  

### **3. Feature Engineering**
- Created tenure buckets to capture customer lifecycle stage  
- Created `total_services` feature to summarize customer engagement  
- Prepared final feature set for machine learning  

### **4. Model Building**
- **Logistic Regression:** Baseline, interpretable model  
- **Random Forest:** Captures non-linear relationships and interactions  
- Evaluated using accuracy, precision, recall, ROC-AUC, and confusion matrix  

### **5. Feature Importance & Insights**
- Short tenure, high monthly charges, and month-to-month contracts are key churn drivers  
- Logistic Regression coefficients confirmed similar trends  

### **6. Batch Predictions & Risk Buckets**
- Calculated churn probabilities for all customers  
- Categorized into **High**, **Medium**, and **Low Risk** buckets  

---

## **Key Insights**

- **Short-tenure customers** are most likely to churn  
- **Month-to-month contracts** have the highest churn rates  
- **High monthly charges** increase churn probability  
- **Multiple services and long-term contracts** reduce churn risk  

---

## **Business Recommendations**

1. **High-Risk Customers (Churn Probability ≥ 0.6)**  
   - Targeted retention campaigns, discounts, and loyalty programs  

2. **Medium-Risk Customers (0.4 ≤ Churn Probability < 0.6)**  
   - Engagement strategies and proactive monitoring  

3. **Low-Risk Customers (Churn Probability < 0.4)**  
   - Minimal intervention; maintain standard loyalty programs  

4. **Contract Strategy**  
   - Promote 1–2 year contracts  

5. **Pricing Strategy**  
   - Review high monthly charges and offer flexible plans  

---

## **Limitations**

- Dataset may not capture all churn drivers  
- Assumes future data follows similar distribution  
- No temporal churn modeling  
- Class imbalance may affect risk identification  

---

⭐ **If you find this project useful, please consider giving it an upvote.**  

🔗 **Project Link:**  
https://www.kaggle.com/code/vighneshnicham/customer-churn-analysis  

---

# **Customer-Churn-Prediction**
