Let $X$ be a topological space, and $A$ a module over a ring $R$. The $n$-*th* (singular) *cohomology* of $X$ with coefficients in $A$ is the quotient $R$-module

$$
H^n(X, A) := \mathrm{Ker}(d_{n+1}: C^{n} \to C^{n+1}) / \mathrm{Im}(d_{n}: C^{n-1} \to C^{n})
$$

where 

- $C^n = \mathrm{Hom}_R(C_n, A)$ is the set of homomorphism from $C_n$ to $A$ as $R$-modules (elements of $C^n$ are called *cochains*); 
- $C_n$ is the free $R$-module generated by the continuous maps $\Delta_n \to X$;
- $\Delta_n := \\{ (x_0, x_1, \ldots, x_n) \in \mathbb{R}^{n+1} \\; : \\; x_i \geq 0 \text{ for each }i, \text{ and } \sum_i x_i = 1 \\}$;
- $d_n : C^{n-1} \to C^n$ is the dual of the homomorphism $\partial_n: C_n \to C_{n-1}$ of $R$-modules;
- $\partial_n: C_n \to C_{n-1}$ is the boundary map given by

$$
\partial_n(\sigma) = \sum_{i=0}^n (-1)^i \sigma(x_0, \ldots, \hat{x}_i, \ldots, x_n)
$$

for each $\sigma: \Delta_n \to X$ (where $\hat{x}_i$ means that the coordinate $x_i$ is omitted).