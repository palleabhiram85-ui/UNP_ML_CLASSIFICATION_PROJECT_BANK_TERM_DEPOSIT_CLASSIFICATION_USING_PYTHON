# UNP_ML_CLASSIFICATION_PROJECT_BANK_TERM_DEPOSIT_CLASSIFICATION_USING_PYTHON


This project was completed as part of the United Network of Professionals (UNP) Machine Learning using python Academic Internship Program , and it was executed as a collaborative group project.

The project focuses on predicting customer subscription to term deposits in a direct marketing campaign of a Portuguese banking institution using machine learning and deep learning. It aims to analyze how customer demographics, financial profiles, and campaign contact attributes influence binary subscription outcomes (0 for No, 1 for Yes).

Project Overview

Analyzed a dataset containing 45,211 records and 17 attributes related to bank direct marketing campaigns.
Conducted exploratory data analysis (EDA) using box plots for outlier detection across numerical features (balance, duration, campaign, pdays, previous), count plots for categorical distributions and target class imbalance, and pie charts for proportional breakdowns.
Performed structural inspection and missing-value diagnostics to verify data completeness.
Applied data preprocessing and feature engineering, including dropping non-generalizable temporal features (day, month), converting sentinel values (-1 to 0) in pdays, and binning 12 granular job categories into three income-aligned tiers (High, Medium, Low).
Encoded binary attributes (default, housing, loan, y) into numerical format and applied one-hot dummy encoding (drop_first=True) to multi-class categorical features to prevent multicollinearity.
Machine Learning Implementation

Applied Variance Inflation Factor (VIF) analysis to evaluate multicollinearity among predictors and used StandardScaler with train-test splitting to prepare the data for modeling.
Developed binary classification models using Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Classification (SVC).
Implemented tree-based and ensemble classification algorithms, including Decision Tree, Random Forest, AdaBoost, Gradient Boosting, and XGBoost.
Built an end-to-end deep learning pipeline using TensorFlow to predict term deposit subscriptions.
Model Evaluation

Assessed predictive performance using classification evaluation metrics including Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
Generated confusion matrices and detailed classification reports to compare algorithm effectiveness across imbalanced target classes. Project Outcome
The project provided hands-on experience in end-to-end data preprocessing, exploratory data analysis, feature engineering, multicollinearity diagnostics, ensemble classification modeling, and deep learning with TensorFlow. It demonstrates how supervised machine learning and neural networks can be applied to banking datasets to predict customer behavior and support targeted marketing strategies.

Google collab link :https://drive.google.com/file/d/1QSzgkz19iSKFgcIvFXocboTpE3kiDNL1/view?usp=sharing
Presentation Link : https://docs.google.com/presentation/d/1SyPyuFPWmk3kO_l4KP-wfZZ-urcswUQX/edit?usp=sharing&ouid=102073202992785711567&rtpof=true&sd=true
