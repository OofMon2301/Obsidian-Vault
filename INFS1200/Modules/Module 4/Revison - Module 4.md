# Revision - Module 4 

## Functional Dependency

A functional dependency (FD) $X \to Y$ holds on relation $R$ if for every legal instance of $R$ such as $r$, for all tuples $t_{1},t_{2}$:
$$
\text{if }t_{1}[X] = t_{2}[X] \to t_{1}[Y] = t_{2}[Y]
$$
Example: Level $\to$ salary (i.e. if two employees have the same level, then they must have the same salary.)

An FD $X \to Y$ is a constraint between two sets of attributes $X$ and $Y$ in a relational schema $R$

It specifies a restriction on the possible tuples that can form a relation instance of $R$.