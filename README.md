Designing a Data-Driven Robo-Advisor for Personalized Investment Portfolios

## Research & User Simulation
1. Defined Investor Personas

Created 3 sample investor profiles:

Conservative Carla: Age 55, risk score 2, goal: retirement
Moderate Mike: Age 35, risk score 5, goal: home purchase
Aggressive Alex: Age 25, risk score 8, goal: wealth growth
Each profile includes:

Age
Income
Risk tolerance (0–10 scale)
Investment goal
Time horizon

2. Simulated User Data (n=1000)

Generated synthetic investor data:

Age: 20–70
Income: log-normal distribution
Risk score: a function of age and income
Time horizon: dependent on goal and age

3. Historical ETF Analysis

Pulled 5 years of daily prices using yfinance for:

SPY (S&P 500), QQQ (tech), IWM (small-cap), BND (bonds), GLD (gold)
Computed:

Log returns
Annualized mean return, volatility
Sharpe ratio
Correlation matrix

## Tech Stack
Python (NumPy, Pandas, Seaborn, Matplotlib)
yfinance
Git, GitHub
