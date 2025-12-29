# Business-Data-Management-Project
Improving Term Deposit Subscription Rates through Data-Driven Customer Segmentation and Campaign Optimization. 

Overview
This project analyzes a real-world bank telemarketing campaign dataset to identify high-performing customer segments, optimal campaign timing, and actionable strategies to improve term deposit subscription rates. The analysis combines exploratory data analysis, customer segmentation, and predictive modeling to generate business-focused insights.
This project was completed as part of the Business Data Management (BDM) Capstone under the IIT Madras Data Science program. 
FINAL SUBMISSION BDM SALONI SIN…
Business Problem
Banks invest heavily in outbound telemarketing campaigns, yet conversion rates remain low due to:
Poor customer targeting
Inefficient call strategies
Lack of timing and segment-level optimization
Objective:
Identify who to target, when to target, and how to optimize outreach to maximize subscription conversions.
Dataset
Source: UCI Bank Marketing Dataset (balanced version from Kaggle)
Records: 11,162 customers
Features: 17 variables including:
Demographics (age, job, education, marital status)
Financial attributes (balance, loans, defaults)
Campaign data (call duration, contact type, month, previous outcomes)
Target variable: Term deposit subscription (yes/no)
Approach
Data Cleaning & Preparation
Handled categorical variables using label and one-hot encoding
Retained “unknown” values as informative categories
Engineered features such as:
Age groups
Call duration buckets
Quarterly campaign timing
Exploratory Data Analysis (EDA)
Segment-wise conversion analysis
Behavioral patterns across call duration, contact type, and financial burden
Temporal analysis of monthly and quarterly performance
Customer Segmentation
Rule-based segmentation combining demographic and behavioral attributes
Identification of high- and low-performing customer profiles
Predictive Modeling
Logistic Regression for feature influence and interpretability
Decision Tree Classifier to extract actionable business rules
Key Insights
High-conversion segments:
Customers aged 60+
Students and retired individuals
Customers with prior positive campaign outcomes
Behavioral drivers:
Longer call durations significantly increase conversion probability
Cellular contact outperforms landline calls
Underperforming segments:
Customers aged 30–44, largely due to higher housing and personal loan burdens
Timing matters:
March, September, October, and December show the highest conversion rates
High-volume months like May show poor efficiency
Business Impact
The findings enable banks to:
Prioritize high-return customer segments
Optimize campaign timing and resource allocation
Design segment-specific messaging strategies
Reduce wasted outreach and improve telemarketing ROI
The approach is directly applicable to CRM-driven campaign planning and performance monitoring.
Tools & Technologies
Python (Pandas, NumPy, Scikit-learn)
Data Visualization (Matplotlib, Seaborn)
Statistical Analysis
Machine Learning (Logistic Regression, Decision Trees)
Author
Saloni Singh
IIT Madras – Data Science
Former Manager, State Bank of India
Focus: Applied analytics, financial domain insights, and business-driven data science
