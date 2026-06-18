Quantitative Financial Pricing Engine - Learning Notes

Purpose

This project implements the Black-Scholes model to calculate the price of a European call option using Python.

The project demonstrates:

* Quantitative finance
* Mathematical modelling
* Numerical computing
* Data visualisation

⸻

Libraries Used

NumPy

Used for numerical calculations such as:

* logarithms
* square roots
* exponentials

Import:

import numpy as np

SciPy

Used for statistical calculations.

Import:

from scipy.stats import norm

The function norm.cdf() calculates cumulative probabilities from the standard normal distribution.

Matplotlib

Used for visualisation.

Import:

import matplotlib.pyplot as plt

⸻

Black-Scholes Model

The Black-Scholes model estimates the fair value of a European option.

Inputs:

* S = Stock Price
* K = Strike Price
* T = Time to Maturity
* r = Risk-Free Interest Rate
* sigma = Volatility

Output:

* Call Option Price

⸻

What is Volatility?

Volatility measures how much a stock price fluctuates.

Higher volatility generally increases option value.

⸻

What are d1 and d2?

d1 and d2 are intermediate quantities used in the Black-Scholes formula.

They help estimate the probability that the option finishes in profit.

⸻

Visualisation

The project generates a graph showing:

Stock Price vs Option Price

As stock price increases, option value also increases.

⸻

Applications

This model is widely used in:

* Investment Banking
* Hedge Funds
* Risk Management
* Quantitative Finance

⸻

Workflow

Input Parameters
↓
Black-Scholes Function
↓
Option Price Calculation
↓
Generate Multiple Stock Prices
↓
Calculate Option Values
↓
Visualisation

⸻

Interview Summary

“I implemented a Black-Scholes option pricing model in Python using NumPy, SciPy, and Matplotlib. The project calculates European call option prices and visualises how option values change with stock price. This project strengthened my understanding of quantitative finance, mathematical modelling, and numerical computing.”
