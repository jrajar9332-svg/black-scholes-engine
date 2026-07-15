# Black-Scholes European Option Pricing Engine

## Overview

This project is an open-source implementation of the **Black-Scholes-Merton model** for pricing **European-style call and put options**.

The primary goal is not simply to create a pricing calculator, but to develop a mathematically rigorous understanding of the Black-Scholes model by studying its assumptions, derivation, implementation, and validation against real market data.

This project is being developed as an educational and research-focused software project, with an emphasis on understanding the mathematics behind option pricing rather than treating the model as a black box.

---

## Project Objectives

Version 1.0 aims to:

- Accurately price European call options
- Accurately price European put options
- Calculate the Black-Scholes Greeks
- Visualise option prices and sensitivities
- Export pricing results for further analysis
- Validate model outputs against textbook examples and market data
- Provide clear documentation of every mathematical assumption and derivation

---

## Educational Philosophy

A core objective of this project is to understand **why** the Black-Scholes model works—not just how to implement it.

The mathematical foundations of the project include:

- Probability Theory
- Statistics
- Calculus
- Partial Differential Equations
- Stochastic Processes
- Brownian Motion
- Geometric Brownian Motion
- Itô's Lemma
- Risk-Neutral Valuation

Every equation implemented in code should be fully understood and documented.

---

## Project Structure


black-scholes-engine/

├── docs/              # Mathematical notes, assumptions and derivations
├── src/               # Python source code
│   ├── mathematics/
│   ├── pricing/
│   ├── greeks/
│   ├── validation/
│   └── visualization/
├── tests/             # Unit tests
├── data/              # Historical market data
├── notebooks/         # Research notebooks
└── examples/          # Example pricing scripts
```

---

## Technology Stack

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib
- Jupyter Notebook
- PyTest
- Visual Studio Code
- Git & GitHub

AI-assisted development tools such as Claude Code and Codex may be used to accelerate implementation. However, all generated code will be reviewed, tested, and understood before becoming part of the project.

---

## Validation

The pricing engine will be validated using:

- Published Black-Scholes examples
- Historical market data
- Broker pricing comparisons
- Error analysis and testing

The objective is to produce prices that closely match theoretical and observed market values within the assumptions of the Black-Scholes model.

---

## Future Development

Once Version 1.0 is complete, potential future work includes:

- American option pricing
- Monte Carlo simulation
- Binomial tree models
- Implied volatility calculations
- Volatility surface visualisation
- Alternative option pricing models

Version 1.0 will remain focused exclusively on European-style options to ensure a complete understanding of the Black-Scholes framework before expanding further.

---

## Contributors

### Jaswant

- Project architecture
- Software development
- Data collection
- Validation
- Documentation

### Dante

- Mathematical derivations
- Proofs
- Theoretical research
- Model verification

Both contributors collaborate closely to ensure that every implementation is mathematically correct and computationally accurate.

---


