# Github-Portfolio
# Home Credit Default Risk – Machine Learning Project

## Table of Contents
- Overview
- Business Problem
- Our Solution
- My Contribution
- Model Performance
- Business Value
- Challenges
- What I Learned
- Repository Contents

---

## Overview

This project focuses on predicting whether a loan applicant will default using machine learning techniques.

The dataset comes from the Home Credit Default Risk Kaggle competition. The goal is to support better lending decisions by identifying high-risk borrowers.

---

## Business Problem

Financial institutions must decide whether to approve or reject loan applications.

- Approving risky applicants leads to financial losses  
- Rejecting too many applicants reduces potential revenue  

This project aims to build a model that predicts default risk and improves decision-making.

---

## Our Solution

Our team developed a machine learning pipeline:

- Data cleaning and preprocessing  
- Feature selection  
- Model training and evaluation  

We tested multiple models:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

We used AUC as the primary evaluation metric due to class imbalance.

---

## My Contribution

This repository contains my individual work.

My responsibilities included:

- Cleaning and preparing the dataset  
- Handling missing values  
- Selecting numerical features  
- Building a Logistic Regression model  
- Splitting data into training and validation sets  
- Evaluating performance using AUC, precision, and recall  
- Creating a model card with SHAP explanations  
- Writing and organizing the notebook  

---

## Model Performance

- AUC: ~0.63  
- Precision: 0.20  
- Recall: 0.064  

### Kaggle Score

Kaggle Public Score: ~0.63  

This indicates moderate predictive performance.

---

## Business Value

This model helps lenders:

- Identify high-risk applicants  
- Reduce loan default losses  
- Improve approval decision-making  

Even a moderately accurate model can significantly improve financial outcomes.

---

## Challenges

During the project, we encountered:

- Imbalanced dataset (~8% default rate)  
- Large number of missing values  
- Limited time for feature engineering  
- Difficulty improving model performance  

---

## What I Learned

Through this project, I learned:

- How to build a full machine learning pipeline  
- Importance of AUC for imbalanced classification  
- How to evaluate model performance  
- Basics of model interpretability (SHAP)  
- How to present a data science project professionally  

---

## Repository Contents

- modeling.ipynb – modeling workflow  
- model_card.ipynb – model explanation  
- README.md – project summary  

---

## Conclusion

This project demonstrates a complete data science workflow from data preprocessing to model evaluation.

Future improvements:

- Advanced feature engineering  
- Use of XGBoost or LightGBM  
- Better handling of class imbalance  
