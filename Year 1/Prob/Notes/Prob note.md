---
tags:
  - maths
  - prob
---
> [!definition|*]- Binomial equation/notation
> $$ \frac{N!}{k!(N-k)!}=\begin{pmatrix}N \\ k\end{pmatrix}=\,^{N}C_{k}$$
> $$(a+b)^{N}=\sum^{N}_{k=0}\begin{pmatrix}N \\
k\end{pmatrix}a^{k}b^{N-k}$$
 ^def-stats-binomial

> [!definition|*]- Multinomial equation/notation
> $$\begin{pmatrix}N \\ n_{1}\end{pmatrix}\times \begin{pmatrix}N-n_{1} \\ n_{2}\end{pmatrix}\dots\begin{pmatrix}n_{p} \\
n_{p}\end{pmatrix}=\frac{N!}{n_{1}!n_{2}!n3!\dots n_{p}!}\equiv \begin{pmatrix}
 &  & N \\ n_{1} & n_{2}  & n_{3}& \dots & n_{p}\end{pmatrix}$$
 $$(a+b+c)^{n}=\sum_{k_{1}+k_{2}+k_{3}}\begin{pmatrix} & N \\ k_{1} & k_{2} & k_{3}\end{pmatrix}a^{k_{1}}b^{k_{2}}c^{k_{3}}$$
 ^def-stats-multinomial

> [!theorem|*]- Bayes Theorem
> $$P(A|B)=\frac{P(B|A)P(A)}{P(B)}=\frac{P(B|A)P(A)}{\sum_{A}P(A|B)P(B)}$$
 ^thm-prob-bayes

> [!definition|*]- Cumulative distribution
> $C(x)=P(X\leq x)$
 ^def-prob-cumul-distri

$$
\left< \frac{x}{s} \right> 
$$
$$
\frac{dC(x)}{dx}=P(x)
$$
$$
P_{y}(y)=\left| \frac{d}{dy}f^{-1}(y) \right|P_{x}(f^{-1}(y)) 
$$
$$
y=f(x)=x^{4}\implies f^{-1}(y)=\sqrt[ 4 ]{ y }
$$

$$
P_{y}(y)=\left| \frac{d}{dy}f^{-1}(y) \right|P_{x}(f^{-1}(y)) 
$$
$$
\frac{d}{dy}y^{1/4}=\frac{1}{4y^{3/4}}
$$
$$
P_{y}(y)=\frac{1}{4y^{3/4}}
$$
> [!definition|*]- Normal distribution
> $$P(x|\mu,\sigma)= \frac{1}{\sqrt[  ]{ 2\pi }\sigma}\exp\left( \frac{(x-\mu)^{2}}{2\sigma^{2}} \right)$$
 ^def-prob-stats

> [!theorem|*]- Central Limit Theorem (CLT)
> Rescaled sums of random variables appear to be Normally distributed. Define sum $$X=x_{1}+x_{2}\dots x_{N}\qquad x_{i}~P(x)\to \langle x_{i} \rangle=\mu \qquad var(x_{i})=\sigma^{2}$$
> $$z\equiv \frac{X-\langle X \rangle }{std(X)}$$
> $$\langle X \rangle=N\mu\qquad var(X)=N\sigma^{2}$$ 
> $$\bar{x}= \frac{1}{N}(x_{1}+x_{2}\dots x_{N})=\frac{X}{N}$$
> $$\langle \bar{x} \rangle = \frac{1}{N}(N\mu)=\mu$$
> $$$$
 ^thm-prob-clt
