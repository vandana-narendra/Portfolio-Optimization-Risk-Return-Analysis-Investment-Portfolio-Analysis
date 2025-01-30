_# Portfolio Optimization: Evaluating Risk-Return Trade-offs Across Investment Strategies_
This project explores portfolio optimization and risk-return trade-offs using Python, focusing on helping investors make informed decisions about where to allocate their wealth based on historical performance and financial theory. 

## Objective
The primary aim of this project is to determine the most suitable portfolio for an investor with average risk aversion by analyzing and optimizing the following portfolios for mean-variance efficiency:
1. **All-Equity Portfolio**  
2. **Traditional 60/40 Portfolio**  
3. **Harry Browne’s Permanent Portfolio**  
4. **Ray Dalio’s All Seasons Portfolio**  
5. **Custom Optimized Portfolio**  

## Methodology
The analysis is conducted using historical annual returns data from 1926 to the present for various asset classes, including equities, bonds, Treasury bills, gold, and real estate. The study involves:
- Risk-return trade-off evaluation using metrics like mean return, standard deviation, Sharpe Ratio, Sortino Ratio, and Value at Risk (VaR).
- Portfolio optimization using Python’s `scipy.optimize` library to identify the portfolio with the maximum Sharpe Ratio.
- Visualization of risk-return characteristics and efficient frontiers.

## Key Findings
1. **All-Equity Portfolio**  
   - High risk and high return.
   - Suitable for aggressive investors with a long-term horizon.  

2. **Traditional 60/40 Portfolio**  
   - Balanced risk-return trade-off with moderate volatility.  
   - Ideal for mid-career investors seeking growth with stability.  

3. **Harry Browne’s Permanent Portfolio**  
   - Low risk and steady returns.  
   - Designed for risk-averse investors prioritizing stability and preservation of capital.  

4. **Ray Dalio’s All Seasons Portfolio**  
   - Moderately diversified with balanced risk and return.  
   - Suitable for investors with moderate risk tolerance.

5. **Custom Optimized Portfolio**  
   - Maximum risk-adjusted returns (highest Sharpe Ratio).  
   - Tailored for investors seeking an efficient balance of growth and risk.

## Tools and Techniques
- **Libraries Used**: Pandas, NumPy, Matplotlib, Seaborn, SciPy.  
- **Performance Metrics**:
  - **Mean Return**: Average annual return.  
  - **Standard Deviation**: Measures portfolio volatility.  
  - **Sharpe Ratio**: Return per unit of risk.  
  - **Sortino Ratio**: Return per unit of downside risk.  
  - **Value at Risk (VaR)**: Estimates potential loss in extreme scenarios.  
- **Visualizations**:
  - Efficient frontier graphs.  
  - Risk vs. return scatter plots.  
  - Cumulative returns over time.  
  - Portfolio comparisons of maximum drawdown, annualized volatility, and recovery times.
