
# American Option Pricing & Numerical Methods

## Overview

This project implements and compares various numerical techniques for pricing American put options. The work was completed as part of the MGMTMFE 432 course at UCLA Anderson School of Management.

## Project Structure

### Documentation
- **Project2_CF.pdf** - Problem statement and project requirements
- **PS2_406534669.pdf** - Complete project report with theoretical background, implementation details, results, and analysis for all six problems

### Implementation
- **PS2_406534669.ipynb** - Jupyter notebook containing Python implementations of all pricing methods

## Methods Implemented

### Tree-Based Methods
- **Binomial Trees**: Cox-Ross-Rubinstein (CRR) and Jarrow-Rudd (JR) models with convergence analysis
- **Trinomial Trees**: Price-space and log-price-space implementations

### Monte Carlo Methods
- **Least Squares Monte Carlo (LSMC)**: Longstaff-Schwartz algorithm with multiple basis functions (Laguerre, Hermite, Monomial polynomials)

### Finite Difference Methods
- **Log-Price Space**: Explicit, Implicit, and Crank-Nicolson schemes
- **Spot-Price Space**: Explicit, Implicit, and Crank-Nicolson schemes

## Option Specifications

- **Type**: American Put Option
- **Strike Price**: $180
- **Initial Asset Price**: $180
- **Time to Maturity**: 0.5 years
- **Volatility**: 25%
- **Risk-Free Rate**: 5.5%

## Key Features

- Convergence analysis across varying time steps
- Greeks calculation (Delta, Theta, Vega) using finite difference approximations
- Stability analysis for different discretization schemes
- Comparative performance evaluation of all methods

## Requirements

- Python 3.x
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Pandas

## Results

The project demonstrates that:
- Trinomial trees converge faster than binomial trees
- Log-space transformations improve numerical stability
- Crank-Nicolson schemes provide optimal balance between accuracy and stability
- LSMC methods scale well with higher polynomial degrees

## Author

Vikalp Thukral (Student ID: 406534669)
