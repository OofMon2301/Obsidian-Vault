---
tags:
  - COMP3506
---
# Recursion

## Recursion Pattern
Recursion: when a method calls itself. A Classic example is factorial function:
$$
n! = 1 \times 2 \times 3 \times 4 \times \dots \times (n-1) \times n
$$
The recursive definition: 
$$ 
f(n) =
\begin{cases}
1, \text{ if } n=0 \\ \\
n \cdot f(n-1) \text{ else}
\end{cases}
$$
## Linear Recursion
Test for **base cases**. Begin by testing for a set of base cases
Every possible chain of recursive calls *must* eventually reach a base case. 

## Defining Arguments for Recursion
Recursive methods may require **additional parameters**.

We defined array reversal as *reverse_list(A, i, j)*, not *reverse_list(A)*.

## Tail Recursion

Recursive call as the **last step**
Result of the call must be used immediately and directly, or it is **not** a tail 