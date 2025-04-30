# 📈 Stock Price Prediction & Algorithmic Trading Strategy

This project demonstrates a full pipeline for building a predictive model to forecast stock price movements and backtesting a simple algorithmic trading strategy using machine learning and technical indicators.

## 📁 Project Structure

- `task1and2.ipynb`: Complete Jupyter Notebook with code for data preprocessing, feature engineering, model training.
- `task3and4.ipynb`: Complete Jupyter Notebook with code for evaluation, and backtesting.
- `README.md`: Project documentation and instructions.

## 🚀 Features

- Download and clean historical stock data (3+ years).
- Feature engineering with technical indicators (Moving Average, RSI, MACD, etc.).
- Binary classification to predict next-day stock movement (Up/Down).
- Model training using XGBoost, Logistic Regression, and Random Forest.
- Performance evaluation using accuracy, precision, recall, F1-score, ROC-AUC.
- Backtesting a basic trading strategy (buy/sell based on prediction).
- Strategy refinement with stop-loss and take-profit.
- Visualization of stock trends, indicators, and strategy performance.

## 🧪 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn, XGBoost
- Matplotlib, Seaborn
- TA-Lib / ta (for technical indicators)
- Jupyter Notebook

## 📊 Performance Metrics

- Classification Accuracy: `58.2%`
- Precision / Recall / F1-score: Reported in notebook
- ROC-AUC Curve: Plotted
- Strategy Sharpe Ratio: `-9.6`
- Cumulative Returns vs. Buy-and-Hold: Plotted

## 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/AgarwalBhavya/stock-price-prediction-algorithmic-trading.git
   cd stock-price-prediction-algorithmic-trading
