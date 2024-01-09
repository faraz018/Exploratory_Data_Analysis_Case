# Exploratory_Data_Analysis_Case

Black Friday Dataset EDA and Feature Engineering
Overview
This code performs Exploratory Data Analysis (EDA) and feature engineering on the Black Friday dataset. The goal is to clean and prepare the data for model training, specifically using data available on the train.csv and test.csv files.

Requirements
Python 3
Libraries: pandas, numpy, matplotlib, seaborn

The dataset columns are explored using info() and describe() to understand their types and statistics.
The "User_ID" column is dropped as it is not needed for the analysis.
The "Gender" column is transformed into numerical values for compatibility with machine learning models.