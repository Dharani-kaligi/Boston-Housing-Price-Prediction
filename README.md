# 🏠 Boston Housing Price Prediction using Multiple Linear Regression

> An end-to-end Machine Learning project that predicts housing prices using Multiple Linear Regression while validating regression assumptions and comparing regularization techniques.

---

## 📌 Project Highlights

✔ Exploratory Data Analysis (EDA)

✔ Data Visualization

✔ Correlation Analysis

✔ Feature Scaling using StandardScaler

✔ Multiple Linear Regression

✔ Regression Assumption Validation

✔ Multicollinearity Detection (VIF)

✔ Ridge, Lasso & Elastic Net Regression

✔ Model Performance Comparison

✔ House Price Prediction

---

## 🎯 Business Problem

Accurately predicting house prices is essential for buyers, sellers, and real estate businesses. This project develops a regression model that estimates the median value of houses using demographic and environmental features.

---

## 📂 Dataset

- **Dataset:** Boston Housing Dataset
- **Source:** Kaggle
- **Target Variable:** `MEDV` (Median House Value)

**Number of Features:** 13

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Statistical Analysis | Statsmodels |

---

# 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset Exploration
- Missing Value Analysis
- Statistical Summary
- Correlation Heatmap
- Feature Correlation with Target Variable
- Scatter Plot Analysis
- Distribution Analysis

---

# ⚙️ Data Preprocessing

- Feature Selection
- Train-Test Split
- Feature Scaling using StandardScaler

---

# 🤖 Machine Learning Models

The following regression models were implemented and compared:

- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

---

# 📈 Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📊 Model Comparison

| Model | R² Score |
|-------|---------:|
| Multiple Linear Regression | **0.7258** |
| Ridge Regression | **0.7258** |
| Elastic Net Regression | **0.7144** |
| Lasso Regression | **0.6542** |

---

# ✅ Regression Assumptions Verified

The following assumptions were validated before finalizing the model:

- ✔ Linearity
- ✔ Normality of Residuals
- ✔ Homoscedasticity
- ✔ Actual vs Predicted Analysis
- ✔ Multicollinearity using Variance Inflation Factor (VIF)

---

# 🔍 Key Insights

- Houses with a higher **average number of rooms (RM)** generally have higher prices.
- **LSTAT** is the strongest negative predictor of house prices.
- Residuals follow an approximately normal distribution.
- Residuals are randomly scattered around zero, satisfying the assumptions of Multiple Linear Regression.
- VIF analysis identified multicollinearity among several predictor variables.
- Ridge Regression produced performance similar to Linear Regression, whereas Lasso and Elastic Net slightly reduced model accuracy.

---

# 🏆 Final Conclusion

Multiple Linear Regression achieved the best predictive performance with an **R² Score of 72.58%**.

Although multicollinearity was present, it did not significantly impact prediction accuracy. Regularization models (Ridge, Lasso, and Elastic Net) were evaluated, but none outperformed the baseline Multiple Linear Regression model.

---

# 📁 Project Structure

```text
Boston-Housing-Price-Prediction/
│
├── Boston_Housing_Price_Prediction.ipynb
├── housing.csv
├── README.md
├── requirements.txt
└── images/
```

---

# 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Engineering
- Outlier Detection
- Random Forest Regression
- XGBoost Regression
- Gradient Boosting Regression
- Model Deployment using Streamlit

---

# 💼 Skills Demonstrated

- Python Programming
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Visualization
- Correlation Analysis
- Feature Scaling
- Multiple Linear Regression
- Model Evaluation
- Regression Diagnostics
- Variance Inflation Factor (VIF)
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Predictive Modeling

---

## 👨‍💻 Author

**Dharani Kaligi**

**Data Engineer @ DXC Technology**

🎯 Aspiring Data Scientist | Machine Learning Engineer | AI Engineer

### Technical Skills

- Python
- SQL
- Statistics
- Machine Learning
- ETL
- Power BI
- Deep Learning
- Generative AI
- MLOps

---

⭐ **If you found this project useful, consider starring the repository!**
