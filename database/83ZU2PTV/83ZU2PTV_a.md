Let $f: U \to \mathbb{R}$ be a function on an open set $U \subseteq \mathbb{R}^n$. We say that $f$ is *differentiable at* $x^* \in U$ if there exists a linear map $L: \mathbb{R}^n \to \mathbb{R}$, called the *derivative of* $f$ *at* $x^* \in U$, such that

$$
f(x + h) - f(x_0) - L(h) = O(|h|^2)
$$

for $h \in \mathbb{R^n}$ as $h \to 0$. The *partial derivatives* of $f$ (at $x^*$) are the components of $L$, in the standard basis:

$$
L = [ \frac{\partial f}{\partial x_1}(x^*) , \frac{\partial f}{\partial x_2}(x^*), \ldots \frac{\partial f}{\partial x_n}(x^*) ]
$$

We say that $f$ is *differentiable* if $f$ is differentiable at all $x^* \in U$, and the *partial derivatives* $\frac{\partial f}{\partial x_i}$, $i=1, \ldots, n$, are functions $U \to \mathbb{R}$, taking $x^* \mapsto \frac{\partial f}{\partial x_i}(x^*)$.
