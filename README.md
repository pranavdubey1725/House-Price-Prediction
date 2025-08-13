House Price Prediction
Overview
Predict house prices using historical housing data.

Perform data cleaning, preprocessing, and feature engineering.

Apply machine learning regression models: Random Forest and XGBoost.

Evaluate model performance using industry-standard metrics.

Save trained models for reuse.

Project Structure
HousePricePrediction.ipynb – Notebook for data preprocessing, feature engineering, model training, and evaluation.

train.csv – Dataset containing historical house price records.

random_forest_model.pkl – Saved Random Forest trained model.

xgboost_model.pkl – Saved XGBoost trained model.

requirements.txt – Python dependencies.

Dataset Used
train.csv — Housing dataset containing numerical and categorical features related to property size, location, and condition.

Engineered feature: TotalBathrooms (combined total of full and half bathrooms).

Categorical variables encoded using one-hot encoding.

Models and Techniques
Models:

Random Forest Regressor (with hyperparameter tuning via RandomizedSearchCV)

XGBoost Regressor

Techniques: Feature Engineering, One-Hot Encoding, Model Evaluation

Evaluation Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score

Final Scores:

Model	MAE	MSE	R² Score
Random Forest	18552.05	883M	0.8762
XGBoost	18822.98	844M	0.8816

Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib

Environment: Google Colab
