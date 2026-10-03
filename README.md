\# PCA Portfolio Risk \& Optimization — WIP



An exploratory Python project testing whether a PCA-based covariance estimate improves long-only minimum-variance portfolios.



\##Current experiment



\- Ten US-listed ETFs across stocks, bonds, gold, and real estate

\- Adjusted daily prices from 2010–2025

\- Monthly out-of-sample backtest from February 2012 through December 2025

\- Rolling 504-trading-day estimation window

\- Three-component PCA covariance model with asset-specific residual variance

\- Equal-weight and sample-covariance benchmarks



\##Preliminary result



PCA and sample covariance produced very similar allocations, largely concentrated in IEF and HYG. With an illustrative trading cost of 10 basis points per dollar traded, annualized returns were 3.017% for PCA and 2.940% for sample covariance. Their realized volatility was nearly identical. This experiment does not show a meaningful risk improvement from PCA.



Equal weight returned 6.364% after the same cost assumption, but held substantially more equity risk, so it serves as a benchmark rather than a like-for-like minimum-variance comparison.



\##Status and next steps



\*\*Work in progress.\*\* The notebook contains the exploration and initial backtest. Next steps are to clean up the code, test whether results change with a larger asset universe or shorter estimation window, and compare against covariance shrinkage. These are historical results, not an investment strategy.





