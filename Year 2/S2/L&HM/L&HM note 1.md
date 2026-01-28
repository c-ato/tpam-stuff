Newton: $$\underline{F}_{i}^{ext}+ \sum_{j}\underline{F}_{ij}=\frac{d\underline{p}_{i}}{dt}$$
$$\underline{F}_{ij}=-\underline{F}_{ji}$$
Newton EoM are excessive - redundant or unnecessary info bc forces of constraint. Newtons EoM are not invariant under coordinate transformations - obey complicated transformation between coordinates.

Lagrandian approach -
Set up EoM based on an invariant, being energy, mostly focuses on conservative forces. 

$T$ denotes $KE$

Lagrangian function (Lagrangian)
$$\mathcal{L} =T-V$$
Lagrangian Equation
$$\frac{d}{dt}\left( \frac{ \partial \mathcal{L}  }{ \partial \underline{\dot{r}} }  \right)-\frac{ \partial \mathcal{L}  }{ \partial \underline{r} } =0$$
The amount of equations is the number of bases we have.

In simple $T=\frac{m}{2}\dot{x}^{2}$
$$\frac{d}{dt}\left( \frac{ \partial \mathcal{L}  }{ \partial \underline{\dot{r}} }  \right)-\frac{ \partial \mathcal{L}  }{ \partial \underline{r} } =\frac{d}{dt}(m\dot{r})+\frac{ \partial V }{ \partial \underline{r} }= m \ddot{\underline{r}}-\underline{F} =0$$
Generalised coordinates $\underline{r}\to q$

$$\mathcal{L} (\underbrace{ q_{1},\dots,q_{s} }_{ \text{gen pos} },\underbrace{ \dot{q}_{1},\dots,\dot{q}_{s} }_{ \text{gen vel} })$$
Degree of freedom:
$3D$ with $N$ particles and $k$ constraints: $3N-k=S$

Holonomic constraints: constraints that can be formally written down as $\psi_{n}(\underline{r}_{1},\dots,\underline{r}_{n})$

$\mathcal{L}\equiv T(q_{i},\dot{q}_{i})-V(q_{i})$

$$d\underline{r}_{n}=d\underline{r}_{n}(q_{1},\dots,q_{s},t)=\frac{ \partial \underline{r}_{n} }{ \partial q_{1} }dq_{1}+\frac{ \partial \underline{r}_{n} }{ \partial q_{s} }dq_{s}+ \frac{ \partial \underline{r}_{n} }{ \partial t }dt$$
$$d\underline{\dot{r}}_{n}=d\underline{\dot{r}}_{n}(\dot{q}_{1},\dots,\dot{q}_{s},t)=\frac{ \partial \underline{r}_{n} }{ \partial q_{1} }d\dot{q}_{1}+\frac{ \partial \underline{r}_{n} }{ \partial q_{s} }d\dot{q}_{s}+ \frac{ \partial \underline{r}_{n} }{ \partial t }$$

scleronomics

bead on parabolic wire

2 DoF, choose $y=\frac{x^{2}}{2a}$ 
$$T=\frac{1}{2}m(\dot{x}^{2}+\dot{y}^{2})\qquad \dot{y}=\frac{x \dot{x}}{a}\impliedby \dot{y}^{2}=\frac{x^{2}\dot{x}^{2}}{a}\implies \frac{a\dot{y}^{2}}{y}=\dot{x}^{2}$$
and then do the thigns and thte lagrangian and yh boom bang

now rotating with $\omega$
$$T=\frac{1}{2}m(\dot{r}^{2}+r^{2}\dot{\theta})+\frac{1}{2}m\dot{y}^{2}=\mathcal{L} +may\omega^{2}$$
where $\mathcal{L}$ is from regular parabola and has effect of replacing $g$ with $g-a\omega^{2}$ in prev of $V$

