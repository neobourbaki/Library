Assume that $A$ is diagonalizable, i.e., $A = SDS^{-1}$ for some invertible matrix $S$ and diagonal matrix $D=\mathop{\mathrm{diag}}(\lambda_1, \ldots, \lambda_n)$ over $\mathbb{C}$. Then,

$$
e^A = \sum_{k=0}^{\infty} \frac{1}{k!} (SDS^{-1})^k = \sum_{k=0}^{\infty} \frac{1}{k!} SD^k S^{-1} = S e^D S^{-1}
$$

where $e^D$ is the diagonal matrix $\mathop{\mathrm{diag}}(e^{\lambda_1}, \ldots, e^{\lambda_n})$. It follows that 

$$
\det (e^A) = \det (e^D) = e^{\lambda_1} e^{\lambda_2} \cdots e^{\lambda_n} = e^{\lambda_1 + \lambda_2 + \cdots + \lambda_n}.
$$

On the other hand, 

$$
\mathop{\mathrm{tr}}(A) = \mathop{\mathrm{tr}}(SDS^{-1}) = \mathop{\mathrm{tr}}(DS^{-1}S) = \mathop{\mathrm{tr}}(D) = \lambda_1 + \cdots + \lambda_n
$$

and the identity follows.

For the general case, $D$ is not diagonal but can be made upper triangular, and the proof is identical.
