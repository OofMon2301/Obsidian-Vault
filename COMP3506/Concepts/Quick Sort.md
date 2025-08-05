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
Thus, the worst case running time of quick-sort is $\mathcal{O}(n^{2})$.

## Expected Running Time
Consider a recursive call of quick-sort on a sequence of size $s$

### Good Call
The sizes of $L$ and $G$ are each less than $3s \div 4$

### Bad Call
One of $L$ and $G$ has size greater than $3s \div 4$.

Good calls have a probability of $\frac{1}{2}$.
