Social Media Advertising Analysis Using Machine Learning
Overview
This project analyzes social media advertising campaigns using machine learning to predict user engagement (ad clicks). By leveraging various classification algorithms, we identify key factors influencing ad performance, helping to optimize targeted marketing strategies.

Problem Statement
The goal of this project is to predict whether a user will click on an ad based on demographic and behavioral data. By analyzing patterns in the dataset, we aim to improve ad targeting, reduce costs, and increase ROI for social media marketing campaigns.

Dataset
The dataset contains user attributes such as:

Age
Gender
Estimated Salary
Ad Type
Time Spent on Platform
Clicked on Ad (Target Variable: 0 or 1)
Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Machine Learning Models: Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, Support Vector Machine (SVM), Naive Bayes
Project Workflow
Exploratory Data Analysis (EDA):

Data cleaning, missing value handling, and visualization.
Feature correlation analysis using heatmaps and scatter plots.
Data Preprocessing & Feature Engineering:

Encoding categorical features using One-Hot Encoding.
Feature scaling using StandardScaler.
Splitting data into training (70%) and testing (30%) sets.
Model Training:

Implemented multiple classification models.
Applied hyperparameter tuning (GridSearchCV) for optimization.
Model Evaluation:

Used Accuracy, Precision, Recall, F1-score, and ROC-AUC to compare models.
Identified the best-performing model (Random Forest).
Results & Insights
Random Forest outperformed other models with high accuracy and balanced precision-recall.
Feature importance analysis showed that certain age groups and ad types significantly influenced engagement.
Actionable insights helped optimize ad targeting, reducing ad spend while improving engagement rates.
