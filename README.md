# California Housing Prices Prediction

## Introduction
This project explores the California Housing Prices dataset from Kaggle to create machine learning models that predict the mean house price within a block. It involves data exploration, cleaning, feature engineering, and evaluating several regression models.

## Dataset
The dataset is from the 1990 California census and provides housing and demographic information. It is used in *Hands-On Machine Learning with Scikit-Learn and TensorFlow* by Aurélien Géron.

- **Source**: [Kaggle: California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Workflow
1. **Exploratory Data Analysis (EDA)**: Identified key trends, outliers, and correlations.
2. **Data Cleaning**: Handled missing values and outliers.
3. **Feature Engineering**: Created new features and removed less relevant ones.
4. **Modeling**:
   - Linear Regression
   - K-Nearest Neighbors Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor

## Results
The best-performing model was **Random Forest Regressor**, achieving:
- **Test Score**: 0.870
- **RMSE**: 41,988
