# Merge Sort

Sorting algorithm based on the divide-and-conquer paradigm

**Guaranteed** $\mathcal{O}(n \log n)$ running time
This is **as good as it gets for worst case sorting**
	- Based on the "comparison" model

## Merge Sort
Sort input sequence $A$ with $n$ elements

Divide: Partition $A$ into two halves

Recur: Recursively sort each half

Conquer: Merge the two halves

### Merging Two Sorted Sequences

*Conquer Step*: