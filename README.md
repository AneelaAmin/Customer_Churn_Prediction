# Customer_Churn_Prediction
Linear Associator, LeakyReLU, BAM 


# Churn Prediction Project

## Overview
This project implements three different neural network architectures to predict customer churn using the Churn_Modelling.csv dataset.

## Steps
1. Data Loading: Dataset loaded into Pandas DataFrame
2. Data Cleaning: Removed irrelevant columns (Surname, CustomerId, RowNumber)
3. Encoding: Applied one-hot encoding for Geography, label encoding for Gender
4. EDA: Count plots, histograms, and heatmaps for data visualization
5. Neural Networks: Implemented Linear Associator, LeakyRelu, and BAM
6. Results: Evaluated models for pattern recall accuracy
7. Conclusion: Compared the models, highlighting Hopfield and BAM advantages

## Results
- Model Accuracy: 84.81%

## Requirements
Install required packages: pip install -r requirements.txt
