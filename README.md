# Volatility Shockwave Simulator

A quantitative finance simulation project that models sudden volatility shocks in financial markets and visualizes their impact on option pricing in real time. The simulator demonstrates volatility clustering, regime switching, and shockwave events while dynamically recalculating option prices and Greeks.


## Overview

Financial markets often exhibit non-constant volatility characterized by clustering and abrupt regime changes. This project provides a simulation environment that:

* Models stock price dynamics using Geometric Brownian Motion (GBM)
* Introduces stochastic volatility regime switching
* Simulates sudden crash events (“volatility shockwaves”)
* Recalculates option prices using the Black–Scholes model
* Computes key option Greeks dynamically
* Presents results through a cinematic, dark-themed animated visualization

The system is designed for educational purposes, research demonstrations, and portfolio risk visualization experiments.

<img width="1366" height="663" alt="Figure_1" src="https://github.com/user-attachments/assets/725e0b22-f1ab-406e-9507-132f95686792" />
<img width="1366" height="663" alt="Figure_2" src="https://github.com/user-attachments/assets/786e60aa-d1c1-498f-9a5e-0845afa236b2" />
<img width="600" height="326" alt="Screenshot_1" src="https://github.com/user-attachments/assets/f88c021f-675a-48fb-8fe7-7e5abe6471d5" />

## Key Features

### Market Simulation

* Geometric Brownian Motion (GBM) price evolution
* Randomized volatility regime transitions
* Sudden crash and shockwave injection events
* Volatility clustering behavior

### Option Pricing

* Black–Scholes European option pricing
* Real-time recalculation of:

  * Delta
  * Vega

### Visualization

* Animated stock price chart
* Highlighted volatility spikes
* Live option price tracking
* Vega meter and volatility indicator
* Shockwave status display
* Dark, cinematic theme

## Volatility Clustering

Volatility clustering is a widely observed market phenomenon in which high-volatility periods tend to be followed by high volatility, and low-volatility periods tend to persist.

This simulator models clustering through:

* Regime-based volatility switching
* Randomized shockwave injections
* Time-dependent volatility states

The application will launch an animated visualization window displaying:

* Real-time simulated stock price
* Volatility spikes
* Dynamic option pricing
* Greeks metrics panel


## Requirements

All required dependencies are listed in `requirements.txt`.

Typical dependencies may include:

* Python 3.9+
* NumPy
* SciPy
* Matplotlib
* Other supporting scientific libraries

Please refer to the `requirements.txt` file for exact versions.



## How to Fork the Project

1. Navigate to the repository page on GitHub.
2. Click the **Fork** button in the top-right corner.
3. Clone your fork locally:

```bash
git clone https://github.com/your-username/volatility-shockwave-simulator.git
```

4. Create a new branch for your modifications:

```bash
git checkout -b feature-name
```

5. Commit and push your changes:

```bash
git push origin feature-name
```


## Potential Extensions

* GARCH-based volatility modeling
* Implied volatility surface visualization
* Multiple option types (Calls and Puts)
* Monte Carlo pricing comparison
* Risk metrics (Gamma, Theta, Rho)
* Exportable simulation logs

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**
