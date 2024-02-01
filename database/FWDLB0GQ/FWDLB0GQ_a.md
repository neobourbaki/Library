Assume that $A$ is diagonalizable, i.e., $A = SDS^{-1}$ for some invertible matrix $S$ and diagonal matrix $D$. Then,

$$
e^A = \sum_{k=0}^{\infty} \frac{1}{k!} (SDS^{-1})^n = \sum_{k=0}^{\infty} \frac{1}{k!} SD^n S^{-1} = S e^D S^{-1}
$$

where $e^D$ is the diagonal matrix where the $i$-th diagonal entry is $e^{\lambda_i}$, $\lambda_i$ being the $i$-th diagonal entry of $D$. It follows that 

$$
\det (e^A) = \det (e^D) = \prod_i e^{\lambda_i} = e^{\sum_i \lambda_i}.
$$

On the other hand, the trace of $A$ is the trace of $D$, which is $\sum_i \lambda_i$.

For the general case, $D$ is not diagonal but upper triangular (say in the Jordan canonical form of $A$), and the proof is identical.
