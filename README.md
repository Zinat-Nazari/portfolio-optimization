# portfolio-optimization
# Portfolio Optimization Using Modern Portfolio Theory

## Overview
This project compares an optimized stock portfolio with an equal-weight portfolio using Markowitz Modern Portfolio Theory and Monte Carlo simulation.

The analysis uses historical daily stock data for Apple (AAPL), Microsoft (MSFT), and Tesla (TSLA).

## Methodology
- Historical stock return analysis
- Monte Carlo portfolio simulation
- Sharpe ratio maximization
- Out-of-sample evaluation
- Sensitivity analysis

## Results

### Optimized Portfolio Allocation

| Asset | Weight |
|---|---:|
| AAPL | 19.34% |
| MSFT | 74.33% |
| TSLA | 6.33% |

### Portfolio Comparison

| Metric | Optimized | Equal Weight |
|---|---:|---:|
| Daily Return | 0.3469% | 0.2723% |
| Daily Volatility | 1.1619% | 1.0730% |
| Sharpe Ratio | 0.2986 | 0.2538 |

The optimized portfolio performed better in the main evaluation, but the equal-weight portfolio achieved a higher Sharpe ratio in the out-of-sample test.

## Tools
Python, pandas, NumPy, yfinance, Matplotlib, Jupyter Notebook

## Project Files
- `portfolio_optimization.ipynb` — Python implementation and analysis.
- `portfolio_optimization_report.pdf` — Detailed research report.

## How to Run
Install the required libraries:

```bash
pip install yfinance pandas numpy matplotlib jupyter
```

Open `portfolio_optimization.ipynb` in Jupyter Notebook and run the cells in order.

## References
- Markowitz, H. (1952). *Portfolio Selection*. The Journal of Finance.
- Sharpe, W. F. (1966). *Mutual Fund Performance*. The Journal of Business.
