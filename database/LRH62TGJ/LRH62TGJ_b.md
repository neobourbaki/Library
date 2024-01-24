By a change of variables $z = e^{ix}$, the integral can be turned into one over the unit circle in the complex plane:

$$
\sin x = \frac{z - z^{-1}}{2i} \qquad dx = \frac{dz}{iz}
$$

and the integral becomes

$$
\int_{-\pi}^{\pi} \frac{dx}{\alpha + \sin x} = \int_{\gamma} \frac{ dz / iz}{(\alpha + (z-z^{-1})/2i)} = \int_{\gamma} \frac{2 \\, dz}{z^2 + 2i\alpha z - 1}.
$$

The integrand is a rational function with two simple poles at the zeros of $z^2 + 2i\alpha z - 1 = (z+i\alpha)^2 + \alpha^2 - 1$,

$$
z_1 = i(-\alpha + \sqrt{\alpha^2-1} ) \qquad z_2 = i(-\alpha - \sqrt{\alpha^2-1})
$$

of which only $z_1$ is inside the unit circle, hence we only need to compute the residue at $z_1$,

$$
\text{Res}(f; z_1) = \lim_{z \to z_1} (z-z_1) f(z) = \left.\frac{ 2 }{(z-z_2)} \right|_{z=z_1} = \frac{1}{i\sqrt{\alpha^2-1}}.
$$

The residue theorem then yields

$$
\int_{\gamma} \frac{-2 \\, dz}{z^2 + 2i\alpha z - 1} = 2\pi i \\, \text{Res}(f; z_1) = \frac{2\pi}{\sqrt{\alpha^2 - 1}}
$$
