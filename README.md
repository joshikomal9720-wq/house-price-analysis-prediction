
# House Price Analysis & Prediction

## Overview
This project explores housing data and develops machine learning regression models to predict house sale prices.

## Objectives
- Clean and analyze the housing dataset.
- Explore relationships between property characteristics and sale prices.
- Handle missing values and encode categorical variables.
- Train and compare regression models.
- Evaluate models using MAE, RMSE, and R².
- Analyze feature importance and prediction errors.

## Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Best Model
The Random Forest model achieved the following results on the held-out test set:

- MAE: 17,525.45
- RMSE: 28,835.69
- R²: 0.8916

## Tools and Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Visualizations
The `graphs and visuals` folder contains the exploratory analysis, model comparison, feature importance, and prediction diagnostic plots.

## Dataset
The project uses a housing dataset containing 1,460 properties and 81 columns. Refer to the dataset source and license before redistributing the data.

## Conclusion
The analysis found that overall quality, above-ground living area, and basement area are useful predictors of house sale prices. Random Forest performed best overall among the initial regression models based on RMSE and R².
