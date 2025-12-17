# 🏠 House Price Prediction using Multiple Linear Regression

This project predicts house prices using **Multiple Linear Regression** based on various housing features such as area, number of bedrooms, location advantages, and furnishing status.

---

## 📌 Features
- Data preprocessing using **ColumnTransformer**
- One-Hot Encoding for categorical variables
- Multiple Linear Regression model
- Train–test split evaluation
- User input based real-time prediction

---

## 📊 Dataset
- **Housing.csv**
- Target variable: `price`
- Includes numerical and categorical features

---

## 🧠 Model Used
- **Multiple Linear Regression**
- Implemented using `sklearn.linear_model.LinearRegression`

---

## ⚙️ How It Works
1. Load and preprocess data
2. Encode categorical features
3. Train regression model
4. Evaluate on test data
5. Predict price for new user input

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python house_price_prediction.py
