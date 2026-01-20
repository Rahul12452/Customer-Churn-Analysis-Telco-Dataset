# 📉 Customer Churn Analysis – Telco Dataset

📊 **End-to-end Exploratory Data Analysis (EDA) project** focused on understanding customer churn behavior in the telecom industry.  
🚀 Built using **Python, Pandas, NumPy, Matplotlib, and Seaborn** to uncover key churn drivers and generate actionable business insights.

---

## 🚀 Project Overview

This project performs a comprehensive analysis of the **Telco Customer Churn dataset** to identify patterns and factors influencing customer attrition.  
The workflow includes **data cleaning, feature engineering, univariate & bivariate analysis, correlation analysis, and visualization**.  
**Goal:** Help businesses proactively reduce churn by understanding high-risk customer segments.

---

## 🎯 Objectives

- Analyze customer behavior and service usage patterns  
- Identify key factors contributing to customer churn  
- Compare churned vs non-churned customer characteristics  
- Provide insights to improve customer retention strategies  
- Build a strong foundation for future predictive modeling  

---

## 📊 Dataset Overview

- **Source:** Telco Customer Churn Dataset  
- **Total Records:** 7,043 customers  
- **Features:** 21 (Demographics, Services, Billing, Contract, Charges)  
- **Target Variable:** `Churn` (Yes / No)  

---

## 🔍 Scope of Analysis

- Data loading & inspection  
- Missing value detection and handling  
- Feature engineering (Tenure grouping)  
- Feature reduction & encoding  
- Univariate & bivariate analysis  
- Churn distribution & imbalance analysis  
- Relationship between charges and churn  
- Correlation analysis with target variable  

---

## 🔧 Tools & Technologies

- **Python** → Core programming language  
- **Pandas & NumPy** → Data manipulation & analysis  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis environment  
- **Statistics module** → Descriptive analytics  

---

## 🛠 Key Data Processing Steps

### 📌 Data Cleaning
- Converted `TotalCharges` from object to numeric  
- Handled missing values using coercion and row filtering  
- Verified data types and null values  

### 📌 Feature Engineering
- Created **Tenure Groups** to analyze customer lifecycle behavior  
- Removed redundant features (`customerID`, original tenure)  

### 📌 Encoding
- Converted target variable (`Churn`) to binary format  
- Applied **One-Hot Encoding** to categorical features  

---

## 📈 Key Visual Analyses

- Churn distribution & class imbalance  
- Monthly charges vs churn (KDE plots)  
- Total charges vs churn  
- Correlation of predictors with churn  
- Contract type & tenure impact on churn  
- Payment method & service-based churn analysis  

---

## 📉 Major Insights

- Customers on **month-to-month contracts** show the highest churn  
- **Short tenure customers (1–12 months)** are more likely to churn  
- Higher **monthly charges** are associated with increased churn risk  
- Customers using **electronic check payment** churn more frequently  
- Lack of **online security and tech support services** increases churn  
- Demographic features have less impact compared to behavioral factors  

---

## 📌 Recommendations

- Encourage customers to switch to **long-term contracts**  
- Offer loyalty incentives for **early-tenure customers**  
- Optimize pricing plans for high monthly charge segments  
- Promote value-added services (Tech Support, Online Security)  
- Target high-risk customers with proactive retention campaigns  

---

## 🚀 Outcomes

- Delivered a complete **EDA pipeline for churn analysis**  
- Generated clear business insights from customer behavior  
- Identified strong churn predictors for modeling readiness  
- Established a solid base for **machine learning churn prediction models**  

---

## 📂 Repository Structure (Suggested)

