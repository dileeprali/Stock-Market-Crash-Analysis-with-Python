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

## charts
<img width="1239" height="482" alt="chart 1" src="https://github.com/user-attachments/assets/b66ea879-4fda-449f-99dc-2297e21277fc" />


<img width="1228" height="492" alt="chart 2" src="https://github.com/user-attachments/assets/2496c54b-36d3-481f-8a1d-ae601cb5514f" />

<img width="1234" height="494" alt="chart 3" src="https://github.com/user-attachments/assets/d3f9ba66-0f4b-4d11-bbfd-f90fac365284" />





