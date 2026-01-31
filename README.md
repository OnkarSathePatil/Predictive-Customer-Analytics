# Predictive-Customer-Analytics
End-to-end predictive customer analytics project focusing on churn prediction, RFM-based segmentation, and customer lifetime value (CLV) estimation using machine learning.

# Predictive Customer Analytics  
### Customer Churn Prediction, RFM Segmentation & Customer Lifetime Value (CLV)

## Project Overview
This project presents a complete **end-to-end predictive customer analytics solution** focused on understanding customer behavior, segmenting customers based on engagement, predicting churn risk, and estimating customer lifetime value (CLV).  

The analysis is conducted using real-world customer data from the telecommunications domain and applies data science and machine learning techniques to support **data-driven marketing and retention decisions**.

The project is developed as part of **WiDS 2025** and follows an analytics-first approach rather than production deployment.

---

## Business Problem
Customer churn poses a significant challenge for subscription-based businesses, where acquiring new customers is often more expensive than retaining existing ones.  

The key questions addressed in this project are:
- Which customers are most likely to churn?
- Which customers contribute the highest long-term value?
- How can customer behavior be segmented for targeted retention strategies?
- How can churn risk and CLV be combined to guide business decisions?

---

## Dataset
- **Dataset Name:** Telco Customer Churn Dataset  
- **Source:** IBM Sample Dataset  
- **File:** `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`

### Dataset Characteristics
- 7,043 customer records  
- Demographic information (gender, senior citizen, dependents)  
- Service subscriptions (internet, phone, add-on services)  
- Account and billing details (tenure, contract type, charges)  
- Churn indicator (Yes / No)

---

## Project Workflow
The project follows a structured analytics pipeline:

1. **Data Loading & Cleaning**
   - Handling missing values
   - Converting data types
   - Removing non-informative identifiers
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Univariate analysis (distributions, class imbalance)
   - Bivariate analysis (contract type vs churn, tenure vs churn)
   - Identification of churn drivers

3. **Feature Engineering**
   - Creation of behavioral and financial features
   - Preparation of modeling-ready datasets

4. **RFM-Based Customer Segmentation**
   - Recency, Frequency, Monetary (RFM) analysis
   - Quantile-based scoring
   - Behavioral customer grouping

5. **Customer Lifetime Value (CLV) Calculation**
   - Baseline CLV estimation
   - Strategic interpretation of CLV across segments

6. **Churn Prediction Modeling**
   - Logistic Regression (baseline, interpretable)
   - Random Forest (non-linear, robust)
   - Model evaluation using Accuracy, Precision, Recall, and F1-score

7. **Business Insights & Recommendations**
   - Combining churn probability and CLV
   - Retention prioritization strategies
   - Actionable marketing recommendations

---

## Models Implemented
- **Logistic Regression**
  - Interpretable baseline model
  - Helps understand feature impact on churn

- **Random Forest**
  - Captures non-linear interactions
  - Improves robustness and predictive performance

---

## Key Results
- Month-to-month contracts show the highest churn risk  
- Churn probability decreases significantly with increasing tenure  
- RFM segmentation effectively identifies high-value and at-risk customers  
- Combining churn probability with CLV enables smarter retention prioritization  

---



