# 📈 Portfolio Optimization Using Deep Learning

This project explores how deep learning, specifically Long Short-Term Memory (LSTM) networks, can be used for optimizing a financial portfolio. We focus on predicting the **Sharpe Ratio** of assets to guide allocation strategies using historical stock data from the Indian market (2013–2023).

---

## 📌 Objective

To develop a deep learning-based model that predicts risk-adjusted returns (Sharpe Ratio) and helps in constructing an optimized investment portfolio.

---

## 🧠 Techniques Used

- **Time Series Forecasting** using LSTM (Long Short-Term Memory)
- **Feature Engineering** with Rolling Sharpe Ratio
- **Portfolio Optimization** based on predicted performance
- **Backtesting** to evaluate strategy effectiveness

---

## 📊 Dataset

- Collected using the `yfinance` Python library
- Stocks: 43 Indian companies
- Time Period: January 2013 – December 2023
- Frequency: Daily closing prices

---

## 🔧 Tools & Libraries

- `Python`  
- `yfinance` – for financial data  
- `pandas`, `numpy` – data processing  
- `matplotlib`, `seaborn` – data visualization  
- `TensorFlow` / `Keras` – LSTM modeling  
- `scikit-learn` – evaluation metrics

---

## 🧮 Methodology

1. **Data Collection**  
   - Downloaded 10 years of daily price data for 43 Indian stocks.

2. **Data Preprocessing**  
   - Cleaned and handled missing values.
   - Calculated **10-day rolling Sharpe Ratio** as target variable.

3. **Modeling with LSTM**  
   - Formatted time-series data for LSTM input.
   - Trained the model to predict future Sharpe Ratios.

4. **Portfolio Construction**  
   - Used predicted Sharpe Ratios to select top-performing assets.
   - Allocated weights based on predicted risk-adjusted return.

5. **Evaluation**  
   - Compared the optimized portfolio against equal-weight and random portfolios.

---

## 📈 Results & Insights

- LSTM was able to capture temporal dependencies in asset performance.
- The portfolio built using predicted Sharpe Ratios showed improved risk-adjusted returns.
- Demonstrated the potential of deep learning in smart portfolio construction.

---

## 📝 Future Work

- Integrate other risk metrics like Sortino Ratio or Maximum Drawdown.
- Try attention-based models like Transformers for financial prediction.
- Apply Reinforcement Learning for dynamic portfolio rebalancing.

---

## 📬 Contact

**Author:** Shruti Mall  
**Email:** mallshruti5030@gmail.com 
**LinkedIn:** [https://www.linkedin.com/in/shruti-mall-57a155233/]  

---

## 📄 License

This project is for academic and educational use. You are free to use and modify it with proper credit.
