An $n\times n$ matrix $A$ over a commutative ring $k$ is *invertible* (over $k$) if $\det(A)$ has an inverse in $k$, and the *inverse matrix* of $A$, denoted $A^{-1}$, is an $n\times n$ matrix over $k$ given by

$$
(A^{-1})_{ij} = \det(A)^{-1} (-1)^{i+j} \det(M_{ji})
$$

where $M_{ij}$ is the $(n-1)\times (n-1)$ matrix obtained by deleting the $i$-th row and $j$-th column from matrix $A$.
