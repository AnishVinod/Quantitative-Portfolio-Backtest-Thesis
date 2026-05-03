# Portfolio Backtest: Diversified Multi-Asset vs. Nifty 50
### By Anish Vinod (with technical help from Gemini)

## What is this?
I wanted to see if a simple 40/30/30 mix—Indian stocks, US tech, and Gold—would actually perform better than just sticking with the Nifty 50. I used Python to look at the last five years of data (2021-2026) to find out.

## The Results
The numbers show that the diversified mix didn't just make more money; it was also less "jumpy" than the index.

| Metric | My Mix | Nifty 50 |
| :--- | :--- | :--- |
| **Total Return** | **124.0%** | **70.0%** |
| **Yearly Return** | **15.35%** | **10.64%** |
| **Risk (Volatility)** | **11.56%** | **13.95%** |
| **Sharpe Ratio** | **0.90** | **0.40** |

## Main Takeaways
- [cite_start]**Better Returns**: The mix ended with a total return of 124%, beating the Nifty 50 by 54%[cite: 7].
- [cite_start]**Lower Risk**: Even though it had tech stocks, the total risk was lower (11.56%) because Gold helped balance things out when markets were down[cite: 6, 8].
- [cite_start]**Efficiency**: The Sharpe Ratio of 0.90 shows the strategy was much more efficient for the amount of risk taken[cite: 6, 8].

## My Process
I used the `yfinance` library to pull the data and wrote a script to handle the math. I used Gemini as a co-pilot to help me clean up the code and fix bugs, which let me focus on the actual strategy and the results.

## Files
- [cite_start]`quantitative_thesis.pdf`: My full write-up[cite: 1].
- [cite_start]`backtest_engine.py`: The Python code I used[cite: 3].
