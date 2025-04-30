# STA2502: Jump-Diffusion Models for Financial Markets

This repository contains code and supplementary materials for a project investigating Jump-Diffusion models as extensions of the classical Black-Scholes framework. These models incorporate sudden, discontinuous changes (jumps) in asset prices, offering improved explanations for empirical features such as **leptokurtosis** and the **volatility smile** observed in financial markets.

## Overview

The project explores the mathematical foundations, simulations, and practical implications of two key Jump-Diffusion models:

- **Merton Model**: Introduces normally distributed jumps (lognormal multiplicative shocks).
- **Kou Model**: Uses an asymmetric double exponential distribution for jumps, allowing for more flexible modeling of upward and downward jumps.

Comparative simulations of these models against the Black-Scholes model highlight the effects of incorporating jump components into asset price dynamics and option pricing.

## Key Features

- 📈 Simulation of asset paths under Black-Scholes, Merton, and Kou models  
- 🔁 Implementation of Compound Poisson Processes to model jumps  
- 📊 Comparative plots for asset trajectories and European call option prices  
- 📘 Mathematical derivation of option pricing under the Merton model  
- 🧠 Interpretation of jumps as reflections of market sentiment and external shocks  

## File Structure

```bash
STA2502/
├── code/              
│   └── STA2502Report.ipynb                 # Code for generating sample paths and option pricing
├── figures/                                # Plots used in the report/presentation
├── Alex_Faassen_STA2502_Report.pdf         # Full project report
├── Alex_Faassen_STA2502_Presentation.pdf   # Presentation slides
└── README.md                               # This file