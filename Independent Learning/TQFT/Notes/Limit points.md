---
tags:
  - maths
  - maths/topology
aliases:
  - limit point
---
> [!definition|*]- Limit points
> A point $z$ is a limit point for a set $A$ if every [[Metric space|open set]] $U$ containing $z$ intersects $A$ in a point other than $z$.
> The point $z$ may or may not be in $A$
 ^def-top-lim-point

> [!example|*]- Open unit disk $D=\{ (x,y):x^{2}+y^{2}<1 \}$ and $z=(1,0)$
> $z$ is not an element of $D$ as $1^{2}+0^{2}=1$ which is not $<1$

> [!definition|*]- Closed (Set)
> A set $C$ is closed if $X-C$ is open.
 ^def-top-close

`\begin{proof}` A closed set includes all its limit points,

Let $C$ be closed. In the trivial case where $C$ does not have any limit points, this holds. $C'$ is the complement and hence open as $C$ is closed by definition $X-C'=C$

Now suppose that $z$ is a limit point of $C$ and for contradiction, assume that $z\notin C$. This means that $z\in C'$ which is a contraction as by the definition of an open set there exists a subset $U\subseteq C'$ which would not intersect $C$ as $C'\cap C=\varnothing$ and by transitivity of a set $U\cap C=\varnothing$ and hence $z$ is not a limit point of $C$. $\therefore$ by contradiction $z \in C$ so all limit points $z$ are contained in $C$ a closed set.
`\end{proof}`

> [!theorem|*]- Closed (Set)
> A set $C$ is closed $\iff$ it contains all of its limit points.
 ^thm-top-closed-set

> [!example|*]- Let $A = \mathbb{Z}$, a subset of $\mathbb{R}$. This is a closed set because it does contain all of its limit points; no point is a limit point! A set that has no limit points is closed, by default, because it contains all of its limit points.
 ^exm-int-clos-lim

