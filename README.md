
# 🏠 House Price Prediction using Regression Models

This project implements **House Price Prediction** using the **Boston Housing Dataset**.
It explores multiple regression models and evaluates their performance with key metrics.

---

## 📌 Project Overview

* Dataset: **Boston Housing Dataset** (`MEDV` as target variable).
* Models Implemented:

  * **Linear Regression**
  * **Ridge Regression**
  * **Lasso Regression**
* Evaluation Metrics:

  * Mean Absolute Error (MAE)
  * Mean Squared Error (MSE)
  * Root Mean Squared Error (RMSE)
  * R² Score
* Extra Features:

  * Gradient Descent optimization
  * Visualizations for comparing predictions vs actual values

---

## 🚀 Installation

Clone the repo and install the dependencies:

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

### Install Required Libraries

```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## 📊 Dataset Information

The Boston Housing dataset contains 506 rows and 14 attributes.

**Attributes:**

* CRIM: Per capita crime rate by town
* ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
* INDUS: Proportion of non-retail business acres per town
* CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
* NOX: Nitric oxide concentration (parts per 10 million)
* RM: Average number of rooms per dwelling
* AGE: Proportion of owner-occupied units built prior to 1940
* DIS: Weighted distance to employment centers
* RAD: Index of accessibility to radial highways
* TAX: Property-tax rate per \$10,000
* PTRATIO: Pupil-teacher ratio by town
* B: Proportion of Black population
* LSTAT: % lower status of the population
* MEDV: Median value of owner-occupied homes (in \$1000s) **(Target)**

---

## 🖥️ Usage

### Run the Jupyter Notebook

To train and evaluate models:

```bash
jupyter notebook Regression_Models_on_Housing_Dataset.ipynb
```

---

## 📈 Results

The models were evaluated using MAE, MSE, RMSE, and R² Score.

| Model                 | MAE  | MSE   | RMSE | R²   |
| --------------------- | ---- | ----- | ---- | ---- |
| **Linear Regression** | 4.74 | 36.52 | 6.04 | 0.64 |
| **Ridge Regression**  | 4.64 | 36.40 | 6.03 | 0.64 |
| **Lasso Regression**  | 4.77 | 37.07 | 6.09 | 0.63 |

✅ **Observation:** Ridge Regression achieved the lowest MAE, MSE, and RMSE, with a slightly better R² score compared to Linear and Lasso Regression.

---

## 📷 Visualizations

* Actual vs Predicted plots for each regression model
* Comparison charts for error metrics

🔗 www.linkedin.com/in/zobayer-al-mahmud-652170352
<img width="1916" height="939" alt="image" src="https://github.com/user-attachments/assets/0ef7acb5-c383-4330-866a-0649a1cc1aa8" />
199399192/483975677-0ef7acb5-c383-4330-866a-0649a1cc1aa8.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250901%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250901T112548Z&X-Amz-Expires=300&X-Amz-Signature=714248c4e5d82ffb24cff7c11c2c26a6c9edc9e39fef7f260773563e380b44ce&X-Amz-SignedHeaders=host
---

## 📌 Future Improvements

* Add Support Vector Regression (SVR) and Random Forest Regression
* Hyperparameter tuning with GridSearchCV
* Deploy on Flask/Streamlit for web-based prediction

---

## 👤 Author

**Zobayer Al Mahmud**
📧 zobayeralmahmud0@gmail.com

