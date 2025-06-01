---
tags:
  - maths
  - sequences
  - series
---
![[ra note 2.1#^def-ra-lim]] 
proof of:
![[sas note#^thm-lim-n-order]]
Suppose $a_{n}\to l,b_{n}\to m$ with $a_{n}\leq b_{n}, ,\forall n\geq N$. Suppose that $l>m$. Let $c_{n}=a_{n}-b_{n}$. Notice that $,\forall n\geq N :c_{n}\leq 0$. Further, $c_{n}=a_{n}+(-b_{n})\to l-m$. By 
![[sas note#^thm-sas-alg-lim]]
Hence $c_{n}$ converges to a positive real, and so by 
![[sas note#^lem-sas-seq-0-bound-lim-adopt]]
and since $a_{n}\to l,\forall n\geq N, \exists N \in \mathbb{N}$ s.t. $|a_{n}-l|< \frac{l}{2}\therefore ,\forall n> N:a_{n}> \frac{l}{n}(>0)\implies \exists N \in \mathbb{N} s.t. c_{n}>0 ,\forall n >N.\textreferencemark$
> [!theorem|*]- Sandwich Theorem
> Let $N_{0}\in \mathbb{N}$ and suppose that $(a_{n}),(b_{n}),(c_{n}),\forall n\geq N_{0}$ satisfying $a_{n}\geq b_{n}\geq c_{n}$. If $a_{n},c_{n}\to l\implies b_{n}\to l$
 ^thm-sas-sandwich
 
> [!definition|*]- Monotone sequence
> A sequence $a_{n}$ is: 
> - increasing if $a_{n+1}\geq a_{n},\forall n \in \mathbb{N}$
> - strictly increasing if $a_{n+1}>a_{n},\forall n \in \mathbb{N}$
> - decreasing if $a_{n+1}\leq a_{n},\forall n \in \mathbb{N}$
> - strictly increasing if $a_{n+1}<a_{n},\forall n \in \mathbb{N}$
 ^def-sas-mono

> [!theorem|*]- Monotone Convergence Theorem - MCT
> If $a_{n}$ is increasing and bounded above, then $a_{n}$ converges. Similarly if $a_{n}$ is decreasing and bounded below, then $a_{n}$ converges.  
 ^thm-sas-MCT

> [!example|*]- Let $a_{n}$ be the sequence of none negative real numbers satisfying $a_{n+1}=\frac{1}{2}\left( a_{n}^{2}+\frac{1}{2} \right)$, where $a_{1}$=0
> Step 1: Prove that $a_{n}\leq 1, \forall n \in \mathbb{N}$.
> Base case: True as $a_{1}=0\leq 1$.
> Induction step: suppose $a_{k}\leq 1$ for some k.
> Now consider $k+1\implies$
 ^exm-

`\begin{proof}` Euler's Sequence
The sequence ($a_{n}$) given by $a_{n}=\left( 1+\frac{1}{n} \right)^{n}$ converges. 
Proof: By ![[#^thm-sas-MCT]] it is enough to show that ($a_{n}$) is increasing and bounded.
$$
a_{n}=\sum^{n}_{k=0} \frac{1}{k!}\left( 1- \frac{1}{n} \right)\left( 1- \frac{2}{n} \right)\dots\left( 1- \frac{k-1}{n} \right)
$$
Show that $\exists M\in \mathbb{R}$ such that $a_{n}\leq M$ for all $n \in \mathbb{N}$
Observe first when $k \in \mathbb{N}$$$
a_{n}\leq \sum^{n}_{k=0} \frac{1}{k!}\left( 1- \frac{1}{n} \right)\left( 1- \frac{2}{n} \right)\dots\left( 1- \frac{k-1}{n} \right),k! =k\cdot(k-1)\dots{3} \cdot2\cdot 1\geq 2^{k-1}
$$
$$
\implies a_{n}\leq 1+ \sum^{n}_{k=1} \frac{1}{2^{k-1}}=1+ \sum^{n-1}_{j=0}\left( \frac{1}{2} \right)^{j}=1+ \frac{1-\frac{1}{2}^{j}}{1-\frac{1}{2}}\leq 1+ \frac{1}{1-\frac{1}{2}}=3, \forall n \in \mathbb{N}
$$
`\end{proof}`
