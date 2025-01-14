# Pairs_Trading
- Developed a pairs trading strategy using **cointegration** and **mean reversion** techniques.  
- Employed the **Euclidean distance method** to select stocks with similar historical price movements.  
- Constructed the spread between paired stocks and standardized it using **z-scores**.  
- Defined trading signals:  
  - **Entry**: Open positions when the z-score exceeds predefined thresholds (e.g., ±2).  
  - **Exit**: Close positions when the z-score reverts to the mean.  
- Backtested the strategy, achieving consistent profitability.  
- Explored improvements, including:  
  - Adjusting **long/short position ratios** for better risk management.  
  - Expanding the strategy to **generalized pairs trading** with ETFs for greater market coverage.  

