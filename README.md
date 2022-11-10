# Unsupervised Machine Learning - Predicting Myopia

## Background
While working on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness, I was tasked with exploring the possibility of identifying distince patient grouping.

## Overview
Raw data was standardized and processed to fit the machine learning models. Dataset reduction with PCA and t-SNE was conducted. The resulting information was used to create dataframes, bar chart, scatter plot, and line chart of the resulting clusters.


## Observations:
1. After applying Dimensionality Reduction with PCA, it appears the first 3 features would explain the variance in the dataset
2. When the dataset was further reducted with t-SNE, it appeared to 5 distinct clusters in the scatter plot.
2. With the K-Means chart, it can be seen that after the third cluster the change in the value of ineratia is no longer significant; k = 3.

## Recommendation: 
Based on the assessment conducted, the data appears to have distinct groups of patients that would be better to analyze separately which is better seen with the t-SNE and K-Means chart.


## Files and Folders included:
* Jupyter Notebook 
  * Predict Myopia.ipynb
  
* Resources folder
  * myopia.csv