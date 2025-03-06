
# 📈 Stock Price Prediction using LSTM & Sentiment Analysis

## 📝 Project Overview
This project builds an **LSTM-based deep learning model** to predict **NVIDIA's stock price** using:
- **Historical stock data** (via `yfinance`)
- **Technical indicators** (SMA, RSI, Bollinger Bands)
- **Sentiment analysis on financial news**

📌 **Goal:** To analyze how sentiment and technical indicators affect stock price movements and improve prediction accuracy.

---

## 📂 Files in This Repository
- **`Sentiment_analysis_stock.ipynb`** → Jupyter Notebook with data preprocessing, LSTM model training, and analysis.
- **`README.md`** → This file explaining the project.
- **`requirements.txt`** → Dependencies needed to run the notebook.

---

## ⚙️ Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/VatsalSangani/Sentiment_Analysis_of_Stocks
cd Sentiment_Analysis_of_Stocks
```
```bash
pip install -r requirements.txt
```

## 📊 Technical Indicators Used
- ✅ Simple Moving Average (SMA) → Detects price trends.
- ✅ Relative Strength Index (RSI) → Identifies overbought/oversold conditions.
- ✅ Bollinger Bands → Measures volatility and breakout points.

## Model
The LSTM model is built using `TensorFlow/Keras`

## Results
- R² Score: `~0.89` → Model explains 89% of stock price variance.
- Mean Absolute Error (MAE): `~2.97` → Average prediction error of `$2.97`.
- MSE: `~15.16` → Low mean squared error.

## 📉 Insights:
- Sentiment alone is NOT a strong predictor (weak correlation with stock price).
- Combining technical indicators with LSTM improves accuracy.

## 📌 Future Improvements
- Add MACD & trading volume for better prediction.
- Experiment with Model Architecture or using Transformer Models.
