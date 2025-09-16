# Best-Model-To-Predict-stock-price
# 📈 Stock Price Prediction – Model Comparison

## 📌 Project Overview
This project aims to **predict stock prices** and **compare different deep learning models** to identify the **best-performing model**.  
We used data from **Tata Motors, Reliance, and Amazon** and trained four models:

- 🔹 RNN (Recurrent Neural Network)  
- 🔹 LSTM (Long Short-Term Memory)  
- 🔹 CNN (Convolutional Neural Network)  
- 🔹 Hybrid CNN + LSTM  

The models were compared using **RMSE (Root Mean Squared Error)** and **MAPE (Mean Absolute Percentage Error)**.  
The best model is selected based on the **lowest RMSE**.

---

## 📊 Dataset
- Stock data downloaded using **[Yahoo Finance](https://pypi.org/project/yfinance/)**.  
- Time range: **2015 – 2025**  
- Features used:
  - Open, High, Low, Close, Volume  
  - Moving Average (MA10, MA50)  
  - Exponential Moving Average (EMA20)  
  - Returns  

---

## ⚙️ Models Implemented
1. **RNN** – Simple recurrent layers.  
2. **LSTM** – Long short-term memory units to capture long dependencies.  
3. **CNN** – 1D convolution for feature extraction.  
4. **CNN+LSTM** – Hybrid model combining CNN feature extraction with LSTM sequence learning.  

---

## 🧪 Evaluation Metrics
- **RMSE (Root Mean Squared Error)** – Measures average prediction error.  
- **MAPE (Mean Absolute Percentage Error)** – Measures percentage error.  

Formula:  
\[
RMSE = \sqrt{\frac{1}{n} \sum (y_{true} - y_{pred})^2}
\]  
\[
MAPE = \frac{100}{n} \sum \left| \frac{y_{true} - y_{pred}}{y_{true}} \right|
\]

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git
   cd stock-price-prediction
