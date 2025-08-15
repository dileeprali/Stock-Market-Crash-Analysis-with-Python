# Stock-Market-Crash-Analysis-with-Python
This project analyzes 30 years of Sensex historical data to detect patterns that precede stock market crashes.
By combining statistical measures and visualization techniques, the goal is to build an early warning system that alerts investors before significant downturns.

## 🎯 Project Goals
* Identify precursors to market crashes using historical Sensex data.
* Understand how markets behave before, during, and after downturns.
* Create an early warning system based on recent return and volatility trends.

## 📊 Key Concepts
1.  Daily Returns
- What: Percentage change in closing prices from one day to the next.
- Why: Large negative returns may indicate sudden shocks or panic selling
- Formula:<img width="421" height="89" alt="daily return formula" src="https://github.com/user-attachments/assets/c92cea34-b74c-4244-8db4-750e454d7e4a" />

2. Drawdowns
- What: The percentage drop from the highest historical price to a given day’s price.
- Why: Measures the depth of a decline and highlights the severity of crashes
- Formula:<img width="383" height="77" alt="drawdowns" src="https://github.com/user-attachments/assets/78d039cf-c3ef-4493-abd3-01f2a1ad00c4" />

3. Rolling Metrics
- What: 10-day moving averages and volatility of daily returns.
- Why: Smooth out daily fluctuations to see short-term trends.

## 🚨 Early Warning System
Trigger Condition:
* Rolling mean return < -0.5%
* Rolling volatility > 2%
Purpose: Detect unstable periods where sustained losses and volatility suggest a crash risk



