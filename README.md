# Black-Scholes Equation Derivation

This repository contains a concise derivation of the Black-Scholes equation for option pricing.

The document starts from a stochastic model for the price of the underlying asset, assumed to follow a geometric Brownian motion. It then applies Itô’s formula to the option price, constructs a delta-hedged portfolio to eliminate the stochastic component, and uses the no-arbitrage principle to derive the Black-Scholes partial differential equation.

The main topics covered are:

- geometric Brownian motion for asset prices;
- Itô’s formula applied to derivative pricing;
- construction of a risk-free hedged portfolio;
- delta hedging;
- no-arbitrage argument;
- derivation of the Black-Scholes PDE.

The final result is the classical Black-Scholes equation:

\[
\frac{\partial V}{\partial t}
+ \frac{1}{2}\sigma^2 S^2 \frac{\partial^2 V}{\partial S^2}
+ rS \frac{\partial V}{\partial S}
- rV = 0.
\]
