# Mini Projects to Begin With
**1. Option Pricing with Black-Scholes vs. Real Market Data**
- Implement Black-Scholes and compare with real option prices (call & put)
- Analyse residuals to spot model limitations
- Visualise how BSM deviates with moneyness or volatility shifts

**2. Bayesian Calibration of Option Pricing Models**
- PyMC3 / PyMC4 or TensorFlow Probability
- Apply Bayesian inference to estimate the parameters of models like Black-Scholes or Heston!
- Simulate data from BSM/Heston
- Use MCMC to infer volatility and drift
- Visualise posterior distributions + uncertainty in price predictions

**3. Simulating Option Payoffs via Monte Carlo**
- Python, NumPy
- Pricing exotic options (Asian, barrier, lookback) via simulation
- Simulate GBM paths
- Use Monte Carlo to estimate option payoffs
- Try variance reduction techniques (antithetic variates, control variates)

**4. Volatility Surface Estimation using ML**
- Python, scikit-learn or PyTorch
- Volatility surface datasets (you can simulate them or scrape options chains)
- Use interpolation + regression or deep learning to model implied volatility surface
- Try Gaussian processes vs neural nets vs splines
- Extend to surface forecasting

**5. Building a Toy Pricing Engine**
- Python
- Build a basic engine to price different types of options and plot greeks
- Modular functions: input parameters → price, delta, gamma
- Add stochastic volatility model (e.g., Heston)
- Package it like a mini-library with documentation

**6. Detecting Arbitrage Opportunities with Statistical Testing**
- Python, statsmodels
- Options chain data (multiple strikes/maturities)
- Use put-call parity and arbitrage constraints to detect mispricings
- Run hypothesis tests or confidence intervals around pricing gaps
- Visualise arbitrage bands
