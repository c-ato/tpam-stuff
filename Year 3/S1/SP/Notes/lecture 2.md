For const energy/ energy conservation we end up with 3D spherical equation, which means we lose one degree of freedom in momentum as energy is related to its square.

$2mE=\underline{p}^{2}=p_x^{2}+p_{y}^{2}+p_{z}^{2}=b^{2}$

So for simple container where $V=0$ we haev 3 spacial DoF and 2 for momentum - total of 5 DoF or 5 dimensional phase space.

All for 3D container with 1 particle

A particles position is represented as $q_{n}$ and each component is $q^{i}_{n}$ for $i=\{ x,y,z \}$. (with $m_{n}=m$)

For $n$ particles we then obtain, by similar results, the momentum is constained by a $3N$ dimensional sphere equation, removing one DoF so $(3N-1)$-D from momentum and $3N$ from spacial.

> [!hypothesis|*]- Ergodic Hypothesis
> The time-average for microscopic motion of a gas (pressure) is the same as the average over the phase space.
 ^hyp-sp-ergod-hyp

Very difficult to prove, but in simple cases has been proven but exceptions exist.

> [!example|*]- 
> We have $f(P,Q)$ and a time average:
> $$\bar{f}=\lim_{ T \to \infty } \int ^{T}_{0}  \, dt f(Q,P)\qquad T\to \infty,T\gg t_{micro}$$
> $$\langle f \rangle =\int ^{}_{}  \, dQdP\,f(Q,P) D(Q,P)=\bar{f}$$
> Where $D$ must respect energy conservation. simplest $D=\delta(E-\mathcal{H}(Q,P))$
 ^exm-sp-ergod