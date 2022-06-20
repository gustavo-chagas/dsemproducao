# Rossmann Sales Prediction
Sales forecast using the dataset from this Kaggle competition: https://www.kaggle.com/c/rossmann-store-sales.


## Context of the project
From the description of the Kaggle competition page: 
> "Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied."
## Data Description

- Renaming columns
- Changing data types
- Filling NA
- Statistic description of numerical (mean, median, std, skew, kurtosis) and categorical atributes
##  Exploratory Data Analysis


- Univariate analysis: response, numerical and categorical variables.
- Bivariate analysis: test of hypothesis
- Multivariate analysis: correlation between atributes 
## Data Preparation

- Rescaling: Robust Scaler and Min Max Scaler
- Encoding: One Hot Encoding, Label Encoding and Ordinal Encoding

## Feature Selection

The Boruta algorithm was used to select the features used in the model, you can learn more about the Boruta algorithm here: https://github.com/scikit-learn-contrib/boruta_py
