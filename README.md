# 📊 Economic Index Prediction using Linear Regression

## 📌 Overview

This project analyzes the relationship between key economic factors such as **interest rate** and **unemployment rate** to predict the **index price** using **Linear Regression**.

It includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Model training & evaluation
* Statistical validation

## 🎓 Learning Source

This project is based on concepts learned from a Udemy course by **Krish Naik**.

> The implementation has been recreated and modified as part of hands-on practice.


## 📂 Dataset

The dataset used is:

* `economic_index.csv`

### Features:

* Interest Rate
* Unemployment Rate
* Index Price (Target Variable)

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

## 🔍 Exploratory Data Analysis (EDA)

* Pairplot visualization to understand feature relationships
* Correlation matrix analysis
* Scatter plots and regression plots

---

## 🧠 Model Building

### Steps:

1. Data Cleaning
2. Feature Selection

   * Independent variables: Interest Rate, Unemployment Rate
   * Dependent variable: Index Price
3. Train-Test Split
4. Feature Scaling using StandardScaler


## 📈 Model Used

* Linear Regression (Scikit-learn)

## ✅ Model Evaluation

### Metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
* Adjusted R²

### Additional Validation:

* Cross-validation
* Residual analysis

## 📊 Statistical Analysis

Used **OLS (Ordinary Least Squares)** from Statsmodels to:

* Understand feature significance
* Analyze model summary

## 📉 Residual Analysis

* Distribution of residuals
* Residual vs predicted values

## 🚀 How to Run

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
jupyter notebook
```

## 📌 Results

* The model demonstrates a clear relationship between economic indicators and index price.
* Performance metrics indicate a reasonably good fit.

## 🔮 Future Improvements

* Add more economic indicators
* Try advanced ML models
* Deploy using Flask / Streamlit

## 🤝 Acknowledgement

Special thanks to **Krish Naik** for the educational content that helped build this project.


## 📜 License

This project is licensed under the MIT License.
