The Lie algebra of $\mathrm{SL}_n(K)$ is, by definition, the set of matrices $X \in M_n(K)$ such that

$$
I + \epsilon X \in \mathrm{SL}_n(K) = \\{ M \in M_n(K) \\; : \\; \det(M) = 1 \\}
$$

up to order $\epsilon^2$. Using the expansion of the $n \times n$ determinant, we have

$$
\begin{aligned}
\det(I + \epsilon X) &= (1 + \epsilon \\, X_{11}) (1 + \epsilon \\, X_{22}) \cdots (1 + \epsilon \\, X_{nn}) + O(\epsilon^2) \\\\
 &= 1 + \epsilon \\,, \mathrm{tr}(X) + O(\epsilon^2)
\end{aligned}
$$

thus $\mathrm{tr}(X) = 0$.
