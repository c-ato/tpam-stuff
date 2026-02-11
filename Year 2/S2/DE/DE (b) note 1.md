> [!theorem|*]- 1st order linear ODE
> If $p(x)$ and $q(x)$ are continuous on an open interval $I:\alpha<x<\beta$ containing $x=x_{0}$, then $!\exists y=u(x)$ that satisfies the DE $$\frac{ dy }{ dx } +p(x)y(x)=q(x)$$for each $x \in I$ that also satisfies the initial condition $y(x_{0})=y_{0}$ where $y_{0}$  is an arbitrary prescribed initial value
 ^thm-ded-b-1-ode

> [!definition|*]- Global Stability
> All initial conditions in $\Omega$ converge the fixed point as $t\to \infty$. A fixed point $\left| x(t)-\underline{x}_{e} \right|\to0$ as $t\to \infty$. Then globally stable.
 ^def-de-b-glob-stab

> [!definition|*]- Asymptotic (non-linearly) Stability
> A fixed point is asymptotically stable if $\exists\delta>0$ s.t. $\exists x(t=0)$ with $\left| \underline{x}(0)-\underline{x}_{e}<\delta \right|$
 ^def-de-b-asymp-stab

> [!definition|*]- Linear (exponential????) Stability
> $\forall\varepsilon>0\exists\delta,\sigma$ s.t. $y$, $\left| \underline{x}(0)-\underline{x}_{e} \right|<\delta$ then $\left| x(t)-\underline{x}_{e} \right|<\varepsilon e^{ -\sigma t }$. For linear stability we to find $\sigma=f'(\underline{x}_{e})$ (1D) 
 ^def-de-b-lin-stab
