# Projet-Python-Machine-Learning-COVID-19-GLOBAL-FORECASTING-by-Kaggle 

Headline Description:
In this challenge, we will be predicting the number of confirmed COVID19 cases as well as the number of fatalities, for future dates.
All along the challenge we will be using currently updating Data Source that is composed of 3 main files which are : train.csv ,test.csv and submission.csv,
our last update was the 13th of may only because our dataset has changed.
This project is based on the Supervised Regression category (confirmed and fatalities cases).

IBM Master Plan as an Approach:
During the realization of our project we followed IBM Master Plane as Data Science MeTHODOLOGY And we focused especially on Data Understanding , Data Preparation and modeling steps.
Add to that, we interested in data visualisation using mainly Plotly as our visualize tool.
Data Preparation is a step in the data analysis process, in which data from one or more sources is cleaned, transformed and enriched to improve its quality prior to its use.

Data Modeling:
We used several methods including:

Ensemble methods: represent a machine learning technique that combines several base models in order to produce one optimal predictive model => XGBOOST, CART
XGBoost(Extreme Gradient Boosting) is a decision-tree-based ensemble Machine Learning algorithm that uses a gradient boosting framework. In prediction problems involving unstructured data
CART : Classification and Regression Trees or CART for short refers to Decision Tree algorithms that can be used for classification or regression predictive modeling problems which are an important type of algorithm for predictive modeling machine learning

Linear Family: For this type of model : "Ridge" to predict fatalities and cases, Ridge regression is an extension for linear regression.
It’s basically a regularized linear regression model. The λ parameter is a scalar that should be learned as well, using a method called cross validation. 
Ridge is used for : classification , Regularisation. The advantage of ridge : it can Reduce the model complexity and Reduce overfitting ridge it is a Better long term prediction.

SVM Family: Support vector machine is a machine learning model that it produces significant accuracy with less computation power. 
It is effective in high dimensional spaces. it tries to find hyper-plane that differentiates between the classes.
Support Vector Machine can also be used as a regression method the Support Vector Regression (SVR) uses the same principles as the SVM for classification.
