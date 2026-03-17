# Bacteria Growth Model

**Course:** CS166 – Minerva University  
**Date:** February 2025  
**Professor:** Prof. Tambasco

## Overview

This project models bacteria growth on a 2D grid coupled with a renewable food resource. Each time step:

- Food grows via a **logistic growth** rule and is capped (capacity 100)
- A small-probability **reseeding** event replenishes depleted cells
- Food **diffuses** to neighboring cells
- Bacteria **consume** food; if insufficient, starvation reduces the population
- Survivors **reproduce** with a growth rate
- Bacteria **diffuse** to neighboring cells

The simulation produces rich spatial dynamics (including wave-like / spiral patterns under certain initial conditions) and includes test cases to validate the implementation under different regimes (minimal food, plentiful food, no bacteria, etc.).

## Key Concepts

- Logistic growth
- Diffusion on a grid
- Resource-constrained population dynamics (consumption + starvation)
- Emergent spatial patterns in dynamical systems

## Tech Stack

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

