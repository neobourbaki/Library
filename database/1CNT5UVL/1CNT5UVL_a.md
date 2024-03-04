The *integral* of a continuous function $f: [a, b] \to \mathbb{R}$ on a closed interval $[a, b] \subset \mathbb{R}$ is

$$
\int_{a}^{b} f(x)\\, dx := \lim_{n\to\infty} \sum_{i=0}^{n-1} f(\xi_i) \frac{b-a}{n}
$$

where $\xi_i := a + i (b - a)/n$ is the left endpoint of the $i$-th subinterval.

If the function $f$ is piecewise continuous, then the *integral* of $f$ is the sum of the integrals over the pieces.
