# 🏡 House Price Prediction

A machine learning project to predict house prices using both **Random Forest** and **XGBoost** regression models.

## 📌 Features

- Cleaned and preprocessed housing dataset
- Feature engineering (`TotalBathrooms`)
- One-hot encoding for categorical variables
- Models used:
  - Random Forest Regressor (with Hyperparameter Tuning using RandomizedSearchCV)
  - XGBoost Regressor
- Evaluation metrics: MAE, MSE, R² Score
- Actual vs Predicted Plot
- Trained models saved as `.pkl`

## 📊 Final Scores

| Model           | MAE      | MSE         | R² Score |
|----------------|----------|-------------|----------|
| Random Forest  | 18552.05 | 883M        | 0.8762   |
| XGBoost        | 18822.98 | 844M        | 0.8816   |

## 🧠 Requirements

See `requirements.txt`.

## 💾 Files

- `HousePricePrediction.ipynb` - Full notebook
- `random_forest_model.pkl` - Trained Random Forest model
- `xgboost_model.pkl` - Trained XGBoost model
- `train.csv` - Dataset
- `requirements.txt` - Python dependencies

---

**Note:** This project is built in Google Colab.

---

