---
tags:
  - maths
  - analysis
---
[[1RA_Lecture_Notes_2024-2025.pdf#page=37|1RA_Lecture_Notes_2024-2025, p.37]]

> [!definition|*]- Convergent improper integrals
> The following improper integrals are called convergent when they exist in $\mathbb{R}$ (otherwise they are called divergent)
> - If $f : [a ,\infty) \mapsto  \mathbb{R}$ is bounded and integrable on all bounded intervals $[a,t]$, where $t>a$, then the improper integral $\int_{a}^{\infty} f$ is defined by $$\int ^{\infty }_{a} f := \lim_{ t \to \infty } \left( \int ^{t}_{a} f   \right) $$ whenever the limit exists in $\bar{\mathbb{R}}:=\mathbb{R}\cup \{ -\infty,+\infty \}$
> - If $f : (-\infty,b] \mapsto  \mathbb{R}$ is bounded and integrable on all bounded intervals $[t,b]$, where $t<b$, then the improper integral $\int_{-\infty}^{b} f$ is defined by $$\int ^{b }_{-\infty} f := \lim_{ t \to \infty } \left( \int ^{b}_{t} f   \right) $$ whenever the limit exists in $\bar{\mathbb{R}}:=\mathbb{R}\cup \{ -\infty,+\infty \}$
> - If $f:\mathbb{R}\to \mathbb{R}$ is bounded and there exists $c \in \mathbb{R}$ such that both improper integrals $\int ^{c}_{-\infty} f$ and $\int ^{\infty}_{c} f$  are convergent, then the improper integral $\int ^{\infty}_{-\infty} f$ is the real number defined by $\int_{-\infty}^{\infty} f \,:=\int ^{c}_{-\infty} f \,+\int ^{\infty}_{c} f$.
 ^def-ra-conv-improp-int

> [!definition|*]- Unbounded functions
> If $f : [a ,b] \mapsto  \mathbb{R}$ is an unbounded function, then the sum $L(f,P)=\sum^{n}_{i=1}m_{i}(x_{i}-x_{i-1})$ and $U(f,P)=\sum^{n}_{i=1}M_{i}(x_{i}-x_{i-1})$ may not be well defined, because $m_{i}=-\infty$ on any subinterval $[x_{i-1}, x_{i}] ⊆ [a, b]$ where the function is not bounded below, and $M_{i} = ∞$ on any subinterval where the function is not bounded above. If the function is bounded except for some asymptotic behaviour at certain points, however, then the Riemann–Darboux integral can be defined on subintervals that exclude those singular points. For example, the function $f (x) := \frac{1}{\sqrt[  ]{ x }}$ is not bounded on $(0, 1]$, but it is bounded on $(δ, 1]$ with $\int ^{1}_{\delta} \frac{1}{\sqrt[  ]{ x }} \, dx=2-2\sqrt[  ]{ \delta }$ for all $δ ∈ (0, 1]$, and $\lim_{ \delta \to 0 } \int ^{1}_{\delta} \frac{1}{\sqrt[  ]{ x }} \, dx=2$. The improper integrals below are defined by taking such limits of Riemann–Darboux integrals
 ^def-ra-unbound

> [!theorem|*]- Integral Comparison Test
> If $f : [a, \infty) \mapsto \mathbb{R}$ and $g : [a ,\infty) \mapsto  \mathbb{R}$ are bounded functions such that $0\leq f(x)\leq g(x)$ for all $x \in [a,\infty)$, then the following implications hold:
> - If $\int ^{\infty}_{a} g$ is convergent $\implies\int ^{\infty}_{a} f$ is also converges
> - If $\int ^{\infty}_{a} f$ is divergent $\implies\int ^{\infty}_{a} g$ is also diverges
 ^thm-ra-int-comp-test

> [!definition|*]- Solvability of a differential equation
> Suppose that $f : \mathbb{R} \times \mathbb{R} \mapsto  \mathbb{R}$, and that $I\subseteq \mathbb{R}$ is an open interval. A solution of the (first order) differential equation
> $$y'=f(x,y)\text{ on }I$$
> Is differentiable function $y:I\to \mathbb{R}$ such that $y'(x)=f(x,y(x))$ for all $x \in I$ such that:$$\left\{ \begin{array}{}y'=f(x,y) \forall x \in [x_{0},\infty) \\y(x_{0})=y_{0}\end{array} \right. $$
 ^def-ra-solv-dif-eq

> [!theorem|*]- Solution of a differntial where $y_{0}$ is known
> If $f:[x_{0},\infty)\to \mathbb{R}$ is continuous, then IVP:$$\left\{ \begin{array}{}y'=f(x) \\
y(x_{0})=y_{0}\end{array} \right. $$has solution $$y(x)=\left( \int ^{x}_{x_{0}} f  \right)+y_{0}\forall x \in [x_{0},\infty)$$
 ^thm-ra-sol-init-y

$$
ay''+by'+cy=0
$$
$$
y=Ce^{  }
$$