📊 Customer Retention & Churn Analysis

📌 Project Overview

Customer churn is one of the biggest revenue risks in subscription-based businesses.
This project performs an end-to-end churn analysis to identify key drivers of customer attrition and propose actionable retention strategies.
The goal is to move beyond basic visualization and deliver business-focused insights backed by machine learning.

🎯 Business Objectives
Measure overall churn rate
Identify high-risk customer segments
Analyze lifecycle churn patterns
Quantify revenue impact
Determine top drivers of churn
Provide strategic recommendations

📂 Dataset
Telco Customer Churn Dataset (Kaggle)
7,043 customer records
21 features including demographics, contract type, services, billing information
Target variable: Churn

🧹 Data Preparation
Converted TotalCharges to numeric
Removed missing values
Encoded categorical variables
Performed segmentation analysis

📊 Key Insights
Overall churn rate: 26.6%
Month-to-month customers show highest churn risk (42.7%)
First-year customers have nearly 48% churn probability
High MonthlyCharges significantly increase churn likelihood
Long-term contracts drastically reduce churn

💰 Revenue Impact
Estimated monthly revenue lost due to churn: ~$139K
Estimated annual revenue impact: ~$1.67M
Even a small reduction in churn could recover significant recurring revenue.

🤖 Machine Learning Model
Model Used: Random Forest Classifier
Accuracy: 78%
Identified top churn drivers:
TotalCharges
MonthlyCharges
Tenure
Contract Type
OnlineSecurity

📈 Business Recommendations
Incentivize long-term contracts
Improve onboarding during first 12 months
Bundle OnlineSecurity and TechSupport
Implement targeted retention strategies for high-bill customers

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib & Seaborn
Scikit-learn
Jupyter Notebook / Kaggle

🚀 Project Outcome
This project demonstrates how churn analytics can directly support:
Revenue protection
Customer lifecycle optimization
Data-driven strategic decision making
