# Mean–Variance Portfolio Optimisation & Performance Attribution

This project implements a constrained mean–variance portfolio optimisation framework to construct and evaluate optimal risky portfolios using historical equity return data.

---

## Modelling Framework

Portfolio construction was carried out using:

- Monthly excess return estimation (Nov 2019 – Nov 2024)
- Covariance matrix computation
- Quadratic optimisation via Solver
- Efficient frontier construction
- Tangency portfolio identification

Two optimisation regimes were implemented:

- Unconstrained optimisation
- Restricted short-selling optimisation

To analyse systematic risk exposure, CAPM beta coefficients were estimated using regression against a market benchmark, enabling classification into:

- High-beta portfolios
- Low-beta portfolios

---

## Portfolio Performance (Out-of-Sample)

Portfolio performance was evaluated from:

**January 2025 – November 2025**

Risk-adjusted performance metrics included:

- Sharpe Ratio
- Treynor Ratio
- Sortino Ratio
- Jensen’s Alpha

The restricted short-selling tangency portfolio achieved improved risk-adjusted performance relative to the unconstrained portfolio:

Expected Monthly Excess Return: **2.10%**  
Volatility: **4.05%**  
Sharpe Ratio: **0.518**

This reflects the role of short-selling constraints as an implicit regularisation mechanism, improving diversification and reducing estimation error sensitivity in optimised portfolios.


---

## ESG Fund Construction

A socially responsible investment fund was constructed using:

- Strategic industry allocation
- Benchmark-relative weighting
- Performance attribution analysis

Fund performance was decomposed into:

- Allocation Effect
- Selection Effect

Attribution results indicated that strategic industry allocation was the primary contributor to relative performance.

---

## Tools Used

- Microsoft Excel
- Mean–Variance Optimisation
- CAPM Regression
- Quadratic Programming (Solver)
- Risk-Adjusted Performance Analysis

---

## Repository Contents

task1meanvariance.xlsx → Portfolio Optimisation Model  
Tasktwo.xlsx → ESG Fund Construction  
Portfolio_Construction_Report.pdf → Technical Report
