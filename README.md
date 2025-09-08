# Housing Price Prediction 🏠📈

This project builds and evaluates a machine learning model to predict housing prices.  
The main model is a **Random Forest Regressor**, optimized using **RandomizedSearchCV** for hyperparameter tuning.

---

## 🚀 Features
- Data preprocessing with **scikit-learn Pipelines**
- Model training with **Random Forest**
- Hyperparameter tuning using **RandomizedSearchCV**
- Evaluation with **RMSE**, **MAE**, and **R²**
- Reproducible workflow in Python (Jupyter/Colab friendly)

---

## 🛠️ Installation
Clone the repo and install dependencies:

git clone https://github.com/fouad3966/housing-price-prediction.git
cd housing-price-prediction
pip install -r requirements.txt
Dependencies:

Python 3.8+

scikit-learn

numpy

pandas

matplotlib (optional for plots)

---

📊 Results
After hyperparameter tuning, the best Random Forest model achieved:

RMSE: 48,887.15

MAE: 31,825.09

R²: 0.818

Best hyperparameters found:

json
Copier le code
{
  "n_estimators": 200,
  "min_samples_split": 2,
  "min_samples_leaf": 1,
  "max_features": 0.5,
  "max_depth": 50
}
📜 Usage
Run training & evaluation:
