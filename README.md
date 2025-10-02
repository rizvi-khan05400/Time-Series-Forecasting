# 📈 Time Series Forecasting with ARIMA

## 📌 Project Overview
This project focuses on forecasting Google stock prices using **Time Series Analysis** techniques.  
The dataset was explored, visualized, and modeled to identify patterns such as **trend** and **seasonality**.  
The **ARIMA (AutoRegressive Integrated Moving Average)** model was implemented to make forecasts.

---

## 🔧 Steps Performed
1. **Data Loading & Cleaning**  
   - Loaded stock price data from CSV.  
   - Handled missing values and ensured data quality.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized stock price trends.  
   - Checked for seasonality and stationarity using decomposition.  

3. **Modeling with ARIMA**  
   - Selected ARIMA parameters (p, d, q).  
   - Trained and evaluated the model.  

4. **Model Evaluation**  
   - Metrics used: **RMSE, MAE**.  
   - Compared forecasted values with actual values.  

---

## ⚡ Challenges Faced
- Difficulty in selecting the right ARIMA parameters.  
- Balancing overfitting vs underfitting.  
- Time series volatility and sudden changes.  

---

## 📊 Results
- ARIMA was able to capture short-term trends fairly well.  
- Forecast accuracy was reasonable but sensitive to parameter selection.  
- Visual comparison showed that forecasts aligned with real stock price movements.  

---

## 🚀 Future Improvements
- Test advanced models: **SARIMA, Prophet, LSTM**.  
- Perform **automated hyperparameter tuning**.  
- Include external features (e.g., trading volume, market news).  

---

## ▶️ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/rizvi-khan05400/your-repo-name.git
   pip install -r requirements.txt
