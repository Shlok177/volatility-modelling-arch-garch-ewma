# volatility-modelling-arch-garch-ewma
A volatility modeling project applying ARCH(1), GARCH(1,1), and EWMA (RiskMetrics) to 3-year S&amp;P 500 returns.


Volatility Modeling Using ARCH, GARCH, and EWMA

This project analyzes and forecasts financial market volatility using three popular econometric models:

ARCH(1) — Autoregressive Conditional Heteroskedasticity

GARCH(1,1) — Generalized ARCH

EWMA — Exponentially Weighted Moving Average (RiskMetrics)

The goal is to study volatility clustering, persistence, and how different models respond to market shocks using 1-year daily returns of TSLA.

📌 Project Highlights

Clean data pipeline (Yahoo Finance API via yfinance)

Log-returns calculation

Estimation of ARCH(1) & GARCH(1,1) using the arch package

EWMA volatility using RiskMetrics (λ = 0.94)

Volatility forecasts comparison

Plots & insights for clear interpretation

📊 Models Used
1. ARCH(1)

Variance depends only on the previous day’s squared return.

2. GARCH(1,1)

Industry standard.
Variance depends on:

Yesterday’s squared return (ARCH term)

Yesterday’s variance (GARCH term)

GARCH captures volatility persistence far better than ARCH.

3. EWMA (RiskMetrics)​


Simple, fast, widely used by risk desks.
