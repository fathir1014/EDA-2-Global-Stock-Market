# Global Stock Market Comparative Analysis

## Project Overview

This project is an exploratory research study on **how major global equity markets behave over time**.
Instead of focusing on prediction or trading strategies, the objective is to **understand the structural characteristics of different markets** through data-driven analysis.

The dataset contains historical index data from multiple countries, including:

* United States — S&P 500
* United Kingdom — FTSE 100
* Germany — DAX 40
* Japan — Nikkei 225
* India — NIFTY 50
* China — SSE Composite
* Brazil — Bovespa
* Turkey — BIST 100
* Saudi Arabia — Tadawul
* Indonesia — IDX Composite

This project treats the dataset as a **mini research laboratory** to explore global financial dynamics.

---

## Research Objective

To answer a central question:

> **How do global equity markets differ in growth, risk, resilience, and interconnectedness?**

---

## Core Research Questions

### 1 How Do Different Markets Grow Over Time?

We examine long-term performance by normalizing price levels to compare markets on an equal footing.

**Goal:**
Identify which markets demonstrate sustained compounding versus unstable or stagnant growth.

---

### 2 How Risky Is Each Market?

We quantify volatility using return-based statistics rather than price movement alone.

**Goal:**
Understand how much uncertainty investors experience in each region.

---

### 3 How Do Markets Behave During Stress Periods?

Through drawdown analysis, we study how markets react to crises and how quickly they recover.

**Goal:**
Measure resilience, not just fluctuation.

---

### 4 Are Global Markets Actually Connected?

By analyzing correlations between market returns, we evaluate whether diversification across countries truly reduces risk.

**Goal:**
Test the assumption of global synchronization.

---

## Analytical Approach

The study follows a structured financial time-series workflow:

1. Data Cleaning & Alignment
2. Return Computation
3. Price Normalization
4. Volatility Measurement
5. Drawdown Analysis
6. Cross-Market Correlation Study
7. Comparative Risk–Return Evaluation

This is intentionally **analysis-first**, avoiding predictive modeling to focus on understanding market mechanics.

---

## Project Structure

```
GLOBAL_STOCK_MARKET_INDICES/

├── data/
│   ├── raw/                # Original datasets
│   └── processed/          # Cleaned/aligned data (if created)

├── notebooks_exploration/  # Experimental analysis (research sandbox)

├── notebooks_portfolio/    # Final structured analysis

├── outputs/
│   ├── figures/            # Generated visualizations
│   ├── tables/             # Summary statistics
│   └── reports/            # Exported findings

├── src/                    # Reusable analytical functions (optional)

└── README.md
```

---

## Why This Project Matters

Many beginner projects jump directly into machine learning models without understanding the data-generating process.

This project emphasizes:

* Financial intuition before modeling
* Time-series reasoning instead of static analysis
* Comparative thinking across economies
* Reproducible analytical workflow

It serves as a foundation for future work in:

* Quantitative finance
* Economic modeling
* Machine learning on financial data

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## Project Status

Currently in the **Exploratory Research Phase**.
Insights and structure will evolve as analysis deepens.

---

## Future Extensions (Not Yet Implemented)

* Rolling correlation regimes
* Risk-adjusted performance metrics (Sharpe-style analysis)
* Regime detection
* Integration with macroeconomic indicators
* Transition into modeling and forecasting (post-analysis)

---

## Data Source

The dataset is obtained from Kaggle:
(https://www.kaggle.com/datasets/jacksaleeby/global-stock-market-indices-4-6m-rows)

Due to licensing restrictions, raw data is not included in this repository.
Please download the dataset manually and place it inside:

data/raw/

## License

This project is for educational and research purposes.
