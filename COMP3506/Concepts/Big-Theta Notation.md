---
tags:
  - COMP3506
---
Big-$\theta$ notation describes a *tight bound* on a **function** (if one exists)

$f(n)$ is $\theta(g(n))$ if $f(n)$ is asymptotically *equal to* $g(n)$

Given functions $f(n)$ and $g(n)$, we say that $f(n)$ is $\theta(g(n))$ if there are positive constants $c_{1},c_{2}$, and $n_{0}$ such that
$$
c_{1} \cdot g(n) \leq f(n) \leq c_{2} \cdot g(n) \quad \text{for }n \geq n_{0}
$$

By definition, if $f(n)$ is in $O(g(n))$ **and** $f(n)$ is in $\Omega(g(n))$, then $f(n)$ must be $\theta(g(n))$.
