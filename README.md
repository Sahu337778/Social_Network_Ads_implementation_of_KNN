# Social_Network_Ads_implementation_of_KNN
Predictive modeling using demographic data from the Social Network Ads Dataset to forecast user purchase behavior with 84% accuracy


# Social Network Ads Dataset

## Overview
The "Social Network Ads Dataset" contains information on users' demographic details and purchase behavior. Each entry represents a user and includes attributes like User ID, Gender, Age, Estimated Salary, and Purchased (indicating a purchase with 1 and no purchase with 0).

## File
- `SocialNetwork_Ads.csv`: Main dataset file containing user details and purchase behavior.

## Data Source
The dataset comprises simulated or anonymized data and is intended for educational and analytical purposes.

## Purpose
This dataset is ideal for predictive modeling aiming to forecast user purchase behavior based on demographic attributes. It serves as a valuable resource for classification tasks to predict if a user is likely to make a purchase given their demographic information.

## Exploratory Data Analysis (EDA)
- No skewness or outliers were observed in the dataset.
- The data is binary, classifying purchases as '0' (no purchase) and '1' (purchase), showing distinct separability between the two classes.

## Model Building
- A K-Nearest Neighbors (KNN) classification model was implemented to predict purchase behavior using Age and Estimated Salary as features.
- Hyperparameter tuning with 'n_neighbors' set to 6 achieved an accuracy of 0.84, indicating a substantial model improvement.

## Model Goal
The primary aim of the model is to forecast or predict whether a customer will make a purchase based on their demographic details.

## Forecasting New Observations
A function was developed to predict potential customer purchases based on Age and Estimated Salary attributes.

## Conclusion
The analysis revealed significant model improvement with an accuracy of 0.84 after refining the KNN model's hyperparameters. The model's primary goal is not just evaluation but forecasting customer behavior concerning product purchases utilizing demographic information.
