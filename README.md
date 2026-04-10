# 🏠 House Price Prediction using Linear Regression

This project predicts the **sale price of houses** based on features like living area, overall quality, garage details, etc., using the [Kaggle House Prices Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

---

## 📂 Dataset Overview

- `train.csv`: Training data (1460 rows, 81 columns)
- `test.csv`: Test data without SalePrice
- `sample_submission.csv`: Sample output format for submission
- Features include:
  - `GrLivArea`: Above-ground living area (sq ft)
  - `OverallQual`: Overall material and finish quality
  - `GarageCars`: Number of cars in garage
  - `GarageArea`: Size of garage in sq ft
  - And many more...

---

## 📊 Techniques Used

- ✅ Data cleaning (`dropna()`)
- ✅ Exploratory Data Analysis (EDA)
- ✅ Outlier Detection & Removal using scatterplots
- ✅ Feature Selection using `correlation analysis`
- ✅ Scaling with `StandardScaler`
- ✅ Linear Regression model building
- ✅ Custom user input-based prediction using `.predict()`

---

## 🔍 Model Evaluation

- **RMSE**: `42682.00`
- **R² Score**: `0.76`

Initially, accuracy was ~60%, which improved to **76%** after:
- Better feature selection
- Removing outliers
- Applying scaling

---

## 🔢 Input Prediction Feature

The model allows you to input:
- Living Area
- Overall Quality
- Garage Info  
➡️ and gives you a predicted house price!

```python
🏠 Estimated Price: ₹ 247337.64
# house-price-prediction

🚀 Future Improvements
Try different regression models: Ridge, Lasso, Random Forest

Add cross-validation

Perform hyperparameter tuning

📦 Requirements
Install using:

bash
Copy
Edit
pip install -r requirements.txt
🧠 Learning Outcome
This was my first end-to-end ML regression project where I applied:

EDA

Feature Engineering

Visualization

Modeling

Evaluation

It boosted my confidence to apply what I learned into something real.

📌 Project Author
👨‍💻 Ravi Roy
raviroy2002@gmail.com
B.Tech CSE, IILM University
Core IIC Club Member, Ex-Intern @ Oasis Infobyte, YBI Foundation, CodeAlpha
Passionate about AI/ML & solving real-world problems 🌱

🔗 Kaggle Dataset
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
🏡 House Prices - Advanced Regression Techniques

