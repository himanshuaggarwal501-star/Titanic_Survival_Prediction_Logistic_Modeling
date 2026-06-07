# Titanic Survival Prediction using Logistic Regression

##  Project Overview
This project focuses on predicting passenger survival on the Titanic dataset using Logistic Regression.  
The objective is to build an interpretable classification model using statistical modeling techniques and evaluate its predictive performance.

##  Dataset
The dataset contains passenger information such as:
- Passenger Class
- Gender
- Age
- Family Details
- Fare
- Embarkation Port

Target Variable:
- Survived (0 = Not Survived, 1 = Survived)


##  Data Preprocessing
Performed:
- Missing Value Treatment
- Outlier Treatment
- Feature Engineering
- Age Binning
- Categorical Encoding using Dummy Variables


##  Model Building
Implemented Logistic Regression using Statsmodels.

Feature selection was performed using:
- p-value based Backward Elimination
- AIC comparison for model selection
- Variance Inflation Factor (VIF) for multicollinearity detection


##  Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Somers' D


##  Model Performance

- Accuracy: 79%
- ROC-AUC Score: 0.84
- Somers' D: 0.68


##  Technologies Used

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Matplotlib


##  Key Learning

This project helped in understanding:
- Logistic Regression implementation
- Statistical feature selection
- Model interpretation
- Classification model evaluation
