<div align="center">

# 📊 FinanceDashboard — Stock Market Intelligence Platform

**A production-ready financial analytics dashboard built with Python, Streamlit & Plotly**

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.35+-FF4B4B?style=for-the-badge\&logo=streamlit\&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.22+-3F4F75?style=for-the-badge\&logo=plotly\&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)

<br/>

**Interactive charts · Technical indicators · Real-time data · Analytics tools**

<br/>

[🚀 Quick Start](#-quick-start) · [✨ Features](#-features) · [🛠 Tech Stack](#-tech-stack) · [📁 Structure](#-project-structure)

</div>

---

## 🎯 Overview

**FinanceDashboard** is a modern stock market analysis platform designed for students, developers, and retail investors who want professional-grade tools without expensive subscriptions.

It provides:

* 📈 Interactive financial charts
* 📊 Advanced technical indicators
* 📉 Statistical analysis tools
* 📥 Exportable datasets

All in a **clean, responsive UI powered by Streamlit**.

---

## ✨ Features

### 📈 Interactive Charts

* Candlestick chart (OHLC)
* Line chart (trend-focused)
* OHLC bar chart
* Zoom, pan & real-time interaction (Plotly)

### 🔬 Technical Indicators

* Moving Averages (MA20 / MA50)
* Bollinger Bands
* VWAP (Volume Weighted Avg Price)
* RSI (Relative Strength Index)
* MACD (Trend + momentum)
* ATR (Volatility)
* OBV (Volume trend)

### 📊 Analytics Dashboard

* Live price tracking
* Daily % change
* 52-week high/low
* Market cap insights
* Average volume

### 📉 Statistics Module

* Mean, Variance, Standard Deviation
* Skewness & Kurtosis
* Sharpe Ratio
* Max Drawdown
* Daily returns analysis

### 📋 Data Features

* Recent OHLCV table
* CSV export support
* Clean tab-based layout

---

## 🛠 Tech Stack

| Layer                 | Technology               |
| --------------------- | ------------------------ |
| Frontend              | Streamlit                |
| Visualization         | Plotly                   |
| Data Source           | Yahoo Finance (yfinance) |
| Data Processing       | Pandas                   |
| Numerical Computation | NumPy                    |
| Styling               | Custom CSS               |

---

## 📁 Project Structure

```
FinanceDashboard/
│
├── app.py                  # Main Streamlit application
│
├── src/
│   ├── config.py           # Settings & constants
│   ├── data_fetcher.py     # Fetches stock data
│   ├── indicators.py       # Technical indicators logic
│   └── charts.py           # Plotly chart builder
│
├── assets/
│   └── style.css           # Custom UI styling
│
├── tests/
│   └── test_indicators.py  # Unit tests
│
├── requirements.txt
└── README.md
```

---

## ⚡ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/your-username/FinanceDashboard.git
cd FinanceDashboard
```

### 2. Create virtual environment

```bash
python -m venv venv
```

Activate:

```bash
# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
streamlit run app.py
```

Open:

```
http://localhost:8501
```

---

## 🖥 Usage

| Task              | Action           |
| ----------------- | ---------------- |
| Select stock      | Sidebar dropdown |
| Change timeframe  | Sidebar slider   |
| Toggle indicators | Overlay switches |
| View analytics    | Tabs section     |
| Export data       | Download CSV     |

---

## 🧪 Testing

Run all tests:

```bash
pytest tests/ -v
```

---

## 🏗 Architecture

```
app.py (UI Layer)
   │
   ├── data_fetcher.py → Fetch stock data
   ├── indicators.py   → Calculate indicators
   └── charts.py       → Generate visualizations
```

---

## 📌 Key Highlights

* No API key required (uses Yahoo Finance)
* Fully interactive charts
* Clean modular architecture
* Beginner-friendly & production-ready
* Works offline with fallback logic (optional)

---

## 🚀 Future Improvements

* Portfolio tracking
* Real-time WebSocket data
* AI-based trading signals
* Multi-stock comparison
* Mobile optimization

---

## 🤝 Contributing

Contributions are welcome.

```bash
git checkout -b feature/new-feature
git commit -m "Add new feature"
git push origin feature/new-feature
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Aryan Modi**

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
