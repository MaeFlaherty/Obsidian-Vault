

# Sequences
## What is a Sequence?
A **Sequence** is a function whose domain is a set of integers $(n=1,2,3...)$ The Domain is typically the set of positive or nonnegative integers($n=1$ or $n=0$).

sequences can either be listed out, or put in the form of a general term 

Listed out: $$\frac{1}{1}, -\frac{1}{2}, \frac{1}{3}, -\frac{1}{4}...$$

General term
$$ (-1)^{n+1}\frac{1}{n}$$
## Infinite Sequence Notation
A sequence can also be written in the form$$\{a_k\}^{+\infty}_{k=1}$$
## Limits of a Sequence 
The Limit of a sequence is the limit of the function(general term) that defines that sequence. However, because a sequence is only defined for integers, it really only makes sense to take the limit of a sequence as $n\to\infty$ 

The Normal Limit Theorems all apply when taking the limit of a sequence. This is because we can map sequences onto their respective functions that are defined for all numbers, not just integers. If one converges, than the other converges. 

**Theorem 1.1.** Suppose that the sequences $\{a_n\}$ and $\{b_n\}$ converge to limits $L_1$and $L_2$, respectively, and _c_ is a constant. Then:

(a) ![](file:////Users/maeflaherty/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image002.jpg)

(b) ![](file:////Users/maeflaherty/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image004.jpg)

(c) ![](file:////Users/maeflaherty/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image006.jpg)

(d) ![](file:////Users/maeflaherty/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image008.jpg)

(e) ![](file:////Users/maeflaherty/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image010.jpg)

(f) ![](file:////Users/maeflaherty/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image012.jpg)

### Convergence Definition
The limit of a sequence $a_n$ is said to converge to a limit $L$ if if for any positive number $\epsilon$ there exists a positive number $N$ such that $|a_n-L|<\epsilon$ for all $n≥N$ 

### Even/Odd Theorem
A sequence converges to a limit L if and ONLY if both the even terms AND the odd terms converge to that limit 

### The Squeeze Theorem(For Sequences)
Let $\{a_n\}, \{b_n\}, \{c_n\}$ be sequences such that 
$$a_n≤b_n≤c_n$$ if $a_n$ and $c_n$ have a common limit, as $n\to\infty$, then $b_n$ also shares that limit.

Common uses for this theorem include with functions whose limits go to 0.
$$1/n$$
### Absolute Value Theorem for sequences
This theorem is useful when dealing with sequences that alternate between positive and negative. 

if $\lim_{n\to\infty}|a_n|=0$ , then $\lim_{n\to\infty}a_n=0$

## Recursively defined sequences 
Sometimes, Sequences are defined recursively, using the previous term of that sequence.

## Monotone Sequences
Sometimes we want to know if a sequence converges without needing to know 


 
# What is a Series
A series is an infinite sum of a given function with respect to $k$ 
$$
\sum^\infty_{k=1} a_k
$$
To find wether a series converges or diverges, use one of many [[Series Convergence Tests]]

( [[Geometric Series]] )
