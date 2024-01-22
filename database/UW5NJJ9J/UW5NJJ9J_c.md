It follows from repeated integration of the bound on $f^{(n)}$. For the sake of definiteness, take $n=3$, and assume $a < b$. Since 

$$
-M \leq f'''(x) \leq M \; , \qquad a < x < b
$$

and $f'''$ is continuous, we can integrate from $a$ to an arbitrary point $x_1 \in [a, b]$

$$
\int_{a}^{x_1} f'''(x) \\, dx \leq \int_{a}^{x_1} M \\, dx = M (x_1 - a)
$$

(the other inequality is similiar). By the Fundamental Theorem of Calculus, we have 

$$
f''(x_1) - f''(a) \leq  M (x_1 - a).
$$

We can now integrate both sides, regarded as functions of $x_1$, from $a$ to an arbitrary point $x_2 \in [a, b]$

$$
f'(x_2)-f'(a) - f''(a)\cdot (x_2 - a) \leq M \frac{(x_2 - a)^2}{2}`}.
$$

By the same token, we integrate the above (as functions of $x_2$`}) from $a$ to $b$

$$
f(b) - f(a) - f'(a)\cdot (b - a) - f''(a)\frac{(b -a)^2}{2} \leq M\frac{(b - a)^3}{3!}
$$

which, along with the other inequality, is exactly as claimed.

This clearly generalizes to $f\in C^{n}$ for any $n$:

$$
\left|f(b) - \sum_{k=0}^{n-1} \frac{f^{(k)}(a)}{k!}(b - a)^{k} \right| \leq \frac{M}{n!} |b - a|^{n},
$$

where the absolute value is inserted to account for the case $a > b$.
