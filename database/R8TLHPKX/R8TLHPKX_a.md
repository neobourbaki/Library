It is a direct computation.

$$
\begin{aligned}
[ \Delta, X ] &= \left[ \sum_i \partial_i^2, \sum_j x_j^2 \right] \\\\
&= \sum_{i,j} [\partial_i^2, x_j^2] \\\\
&= \sum_{i} [\partial_i^2, x_i^2] \\\\
&= \sum_i \left( \partial_i^2(x_i^2) + 2 \partial_i (x_i^2) \partial_i + x_i^2 \partial_i^2 - x_i^2 \partial_i^2 \right) \\\\
&= \sum_i (2 + 4x_i \partial_i) \\\\
&= 4\sum_i x_i \partial_i + 2n \\\\
&= 4 E
\end{aligned}
$$

where the operator $E$ (Euler operator with a shift) is defined by

$$
E = \sum_i x_i \partial_i + \frac{n}{2}.
$$

Next,

$$
[E, \Delta] = \sum_i [ x_i \partial_i, \partial_i^2] = \sum_i -2\partial_i^2 = -2 \Delta
$$

$$
[E, Q] = \sum_i [ x_i \partial_i, x_i^2] = \sum_i 2 x_i^2 = 2 Q
$$

thus, we can identify $H \mapsto E$, $X \mapsto \frac{1}{2}Q$, and $Y \mapsto \frac{1}{2}\Delta$, where $H, X, Y$ are the standard basis 

$$
H = \begin{pmatrix} 1 & \\\\ & -1 \end{pmatrix} \qquad X = \begin{pmatrix} & 1 \\\\ 0 & \end{pmatrix} \qquad Y = \begin{pmatrix} & 0 \\\\ 1 & \end{pmatrix}
$$

of $\mathfrak{sl}_2(K)$.
