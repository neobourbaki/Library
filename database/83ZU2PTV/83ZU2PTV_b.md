Let $f: U \to \mathbb{R}$ be a function on an open set $U \subseteq \mathbb{R}^n$. The *partial derivatives of* $f$ at $x^* = (x_1, \ldots, x_n) \in U$ are 

$$
\frac{\partial f}{\partial x_i} (x^*) = \lim_{h \to 0} \frac{f(x_1, \ldots, x_i + h, \ldots, x_n) - f(x_1, \ldots, x_n)}{h}
$$

for $i = 1, \ldots, n$. If the partial derivatives exists for all $x^* \in U$, and furthermore are continuous for $x^* \in U$, then the function $f$ is said to be *differentiable*.
