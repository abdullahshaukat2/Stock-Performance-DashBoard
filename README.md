# Stock Performance Dashboard

An interactive dashboard to analyze and visualize the performance of major S&P 500 companies over the past 6 months. This project pulls stock data using Python, processes it with Pandas, and presents interactive visualizations.

---

## Features

- Fetches historical stock data using the **Yahoo Finance API** (`yfinance`).  
- Supports multiple tickers: AAPL, NVDA, JPM, BAC, GS, MS, C, WFC.  
- Computes daily returns and cumulative gains.  
- Exports data to Excel for further analysis.  
- Interactive visualization-ready for tools like **Tableau**.

---

## Tech Stack

- **Python 3.11+**  
- **yfinance** – fetch stock data  
- **pandas** – data manipulation  
- **openpyxl** – Excel export  
- **Jupyter Notebook / VS Code** – interactive development  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/stock-performance-dashboard.git
cd stock-performance-dashboard
