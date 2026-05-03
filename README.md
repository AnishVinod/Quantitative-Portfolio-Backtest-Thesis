# Multi-asset portfolio backtest (2021-2026)
By Anish Vinod

### The Project
I wanted to test if a 40/30/30 split between the Nifty 50, US Tech (Nasdaq), and Gold would actually perform better than just holding the Nifty 50 index. I used Python to pull 5 years of data and compare the two.

### Results
The diversified mix ended up beating the Nifty 50 by about 54% in total returns. More importantly, it did it with less "swing" (lower volatility).

| Metric | 40/30/30 Mix | Nifty 50 |
| :--- | :--- | :--- |
| Total Return | 124.0% | 70.0% |
| Annualized Return | 15.35% | 10.64% |
| Annualized Risk | 11.56% | 13.95% |
| Sharpe Ratio | 0.90 | 0.40 |

### Observations
1. Higher Returns: The mix outperformed the benchmark significantly over the 5-year period.
2. Risk Management: Adding Gold helped lower the overall risk (11.56%) compared to the Nifty 50 (13.95%).
3. Efficiency: The Sharpe Ratio of 0.90 shows the strategy was about twice as efficient as just holding the index.

### Technical side
I used `yfinance` for the data and `pandas` for the math. I used Gemini as a co-pilot to help me debug the loops and get the plotting right, which saved a lot of time on the coding side.

### Files in repo
* `quantitative_thesis.pdf` - The full research write-up
* `backtest_engine.py` - The Python script used for the calculations
