# Prasunet_DS_03
# Task-03
# Bank Marketing

Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

## AIM
Build Decision Tree Classifier to predict the outcomes using the dataset

## Features of data
1. age (numeric)
2. job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student","blue-collar","self-employed","retired","technician","services")
3. marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
4. education (categorical: "unknown","secondary","primary","tertiary")
5. default: has credit in default? (binary: "yes","no")
6. balance: average yearly balance, in euros (numeric)
7. housing: has housing loan? (binary: "yes","no")
8. loan: has personal loan? (binary: "yes","no")
9. contact: contact communication type (categorical: "unknown","telephone","cellular")
10. day: last contact day of the month (numeric)
11. month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
12. duration: last contact duration, in seconds (numeric)
13. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
14. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
15. previous: number of contacts performed before this campaign and for this client (numeric)
16. poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
17. y : has the client subscribed a term deposit? (binary: "yes","no") (desired target)

## Libraries used
- `numpy` : Numerical computation
- `pandas` : Data manipulation and analysis
-  `matplotlib.pyplot` : Plotting library for static and interactive visualizations
-  `train_test_split` : Splits the data into train and test dataset
-  `StandardScaler` : Standardize features by removing the mean and scaling to unit variance
-  `DecisionTreeClassifier` : Creates a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.
-  `accuracy_score` : Computes subset accuracy i.e. the set of labels predicted for a sample must exactly match the corresponding set of labels in true sample.
-  `classification_report` : Build a text report showing the main classification metrics.

## Conclusion
This project offers insights of the prediction model of customers for the campaign. Using `DecisionTreeClassifier`, we get a testing accuracy score of 84.9% for the given dataset.
