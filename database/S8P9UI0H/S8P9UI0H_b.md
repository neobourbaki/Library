Let 

$$
g(x) := f(x) - \int_{a}^{x} f'(t)\\,dt \\; , \qquad x \in I
$$

with $a$ fixed. By continuity of $f'$, the function $g$ is well-defined, and we are to show $g(b)=g(a)$. Indeed, by another Fundamental Theorem of Calculus, the integral is differentiable with respect to the upper limit, and

$$
g'(x) = f'(x) - \frac{d}{dx}\int_a^x f'(t)\\,dt = f'(x) - f'(x) = 0
$$

at any $x\in I$. It follows that $g$ is constant, by an application of the mean value theorem.

In the case that $f'$ fails to exist at either $x=a$ or $x=b$, we may use a continuity argument.
