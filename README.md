# Insurance_cost_prediction
This project demonstrates how to use Support Vector Regression (SVR) to predict medical insurance costs based on various customer features such as age, BMI, smoking habits, and more. The dataset used is a popular insurance dataset available on Kaggle.

Project Overview
Medical insurance pricing can be affected by many personal and demographic factors. In this project, we use SVR to model the relationship between these factors and insurance charges, aiming to predict the cost for new customers.

Dataset
The dataset is available here on Kaggle.

Features:
age: Age of primary beneficiary

sex: Gender

bmi: Body mass index

children: Number of children covered by health insurance

smoker: Whether the person smokes

region: Residential area in the US

charges: Individual medical costs billed by health insurance (Target)

Model: Support Vector Regression (SVR)
We use SVR from Scikit-learn with RBF kernel to capture non-linear patterns in the data.

Workflow Summary
Data Loading & Exploration
Load the dataset, check missing values, and visualize correlations.

Preprocessing

Encode categorical features (sex, smoker, region)

Feature scaling using StandardScaler

Model Training

Use SVR

Prediction
Predict insurance costs for test data or new user inputs.

Key Learnings
How to apply Support Vector Regression to a real-world regression task

Importance of feature scaling in SVR

Handling categorical variables and evaluating regression performance

References
Scikit-learn Documentation - SVR

Kaggle Dataset: Medical Cost Personal Datasets

 Author
Arunima Upreti
Feel free to connect on LinkedIn or check out the GitHub repository.

