OVERVIEW
- Predict house prices using historical housing data from the provided `train.csv` file.
- Involves data cleaning, preprocessing, and extensive feature engineering.
- Applies machine learning regression models: **Random Forest** and **XGBoost**.
- Evaluates model performance using industry-standard metrics and saves trained models for reuse.

---

PROJECT STRUCTURE
- **HousePricePrediction.ipynb** – Main notebook for data preprocessing, feature engineering, model training, and evaluation.
- **train.csv** – Dataset containing historical house price records.
- **random_forest_model.pkl** – Saved Random Forest trained model.
- **xgboost_model.pkl** – Saved XGBoost trained model.
- **requirements.txt** – A list of the project's Python dependencies.

---

DATASET USED
- **train.csv** — A single dataset containing housing records with both numerical and categorical features related to property size, condition, and location.
- An engineered feature, **TotalBathrooms**, was created by combining the total number of full and half bathrooms.
- Categorical variables were encoded using one-hot encoding for model compatibility.

---

TECH STACK
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib
- **Techniques:** Feature Engineering, One-Hot Encoding, Hyperparameter Tuning (RandomizedSearchCV), Regression Modeling, Model Evaluation
- **Environment:** Google Colab

---

MODEL PERFORMANCE
Final model scores were evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R² Score.

| Model | MAE | MSE | R² Score |
| :--- | :--- | :--- | :--- |
| Random Forest | $18,552.05 | $8.83e8 | 0.8762 |
| XGBoost | $18,822.98 | $8.44e8 | 0.8816 |

---

HOW TO RUN
1.  **Clone the repository**
    ```bash
    git clone <YOUR_REPOSITORY_URL>
    cd <PROJECT_DIRECTORY>
    ```
2.  **Create a virtual environment and install dependencies**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
3.  **Launch the Jupyter Notebook**
    Open and run the cells within **HousePricePrediction.ipynb** to execute the data analysis and model training pipeline.
