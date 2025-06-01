---
tags:
  - maths
  - analysis
---
> [!lemma|*]- Partition lemma
> Suppose that $f:[a,b]\to[0,\infty)$ is a bounded function. The following properties hold for partitions $P$, $Q$, $R$ and $S$ of $[a,b]$:
> - $L(f,P)\leq U(f,P)$
> - $P\subseteq Q\implies \left\{ \begin{array}{}L(f,P)\leq L(f,Q) \\ U(f,P)\geq U(f,Q) \end{array} \right .$
> - $L(f,R)\leq U(f,S)$
 ^lem-ra-parti

$$
x\quad\dot{x}\quad\ddot{x}\quad\dddot{x}\quad \ddddot{x}\quad \dot{\ddddot{x}}\quad \ddot{\ddddot{x}}\quad\dddot{\ddddot{x}}\quad \dot{\dddot{\ddddot{x}}}\quad \ddot{\dddot{\ddddot{x}}}\quad \dot{\ddot{\dddot{\ddddot{x}}}}
$$

> [!theorem|*]- Riemann's Criterion
> The following are equivalent
> - $f$ is integrable
> - For each $\varepsilon>0\exists P$ s.t. $U(f,P)-L(f,P)<\varepsilon$ 
 ^thm-ra-riemann-int-crit

$\exists0<\varepsilon \in \mathbb{R}$ s.t. $f(x)\leq f(x+\varepsilon)$ where $f:\mathbb{R}\mapsto \mathbb{R}$

> [!example|*]- Prove that $f:\left[ 0, \frac{\pi}{2} \right]\to[0,1]$ given by $f(x)=\sin(x)$ is integrable
> `\begin{proof}`
> We will need to show Riemann's criteria s.t. for each $\varepsilon \exists$ partition $P$ s.t. $U(f,P)-L(f,P)<\varepsilon$
> Let $n \in \mathbb{N}$ and $P_{n}=\left\{  0, \frac{\pi}{2n}, \frac{2\pi}{2n}\dots \frac{n\pi}{2n}  \right\}$
> $$U(f,P_{n})-L(f,P_{n})=\sum^{n}_{i=1}(M_{i}-m_{i})\left( \frac{\pi}{2n} \right)=\frac{\pi}{2n}\sum^{n}_{i=1}\sin \left( \frac{i\pi}{2n} \right) - \sin \left( \frac{(i-1)\pi}{2n} \right)$$
> $$=\frac{\pi}{2n} \sin\left( \frac{n\pi}{2n} \right)=\frac{\pi}{2n}$$
> Let $\varepsilon>0$. We want $\frac{\pi}{2n}<\varepsilon$, ie $\frac{\pi}{2\varepsilon}<n$. Now choose $N\in \mathbb{N}$ s.t. $N> \frac{\pi}{2\varepsilon}$
> $$U(f,P_{n})-L(f,P_{n})=\frac{\pi}{2N}<\varepsilon$$
> Hence by RC $f$ is integrable
> `\end{proof}`
 ^exm-ra-rc

> [!theorem|*]- 
> If $f,g:[a,b]\to \mathbb{R}$ integrable then $fg$ is integrable. 
 ^thm-ra-funct-prod-int

> [!theorem|*]- 
> If $f,g:[a,b]\to \mathbb{R}$ integrable then $f+g$ is integrable. 
 ^thm-ra-funct-sum-int

> [!definition|*]- Split function into positive and negative component
> Define $f:[a,b]\to \mathbb{R}$:
> - $$f^{+}(x):=\left\{   \begin{matrix}f(x)&\quad f(x)>0 \\0&\quad\end{matrix}\right.$$
> - $$f^{-}(x):=\left\{   \begin{matrix}-f(x)&\quad f(x)<0 \\0&\quad\end{matrix}\right.$$
> $$f=f^{+}-f^{-}$$
 ^def-ra-func-split

> [!theorem|*]- Bounded function $\implies$ bounded integral
> If $f:[a,b]\to \mathbb{R}$ with 
> $$m\leq f(x)\leq M\implies m(b-a)\leq \int ^{}_{} f(x)\leq M(b-a) $$
 ^thm-ra-bound-func-bound-int

> [!theorem|*]- The First Fundamental Theorem of Calculus (FTC)
> Let $f:[a,b]\mapsto \mathbb{R}$ denote a bounded integrable function and suppose that $F : [a,b]\mapsto \mathbb{R}$ is given by $F:= \int ^{x}_{a} f\forall x \in [a,b]$. If $f$ is continuous at $c$ where $c \in [a,b]$ then $F$ is differentiable at $c$ with derivative $F'(c)=f(c)$ 
 ^thm-ra-fftc

> [!theorem|*]- Second Fundamental Theorem of Calculus
> If $f : [a ,b] \mapsto  \mathbb{R}$ is a bounded integrable function and there exists a differentiable function $g : [a ,b] \mapsto  \mathbb{R}$ such that $f=g'$, then $\int ^{b}_{a} f \, = g(b)-g(a)$
 ^thm-ra-sft

