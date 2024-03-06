A [[series]] which does not have [[Absolute Convergence]] converges conditionally

### Example
Determine if the given series is conditionally convergent, absolutely convergent, or divergent
$$
\sum^\infty_{k=1}\frac{(-1)^k}{\sqrt k}
$$
$$
\sum^\infty_{k=1}|\frac{(-1)^k}{\sqrt k}| = \sum^\infty_{k=1}\frac{1}{k^{1/2}}
$$
which is a p series that diverges, so it does not converge absolutely

use alternating series
$$
\frac{\frac{1}{\sqrt {k+1}}}{\frac{1}{\sqrt k}} = \frac{\sqrt{k+1}}{\sqrt{k}}>1
$$
$$
\lim_{k\to\infty}\frac{1}{\sqrt k} = 0
$$
so by the alternating series test, the series converges, meaning it converges conditionally. 

