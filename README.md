# Improving Term Deposit Subscription Rates through Data-Driven Customer Segmentation

## Overview
This project analyzes a real-world bank telemarketing dataset to identify high-performing customer segments, optimal campaign timing, and actionable strategies to improve term deposit subscription rates. The analysis combines exploratory data analysis, customer segmentation, and predictive modeling to generate business-focused insights.

This project was completed as part of the Business Data Management (BDM) Capstone under the IIT Madras Data Science program.

---

## Business Problem
Banks invest heavily in outbound telemarketing campaigns, yet conversion rates remain low due to poor targeting, inefficient call strategies, and lack of timing optimization.

**Objective:**  
Identify who to target, when to target, and how to optimize outreach to maximize subscription conversions.

---

## Dataset
- Source: UCI Bank Marketing Dataset (balanced version from Kaggle)
- Records: 11,162 customers
- Features include:
  - Demographics (age, job, education, marital status)
  - Financial attributes (balance, loans, credit default)
  - Campaign variables (call duration, contact type, month, previous outcomes)
- Target variable: Term deposit subscription (yes/no)

---

## Approach
1. Data Cleaning and Preparation  
   - Encoded categorical variables using label and one-hot encoding  
   - Retained "unknown" values as informative categories  
   - Engineered features such as age groups, call duration buckets, and campaign quarters  

2. Exploratory Data Analysis (EDA)  
   - Segment-wise conversion analysis  
   - Behavioral analysis across call duration, contact type, and financial burden  
   - Temporal analysis of monthly and quarterly performance  

3. Customer Segmentation  
   - Rule-based segmentation combining demographic and behavioral attributes  
   - Identification of high- and low-performing customer profiles  

4. Predictive Modeling  
   - Logistic Regression for feature influence and interpretability  
   - Decision Tree classification to extract actionable business rules  

---

## Key Insights
- High-conversion segments include customers aged 60+, students, retired individuals, and customers with previous campaign success  
- Longer call durations significantly increase conversion probability  
- Cellular contact performs better than landline calls  
- Customers aged 30–44 underperform due to higher financial liabilities  
- March, September, October, and December show the highest conversion rates  

---

## Business Impact
The insights from this analysis can help banks:
- Prioritize high-return customer segments  
- Optimize campaign timing and resource allocation  
- Design segment-specific messaging strategies  
- Reduce wasted outreach and improve telemarketing ROI  

---

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Data Visualization (Matplotlib, Seaborn)
- Statistical Analysis
- Machine Learning (Logistic Regression, Decision Trees)

---

## Author
Saloni Singh  
IIT Madras – Data Science  
Former Manager, State Bank of India  

Focus areas: Applied analytics, financial domain insights, and business-driven data science
