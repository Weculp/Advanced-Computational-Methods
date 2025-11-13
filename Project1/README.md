# Project1

## Overview

Implementation of Monte Carlo simulation techniques and random number generation methods for computational finance applications. Focus areas include variance reduction techniques, stochastic differential equations, and options pricing models.

## Files

- **PROJECT-1__MGMTMFE_432_SPR_2025__v2.pdf** - Problem statement and project requirements
- **Project1_406534669.ipynb** - Complete implementation notebook with all solutions
- **Project1_406534669.pdf** - Exported notebook with outputs and visualizations

## Topics Covered

### Lecture 1: Random Number Generation
- Linear Congruential Generator (LGM) implementation
- Binomial, Exponential, and Normal distributions
- Box-Muller and Polar-Marsaglia methods
- Performance comparison of algorithms

### Lecture 2: Monte Carlo Methods
- Wiener process simulation
- Geometric Brownian Motion
- European call option pricing
- Variance reduction techniques (Antithetic variates)

### Lecture 3: Advanced Techniques
- Euler and Milstein discretization schemes
- Greeks estimation (Delta, Gamma, Theta, Vega)
- Heston stochastic volatility model
- Quasi-Monte Carlo methods (Halton sequences)

## Key Features

- Custom random number generators without built-in libraries
- Black-Scholes formula implementation with numerical approximations
- Multiple variance handling schemes (Full Truncation, Partial Truncation, Reflection)
- Comprehensive visualization of results

## Requirements

```
numpy
matplotlib
scipy
```

## Notes

All implementations follow the specifications outlined in the problem statement. Code quality, accuracy, and execution speed were primary considerations in development.
