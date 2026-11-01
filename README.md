# Stochastic Optimization for Assembly-to-Order Production

## Overview

This project addresses a production planning problem under uncertain demand using a two-stage stochastic programming approach.

The case study considers an Assembly-to-Order (ATO) manufacturing system producing three types of bicycles: Bike, E-City, and E-MTB.

The objective is to maximize expected profit while accounting for uncertain demand, production capacity constraints, and component availability.

The project was developed as part of the *Optimization and Simulation under Uncertainty* course at Politecnico di Torino.

## Methodology

A two-stage stochastic optimization model was implemented:

- **First-stage decisions:** determine component production quantities before demand is observed.
- **Second-stage decisions:** determine the quantities of finished products to assemble after demand is realized.

The analysis includes:

- **Sample Average Approximation (SAA):** approximation of the stochastic optimization problem using sampled demand scenarios.
- **In-sample and Out-of-sample Validation:** evaluation of solution stability and performance.
- **Value of the Stochastic Solution (VSS):** quantification of the economic benefit of stochastic optimization.
- **Expected Value of Perfect Information (EVPI):** estimation of the value of eliminating uncertainty.
- **Robustness Analysis:** evaluation of solution sensitivity to changes in demand parameters, scenario probabilities, and probability distributions.

## Results

The experiments demonstrate the economic benefits of explicitly accounting for demand uncertainty in production planning.

The stochastic approach achieves a higher expected profit than the deterministic strategy based on average demand.

The robustness analysis also evaluates how production decisions and economic performance change under alternative demand assumptions.
