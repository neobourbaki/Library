Each matrix can be realized as a linear map between two vector spaces, and associativity follows from the associativity of composition of functions:

$$
(f \circ g) \circ h = f \circ (g \circ h).
$$

Indeed, let $v$ be any vector (of appropriate size), and

$$
((AB)v)_i = \sum_{j} (AB)_{ij} v_j = \sum_{j} \sum_{k} A_{ik}B_{kj} v_j = \sum_{k} A_{ik} (Bv)_k = (A(Bv))_i
$$

shows that $(AB)v = A(Bv)$. It then follows that

$$
((AB)C)v = (AB)(Cv) = A(B(Cv)) = A((BC)v) = (A(BC))v
$$

for any $v$, hence $(AB)C=A(BC)$.
