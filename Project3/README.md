# MGMTMFE 432 - Project 3: Exotic Derivatives and Fixed Income Securities

## Overview

This project implements advanced numerical methods for pricing exotic derivatives and fixed income securities. The analysis covers five main problems involving jump-diffusion models, stochastic volatility, interest rate models, and mortgage-backed securities.

## File Descriptions

### Problem Statement
- **PROJECT-3__MGMTMFE432_SPRING2025_.pdf**: Complete project requirements detailing five problems on exotic options, variance swaps, jump-diffusions, fixed income securities, and MBS valuation.

### Implementation
- **Project3CF.ipynb**: Python implementation containing executable code for all five problems, including Monte Carlo simulations, PDE solvers, and numerical methods.

- **Project3CFipynb.pdf**: PDF export of the Jupyter notebook showing code cells and their outputs.

### Documentation
- **Project3_CF_Writeup_Code_Snippet.pdf**: Comprehensive technical report (37 pages) documenting mathematical models, Python implementations with code snippets, simulation results, visualizations, and interpretations for each problem.

## Problems Covered

1. **Default Option Valuation**: Collateralized loan with jump-diffusion collateral dynamics
2. **Down-and-Out Put Options**: Stochastic volatility model with time-dependent barriers
3. **Fixed Income Securities**: CIR model for bond and option pricing using Monte Carlo and PDE methods
4. **G2++ Model**: Two-factor Gaussian model for European options on zero-coupon bonds
5. **Mortgage-Backed Securities**: MBS pricing with Numerix prepayment model, OAS computation, and IO/PO tranche valuation

## Technical Approach

All implementations use Monte Carlo simulation with variance reduction techniques where applicable. The CIR and G2++ models employ full truncation schemes to ensure numerical stability. Fixed income derivatives are cross-validated using both Monte Carlo and finite difference PDE solvers.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- SciPy
- Pandas
- Seaborn

## Author

Vikalp Thukral (UID: 406534669)  
UCLA Anderson School of Management  
June 2025
