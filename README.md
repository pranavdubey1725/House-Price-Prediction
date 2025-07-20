# 🏠 House Price Prediction

A simple machine learning project to predict house prices using **Linear Regression** and **Random Forest Regression**.

## 📁 Dataset
- Kaggle’s Ames Housing Dataset
- Contains features like lot size, house style, area, year built, etc.

## 🧠 Models Used
- Linear Regression
- Random Forest Regressor

## 🛠️ Features Engineered
- Numeric: LotArea, GrLivArea, YearBuilt, etc.
- Categorical: Neighborhood, HouseStyle (One-hot encoded)

## 📊 Evaluation
- MAE: ~18020  
- R² Score: ~0.90

## 📂 Files Included
- `HousePricePrediction.ipynb`: Complete notebook
- `train.csv`: Dataset used
- `random_forest_model.pkl`: Saved trained model
- `requirements.txt`: Python dependencies

## 🚀 To Run
```bash
pip install -r requirements.txt
