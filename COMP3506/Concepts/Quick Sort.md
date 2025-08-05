# Quick Sort

**Randomised** divide-and-conquer sorting algorithm

Divide: pick a random element $x$ (called *pivot*) and partition $S$ into:
$L$ elements less than $x$
$E$ elements less than $x$
$G$ elements less than $x$.

Recur: Sort $L$ and $G$,
Conquer: Join $L, E$ and $G$ together again

##  Worst-Case Running Time

Worst case for quick-sort occurs when the pivot is the minimum or maximum element
Running time is proportional to the sum $n +(n-1)+\dots+2+1$
