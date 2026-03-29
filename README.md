# GSoC_2026
This notebook explores three approaches to this problem, each answering a different question:

- **Monte Carlo Simulation** — randomly generates one million portfolios and identifies the one with the highest Sharpe ratio. This is a brute-force approach that explores the risk-return space broadly but relies on random sampling and is only approximate.

- **Risk Parity** — finds the portfolio where every asset contributes equally to total portfolio risk, regardless of expected return. This leads to a more balanced and diversified allocation across assets.

- **Quadratic Programming** — solves the optimisation problem exactly for each value of a risk-aversion parameter $\lambda$, tracing out the efficient frontier and identifying the portfolio with the optimal risk-return trade-off. This is the most rigorous and precise of the three methods.
