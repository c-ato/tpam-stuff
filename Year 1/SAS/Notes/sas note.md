---
tags:
  - maths
  - sequences
  - series
---
Sequences are a functions which takes the domain of $n\in\mathbb{N}$ and give the range of $a_{n}\in \mathbb{R}$ and naturally can be graphed

$$
\mathbb{N}=\{ 1,2,3\dots \}\,,\,
\mathbb{N} \to \mathbb{R}
$$

>[!def|*]- Tending to infinity
Sequence ($a_{n}$) of $\mathbb{R}$ tends to $\infty$ if for any $A>0$ there exists a $N\in\mathbb{N}$ such that $a_{n}>A$ for all $n>N$.
>^def-sas-tend-inf

---

Prove $a_{n}=n^{2}$, $a_{n}\to \infty$
$$
\text{Let }A>0
$$
$$
\text{We require to show that theres is a }N\in\mathbb{N} \text{ such that }n>n\implies a_{n}>A
$$
$$
n^{2}>A\implies n=\sqrt[  ]{ A }
$$
$$
N\in\mathbb{N}\text{ such }N\geq \sqrt[  ]{ A }\text{ (eg.}N=[\sqrt[  ]{ A }]+1) \text{: we have } n>N\implies n>\sqrt[  ]{ A }\implies n^{2}>A
$$

---

$$
a_{n}=\frac{n^{3}+5n^{2}+3}{2n^{2}+n+1}\overset{ \because 5n^{2}+3>0 }{ \geq } \frac{n^{3}}{2n^{2}+n+1}\geq \frac{n^{3}}{2n^{2}+n^{2}+n}=\frac{n}{4}
$$
$$
\text{Let }N\in \mathbb{N} \text{ such that }N\geq 4A \implies n>N \implies n>4A
$$
$$
\implies \frac{n}{4}>A\implies a_{n}>A\therefore a_{n} \to \infty
$$

---

>[!def|*]- Convergence
>A sequence ($a_{n}$) of $\mathbb{R}$ that tend to converge to $l\in\mathbb{R}$ ($a_{n}\to \infty$) if given any $\epsilon>0$, there exists $N\in\mathbb{N}$ such $|a_{n}-l|<\epsilon$ for all $n>N$.
>^def-sas-conv

---

$$
a_{n}=1+\frac{1}{n}\to 1=l
$$
$$
\text{Given }\epsilon>0\,,\,N\in\mathbb{N\text{ such }}|a_{n}-1|<\epsilon: n>N
$$
$$
\text{Observe }|a_{n}-1|=\frac{1}{n}\,,\,\text{ such that }N\geq \frac{1}{3}\therefore n>N\implies n> \frac{1}{3}
$$
$$
\implies \frac{1}{n}<\epsilon\implies |a_{n}-1|<\epsilon
$$

---

$$
a_{n}= \frac{n^{3}+3n^{2}+5}{2n^{3}+4n}\to \frac{1}{2},\epsilon>0
$$
$$
|\frac{n^{3}+3n^{2}+5}{2n^{3}+4n}-\frac{1}{2}|<\epsilon
$$
$$

|\frac{n^{3}+3n^{2}+5}{2n^{3}+4n}-\frac{1}{2}|=
|\frac{2n^{3}+6n^{2}+1-2n^{3}-4n}{2n^{3}+4n}|
$$
$$
=| \frac{6n^{2}-4n+10}{2n^{3}+4n}|\leq \frac{6n^{2}+10}{2n^{3}}\leq\frac{16n^{2}}{2n^{3}}=\frac{8}{n}<\epsilon\implies n> \frac{8}{\epsilon}
$$
for all $N \in\mathbb{N}$. Let $N \in \mathbb{N}$ s.t $N\geq \frac{5}{\epsilon}$

>[!thm|*]- Uniqueness of limits
If $a_{n}$ converges then it has a unique limit:
>^thm-sas-uniq-lim

proof:

Suppose for a contradiction that $a_{n} \to l$ and $a_{n}\to m$ for some distinct $l,m \in\mathbb{R}$.
$$
\begin{matrix}
|a_{n}-m|=\epsilon \implies m-\epsilon<m<m+\epsilon \\

|a_{n}-l|=\epsilon \implies l-\epsilon<l<l+\epsilon
\end{matrix}
$$
Let $\epsilon= \frac{l-m}{4}$. Since $a_{n}\to l$ there exists $N_{1} \in\mathbb{N}$ s.t. $|a_{n}-m|<\epsilon$ for $n>N_{1}$. Since $a_{n}\to m$ there exists $N \in\mathbb{N}$ s.t. $|a_{n}-m|<\epsilon$ for $n>N_{2}$. If $n>max\{ N_{1},N_{2} \},|l-m|=|(l-a_{n})+(a_{n}-m)|\leq |l-m|<\epsilon =\frac{1}{2}|l-m| \textreferencemark$

---

> [!definition|*]- Bounded sequences
> A sequence $(a_{n})$ of $\mathbb{R}$ is:
> (i) bounded above if there exists $M \in \mathbb{R}:a_{n}\leq M$
> (ii) bounded below if there exists $M \in \mathbb{R} :a_{n}\leq M$
> (iii) bounded if both the above such that $M\geq 0: |a_{n}|\leq M$ for all $n$
 ^def-sas-bound-seq

> [!lemma|*]- If $a_{n}$ converges then it is bounded
> Suppose $a_{n}$ coverges to $l \in \mathbb{R}$. We need to show that $M\geq 0:|a_{n}|\leq M$ for all n.
> $\because a_{n}\to l\implies N \in \mathbb{N}:|a_{n}-l|<1$ for $n>N$. Using triangle inequality $|a_{n}|=|(a_{n}-l)+l| \leq |a_{n}-l|+|l|<l+|l|$ for all $n>N$. Let $M=max{1+|l|,|a_{1}|,|a_{2}|\dots |a_{N}|}$ so that $|a_{n}|\leq M$ for all $n \in \mathbb{R}$
 ^lem-sas-conv-bound

> [!theorem|*]- Algebra of limits
> Suppose $a_{n},b_{n}\in \mathbb{R}$ converge to $l$ and $m$ $(l,m \in \mathbb{R})$. Then:
> (i) $a_{n}+b_{n}\to l+m$
> (ii) $\lambda a_{n}\to \lambda l$
> (iii) $a_{n}b_{n}\to lm$
> (iv) $\frac{a_{n}}{b_{n}}\to \frac{l}{m}:m\neq 0$
 ^thm-sas-alg-lim


> [!example|*]- Prove (using the algebra of limits) that
> $$a_{n}= \frac{n^{2}+n+1}{3n^{2}+2n-4}\to \frac{1}{3}$$
> $$ a_{n}= \frac{1+\frac{1}{n}+\frac{1}{n^{2}}}{3+\frac{2}{n}-\frac{4}{n^{2}}} $$
> Using on $\frac{1}{n}$ ![[#^4f6a00]]  $\frac{1}{n}\to 0$ and using this with (iii) of ![[#^thm-sas-alg-lim]] 
> $$ a_{n}= \frac{1+\frac{1}{n}+\frac{1}{n^{2}}}{3+\frac{2}{n}-\frac{4}{n^{2}}} \to \frac{1}{3}$$
 ^exm-sas-alg-lim

Proof of (i)
We are required to show that given any $\epsilon>0$ there exists $N \in \mathbb{N}:|(a_{n}+b_{n})-(l_+m)|<\epsilon$ for all $n>N$
$$
\implies |(a_{n}-l)+(b_{n}-m)|\leq |a_{n}-l|+|b_{n}-m|
$$
Since $a_{n}\to l, \forall n>N_{1},N_{1} \in \mathbb{R}:|a-l|<\epsilon$. Similarly, since $b_{n}\to l, \forall n>N_{2},N_{2} \in \mathbb{R}:|b-m|<\epsilon$
$$
\text{If }N=max\{ N_{1},N_{2} \}, \text{ then }n>N \implies |a_{n}-l|< \frac{\epsilon}{2} \wedge |b_{n}-l|< \frac{\epsilon}{2}
$$
$$
\implies |(a_{n}-l)+(b_{n}-m)|<\epsilon
$$

Proof of (iii)
Let $\epsilon>0$. Observe first $|a_{n}b_{n}-lm|=|a_{n}b_{n}-ma_{n}+ma_{n}-lm|=|a_{n}(b_{n}-m)+m(a_{n}-l)|\leq |a_{n}(b_{n}-m)|+|m(a_{n}-l)|$
$=|a_{n}||b_{n}-m|+|m||a_{n}-l|.$ Since ![[#^lem-sas-conv-bound]]
$\forall n,\exists M \in \mathbb{R}:|a_{n}\leq M|\therefore |a_{n}b_{n}-lm|\leq M|b_{n}-m|+|m||a_{n}-l|$. Since $b\to m, \forall n,\exists N_{1} \in\mathbb{N}:|b_{n}-m|< \frac{\epsilon}{2M} \wedge a_{n}\to,\forall n,\exists N_{2} \in N:|a_{n}-l|< \frac{\epsilon}{2(|m|+1)}\therefore N=max\{ N_{1},N_{2} \}$
$\implies n>N\implies |b-m|< \frac{\epsilon}{2M} \wedge |a_{n}-l|< \frac{\epsilon}{2(|m|+1)}\implies |a_{n}b_{n}-lm|<M \frac{\epsilon}{2M}+ |m| \frac{\epsilon}{2(|m|+1)}$
$=\frac{\epsilon}{2}+ \frac{|m|}{|m+1|} \frac{\epsilon}{2}< \epsilon$

> [!theorem|*]- Limit and Order
> Let $N_{0} \in \mathbb{N}$. Suppose $a_{n}\to l \wedge b_{n}\to m$ s.t. $m, l \in \mathbb{R} \wedge \forall n\geq N_{0}:a_{n}\leq b_{n}\implies l\leq m$
 ^thm-lim-n-order

> [!corollary|*]- Limit adopts upper bound of sequence
> If $a_{n}\to l,l\in \mathbb{R}\wedge \exists M \in\mathbb{R}$ s.t. $a_{n}\leq M, \forall n\implies l\leq M$
 ^cor-sas-seq-0-bound-lim-adopt

> [!lemma|*]- Sequence adopts 0 bound of limit for some $N$
> Suppose that $a_{n}\to l,l>0(l<0)\implies\forall n, \exists n \in \mathbb{N}:a_{n}>0(a_{n}<0)$
 ^lem-sas-seq-0-bound-lim-adopt
 