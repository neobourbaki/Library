A *smooth* $n$-*manifold* is a set $M$, together with a collection $\\{(U_i, \phi_i)\\}$ of local coordinates on $M$, where $U_i \subset M$ and $\phi_i: U_i \to \mathbb{R}_n$, such that

- $M = \bigcup_i U_i$;
- for each pair $i, j$, the image $\phi_i(U_i \cap U_j)$ is open in $\mathbb{R}^n$; and

$$
\phi_j \circ \phi_i^{-1}: \phi_i(U_i \cap U_j) \to \phi_j(U_i \cap U_j)
$$

is smooth (infinitely differentiable) with a smooth inverse.
