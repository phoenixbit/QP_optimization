## Quantum vs Classical Portfolio Optimization

This project explores and benchmarks classical and quantum approaches to solving constrained portfolio optimization problems. We investigate whether quantum algorithms such as the **Quantum Approximate Optimization Algorithm (QAOA)** and **Quantum Annealing (via D-Wave)** can outperform traditional methods like **mean-variance optimization** under realistic constraints such as no short-selling, full capital allocation, and multiple assets.

By formulating the problem as a **Quadratic Unconstrained Binary Optimization (QUBO)** instance, we compare solution quality, computational performance, and constraint handling across three paradigms:

- **Classical optimization** (CVXPY)
- **QAOA** (IBM Qiskit)
- **Quantum Annealing** (D-Wave Ocean SDK)

This repository is intended as a prototype and proof-of-concept for applying quantum algorithms to real-world financial optimization challenges and hence, is not conclusive evidence to prove outright that the hypothesis is either true or null and void.

### Features
- Modular Jupyter Notebooks for each approach
- Clean dummy data and baseline comparisons (initial, subject to change)
- Optional extensions: real financial data, cardinality constraints, visualization
