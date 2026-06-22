# Financial Modelling for Probability-Based Games

Monte Carlo and expected-value analysis of the financial design of two
probability-based games: a sequential coin-flip game and a scratchcard lottery.

## Overview

This project evaluates the mathematical and commercial viability of two game
designs developed for Chance It, a proposed mobile application combining gaming,
prize mechanics, and charitable giving.

- **Flip It** uses repeated coin-flip decisions and escalating potential payouts.
- **Crack It** uses a finite pool of scratchcards with prizes distributed across
  multiple tiers.

The analysis focuses on payout design, operator exposure, player incentives, and
the trade-off between attractive headline prizes and sustainable expected cost.

## Methodology

- Monte Carlo simulation of repeated game outcomes
- Expected-value and payout-distribution analysis
- Stress testing of high-multiplier jackpot structures
- Finite prize-pool design for scratchcard games
- Sensitivity analysis across probabilities, prize values, and player behaviour

## Repository Contents

- `Flip_It_Code.ipynb` - simulation and financial analysis for Flip It.
- `Crack_It_Code.ipynb` - scratchcard allocation and prize-pool analysis.
- `Report_1.pdf` - initial game mechanics and financial framework.
- `Report_2.pdf` - revised models, including the viability of a 100x headline
  prize and the distribution of scratchcard prizes.

## Running the Analysis

Open either notebook in Jupyter and run the cells in order. The analyses are
self-contained apart from the standard Python packages imported at the start of
each notebook.

## Key Skills Demonstrated

Monte Carlo simulation, probability, expected value, risk analysis, product
modelling, sensitivity analysis, and communicating quantitative findings.
