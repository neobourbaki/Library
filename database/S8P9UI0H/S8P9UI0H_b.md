Let 

$$
g(x) := f(x) - \int_{a}^{x} f'(t)\\,dt 
$$

as a function of $x\in I$, with $a$ fixed. By continuity of $f'$, the function
$g$ is well-defined, and that $g(a)=f(a)$. By another Fundamental Theorem of Calculus,
the integral is differentiable with respect to the upper limit, and

$$
g'(x) = f'(x) - \frac{d}{dx}\int_a^x f'(t)\\,dt = f'(x) - f'(x) = 0
$$

at any $x\in I$. By the mean value theorem, there exists
$\xi\in (a, b)$ such that

$$
\begin{align*}
g(b) &= g(a) + g'(\xi)\\, (b-a) \\\\
&= g(a) \\\\
&= f(a).
\end{align*}
$$

Using the definition of $g$, we have

$$
f(b) - \int_{a}^{b} f'(t)\\,dt = f(a).
$$
