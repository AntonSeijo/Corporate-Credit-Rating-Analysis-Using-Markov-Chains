# Corporate Credit Rating Analysis Using Markov Chains

Application of **Markov chain theory** to model the evolution of corporate credit ratings and quantify default risk over multiple time horizons.

Credit ratings are treated as discrete states (AAA to D), with **default as an absorbing state**. A transition matrix drives the dynamics, allowing the computation of multi-year transitions, cumulative default probabilities, and expected loan returns.

## Features
- One-year and multi-year rating transition matrices
- Cumulative default probabilities by rating
- Expected payoff and net gain of a loan over time
- Numerical examples and visualizations

## Methodology
- Build or estimate a rating transition matrix from data
- Use matrix powers to obtain multi-year transitions
- Compute default probabilities and expected gains for a loan with initial capital `S₀`

## Authors
Antón Seijo Barrio
Juan Carlos Pajares García  
