# Monte Carlo Methods for SDEs

This repository contains a set of Jupyter notebooks for simulating and approximating Brownian Motion using various mathematical techniques, specifically targeting Monte Carlo methods and the Lévy-Ciesielski representation. The project includes two main parts:

1. **Monte Carlo Approximation of Brownian Motion**  
   This section focuses on simulating and approximating one-dimensional standard Brownian motion using Monte Carlo techniques, including proofs of approximations for realizations of Brownian paths.

2. **Lévy-Ciesielski Representation of Brownian Motion**  
   This section demonstrates the Lévy-Ciesielski representation of Brownian motion and applies Multilevel Monte Carlo methods to compute Brownian marginals. These techniques are valuable for applications such as option pricing in financial contexts.

3. **Option pricing using Multi Level Monte Carlo**
   Implements the Multilevel and standard Monte Carlo Euler-Maruyama methods to solve the Black-Scholes equation.

---

## Repository Structure

### Series 2a: Monte Carlo Approximation of Brownian Motion
- **`Series2a_Oscar_Romero`**: Contains the theoretical construction for the Monte Carlo approximation of Brownian motion.
- **`Series2a_code`**: Implements simulations of Brownian motion paths using Monte Carlo methods, provides visualizations of the Brownian paths, and proves approximation properties.

### Notebook 2: Lévy-Ciesielski Representation of Brownian Motion
- **`Series2b_Oscar_Romero`**: Includes the theoretical background for the Lévy-Ciesielski representation of Brownian motion.
- **`Series2b_code`**: Demonstrates the implementation of the Lévy-Ciesielski representation and applies Multilevel Monte Carlo methods to calculate Brownian marginals.

### Series 5b: Multilevel and Normal Monte Carlo Euler-Maruyama for the Black-Scholes Model
- **`Series5b_code`**: Implements the Multilevel and standard Monte Carlo Euler-Maruyama methods to solve the Black-Scholes equation.
  - Simulates the dynamics of the underlying asset price modeled by a stochastic differential equation (SDE).
  - Estimates the price of a European call option using these numerical methods.
  - Compares the results to the analytical solution given by the Black-Scholes formula.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd monte_carlo_sdes
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Navigate to the relevant directories and open the Jupyter notebooks using:
   ```bash
   jupyter notebook
   ```

---
