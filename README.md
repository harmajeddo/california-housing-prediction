# Housing Price Prediction

This project aims to predict housing prices based on various features using machine learning models: **XGBoost** and **Random Forest**. The dataset used is the California Housing dataset.

---

## Installation

1. Clone the repository:

git clone https://github.com/harmajeddo/california-housing-prediction.git
cd california-housing-prediction

2. Create and activate a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install the required packages:

pip install -r requirements.txt


## Usage
Run the Jupyter notebooks in the following order to reproduce the analysis and model training:

1. notebooks/01_data_preparation.ipynb — Data loading, cleaning, and preprocessing

2. notebooks/02_model_training.ipynb — Model training and hyperparameter tuning

3. notebooks/03_evaluation_and_analysis.ipynb — Model evaluation and residual analysis

You can also run Python scripts (if available) to train and evaluate models.

## Project Structure
housing-price-prediction/
│
├── data/                      # Dataset files
│   └── housing.csv
├── notebooks/                 # Jupyter notebooks for step-by-step analysis
│   ├── 01_data_preparation.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_evaluation_and_analysis.ipynb
├── scripts/                   # Python scripts (optional)
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

## Evaluation Metrics
 Root Mean Squared Error (RMSE):
Measures the average magnitude of errors between predicted and actual values. Lower RMSE indicates better model accuracy.

 Mean Absolute Error (MAE):
Average absolute difference between predicted and actual values.

 R² Score (Coefficient of Determination):
Indicates how well the model explains the variance in the data. Values closer to 1 mean better fit.


## Results
XGBoost RMSE: ~48237

Random Forest RMSE: ~49767

XGBoost MAE: ~32084

Random Forest MAE: ~32450

XGBoost R²: 0.826

Random Forest R²: 0.815

XGBoost performs slightly better based on these metrics


## Future Work / Improvements
Experiment with additional feature engineering.

Try other models like LightGBM or CatBoost.

Perform deeper hyperparameter tuning with more parameters.

Use cross-validation with different splits.

Analyze residuals further to improve model robustness.

## Contact
Feel free to open issues or pull requests.
For questions, contact: roozbeh.bayat@gmail.com