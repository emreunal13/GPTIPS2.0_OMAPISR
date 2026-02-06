
# GPTIPS2.0_OMAPISR

MATLAB code accompanying the paper **“Order of Magnitude Analysis and Data-Based Physics-Informed Symbolic Regression for Turbulent Pipe Flow”**.

This repository implements a physics-informed symbolic regression workflow to discover compact correlations for turbulent pipe friction factor **f = f(Re, ε/D)**, targeting accurate reproduction of Nikuradse rough
pipe trends while maintaining correct smooth/fully-rough asymptotics.

## Changes to GPTIPS-2 (summary)

We modified GPTIPS-2 core files and added new MATLAB functions to support:
- physics-informed constraints (C1/C2/C3/C4)
- multi-objective scoring (J_err, J_phys, complexity)
- plotting and reproducibility scripts for turbulent pipe-flow friction-factor modeling
- 3-D Pareto front
- New joint coefficient optimization (using Nelder-Mead and SVD-based least squares)

![Nikuradse's Friction Factor with GPTIPS_OMAPISR](CANDIDATE_1_MODIFIED.jpg)

## Upstream & license
This repository is based on **GPTIPS-2** by Dom Searson, licensed under the **GNU GPL v3.0**.
We modified GPTIPS-2 core files and added additional modules for physics-informed symbolic regression
(OMA-based constraints and multi-objective scoring) applied to turbulent pipe-flow friction modeling.

Accordingly, this repository is distributed under **GPL-3.0**. See `LICENSE.txt`.
