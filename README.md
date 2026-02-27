# 📊 10-Year Financial Asset Analysis
### Bitcoin · Gold · Crude Oil · US Dollar Index (DXY)
**Analysis Period: January 2015 – January 2026**

---

## 🗂️ Project Overview

This project is a comprehensive, data-driven analysis of four major financial assets over a 10-year period. It was built as a final project for a Data Analysis course, covering everything from raw data ingestion to advanced statistical testing and professional visualization.

The goal is not just to describe historical price movements, but to uncover structural relationships, behavioral patterns, risk profiles, and macro-driven dynamics across these four distinct asset classes.

---

## 📁 Repository Structure
```
├── Final_Project_Oil_Gold_DXY_BTC.ipynb   # Main analysis notebook
├── Financial_Analysis_Report_2015_2026.pdf # Full written report & predictive analysis
├── files/
│   ├── bitcoin_2010-01-01_2026-01-01.csv
│   ├── crude-oil-price.csv
│   ├── Gold-XAU_1d_data.csv
│   └── US Dollar Index Historical Data.csv
└── README.md
```

---

## 📄 Analysis Report

A **full written report** is included in this repository as a PDF file:

📎 **`Financial_Analysis_Report_2015_2026.pdf`**

This document goes beyond the notebook and includes:
- Executive summary of all key findings
- Deep-dive analysis on each of the four assets
- Correlation & inter-asset relationship breakdown
- Summary of all statistical test results
- A timeline of the decade's most important market events
- **Forward-looking predictive analysis** for each asset based on identified cycles and structural patterns
- Portfolio construction insights and risk assessment

> **It is recommended to read the report after exploring the notebook**, as it ties together all analytical stages into a coherent narrative and provides context for the visualizations and statistical outputs.

---

## 🔍 What's Covered

### 13-Stage Analytical Pipeline

| Stage | Description |
|-------|-------------|
| 1 | Data loading & initial inspection |
| 2 | Individual asset cleaning (BTC, Oil, Gold, DXY) |
| 3 | DataFrame merging & descriptive statistics |
| 4 | Daily return calculation & normalization |
| 5 | Pairwise scatter plots & return correlation |
| 6 | Risk & performance analysis (Sharpe, Drawdown) |
| 7 | Time series analysis (monthly, quarterly, yearly) |
| 8 | Outlier detection & historical event mapping |
| 9 | Multi-timeframe correlation & regression analysis |
| 10 | Market event annotation & timeline |
| 11 | Advanced visualization suite (dashboards, heatmaps) |
| 12 | Statistical hypothesis testing |
| 13 | Final report & executive summary |

---

## 📈 Assets Analyzed

| Asset | Ticker | Type | Data Range |
|-------|--------|------|------------|
| Bitcoin | BTC | Cryptocurrency | 2015–2026 |
| Gold | XAU | Precious Metal | 2015–2026 |
| Crude Oil | WTI | Commodity | 2015–2026 |
| US Dollar Index | DXY | Currency Index | 2015–2026 |

---

## 📊 Key Visualizations

- **Price trend charts** — 10-year trajectory for each asset
- **Normalized comparison** — Min-Max scaled overlay of all four assets
- **Cumulative returns** — $1 invested in 2015, tracked to 2026
- **Return histograms** — Distribution shape and fat-tail behavior
- **Correlation heatmaps** — Daily, monthly, and quarterly timeframes
- **Rolling correlation** — 60-day dynamic relationship between asset pairs
- **Scatter plots with regression** — Pairwise return relationships
- **Hierarchical clustering dendrogram** — Behavioral grouping of assets
- **Outlier visualization** — Extreme price days marked on price charts
- **Event-annotated charts** — Major market events mapped to price action
- **Performance dashboard** — Multi-panel risk and return overview
- **Monthly/yearly heatmaps** — Seasonal pattern analysis
- **Q-Q plots & violin plots** — Statistical distribution diagnostics

---

## 🧪 Statistical Tests Applied

- **ANOVA** — Comparison of mean returns across assets
- **Mann-Whitney U** — Non-parametric pairwise post-hoc tests
- **Shapiro-Wilk** — Normality testing
- **Jarque-Bera** — Skewness and kurtosis (fat tails)
- **Kolmogorov-Smirnov** — Distribution comparison
- **Levene & Bartlett** — Variance homogeneity (heteroscedasticity)

---

## 🔑 Key Findings

- **Bitcoin** delivered the highest cumulative return of the group (thousands of percent) but with the highest volatility, deepest drawdowns, and most outlier events.
- **Gold** proved to be the most structurally stable asset, maintaining its role as a safe-haven and inflation hedge throughout the decade.
- **Oil** was the most externally disrupted asset — including the historic April 2020 negative price event — and shows the weakest correlations with the other assets.
- **DXY** functions as a macro barometer. Its inverse relationship with Gold is one of the most consistent correlations confirmed across the full study period.
- **All four assets** reject normality across every statistical test applied, confirming fat-tailed distributions and the inadequacy of standard normal-assumption models for risk estimation.
- **Correlation convergence** during crises was confirmed — assets that appear diversified in normal conditions tend to move together during acute market stress.

---

## 🛠️ Libraries & Tools
```python
pandas
numpy
matplotlib
seaborn
scipy
sklearn (MinMaxScaler)
arabic_reshaper        # Persian text rendering in plots
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn arabic-reshaper python-bidi
```

3. Open the notebook:
```bash
jupyter notebook Final_Project_Oil_Gold_DXY_BTC.ipynb
```

4. Make sure the `files/` directory with all four CSV datasets is in the same folder as the notebook.

---

## 📌 Notes

- The notebook uses an **inner join** on trading dates, so days where any single asset has missing data are excluded.
- Bitcoin trades 24/7 while traditional assets do not — this affects the merged dataset's date range slightly.
- All forward-looking statements in the report are **analytical projections** based on identified historical patterns — not financial advice.

---

## 👤 Author

**[Matin Zarei]**
Data Analysis Course — Final Project
*2026*

---


> ⭐ If you found this project useful or interesting, feel free to star the repository.
