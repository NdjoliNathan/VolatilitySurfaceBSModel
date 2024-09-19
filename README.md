---

# European Options Volatility Surface, Term Structure, Prices & Payoff (Black & Scholes Model)

This script provides an analysis of European options using real-time data from either Yahoo Finance (yfinance) or CBOE. While yfinance is the default due to ease of access, CBOE is used to ensure more reliable data when needed.

### Key Features:
- **Black & Scholes Model**: The script calculates implied volatility using the Newton-Raphson method based on the Black & Scholes option pricing model for European Options.
- **Data Sources**: Fetches option chain data from Yahoo Finance by default, with the option to switch to CBOE for more reliable market data.
- **Volatility Surface**: Generates a 3D surface representing the implied volatility against the strike price and time to expiration.
- **Greeks Calculation**: Computes key Greeks (Delta, Gamma, Theta, Vega, Rho) to measure risk sensitivities.
- **P&L Analysis**: Projects the potential profit and loss based on changes in the underlying asset's price.
- **Term Structure Visualization**: Illustrates how implied volatility varies with expiration dates.

### Optimization:
The script includes an optimization of the smoothing parameters to ensure accurate representation of the volatility surfaces.

- Libraries: `yfinance`, `numpy`,`scipy`, `pandas`, `matplotlib`, `requests`

### Note:
The markdown documentation within the script is in **French**.

---
