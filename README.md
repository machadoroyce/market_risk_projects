# market_risk_projects
1. Log_returns project:
"Used yfinance library to download 1 year close data of the Nifty index, HDFC Bank, TCS and Reliance stocks. Instead of percentage returns made this project in logarithmic returns to take advantage of it's mathematical properties. A simple comparison of the above variables(securities) through visualizing cumulative returns, a correlation heatmap and normal distribution of each."
2. Historical Value at Risk project:
"yfinance for data of Nifty, TCS and Reliance, percentage return of dates 1st jan 2024 to 1st jan 2025. Assumed VaR of 99% and 95% on portfolio value of Rs 1,00,00,000 with weights of 50%, 20%, 30% respectively."
3. Parametric Value at Risk project:
"same procedure as the historical VaR however, parametric VaR uses geometric returns(logarithmic returns), kept weights and confidence levels the same as above. Tested the formula on 10 days confidence level VaR's as well and at the end visualized the info by comparing the probability density function and a normal fit."
4. Monte Carlo Value at Risk project:
"same procedure same assets and same weights as above, used percentage returns instead and tried to plot it in normal distribution to understand where the confidence levels lie on the graph"
