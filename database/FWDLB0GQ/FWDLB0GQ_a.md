Assume that $A$ is diagonalizable, i.e., $A = SDS^{-1}$ for some invertible matrix $S$ and diagonal matrix $D=\mathop{\mathrm{diag}}(\lambda_1, \ldots, \lambda_n)$. Then,

$$
e^A = \sum_{k=0}^{\infty} \frac{1}{k!} (SDS^{-1})^k = \sum_{k=0}^{\infty} \frac{1}{k!} SD^k S^{-1} = S e^D S^{-1}
$$

where $e^D$ is the diagonal matrix $\mathop{\mathrm{diag}}(e^{\lambda_1}, \ldots, e^{\lambda_n})$. It follows that 

$$
\det (e^A) = \det (e^D) = \prod_i e^{\lambda_i} = e^{\sum_i \lambda_i}.
$$

On the other hand, the trace of $A$ is the trace of $D$, which is $\sum_i \lambda_i$.

For the general case, $D$ is not diagonal but can be made upper triangular (working over $\mathbb{C}$ if necessary), and the proof is identical.
