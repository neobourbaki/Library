By repeated application of the Fundamental Theorem of Calculus, one can express
the value of $f(b)$ in terms of as much local information of $f$ at $x=a$ as possible, 
and the terms of the Taylor series simply fall out, along with an exact expression
for the remainder. To wit,

$$
\begin{aligned}
f(b)=f(a)+\int_a^b & \underbrace{f'(x_1)} \\,dx_1 \\\\
 &  f'(a) + \int_a^{x_1} \underbrace{f''(x_2)}\\,dx_2 \\\\
 & \qquad\qquad\quad\\; f''(a)+ \int_a^{x_2} \underbrace{f'''(x_3)}_{\vdots}\\,dx_3
\end{aligned}
$$

and by evaluating the integrals of the constant terms, we obtain the identity

$$
f(b) = f(a) + f'(a) (b-a) + f''(a)\frac{(b-a)^2}{2} +  \int_a^b\\! \int_{a}^{x_1}\\!\\! \int_{a}^{x_2} f'''(x_3)\\,dx_3 dx_2 dx_1
$$

for $f \in C^3$, for the sake of definiteness.

Now, with the bound $|f'''(x)|\leq M$ on the interval $[a, b]$, the triple integral is bounded by

$$
\left| \iiint f'''(x_3)\\,dx_3 dx_2 dx_1 \right| \leq M \left| \iiint dx_3 dx_2 dx_1 \right| = M\frac{|b-a|^3}{3!}
$$

either by a direct evaluation of the *iterated integral*, or by recognizing it 
as the volume of a (right-angled) tetrahedron.

This works verbatim for $f \in C^{n}$ for any $n\geq 1$:

$$
f(b) = \sum_{k=0}^{n-1}\frac{f^{(k)}(a)}{k!} (b-a)^k +  \int_{a}^{b}\\! \int_{a}^{x_1}\\!\\!\\!\\!\cdots\\! \int_{a}^{x_{n-1}} f^{(n)}(x_n)\\,dx_n\cdots dx_2 dx_1
$$

where the $n$-fold iterated integral is simply bounded by

$$
\frac{M}{n!}|b-a|^n
$$

as claimed; the only calculation incolved is that, for $k=1,\ldots,n$,

$$
\int_{a}^{b}\\! \int_{a}^{x_1}\\!\\!\\!\cdots\\! \int_{a}^{x_{k-1}} dx_k\cdots dx_2 dx_1 = \frac{(b-a)^k}{k!}
$$

which is the (signed) volume of a particular $k$-simplex.
