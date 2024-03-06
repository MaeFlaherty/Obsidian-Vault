An [[Alternating Series]] of the form
$$
\sum^\infty_{k=1}(-1)^k a_k
$$
or
$$
\sum^\infty_{k=1}(-1)^{k+1}a_k
$$
where $a_k\geq0$ for all k

**Converges** if:
a) $(a_k)^\infty_{k=1}$ is decreasing and 
b) $\lim_{k\to\infty}a_k = 0$
Else: The test is **inconclusive** and doesn't necessarily diverge

### Example
Determine if the given series converges or diverges
$$
\sum^\infty_{k=1}\frac{(-1)^{k+1}}{k}
$$
otherwise known as the **Alternating Harmonic Series**
$a_k = 1/k$
$$
\frac{a_k}{a_{k+1}} = \frac{k+1}{k} > 1
$$
so $a_k$ is decreasing, and 
$$
\lim_{k\to\infty}\frac{1}{k} = 0
$$
so, by the **Alternating Series Test**, $\sum^\infty_{k=1}\frac{(-1)^{k+1}}{k}$ converges