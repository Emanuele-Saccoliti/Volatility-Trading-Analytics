# Volatility-Trading-Analytics


Developed a Python volatility crush analyzer to model and stress-test short and long ATM straddle strategies.
Integrated IBKR via API for soft real-time market and implied-volatility feeds and data, enabling live pricing and risk updates.
Integrated Black–Scholes pricing and Greeks computation (Δ, Γ, Vega, Θ) for real-time valuation and sensitivity monitoring.
Automated scenario and P&L stress-testing modules to assess long/short straddle exposures under spot/IV shocks.
The toolkit integrates a front-end analytics dashboard for live visualization of prices, Greeks, P&L and scenario outcomes,
supporting rapid option-risk assessment and intraday decision making.
Integrated robust IBKR connection management and data pipelines (multi-threaded API calls, historical data handling, error
logging) for reliable intraday operation.
The platform is designed to provide a scalable foundation for further automations and systematic strategy development.
