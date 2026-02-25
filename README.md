# Path Continuity (Stateful Phase-Lift)

**ID:** `core-path-continuity`  
**Tier:** core  
**Score:** 66  
**Units:** OK  
**Theory:** PASS  

## Equation

$$
\theta_{R,k}=\mathrm{unwrap}(\arg z_k;\,\theta_{R,k-1})
$$

## Description

Turns phase into a continuous real trajectory by chaining the unwrap rule sample-to-sample (except at true singularities like z=0).

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
