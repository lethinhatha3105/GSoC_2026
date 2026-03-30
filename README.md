# GSoC_2026
This notebook explores three approaches to this problem, each answering a different question:

- **Monte Carlo Simulation** — randomly generates one million portfolios and identifies the portfolio with the highest Sharpe ratio among the sampled portfolios. This is a brute-force approach that explores the risk-return space broadly but relies on random sampling and provides only an approximate solution.

- **Risk Parity** — finds the portfolio in which each asset contributes equally to total portfolio risk, regardless of expected return. This leads to a more balanced distribution of risk across assets.

- **Quadratic Programming** — solves the optimization problem deterministically for each value of a risk-aversion parameter $\lambda$, providing a parametric representation of the efficient frontier and identifying the portfolio with the optimal risk-return trade-off. This is a more systematic and precise approach than Monte Carlo simulation.

