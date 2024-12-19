The *spectrum* of a ring $R$ is a locally ringed space:

- the underlying set is $X = \mathrm{Spec}(R)$ of all prime ideals $\mathfrak{p} \subsetneq R$;
- the *Zariski topology*: for any ideal $I \subset R$, the set $V_I := \\{ \mathfrak{p} \in \mathrm{Spec}(R) \\; : \\; \mathfrak{p} \supseteq I \\}$ is closed;
- the *structure sheaf* $\mathcal{O}_{X}$ is determined as follows: for $f \in R$

$$
\mathcal{O}_{X}(D_f) := R_{f}
$$

where $D_f := \\{ \mathfrak{p} \in \mathrm{Spec}(R) \\; : \\; f \notin \mathfrak{p} \\}$ is the *distinguished* open set.
