This repository contains three machine learning projects demonstrating practical applications of supervised learning in healthcare and real estate.
Each notebook covers the complete workflow from data preprocessing and exploratory analysis to model training, evaluation, and visualization.



 Projects Included:


 
1. Breast Cancer Classification

Objective: Predict whether a tumor is malignant or benign.

Techniques: Random Forest Classifier (can be extended to Logistic Regression or SVM).

Highlights:

Data cleaned and preprocessed with appropriate encoding.

Features scaled for better model performance.

Includes confusion matrix, classification report, and feature importance visualization.

Performance: Accuracy ~96%, with high precision and recall.




2. Diabetes Prediction

Objective: Predict the likelihood of diabetes based on patient health indicators.

Techniques: Random Forest Classifier with SMOTE for handling class imbalance.

Highlights:

Categorical features encoded, numerical features scaled.

Model threshold adjusted for better recall on diabetic patients.

ROC curve visualization included.

Performance: Accuracy ~93%, with strong recall for positive cases.






3. House Price Prediction

Objective: Predict house prices based on multiple features.

Techniques: Ridge Regression with polynomial features and hyperparameter tuning via GridSearchCV.

Highlights:

Log-transformed target variable to reduce skewness.

One-hot encoding for categorical variables.

Pipeline ensures reproducibility of preprocessing and modeling steps.

Performance: R² ~0.07 — serves as a baseline model; performance can be improved using ensemble models like Random Forest or XGBoost.






Features



Fully documented Jupyter Notebooks.

Exploratory data analysis (EDA) included.

Step-by-step demonstration of data preprocessing → model training → evaluation → visualization.

Comparison of multiple models (where applicable) to illustrate performance differences.
