# 🏠 House Price Prediction using Linear Regression

This project implements a **Linear Regression model** to predict house prices based on key features like:
- Square footage (`GrLivArea`)
- Number of bedrooms (`BedroomAbvGr`)
- Number of full bathrooms (`FullBath`)

Dataset used is from the Kaggle competition:  
🔗 [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

---

## 📂 Dataset

- File: `train.csv`
- Source: Downloaded from Kaggle and included locally in the project
- Target variable: `SalePrice`

---

## 📌 Features Used

| Feature       | Description                           |
|---------------|---------------------------------------|
| GrLivArea     | Above grade (ground) living area (sq ft) |
| BedroomAbvGr  | Number of bedrooms above ground       |
| FullBath      | Number of full bathrooms              |

---

## 🧠 Model Used

- **Linear Regression** (from `scikit-learn`)
- Evaluated using:
  - ✅ Mean Squared Error (MSE)
  - ✅ R² Score

---

## 📈 Results (Example)



Installation requirement:
pip install -r requirements.txt

Or maunally:
pip install pandas scikit-learn matplotlib seaborn
