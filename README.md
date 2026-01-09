# Gamma Reactor Management – Gamma Scalping Simulator

##  Project Overview
This project implements a *Gamma Reactor Management / Gamma Scalping Simulator* using Python.  
The objective is to simulate *delta-hedged option trading, analyze **gamma exposure, and evaluate **PnL dynamics* under transaction costs.

The model tracks:
- Option price (Black–Scholes)
- Delta & Gamma evolution
- Dynamic delta hedging
- Hedging transaction costs
- Daily & cumulative PnL

This project is designed for *Quantitative Risk / Trading roles* and demonstrates practical derivatives risk management.
---
##  Key Concepts Used
- Black–Scholes option pricing
- Delta hedging
- Gamma exposure
- Transaction cost modeling
- PnL attribution (Option + Hedge)
- Risk metric
---
##  Methodology (Step-by-Step)
1. Simulate underlying price path
2. Price European call option using Black–Scholes
3. Compute Greeks (Delta & Gamma)
4. Delta hedge daily
5. Apply transaction costs on hedge rebalancing
6. Calculate PnL
   - Option PnL
   - Hedge PnL
   - Total & cumulative PnL
7. Export results to CSV for analysis

---
###  Visual Outputs
- Price vs Time
- Delta & Gamma evolution
- Cumulative PnL curve

- Delta & Gamma evolution
- Cumulative PnL curve
