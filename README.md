# Real-Time-Stock-Price-Prediction-App
A HTML-powered Stock Price Prediction App leveraging LSTM networks to forecast market trends using historical financial data
Predict stock prices **in real-time** using deep learning and visualize market trends with dynamic, interactive dashboards — all through a beautiful, intuitive web interface powered by Flask, TensorFlow, YFinance, Plotly, and Matplotlib.

---

## 🚀 Overview

> **"What if investors, financial analysts, or fintech platforms could anticipate market trends seconds before they unfold?"**

The **Real-Time Stock Prediction App** is a product-inspired data science project that answers this question using real-time financial data and AI. It integrates modern tools such as `yfinance`, LSTM-based deep learning, and interactive dashboards to enable users to **predict future stock prices based on real-time inputs**.

---

## 🧠 Built Using

- 🧠 **TensorFlow** – LSTM neural network for time series forecasting
- 🔍 **YFinance** – Real-time market data from Yahoo Finance API
- 🧪 **scikit-learn** – Data normalization with MinMaxScaler
- 📊 **Matplotlib** & **Plotly** – Static and interactive visualizations
- 🌐 **Flask** – Backend API + Web interface
- 🧾 **HTML/CSS** – Frontend templating

---

## 🎯 Product Purpose: STAR Framework

### ⭐ Situation:
Retail investors, financial analysts, and fintech firms face a challenge: **predicting short-term market fluctuations** in a fast-moving digital economy. While tools like Bloomberg Terminal exist, they are expensive, technical, and inaccessible to most users.

### 🎯 Task:
Design an **affordable, intelligent, and user-friendly web tool** that:
- Retrieves real-time stock data,
- Predicts short-term stock trends,
- Visualizes both actual vs predicted performance,
- Can be adapted for fintech, education, or investor use cases.

### ⚙️ Action:
- Used **YFinance API** to pull real-time OHLC data of any publicly traded company.
- Preprocessed time series data with **MinMaxScaler** for consistency.
- Trained an **LSTM deep learning model** using TensorFlow to learn stock price patterns.
- Built a lightweight **Flask app** to serve predictions dynamically on the web.
- Visualized trends using **Plotly** for interactivity and **Matplotlib** for clean reporting visuals.

### 📈 Result:
- Achieved **real-time prediction with minimal latency**, demonstrating how ML can be deployed in production-like financial systems.
- Made stock forecasting **accessible to non-technical users** through an intuitive interface.
- Can be adapted for educational demos, fintech MVPs, or integration with trading dashboards.

---

## 🔥 Why This Matters

- 📉 **Empowers Retail Traders**: Offers an open-source alternative to high-cost market forecasting tools.
- 🏦 **Inspires Fintech Innovation**: Provides a template for fintech startups to build intelligent investment platforms.
- 🎓 **Educates Learners**: Acts as a capstone for learners of time series forecasting, ML deployment, and Flask APIs.

---

## 🛠 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/real-time-stock-prediction.git
cd real-time-stock-prediction
```
### 2. Install dependencies

Copy
Edit
```bash
pip install -r requirements.txt
```
### 3. Run the Flask server

Copy
Edit
```bash
python app.py
```

### 4. Open in browser
Visit: http://127.0.0.1:5000

