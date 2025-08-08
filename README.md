# Systematic Trading Backtest

This project explores a simple **moving average crossover strategy** applied to historical price data. It was built using Python and Jupyter/Colab to practice basic quant research workflows — including strategy definition, signal generation, performance evaluation, and Sharpe ratio optimization.

---

## 📈 Strategy: Simple Moving Average (SMA) Crossover

- **Buy Signal**: When the short-term SMA crosses above the long-term SMA
- **Sell Signal**: When the short-term SMA crosses below the long-term SMA
- This is a trend-following strategy designed to capture upward momentum

---

## 📊 Performance Metrics

- **Backtest period**: 2018–2024
- **Best-performing SMA combo** (via grid search):  
  - `short_window = 5`  
  - `long_window = 20`
- **Sharpe Ratio** (optimized): ~0.18  
- **Strategy Return**: Slightly higher than market, but with low risk-adjusted return

---

## 🛠 Technologies Used

- Python (Pandas, Matplotlib)
- Google Colab / Jupyter Notebook
- Yahoo Finance data via CSV
- GitHub for version control

---

