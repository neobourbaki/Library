The *polynomial ring* over a commutative ring $R$ (in one variable) is the commutative ring $R[x]$ of all polynomials

$$
p(x) = a_n x^n + a_{n-1} x^{n-1} + \cdots + a_1 x + a_0
$$

of degree $\leq n$, $n \in \mathbb{N}$, with coefficients $a_i \in R$. The operations of addition and multiplication are defined on the monomials by $x^n \cdot x^m = x^{n+m}$.

The *polynomial ring* over $R$ in $n$ variables is the polynomial ring $R[x_1, \ldots, x_{n-1}][x_n]$ over $R[x_1, \ldots, x_{n-1}]$, and is denoted $R[x_1, \ldots x_n]$. Elements of $R[x_1, \ldots x_n]$ can be written as a (finite) sum of *monomials* in $x_1, \ldots, x_n$ with coefficients in $R$,

$$
p(x_1, \ldots, x_n) = \sum_{I \in \mathbb{N}^n} a_{I} x^I
$$
