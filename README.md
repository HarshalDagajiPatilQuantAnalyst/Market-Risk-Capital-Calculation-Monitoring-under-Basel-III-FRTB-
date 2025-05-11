# VaR and CVaR Calculator: Excel & Python

This project calculates Value at Risk (VaR) and Conditional VaR (CVaR) using three methods:

1. Delta-Normal Approach
2. Historical Simulation
3. Monte Carlo Simulation

## 🔍 Features

- Excel-based implementation with formulas and templates.
- Python scripts using Alpha Vantage API for real-time data.
- Single and multi-asset portfolio support.

---

## 📊 Excel Files

Located in the `/excel/` folder:
- **Delta-Normal**: Calculates VaR & CVaR using mean and covariance matrix.
- **Historical**: Uses sorted historical returns to estimate percentile losses.
- **Monte Carlo**: Simulates returns using random normal distributions.

---

## 🐍 Python Scripts

Located in the `/python/` folder:

- `data_fetch_alpha_vantage.py`: Download historical stock data using Alpha Vantage API.
- `var_cvar_delta_normal.py`: Calculates Delta-Normal VaR and CVaR.
- `var_cvar_historical.py`: Historical approach.
- `var_cvar_monte_carlo.py`: Monte Carlo simulation.

---

## 📦 Requirements

Install via:

```bash
pip install -r requirements.txt

