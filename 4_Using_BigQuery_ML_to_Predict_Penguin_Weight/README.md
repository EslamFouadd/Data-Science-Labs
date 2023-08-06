# Using BigQuery ML to Predict Penguin Weight

In this lab, you will learn to create and execute machine learning models in BigQuery using SQL queries.
![img](https://cdn.analyticsvidhya.com/wp-content/uploads/2023/01/bq3.jpg)

# Overview
Penguin Table:
![img](https://cloud.google.com/static/bigquery/images/predict-penguins-insta-model.png)
https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=ml_datasets&t=penguins&page=table&_ga=2.220042073.1354982557.1633082321-1341342707.1620127293&project=avid-lacing-355813

In this lab, you use the penguin table to create a model that predicts the weight of a penguin based on the penguin's species, island of residence, culmen length and depth, flipper length, and sex.

This lab introduces data analysts to BigQuery ML. BigQuery ML enables users to create and execute machine learning models in BigQuery using SQL queries. The goal is to democratize machine learning by enabling SQL practitioners to build models using their existing tools and to increase development speed by eliminating the need for data movement.

# Learning objectives
Create a linear regression model using the CREATE MODEL statement with BigQuery ML.

Evaluate the ML model with the ML.EVALUATE function.

Make predictions using the ML model with the ML.PREDICT function.

