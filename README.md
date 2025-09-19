# Financial Performance Analysis (SQL + Python)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mpclazz/Labwork/blob/main/financial-performance-sql-python/financial-performance-sql-python.ipynb)
[![nbviewer](https://img.shields.io/badge/View%20in-nbviewer-blue)](https://nbviewer.org/github/mpclazz/Labwork/blob/main/financial-performance-sql-python/financial-performance-sql-python.ipynb)

**Goal:** Monthly rollups for revenue & expense, KPIs (Net Income, Margin %), anomaly flags, and a 3-month revenue forecast.  
**Stack:** SQLite (SQL), pandas, matplotlib, statsmodels (Holt-Winters ETS).

## 🔎 Business Results
- **12-month revenue growth:** `<paste from summary cell>`
- **Avg margin (last 12m):** `<paste from summary cell>%`
- **Anomaly months (margin < 5%):** `<paste list>`
- **Next 3-month revenue forecast:** `<paste dict>`

## 📁 Key Files
- Notebook: [`financial-performance-sql-python.ipynb`](./financial-performance-sql-python.ipynb)
- Figures: [`figures/revenue_vs_expense.png`](./figures/revenue_vs_expense.png), [`figures/profit_margin.png`](./figures/profit_margin.png)
- Outputs: [`outputs/monthly_company.csv`](./outputs/monthly_company.csv), [`outputs/forecast_next_3_months.csv`](./outputs/forecast_next_3_months.csv)
- SQL: [`sql/monthly_rollup.sql`](./sql/monthly_rollup.sql)
- Repro: [`requirements.txt`](./requirements.txt)

## ▶️ Run Locally
```bash
pip install -r requirements.txt
# then open the notebook and Run All

