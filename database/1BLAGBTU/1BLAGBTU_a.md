Let $\mathcal{C}$ be a category with a faithful functor $U: \mathcal{C} \to \mathcal{Set}$, and $A$ a set (an object in $\mathcal{Set}$). A *free object* on $A$ in the category $\mathcal{C}$ is an object $F_A$ in $\mathcal{C}$, together with an injection $i: A \to U(F_A)$, that satisfies the following universal property:

- For any object $B$ in $\mathcal{C}$ and any map $g: A \to U(B)$ of sets, there exists a unique morphism $f: A \to B$ in $\mathcal{C}$ such that $g = U(f) \circ i$.

In other words, there exists a bijection

$$
\mathrm{Mor}_{\mathcal{C}}(F_A, B) \cong \mathrm{Mor}_{\mathcal{Set}}(A, U(B))
$$

(that is, $A \mapsto F_A$ is the left adjoint to the functor $U$).
