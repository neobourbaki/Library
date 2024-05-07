A (formal) *power series* in a commutative ring $R$ is a (formal) expression

$$
\sum_{n=n_0}^{\infty} x_n \qquad \text{or} \qquad \sum_{n \geq n_0} x_n
$$

where $x_n \in R$ for each $n \geq n_0$. Formally, it is nothing but a map $\mathbb{Z} \to R$ that is zero for all $n \leq n_0$, with $x_n$ denoting the image of $n$.

The set of all power series is a ring, denoted $R[[x]]$, under addition and multiplication:

- $\sum x_n + \sum y_n = \sum (x_n + y_n)$
- $\sum x_n \cdot \sum y_n = \sum_n (x_i y_{n-i})$
