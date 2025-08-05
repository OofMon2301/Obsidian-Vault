# Quick Sort

**Randomised** divide-and-conquer sorting algorithm

Divide: pick a random element $x$ (called *pivot*) and partition $S$ into:
$L$ elements less than $x$
$E$ elements less than $x$
$G$ elements less than $x$.

Recur: Sort $L$ and $G$,
Conquer: Join $L, E$ and $G$ together again
