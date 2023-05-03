# Predicting Falcon Stage 1 Landing Succesfully
Capstone project for [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science)

## Introduction
SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars.
Other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.
Our goal is to predict if the first stage will land successfully, for an imaginary company who wants to bid against SpaceX.

## Methodology
### 1. Data collection:
  - Using SpaceX Rest API
  - Web Scraping from Wikipedia
  ### 2. Data Wrangling:
  - Cleaning the Data
  - Dealing with Missing Data
  - Standard Scaling
  - One-Hot Encoding
  - Feature Selection and Engineering
  ### 3. Exploratory Data Analysis using Visualization and SQL
  ### 4. Interactive Visual Analysis and Dashboard using Folium and Plotly Dash
  ### 5. Predictive Analysis with Classification
  - With Logistic Regression, KNN Classifier, Support Vector Classifier, and Decision Tree Classifier
  - Model Selection and Hyperparameter Tuning with GridSearch and Cross Validation

## Error Metric
Classification Accuracy defined as:
$$Accuracy = \frac{TP+TN}{TP+FP+TN+FN}$$
![Confusion Matrix](https://github.com/DenizK00/Predicting-Falcon-Stage-1-Landing-Succesfully/blob/f75215381cd7ac751c6879a8021fb758db06848a/confusion-matrix.png)



