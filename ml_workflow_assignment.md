\# **ML Workflow Assignment**



\## **Task 1 — Label \& Data Leakage Identification**



\### **Label Column**

\- \*\*repeat\_purchase\_flag\*\*



\*\***Justification**:\*\*  

This column represents the target outcome (whether the customer makes a repeat purchase within 30 days), which the model is trying to predict.



\---



\### **Data Leakage Column**

\- \*\*discount\_used\_on\_repeat\_order\*\*



\*\***Justification:**\*\*  

This feature is only known \*after\* the repeat purchase happens, so including it would leak future information and artificially inflate model performance.



\---



\## **Task 2 — Missing Steps in ML Workflow**



\### **1. Data Exploration \& Validation (EDA)**



\*\*Why it matters:\*\*  

Before training any model, it is important to understand the dataset, check for missing values, detect outliers, and ensure data quality. Poor data leads to unreliable models.



\---



\### **2. Establishing a Baseline Model**



\*\*Why it matters:\*\*  

A simple baseline (e.g., logistic regression or majority class prediction) helps measure whether the complex model (like gradient boosting) actually improves performance.



