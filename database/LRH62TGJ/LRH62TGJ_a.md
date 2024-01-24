The integrand is a rational function of $\sin x$ and $\cos x$, so we may proceed via the rational parametrization of the circle: let $t = \tan(x/2)$, so that 

$$
\sin x = \frac{2t}{1+t^2} \qquad dx = \frac{2dt}{1+t^2}
$$

which results in

$$
\int_{-\pi}^{\pi} \frac{dx}{\alpha+\sin x} = 2 \int_{-\pi/2}^{\pi/2} \frac{dx}{\alpha+\sin x} = 2 \int_{-\infty}^{\infty} \frac{2dt}{\alpha(1+t^2)+2t}.
$$

Now, the integrand is a rational function of $t$, so that the primitive can be found by the method of partial fractions. In this case, the denominator is quadratic with no real roots, and we shall turn it into the form of the derivative of $\tan^{-1}$, to wit,

$$
\frac{1}{\alpha + 2t + \alpha t^2} = \frac{\alpha^{-1}}{(t+\alpha^{-1})^2+1-\alpha^{-2}} = \frac{1}{\alpha\beta^2}\frac{1}{(t/\beta+(\alpha\beta)^{-1})^2 + 1}
$$

where $\beta=\sqrt{1-\alpha^{-2}}$. This is seen to be the derivative of 

$$
\frac{1}{\alpha\beta}\tan^{-1}\left(\frac{t}{\beta} + \frac{1}{\alpha\beta} \right),
$$

so that at last the integral becomes

$$
\frac{4}{\alpha\beta} \left.\tan^{-1}\left(\frac{t}{\beta} + \frac{1}{\alpha\beta}\right)\right|_{-\infty}^{\infty} = \frac{4\pi}{\alpha\beta} = \frac{4\pi}{\sqrt(\alpha^2 - 1)}.
$$
