# House Price Prediction Using Random Forest
This project uses a Random Forest Regressor to predict house prices based on various features from a dataset. The goal is to accurately estimate the sale price of houses using training data and apply the model to make predictions on test data.

## Project Overview
### Steps Involved:
1. #### Data Loading and Preparation:

- Load training data from a CSV file.
- Extract the target variable (SalePrice) and selected features for prediction.

2. #### Feature Selection:

- Chosen features include LotArea, ScreenPorch, MSSubClass, YearRemodAdd, 3SsnPorch, MiscVal, 1stFlrSF, 2ndFlrSF, FullBath, BedroomAbvGr, OverallCond, OverallQual, Fireplaces, YearBuilt, GrLivArea, and YrSold.

3. #### Model Training and Validation:

- Split data into training and validation sets.
- Train a Random Forest Regressor on the training data.
- Evaluate the model using Mean Absolute Error (MAE).

4. #### Final Model Training and Prediction:

- Retrain the model on the full dataset.
- Load test data and make predictions.
- Save predictions to a CSV file.

## Key Takeaways
- Feature Selection: Critical for improving model performance.
- Model Evaluation: MAE is used to measure prediction accuracy.
- Random Forest Regressor: An effective ensemble learning method for regression tasks.
## Conclusion
This project demonstrates the use of a Random Forest Regressor to predict house prices with reasonable accuracy, leveraging historical data for training and validation, and applying the model to new data for prediction.
