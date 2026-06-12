# Portfolio Optimization in R
## VCU – Financial Analytics (FIRE 540)

Two complementary optimization exercises in R: **quantitative portfolio optimization** using real hedge fund return data, and **linear programming** applied to a resource allocation problem.

---

## Contents

### EDHEC Portfolio Optimization (`edhec-portfolio-optimization.html`)

Minimum variance and efficient frontier construction using the **EDHEC hedge fund index returns** — a real-world dataset spanning Convertible Arbitrage (CA), CTA Global (CTAG), Distressed Securities (DS), and Emerging Markets (EM) strategies.

**Techniques:**
- Unconstrained minimum variance portfolio (via quadratic programming)
- Constrained optimization (fully invested, long-only)
- Efficient frontier visualization
- Risk-return tradeoff analysis across hedge fund strategies

### Linear Programming – Jean the Farmer (`linear-programming-jean-farmer.html`)

A foundational linear programming problem: optimizing crop allocation (Parsnips vs Kale) across land and budget constraints to maximize profit. Step-by-step formulation from decision variables to interpreted solution.

**Techniques:**
- Decision variable definition
- Objective function formulation
- Constraint identification and inequality setup
- Feasible region visualization
- Solver implementation and solution interpretation

---

## Tech Stack

`R` `tidyverse` `tidyquant` `tbl2xts` `broom` `gt` `lpSolve` `Quarto`

---

*Virginia Commonwealth University · MS Business (Financial Analytics) · FIRE 540*
*Instructor: Prof. Larry Tentor*
