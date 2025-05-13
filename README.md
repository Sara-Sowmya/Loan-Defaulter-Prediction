Loan Default Prediction Using Machine Learning
Project Overview
This project aims to predict whether a loan will be repaid or defaulted based on an applicant's financial and personal data using machine learning algorithms. The objective is to create a predictive model that can assist in loan decision-making, allowing financial institutions to assess the default risk for each loan applicant.

Algorithms Used
Logistic Regression: A simple linear classification model used for predicting binary outcomes (loan repaid or defaulted).

Random Forest: An ensemble learning method that uses multiple decision trees to predict the loan default status.

XGBoost: An optimized gradient boosting method that performs well in classification tasks, providing high accuracy with fast training.

Features
The model predicts the loan default risk based on the following features:

Requested Loan Amount (₹): Amount the applicant requests to borrow.

Annual Income (₹): Applicant’s yearly income.

Applicant Age (Years): Age of the loan applicant.

Work Experience (Years): Professional experience in years.

Years in Current Employment (Years): Duration at the current job.

Years in Current Residence (Years): Duration at the current residence.

Marital Status (Single): Whether the applicant is single.

Home Ownership (Owned): Whether the applicant owns their home.

Data Preprocessing
Data Cleaning: The dataset has been cleaned, with missing values handled and irrelevant features removed.

Feature Encoding: Categorical variables such as marital status and home ownership have been converted into binary format.

Class Balancing: The dataset was imbalanced, so we applied oversampling (using SMOTE) to balance the classes.

Model Training
1. Logistic Regression
A simple binary classification model was trained to predict whether a loan will default (1) or be repaid (0).

2. Random Forest
A Random Forest Classifier was used to improve the model’s performance by combining multiple decision trees to predict loan outcomes.

3. XGBoost
XGBoost was applied to further improve accuracy, by using an ensemble of weak models (trees) and gradient boosting techniques to correct errors made by earlier models.

Evaluation Metrics
The model’s performance was evaluated using the following metrics:

Accuracy: The proportion of correctly predicted instances (either repaid or defaulted).

Confusion Matrix: Shows the true positives, false positives, true negatives, and false negatives.

Precision, Recall, and F1-Score: These metrics were used to evaluate the model’s performance, especially for the minority class (loan defaults).

ROC Curve: Used to assess the true positive rate versus the false positive rate.
