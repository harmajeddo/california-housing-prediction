# California Housing Price Prediction 🏡

This project uses the California housing dataset to predict median house values using machine learning models (XGBoost, Random Forest). The best model was XGBoost with RMSE of 48,237.

## Structure
- data/ contains the dataset
- notebooks/ has the main development notebook
- models/ stores the trained model and preprocessing pipeline

## Usage
Load the model and pipeline with joblib and use .predict() on new data