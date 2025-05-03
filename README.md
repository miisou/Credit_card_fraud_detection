# Credit Card Fraud Detection

Main goal of this project is to select and analyze features that can detect fraud card operations, build a binary classification model with highly unbalanced classes,

## Project content

This project additionaly involves:
+ Exploratory Data Analysis
+ Feature engineering
+ Analyzing outliners and their impact on dataset
+ Detecting anomalies in distributions of features
+ Building a desicion tree model
+ Analyzing leaves of the tree model and explaining result

Most of individual decisions are provided with explanations and comments.

## Dataset
This project was based on this dataset with high usability that is claimed to be soursed by some unknown institute https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud/data. 

## Libraries
+ numpy
+ matplotlib
+ pandas
+ seaborn
+ scikit-learn

## Key Findings

+ all numeric features in this dataset have distribution that is different from usual operations distribution. Moreover, all numeric features have exact numbers, starting from which distribution of fraud operations changes immediately.
+ Decision Tree Model with depth of 10 can achieve almost perfect score without overfitting.
+ Outliners account for 80% of all fraud transactions.
+ 99.6% of fraud transactions were commited not using pin
+ 95% of fraud transactions are made online.
