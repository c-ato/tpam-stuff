> [!definition|*]- Curl
> $$\underline{F}=(P,Q,R)\qquad\text{curl}(\underline{F})=\underline{\nabla}\times \underline{F}=\left( R_{y}-Q_{z},P_{z}-R_{x},P_{y}-Q_{x}\right) $$
 ^def-mva-curl

> [!theorem|*]- Green's Theorem
> Let $C$ be a closed curve, oriented counterclockwise and enclosing a region $R \in \mathbb{R}^{2}$. If $\underline{F}$ is a vector field defined and differentiable everywhere in $R$, then $$\oint_{C}\underline{F}\cdot d\underline{r}=\iint_{R}\underline{\nabla}\times\underline{F}dA$$
 ^thm-mva-green

> [!definition|*]- Divergence
> $$\underline{F}=(M(x,y),N(x,y))\qquad Div(\underline{F})=\underline{\nabla}\cdot \underline{F}= \frac{ \partial M }{ \partial x } +\frac{ \partial N }{ \partial y } $$
 ^def-mva-div

> [!definition|*]- Flux
> Let $\mathbf{F}:\mathbb{R}^{2}\to \mathbb{R}^{2}$ be a vector field and let $C$ be a planar curve with planar unit normal vector $\hat{n}$. The flux is then defined as the line integral: $$\int ^{}_{C}  \, \mathbf{F}\cdot \hat{n}\,ds $$
 ^def-mva-flux

> [!definition|*]- Parameterised normal of a parameterised surface
> Where $\mathbf{r}(u,v)$ is the parameterised surface
> $$\hat{n}= \frac{\frac{ \partial \mathbf{r} }{ \partial u } \times \frac{ \partial \mathbf{r} }{ \partial v } }{\left| \frac{ \partial \mathbf{r} }{ \partial u } \times \frac{ \partial \mathbf{r} }{ \partial v } \right|}$$
 ^def-mva-para-norm

> [!definition|*]- Surface differential
> The surface differential is given by the parameterisation of $\mathbf{r}(u,v)$ of some surface $S$. 
> $$dS=\left| \frac{ \partial \mathbf{r} }{ \partial u } \times \frac{ \partial \mathbf{r} }{ \partial v }  \right| dudv$$
> and to vectorise it:
> $$d\mathbf{S}=\hat{n}dS$$
 ^def-mva-surface-diff

> [!theorem|*]- Green's Theorem in normal form
> $$\oint ^{}_{C}  \, \mathbf{F}\cdot \hat{n}\,dS =\iint_{R} \underline{\nabla}\cdot\mathbf{F}\,dA$$
 ^thm-mva-green-thm-norm

> [!theorem|*]- Gauss' Divergence Theorem
> Let $S$ be a closed orientable surface, and an enclosing a solid region $D\subset\mathbb{R}^{3}$ If $\mathbf{F}$ is a vector field defined and differentiable in $D$, then $$\iint_{S}\mathbf{F}\cdot d\mathbf{S}=\iiint_{D}\underline{\nabla}\cdot \mathbf{F}dV$$
 ^thm-mva-gaus-div-thm
