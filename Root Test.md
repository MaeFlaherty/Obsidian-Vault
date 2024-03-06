#mathematics #calculus 
 Companion to the [[Ratio Test]]
 Let 
 $$
 \sum^\infty_{k=1}u_k
 $$
 be a series with positive terms and let 
 $$
 p = \lim_{k\to \infty}\sqrt[k]{u_k}
 $$
 if $p<1$, then $\sum^\infty_{k=1}u_k$ converges
 if $p>1$, then $\sum^\infty_{k=1}u_k$ diverges
 if $p=1$, then the test is inconclusive

# Examples
---
1. Determine if the given series diverges
	$$
	\sum^\infty_{k=1}\frac{1}{k^k}
	$$
	Using the root test
	$$
	\lim_{k\to\infty}\sqrt[k]{\frac{1}{k^k}} = \lim_{k\to\infty}\frac{1}{k} = 0 < 1
	$$
	So by the root test, the series converges

2. Determine if the series converges or diverges 
	$$ 
		\sum^\infty_{k=1}(\frac{2k^2+1}{k^2+7})^k
	$$
	use root test
	$$
	\lim_{k=1}\sqrt[k]{(\frac{2k^2+1}{k^2+7})^k} = \lim_{k=1}\frac{2k^2+1}{k^2+7} =2 > 1
	$$
	so by the root test, the original series diverges
