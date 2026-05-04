# The Bayesian-Kelly Pareto Frontier

### Optimal Transaction Acceptance under Information Uncertainty

## 1. The Core Signal

This repository introduces a rigorous derivation for the critical acceptance threshold in binary outcomes under uncertainty. By integrating the **Kelly Criterion** with a **Bayesian Beta-distribution** $(\alpha, \beta)$ update mechanism, we define a sharp boundary for growth.

The fundamental inequality for transaction acceptance is defined as:

$$b > \frac{\beta}{\alpha}$$

Where:

- **$b$**: The profit-to-loss ratio (odds).
    
- **$\alpha$**: The count of successful outcomes (plus prior).
    
- **$\beta$**: The count of failed outcomes (plus prior).
    

## 2. The Pareto Frontier

Unlike traditional models that require heavy Monte Carlo simulations, this model identifies the **Analytical Pareto Frontier** where the expected growth rate $\mathbb{E}[\ln(G)]$ transitions from negative to positive. It represents the "Path of Least Action" for capital preservation and accumulation.

## 3. Key Features

- **No-Work Elegance**: A closed-form solution that bypasses "Baroque" computational complexity.
    
- **Information-Theoretic Rigor**: Grounded in Shannon entropy and the Kelly growth logic.
    
- **Dynamic Updating**: The threshold self-corrects as new data $(\alpha, \beta)$ is ingested.
    

## 4. Repository Contents

- `manuscript.pdf`: The full theoretical derivation and proof.
    
- `src/`: Reference implementation (Python/Julia) to visualize the growth boundary.
    
- `latex/`: Source files for the manuscript.
    

## 5. Licensing & Attribution

This work is licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.
