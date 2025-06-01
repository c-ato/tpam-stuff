---
tags:
  - topology
  - maths
  - physics
  - quantum
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%202" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf" class="button">Go to PDF
	</a> 
</div>

> [!definition|*]- Metric space
> This is a set $X$ where a notion of distance exists. Specifically, if $x,y \in X$ then $d(x,y)$ is some function that determines the "distance" between $x$ and $y$. 
> 
> This distance function must satisfy the following:
> - $d(x,y)\geq 0\forall x,y \in X$
> - $d(x,y)=0\iff x=y$
> - $d(x,y)=d(y,x)$
> - $d(x,z)\leq d(x,y)+d(y,z)$ 
 ^def-top-met-spa

> [!definition|*]- Discrete metric
> For any space $X$, $d(x,y)=0\iff x=y$, otherwise $d(x,y)=c$, where $c$ is some constant.
 ^def-top-disc-met

> [!example|*]- Pythagoras Theorem as Distance
> This gives a notion of distance for points in (Euclidean) $\mathbb{R}^{n}$. Particularly when given $x=(x_{1},x_{2},\dots ,x_{n})$ and $y=(y_{1},y_{2},\dots,y_{n})$, the distance function is defined:
> $$d(x,y)=\sqrt[  ]{ \sum^{n}_{i=1}(x_{i}-y_{i})^{2} }$$
 ^exm-top-dist-pythag

> [!definition|*]- Ball
> Let $X$ be a metric space. A ball $B$ of radius $r$ around a point $x \in X$ is $B=\{ y \in X | d(x,y)<r \}$.
 ^def-top-ball

> [!definition|*]- Open (Set)
> A subset $O \subseteq X$ is open if for every point $x \in O$, there is a ball around $x$ entirely contained in $O$.
 ^def-top-open-set

> [!example|*]- Let $X=[0,1]$. The interval $\left( 0, \frac{1}{2} \right)$ is open in $X$.
> Let $x \in O$ such that $x=\varepsilon(>0)$. A ball of $r\leq \min\left( \varepsilon, \frac{1}{2}-\varepsilon \right)$ will satisfy being contained. This then holds for all points in the interval.
 ^exm-top-open

> [!example|*]- Let $X = \mathbb{R}$. The interval $[0, 1/2)$ is not open in $X$.
> Let $x \in O$. Lets choose $x=0$. To have this ball entirely contained in $O$ $r\leq 0$. Such a ball contains points $d(x,y)<r\leq 0$ so $d(x,y)<0$ and by the definition $d(x,y)\geq 0$. So no ball satisfies this $x$ and is not true $\forall x \in O$, hence it is not open
 ^exm-top-not-open

