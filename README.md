# Amsterdam-House-Price-Prediction

Amsterdam Housing Price Analysis
This project aims to analyze housing prices in Amsterdam using machine learning techniques. It includes data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

## Overview

The analysis pipeline consists of the following steps:

1. **Data Loading**: The dataset containing housing price information for Amsterdam is loaded from a CSV file.

2. **Data Preprocessing**:
   - Zip code encoding.
   - Handling missing values.
   - Calculating additional features such as median price per zip code, price per square meter and distance to city center.

3. **Exploratory Data Analysis (EDA)**:
   - Heatmap to visualize feature correlations.
   - Scatter plot to identify location patterns.

4. **Model Building**:
   - Features and target variable setup.
   - Train-test split.
   - Random Forest Regressor model training and evaluation.
   - Hyperparameter tuning using GridSearchCV.

5. **Evaluation**:
   - Final accuracy score of the best model.

