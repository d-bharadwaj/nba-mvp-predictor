# This is the heading 

This project focuses on building a machine learning model that accurately predicts the NBA MVP for the regular season based on individual and team statistics. The main objective is to achieve high accuracy in predicting the MVP label, while also minimizing the average mean absolute error (MAE) and maximizing the coefficient of determination (R²) across all years. 

The approach taken treats this as a regression problem, with the target variable being the MVP share metric. Linear regression was chosen due to the observed linear relationships between many features and the response variable. Three tree-based models, namely Random Forest, XGBoost, and LightGBM, were employed. Random Forest is an ensemble learning method that constructs multiple decision trees, while XGBoost and LightGBM are more efficient and powerful variations of tree learning models. Extensive parameter tuning was performed for these models to achieve optimal performance.
