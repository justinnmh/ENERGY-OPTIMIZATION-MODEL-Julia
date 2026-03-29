# ENERGY-OPTIMIZATION-MODEL-Julia
#### An end-to-end project about finding the optimal energy mix under constraints such as cost, land use, and emissions. The problem was formulated using Mixed-Integer Linear Programming (MILP), with constraint modelling to represent real-world limitations. The model was solved using optimisation solvers in JuMP, while slackness analysis identified key limiting constraints and sensitivity analysis was used to evaluate how changes impact the solution.

### Tools: Julia (JuMP), HiGHS, Mosek
### Analysis: Mixed-Integer Linear Programming, Constraint Modelling, Optimisation, Slackness Analysis, Sensitivity Analysis
#### How to Run

1. Download .ipynb file
2. Install Julia (https://julialang.org)
3. Install required packages:
   using Pkg
   Pkg.add(["JuMP", "HiGHS"])

4. Run in Jupyter notebook.
