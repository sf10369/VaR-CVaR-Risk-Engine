# Portfolio Risk Management Engine

## Overview

This project implements industry-standard portfolio risk management techniques using five years of historical market data.

The objective is to estimate downside portfolio risk and compare different approaches used by risk managers and financial institutions.

---

## Concepts Covered

- Value at Risk (VaR)
- Expected Shortfall (CVaR)
- Historical Simulation
- Parametric VaR
- Portfolio Construction
- Risk Measurement
- Confidence Intervals (90%, 95%, 99%)

---

## Methodology

### 1. Data Collection

Downloaded five years of historical price data using Yahoo Finance.

Assets:

- AAPL
- MSFT
- NVDA
- GOOGL
- AMZN

### 2. Portfolio Construction

- Calculated daily returns
- Constructed an equally weighted portfolio
- Generated portfolio return series

### 3. Historical VaR

Calculated portfolio Value at Risk using historical simulation without assuming any probability distribution.

### 4. Expected Shortfall (CVaR)

Calculated Expected Shortfall as the average loss beyond the VaR threshold.

### 5. Parametric VaR

Estimated VaR using the normal distribution assumption and compared results with Historical VaR.

---

## Key Learning Outcomes

- Understanding what VaR measures
- Understanding the limitations of VaR
- Comparing Historical and Parametric approaches
- Measuring tail risk using CVaR
- Evaluating portfolio downside risk across confidence levels

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance

---

## Repository Structure

```
VAR_project.ipynb
README.md
```

---

## Author

Steve Fernandes

B.S. Data Science, University of Georgia (High Honors)

Incoming MSc Risk Management & Financial Engineering, Imperial College London
