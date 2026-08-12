# US Inflation Dynamics & Monetary Policy

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ARIMA-GARCH](https://img.shields.io/badge/Model-ARIMA--GARCH-orange)]()

<img src="data/giphy (3).gif" width="700">
## Overview       

This project explores the relationship between **US inflation** and monetary policy (Federal Funds Rate). Using a two-phase analytical approach—**Exploratory Data Analysis (EDA)** followed by **advanced time-series modeling**—a hybrid **ARIMA-GARCH** model was developed to forecast both inflation trends and market volatility. The final model achieves an **RMSE of 0.409**, demonstrating high predictive accuracy. 
<img src="data/giphy.gif" width="300">

---

## Key Findings   <img src="data/money.gif" width="50">

- Inflation exhibits cyclical patterns and significant regime shifts over decades.
- The Federal Funds Rate generally follows inflation trends, confirming its role as a primary monetary policy tool.
- The correlation between inflation and interest rates is positive (~0.71) but **not static**—it varies across different economic regimes.
- ARIMA residuals show **volatility clustering**, indicating heteroskedasticity and justifying the use of a GARCH model.

---

## Methodology     <img src="data/money.gif" width="50">

### 1. Exploratory Data Analysis (EDA)

- Time-series visualization of inflation and interest rates
- Lag correlation analysis
- Correlation heatmap (≈ 0.71)
- Rolling correlation analysis
- Statistical summary of the dataset

### 2. Time-Series Modeling (ARIMA)   

- Modeling the underlying inflation trend
- 12-month inflation forecasting
- Residual diagnostics

### 3. Hybrid ARIMA-GARCH Model   

- ARIMA models the conditional mean (trend)
- GARCH models conditional variance (volatility)
- Combined forecasting of inflation and uncertainty

---

## Results    <img src="data/money.gif" width="50">

- **Final Forecast:** Reliable inflation predictions using the hybrid ARIMA-GARCH model
- **Performance Metric:** RMSE = **0.409**
- **Volatility Forecast:** Conditional variance successfully captures changes in inflation uncertainty

---

## Technologies Used   <img src="data/money.gif" width="50">

- Python
- Pandas
- NumPy
- Statsmodels
- ARCH
- Matplotlib
- Seaborn

---

## Getting Started  <img src="data/money.gif" width="50">

### Clone the Repository

```bash
git clone https://github.com/zahrarahgosha84-gif/inflation-analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

Open the notebook:

```text
inflation_test1.ipynb
```

and run all cells.

---

## Repository Structure   <img src="data/money.gif" width="50">

```text
inflation-analysis/
│
├── data/
│   ├── cpi.csv
│   └── interest_rate.csv
│
├── inflation_test1.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

**Zahra Rahgosha**

Economics Student | Alzahra University

