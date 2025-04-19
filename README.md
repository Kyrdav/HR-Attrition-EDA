# HR Attrition EDA
A Jupyter Notebook–based exploratory data analysis (EDA) and baseline modeling project for the IBM HR Analytics Employee Attrition & Performance dataset.
---
Overview

This repository hosts a self‑contained Jupyter Notebook that walks through:

1. **Data Loading & Structure Inspection**  
2. **Univariate & Bivariate EDA**  
3. **Data Cleaning & Feature Engineering**  
4. **Baseline Modeling with Logistic Regression**  
5. **Threshold Selection via Precision–Recall**  
6. **Feature Importance Analysis**    
7. **Satisfaction‑Score Comparison by Attrition**

All steps are fully documented with code, visualizations, and markdown explanations.
---
Dataset
- **Source**: Kaggle “IBM HR Analytics Employee Attrition & Performance”  
- **Download**: https://www.kaggle.com/datasets/pavansubhash/ibm-hr-analytics-employee-attrition-performance  
- **Filename**: `WA_Fn-UseC_-HR-Employee-Attrition.cs

- Key Results
Class Balance: Attrition class heavily imbalanced (~16% “Yes”).
Baseline ROC‑AUC: ~0.83 with tuned logistic regression (C=10, L2).
Precision–Recall: AP ≈ 0.59; optimal F1 threshold ≈ 0.26 (F1 ≈ 0.56).
Top Predictors: Roles (Sales Rep, Lab Tech), Overtime, Business Travel, Education field.
Satisfaction Differences: Leavers report significantly lower job, environment, relationship, and work‑life satisfaction.
