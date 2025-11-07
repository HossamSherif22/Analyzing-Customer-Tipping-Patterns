# 🧠 Tip Prediction using Machine Learning

This project demonstrates a full end-to-end **data analysis and machine learning workflow** using the famous **Tips Dataset**.  
It includes **data cleaning, exploratory data analysis (EDA)**, feature engineering, and multiple regression models to predict **tip amount** based on restaurant bill information.

---

## 🚀 Project Overview

### 🔍 Objective
Predict the **tip amount** given restaurant bill details such as total bill, gender, day, time, smoker status, and party size.

### 🧩 Steps Covered
1. **Data Preprocessing**
   - Handle missing values and outliers  
   - Feature engineering (e.g., `tip_pct`)  
2. **Exploratory Data Analysis (EDA)**
   - Statistical summary  
   - Visualizations (histograms, boxplots, correlation heatmaps)  
3. **Model Building**
   - Models used: `LinearRegression`, `RandomForestRegressor`, `GradientBoostingRegressor`
   - Pipeline and column transformer for preprocessing  
4. **Model Evaluation**
   - Metrics: RMSE, MAE, R²  
   - Best model selection based on test performance  
5. **Model Tuning**
   - RandomizedSearchCV for hyperparameter optimization  

---

## 📊 Results

| Model                | RMSE  | MAE   | R²   |
|----------------------|-------|-------|------|
| GradientBoosting_best | 0.1272 | 0.1815 | 0.8982 |
| RandomForest_best     | 0.2049 | 0.2327 | 0.8361 |
| LinearRegression      | 0.2427 | 0.3488 | 0.8059 |

✅ **Gradient Boosting** achieved the best overall performance with **R² = 0.898**.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Machine Learning Regression Models
- Data Visualization

---

## 📈 Key Insights
- Tip percentage (`tip_pct`) correlates strongly with total bill and party size.  
- Gender and smoking habits show interesting but subtle effects on tipping behavior.  
- Ensemble methods outperform simple linear regression models.

---

## 📂 Project Structure
