# Reverse coevolving nonlinear voter model

Reference: https://www.nature.com/articles/s41598-017-13047-2

## Original model definition

Interaction is measured by $q$, and rewring happens at rate $p$. 

Phase diagram: $p,q$ with three different phases.

### Nonlinear voter model

- Start with an initial condition with opinions -1 or +1.
- Select a node $i$.
  - With probability $\rho_i^q$, selects one of the active neighbor $j$.
  - With probability $p$, remove the link. Otherwise, change the opinion assigning $\sigma_i = \sigma_j$.

$q$ is a parameter and $\rho_i = a_i/k_i$, with $a_i$ being the number of active links and connecting $i$ to a node in a different state, and $k_i$ its degree
