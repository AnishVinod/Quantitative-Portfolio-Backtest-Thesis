# Quantitative-Portfolio-Backtest-Thesis
A 5-year historical backtest (2021-2026) comparing a multi-asset strategy against the Nifty 50, featuring a 0.90 Sharpe Ratio and 54% Alpha.
Portfolio Optimization via Multi-Asset Diversification
Author: Anish Vinod | Technical Collaborator: Gemini (AI Co-Pilot)

 Executive Summary
This research analyzes the effectiveness of a 40/30/30 allocation (Nifty 50, US Tech, Gold) against the Nifty 50 benchmark[cite: 1, 4]. The backtest, conducted in Python, covers Jan 2021 to May 2026[cite: 1, 2].

Results Summary
| Metric | My Portfolio | Nifty 50 (Benchmark) |
| :--- | :--- | :--- |
| Total Return | 124.0% | 70.0% |
| Annualized Return | 15.35% | 10.64% |
| Annualized Risk | 11.56% | **13.95%** |
| Sharpe Ratio | 0.90 | 0.40 |

 Key Insights
- Alpha Generation: The strategy outperformed the benchmark by 54 percentage points[cite: 7].
- Risk Mitigation: The inclusion of Gold and Global Tech reduced annualized risk by ~2.4%[cite: 8].
- Efficiency: A Sharpe Ratio of 0.90 confirms superior risk-adjusted returns compared to the index[cite: 8].

 Repository Contents
- `quantitative_thesis.pdf`: Complete research paper.
- `backtest_engine.py`: Python script for data retrieval and metric calculation.
