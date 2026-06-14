Risk Alert Classifier
Project Overview

The Risk Alert Classifier is a machine learning project developed to identify whether a customer is at high risk or low risk based on financial and behavioral attributes. The project covers the complete machine learning workflow including data preprocessing, handling missing values, class imbalance treatment, model building, hyperparameter tuning, and performance evaluation.

Objectives
Predict customer risk status using classification models.
Handle missing values using KNN Imputation.
Address class imbalance using sampling techniques.
Compare multiple machine learning models.
Select the best model based on business requirements.
Minimize false negatives in risk prediction.
Dataset Description

The dataset contains customer financial and behavioral information such as:

Customer ID
Age
Gender
Region
Employment Type
Annual Income
Credit Score
Credit Utilization Ratio
Missed Payments
Monthly Spending
Debt Balance
Account Tenure
Risk Status (Target Variable)
Target Variable

risk_status

0 = Low Risk
1 = High Risk
Project Workflow
1. Data Preprocessing
Loaded dataset using Pandas
Identified missing values
Applied KNN Imputer
Encoded categorical variables
2. Exploratory Data Analysis (EDA)
Dataset information
Summary statistics
Missing value analysis
Correlation analysis
Class distribution visualization
3. Baseline Model

Implemented:

Logistic Regression

Evaluation Metrics:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
4. Handling Imbalanced Data

Techniques Applied:

Random Under Sampling
Random Over Sampling
SMOTE
ADASYN
5. Tree-Based Models

Implemented:

Decision Tree Classifier
Random Forest Classifier

Compared models based on:

Accuracy
Recall
F1-Score
Generalization Performance
6. Hyperparameter Tuning

Applied:

Randomized Search CV
Grid Search CV

Optimized:

Decision Tree parameters
Random Forest parameters
7. Model Evaluation

Generated:

Confusion Matrix
ROC Curve
AUC-ROC Score
Performance Comparison Table
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Imbalanced-Learn
Installation
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
Running the Project
Open Jupyter Notebook.
Load the dataset.
Execute cells sequentially.
Train and evaluate models.
Compare results and select the best model.
Business Impact

The Risk Alert Classifier helps organizations identify potentially risky customers before making financial decisions. By reducing false negatives, businesses can minimize financial losses and improve risk management strategies.

Results

The best-performing model was selected based on:

Highest Recall
Strong F1-Score
High AUC-ROC
Ability to minimize False Negatives
Future Improvements
Feature Engineering
XGBoost and LightGBM Models
Real-Time Risk Prediction
Model Deployment using Flask or Streamlit
Author

Purvi Talaviya
