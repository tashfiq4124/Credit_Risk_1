This project involves the analysis and modeling of credit risk using the German Credit Data dataset. The primary goal is to explore the dataset to understand the factors affecting creditworthiness and to build a machine learning model capable of classifying credit risk as either "Good" or "Bad. 
Dataset: 
The project uses the german_credit_data.csv file. It includes user-uploaded financial and demographic information with the following key features:
Demographics: Age, Sex, Job.
Financial Status: Saving accounts, Checking account, Credit amount, Housing status.
Loan Details: Duration of the loan, Purpose (e.g., car, education, radio/TV).
Target Variable: Risk (Classified as "good" or "bad").
Technologies Used
Python 3
Data Manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: xgboost (XGBoost Classifier)
Model Serialization: joblib
Project Workflow
Data Loading & Inspection:
Loaded the dataset using Pandas.
Performed initial inspection using .info(), .describe(), and .head() to understand data types and distributions.
Checked for class imbalance in the Risk column (700 Good vs. 300 Bad).
Exploratory Data Analysis (EDA):
Visualized distributions and relationships between features using Seaborn and Matplotlib.
Model Training:
Implemented an XGBoost Classifier to predict credit risk.
Tuned hyperparameters (e.g., learning_rate, max_depth, n_estimators).
Evaluation & Saving:
Achieved an accuracy of approximately 61.9% with the XGBoost model.
Saved the best-performing model to xgb_credit_model.pkl for future use
