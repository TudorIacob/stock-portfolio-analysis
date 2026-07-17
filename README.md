# Portfolio Analysis with Quantstats

A Python-based financial analytics project designed to evaluate asset performance and risk metrics. This project leverages the **Quantstats** library to perform deep portfolio profiling on historical stock data, comparing individual asset returns against broader market benchmarks.

## 📊 Key Highlights & Metrics

This analysis downloads historical performance data for **Apple (AAPL)** and compares it against the **S&P 500 (SPY)** benchmark. 

Based on the historical performance profile generated in the notebook, key risk-adjusted performance metrics include:

*   **Compound Annual Growth Rate (CAGR):** **19.35%** (demonstrating strong long-term compounding growth)
*   **Sharpe Ratio:** **0.63** (evaluating risk-adjusted return)
*   **Maximum Drawdown:** **-81.80%** (highlighting historical volatility and worst-case peak-to-trough decline)
*   **Portfolio Greeks (vs. SPY):**
    *   **Beta:** **1.11** (indicating the asset is slightly more volatile than the market)
    *   **Alpha:** **0.18** (representing active excess return over the benchmark)

The project also generates key financial visualizations, including cumulative earnings curves, to help map out historical growth trajectories visually.

## 🛠️ Installation & Setup

To run this notebook locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/TudorIacob/stock-portfolio-analysis.git](https://github.com/TudorIacob/stock-portfolio-analysis.git)
   cd stock-portfolio-analysis
