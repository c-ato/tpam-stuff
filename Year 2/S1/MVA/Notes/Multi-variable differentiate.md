> [!theorem|*]- Chain rule of single variable functions
> Suppose $y=y(x)$ and $x=x(u)$ being differentiable:
> $dy=y_{x}dx$, $dx=x_{u}du\implies dy=y_{x}x_{u}du$
> Denoting $y=y(x(u))=y(u)$ we have $dy=Y_{u}du\therefore Y_{u}=y_{x}x_{u}$
 ^thm-mva-sing-chain-rule-var-funct

> [!theorem|*]- Chain Rule for multi-variable functions
> Let $f$ be a function,$f(x_{1},x_{2},\dots,x_{n})$ and each $x_{j}$ of $x_{1},x_{2},\dots,x_{n}$ is $x_{j}=x_{j}(t_{1},t_{2},\dots t_{m})$ and $y(u,v)$ and are all differentiable. Then $df=f_{x}dx+f_{y}dy$. We have $dx=x_{u}du+x_{v}dv$ and $dy=y_{u}du+y_{v}dv\implies df=f_{u}du+f_{v}dv$. If $f$ and $x_{j}$ are sufficiently smooth then:
> $$\frac{ \partial f }{ \partial t_{i} } =\frac{ \partial f }{ \partial x_{1} } \frac{ \partial x_{1} }{ \partial t_{i} } + \frac{ \partial f }{ \partial x_{2} } \frac{ \partial x_{2} }{ \partial t_{i} } +\dots+\frac{ \partial f }{ \partial x_{n}}\frac{ \partial x_{n} }{ \partial t_{i} } ,\quad i=1,2,\dots,m$$
 ^thm-mva-mult-chain-rule-var-funct
 
