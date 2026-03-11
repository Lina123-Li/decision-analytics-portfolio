# System Regime Detection using Hidden Markov Models
## Overview
This project applies Hidden Markov Models (HMM) to identify latent system regimes characterized by different return–volatility dynamics. Regime-switching models are widely used in financial markets and operational systems to detect shifts between stable and unstable states. Using time-series data, the model estimates hidden states and transition probabilities to analyze how regimes evolve over time.


## Data
The analysis uses time-series return data derived from market observations.

Key variables include:
- daily returns
- volatility measures

This dataset was scraped directly from the Yahoo website and contains three elements: the S&P 500 Index as a broad market benchmark for identifying bull and bear markets; AI-related assets (Nvidia, AMD, SOXX) to capture the dynamics of the technology and semiconductor industries; and the VIX Index (^VIX).


## Methodology

The Hidden Markov Model assumes that the observed data are generated from a sequence of unobserved states.Each state follows a different probability distribution.
- Hidden Markov Models
- Regime detection
- Time-varying transition probabilities
