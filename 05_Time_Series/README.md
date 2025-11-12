# ⏳ Forecasting Exchange Rates Using Time Series Analysis

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Time Series](https://img.shields.io/badge/TimeSeries-ARIMA-orange)](https://www.statsmodels.org/stable/tsa.html)
[![Exponential Smoothing](https://img.shields.io/badge/ExponentialSmoothing-lightgrey)](https://www.statsmodels.org/stable/tsa.html)

---

## 🚀 Objective
Leverage **ARIMA** and **Exponential Smoothing** techniques to **forecast future exchange rates** based on historical data from `exchange_rate.csv`.

---

## 🗂 Dataset
- **Filename:** `exchange_rate.csv`  
- **Columns:**  
  - `Date` → Date of observation  
  - `Ex_rate` → USD to AUD exchange rate  

<details>
<summary>📊 Dataset Sample (Click to Expand)</summary>

| Date           | Ex_rate |
|----------------|---------|
| 01-01-1990     | 0.7855  |
| 02-01-1990     | 0.7818  |
| 03-01-1990     | 0.7867  |
| 04-01-1990     | 0.7860  |
| 05-01-1990     | 0.7849  |
| 06-01-1990     | 0.7866  |
| 07-01-1990     | 0.7886  |
| 08-01-1990     | 0.7910  |
| 09-01-1990     | 0.7939  |
| 10-01-1990     | 0.7894  |

</details>

---

## 🔹 Workflow & Tasks

<details>
<summary>Click to Expand 📝</summary>

### **Part 1: Data Preparation & Exploration**
- Load the dataset and parse `Date` column as datetime  
- Visualize the time series for **trends, seasonality, and anomalies**  
- Handle **missing values** or anomalies  

### **Part 2: Model Building - ARIMA**
- Use **ACF & PACF** plots to estimate initial parameters `(p, d, q)`  
- Fit **ARIMA model** on preprocessed series  
- Perform **residual diagnostics** to ensure no patterns  
- Forecast future exchange rates and visualize predictions vs actual  

### **Part 3: Model Building - Exponential Smoothing**
- Choose suitable model: **Simple, Holt’s Linear, or Holt-Winters**  
- Optimize parameters via **grid search / AIC**  
- Fit model and forecast future values  
- Visual comparison with actual data  

### **Part 4: Evaluation & Comparison**
- Compute metrics:  
  - **MAE** → Mean Absolute Error  
  - **RMSE** → Root Mean Squared Error  
  - **MAPE** → Mean Absolute Percentage Error  
- Compare **ARIMA vs Exponential Smoothing** performance  
- Summarize insights and best-performing model  

</details>

---

## ⚡ Techniques & Libraries
- **Python 3**  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn  
- **Techniques:**  
  - Time Series Analysis  
  - ARIMA & SARIMA  
  - Exponential Smoothing  
  - Forecast Evaluation Metrics  

---

## 📊 Visualizations
- **Time series plot** → USD to AUD trends  
- **ACF & PACF plots** → ARIMA parameter selection  
- **Forecast vs Actual** → ARIMA & Exponential Smoothing comparison  
- **Residual analysis** → Validate ARIMA assumptions  

---

## 🎯 Key Learning Outcomes
- End-to-end **time series forecasting** workflow  
- Understanding of **trend, seasonality, and anomalies** in financial data  
- Applying and **comparing ARIMA and Exponential Smoothing**  
- Evaluating forecast accuracy using **MAE, RMSE, and MAPE**  

---

## 💡 Conclusion
This assignment demonstrates **real-world forecasting of currency exchange rates** using statistical models.  
It highlights **data exploration, modeling, evaluation, and insights extraction**, forming a solid foundation in time series analysis.  

> _“Forecasting the future begins with understanding the past — and making the machine see the patterns.”_

---

## 🔗 References
- [Statsmodels Time Series Documentation](https://www.statsmodels.org/stable/tsa.html)  
- [Python Pandas Documentation](https://pandas.pydata.org/docs/)  
- [Matplotlib & Seaborn Visualization Docs](https://matplotlib.org/stable/contents.html)  
- [Scikit-learn Metrics & Evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html)  

---

