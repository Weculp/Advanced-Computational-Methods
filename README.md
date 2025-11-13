# Advanced Computational Methods in Financial Engineering

## Repository Overview

This repository contains implementations of advanced computational methods for pricing and analyzing complex financial derivatives and securities. The work encompasses Monte Carlo simulation, finite difference methods, tree-based algorithms, and various numerical techniques applied to options, fixed income securities, and structured products.

**Course**: MGMTMFE 432 - Computational Methods in Finance  
**Institution**: UCLA Anderson School of Management  
**Author**: Vikalp Thukral

## Projects

### Project 1: Foundational Option Pricing Methods

Implementation of core computational techniques for derivative pricing:

- **Binomial and Trinomial Trees**: American and European options with discrete dividends
- **Monte Carlo Simulation**: Asian options, variance reduction techniques
- **Implied Volatility**: Newton-Raphson and bisection methods
- **Finite Difference Methods**: Explicit, implicit, and Crank-Nicolson schemes for American puts

**Key Methods**: Tree models, Monte Carlo with control variates and antithetic variables, PDE solvers

---

### Project 2: Advanced Options and Term Structure Models

Extension to complex derivatives and interest rate products:

- **Exotic Options**: Lookback options, barrier options with rebates
- **Interest Rate Models**: Vasicek and CIR short rate models
- **Monte Carlo Applications**: Path-dependent options, interest rate derivatives
- **Numerical Integration**: Quadrature methods for option pricing

**Key Methods**: Advanced Monte Carlo, analytical solutions, Richardson extrapolation, term structure modeling

---

### Project 3: Exotic Derivatives and Fixed Income Securities

Advanced implementations of multi-factor models and structured products:

- **Jump-Diffusion Models**: Default option valuation with Poisson jumps
- **Stochastic Volatility**: Down-and-Out puts under Heston-type dynamics
- **Fixed Income**: CIR and G2++ models for bonds and options
- **Mortgage-Backed Securities**: MBS pricing with prepayment modeling, IO/PO tranches, OAS computation

**Key Methods**: Two-factor models, full truncation schemes, Numerix prepayment model, implicit FDM

---

## Technical Stack

- **Language**: Python 3.x
- **Core Libraries**: NumPy, SciPy, Pandas
- **Visualization**: Matplotlib, Seaborn
- **Numerical Methods**: Monte Carlo, finite differences, tree algorithms, root-finding, quadrature

## Repository Structure

```
Advanced-Computational-Methods/
├── Project1/
│   ├── README.md
│   ├── implementation files
│   └── documentation
├── Project2/
│   ├── README.md
│   ├── implementation files
│   └── documentation
└── Project3/
    ├── README.md
    ├── implementation files
    └── documentation
```

## Key Competencies Demonstrated

- Monte Carlo simulation with variance reduction
- Finite difference PDE solvers (explicit, implicit, Crank-Nicolson)
- Tree-based methods for American options
- Multi-factor stochastic models
- Interest rate term structure modeling
- Structured product valuation
- Numerical optimization and root-finding
- Statistical analysis and result interpretation

## Academic Integrity

This repository represents original academic work completed for MGMTMFE 432. The implementations follow standard financial engineering methodologies and are documented with appropriate citations where applicable.

## Contact

Vikalp Thukral  
UCLA Anderson School of Management  
Master of Financial Engineering Program
