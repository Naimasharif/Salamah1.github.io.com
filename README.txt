This project analyzes breast cancer data using machine learning to predict tumor malignancy. It includes data preprocessing, exploratory analysis, and model evaluation. Key features like tumor radius and texture are used for classification. Built with Python, pandas, and scikit-learn. 
The goal of this project is to build a machine learning model that can accurately classify whether a tumor is benign or malignant based on the features in the dataset.
We analyzed this project in a pandas frame work,we did some data analysis like data cleaning and preprocessing. From our analysis, we found no missing values in the dataset,we also used Logistic Regression algorithm to predict our model,the model's accuracy is 95%.
Dataset Overview
•	Source: Kaggle Machine Learning Repository
•	Total Instances: 569
•	Total Features: 32 (including ID and diagnosis)
•	Target Variable: Diagnosis (Benign = B, Malignant = M)
Feature Selection
•	Removed highly correlated features to avoid multicollinearity and improve model interpretability.
•	Selected important features based on correlation matrix and domain knowledge.
