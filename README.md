# Gold Price Prediction using Machine Learning

This project uses machine learning to predict the price of gold using various financial indicators such as crude oil prices, S&P 500 index, silver prices, and EUR/USD exchange rates. The model is built using a Random Forest Regressor and evaluated using standard regression metrics.

---

## 📊 Problem Statement

Gold price is an important economic indicator influenced by various global factors. Accurate predictions can assist investors and analysts in making better financial decisions. This project aims to build a predictive model using historical data and financial indicators.

---

## 💡 Proposed Solution

1. **Data Collection**: Historical data including gold prices and financial indicators.
2. **Data Preprocessing**: Cleaning, feature selection, and handling missing values.
3. **Modeling**: Random Forest Regressor trained on historical features.
4. **Evaluation**: Metrics such as R² Score, MAE, and RMSE.

---

## 🛠 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn

---

## 📁 Project Files

| File/Folder       | Description                               |
|-------------------|-------------------------------------------|
| `notebook/`       | Jupyter/Colab notebook with full code     |
| `data/`           | Dataset used in training                  |
| `images/`         | Graphs and plots                          |
| `model/`          | Trained model saved via `joblib`          |
| `app/`            | Streamlit app for deployment (optional)   |
| `README.md`       | This project summary                      |
| `requirements.txt`| List of libraries to install              |

---

## 📈 Results

- **R² Score**: 0.9887
- **MAE**: 1.3536
- **RMSE**: 2.4411

---

## 🔗 Dataset Link
https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data
