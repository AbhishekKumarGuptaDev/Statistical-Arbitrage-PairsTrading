# 📈 Statistical Arbitrage System using Cointegration & Kalman Filter

Quantitative Finance • Statistical Arbitrage • Time Series Modeling • Backtesting • Portfolio Optimization

---

## 🚀 Live Project

📦 **GitHub Repository**
https://github.com/AbhishekKumarGuptaDev/Statistical-Arbitrage-PairsTrading

---

# 📌 Project Overview

A production-style **Statistical Arbitrage (Pairs Trading) framework** designed to identify and trade statistically related financial assets using **cointegration analysis, adaptive hedge ratio estimation, and quantitative backtesting**.

This system automates the complete quantitative research workflow:


✔ Market Data Collection

✔ Candidate Pair Discovery

✔ Cointegration Validation

✔ Dynamic Spread Modeling

✔ Trading Signal Generation

✔ Backtesting & Evaluation

✔ Parameter Optimization

✔ Deployment Configuration Export


Built as a modular framework inspired by quantitative hedge-fund research pipelines.

---

# 🎯 Business Objective

Traditional pair trading strategies often fail because relationships between assets change over time.

This project solves that problem using:

* Statistical validation of asset relationships
* Dynamic hedge ratio estimation
* Adaptive spread modeling
* Portfolio-level backtesting

Goal:

Generate market-neutral trading opportunities while reducing directional market exposure.

---

# 🏗 System Architecture

```text
Market Data (Yahoo Finance)
            │
            ▼
Data Cleaning & Alignment
            │
            ▼
Correlation Filtering
            │
            ▼
Cointegration Testing
(Engle–Granger)
            │
            ▼
OLS + Kalman Filter
Dynamic Hedge Ratio
            │
            ▼
Spread Construction
            │
            ▼
Z-Score Signal Engine
            │
            ▼
Backtesting Engine
            │
            ▼
Performance Analytics
            │
            ▼
Production Config Export
```

---

# 🧠 Quantitative Methods Used

## Statistical Selection Layer

* Pearson Correlation Filtering
* Engle–Granger Cointegration Test

## Spread Modeling

* Ordinary Least Squares (OLS)
* Dynamic Hedge Ratio via Kalman Filter

## Trading Logic

* Mean Reversion Strategy
* Z-Score Signal Generation
* Entry / Exit Threshold Logic

## Risk Management

* Position Controls
* Stop Conditions
* Portfolio Constraints

---

# ✨ Key Features

### 📊 Automated Data Pipeline

* Historical data ingestion using Yahoo Finance

### 🔍 Statistical Pair Discovery

* Detects economically related assets

### 🧠 Adaptive Hedge Ratio

* Kalman Filter updates exposure dynamically

### 📈 Quantitative Backtesting

* Trade logs
* Portfolio simulation
* Equity curve generation

### ⚙ Optimization Engine

* Multi-parameter evaluation
* Strategy comparison

### 🚀 Deployment Ready

* Export optimized production configuration

---

# 📊 Example Evaluation Metrics

| Metric           | Description               |
| ---------------- | ------------------------- |
| Sharpe Ratio     | Risk-adjusted performance |
| Portfolio Return | Strategy profitability    |
| Maximum Drawdown | Capital protection        |
| Win Rate         | Trade success percentage  |
| Trade Count      | Execution frequency       |
| Volatility       | Risk estimation           |

---

# 🛠 Tech Stack

| Layer         | Technologies            |
| ------------- | ----------------------- |
| Data          | yfinance, Pandas, NumPy |
| Statistics    | Statsmodels             |
| Modeling      | Kalman Filter           |
| Backtesting   | Backtrader              |
| Optimization  | Python                  |
| Visualization | Matplotlib              |
| Deployment    | JSON Config             |

---

# 📂 Project Structure

```bash
Statistical-Arbitrage-PairsTrading/
│
├── Notebooks/
│     ├── 01_stat_arb_kalman_backtest.ipynb
│     └── 02_kalman_optimization.ipynb
│
├── config/
│     └── kalman_prod_config.json
│
├── data/
│     ├── cleaned
│     ├── pairs
│     └── raw
│
├── reports/
│     ├── kalman_param_optimization_results.csv
│     └── portfolio_equity_curve.csv
│
├── src/
│     └── temp   
│
├── requirements.txt
└── README.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/AbhishekKumarGuptaDev/Statistical-Arbitrage-PairsTrading.git
```

## Move Into Project

```bash
cd Statistical-Arbitrage-PairsTrading
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🧪 Research Workflow

## Step 1 — Explore Market Relationships

```bash
Notebooks/01_stat_arb_kalman_backtest.ipynb
```

Performs:

* Data collection
* Correlation analysis
* Cointegration screening

---

## Step 2 — Run Optimization

```bash
Notebooks/02_kalman_optimization.ipynb
```

Performs:

* Hyperparameter search
* Portfolio simulation
* Performance ranking

---

## Step 3 — Deploy Best Configuration

```bash
config/kalman_prod_config.json
```

Export optimized settings for future execution.

---

# 📈 Future Roadmap

* Live Trading (Alpaca / IBKR)
* Walk Forward Validation
* Regime Detection Models
* Streamlit Dashboard
* Docker Deployment
* Cloud Scheduling
* Portfolio Allocation Layer

---

# 🏆 Learning Outcomes

Through this project:


✔ Applied quantitative finance concepts

✔ Built statistical trading systems

✔ Implemented adaptive state-space modeling

✔ Developed research → backtest → deployment workflow


---

# ⚠ Disclaimer

This project is intended solely for:

* Educational purposes
* Research experimentation
* Portfolio demonstration

It does **NOT constitute financial or investment advice.**

Real-world trading involves financial risk.

---

# 👨‍💻 Author

### Abhishek Kumar Gupta

B.Tech CSE (AI & ML)

Machine Learning • Quantitative Research • Financial Modeling

🔗 LinkedIn
https://www.linkedin.com/in/abhishek-kumar-gupta-55488a27a/

🔗 GitHub
https://github.com/AbhishekKumarGuptaDev

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork for experimentation
🚀 Share feedback & ideas
