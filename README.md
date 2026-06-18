# DATA-ANALYST
# Telco Customer Churn Prediction Using Machine Learning

## 📌 Introduction
Customer churn is a major challenge for telecommunication companies because losing customers directly impacts revenue and business growth.  
This project focuses on analyzing customer behavior and predicting whether a customer is likely to leave the company using machine learning techniques.

---

## 🎯 Objective
The main objectives of this project are:

- Analyze customer data and identify churn patterns  
- Build machine learning models to predict customer churn  
- Segment customers based on their value and risk level  
- Identify high-risk customers for retention strategies  

---

## 📊 Dataset
The project uses the **Telco Customer Churn dataset**.  
It contains customer demographic information, service details, contract information, billing details, and churn status.

### Important Attributes:
- Tenure  
- Monthly Charges  
- Total Charges  
- Contract Type  
- Internet Service  
- Payment Method  
- Churn  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Removed unnecessary spaces from column names  
- Converted `TotalCharges` to numeric format  
- Replaced missing values using median  
- Removed duplicate records  

### 2. Feature Engineering
- Average Spend Per Month  
- Customer Lifetime Value  
- Long-Term Customer Indicator  

---

## 📈 Exploratory Data Analysis (EDA)
The following visualizations were generated:
- Churn Distribution  
- Revenue Trend Analysis  
- Correlation Heatmap  
- Customer Segmentation Scatter Plot  

---

## 👥 Customer Segmentation
Customers were categorized into:
- High Value Customers  
- Medium Value Customers  
- Low Value Customers  

Based on spending behavior and usage patterns.

---

## 🤖 Machine Learning Models
Two machine learning models were implemented:

- Logistic Regression  
- Random Forest Classifier  

---

## 📏 Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC Score  
- Confusion Matrix  

---

## ⚠️ Risk Analysis
Customers were classified into:

- High Risk  
- Medium Risk  
- Low Risk  

based on churn probability predicted by the Random Forest model.

---

## 📌 Results
The Random Forest model provided strong predictive performance and successfully identified customers likely to churn.

### Key Influencing Factors:
- Tenure  
- Contract Type  
- Monthly Charges  
- Total Charges  

---

## 🧠 Conclusion
This project demonstrates how machine learning can help telecom companies predict customer churn and improve retention strategies.

It enables:
- Identification of valuable customers  
- Early detection of churn risk  
- Data-driven business decisions  
