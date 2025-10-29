Notation $S=\{ v_{1},v_{2},\dots,v_{k} \}$ for $v_{i}\in V$ then where $f:V\to W$ is a linear transformation, then $f(S)=\{ f(v_{1}),f(v_{2}),\dots,f(v_{k}) \}$, $f(V)=\mathrm{Im}\,f$

> [!remark|*]- Linear transformation image is less than set
> $$\left| f(S) \right|\leq \left| S \right| \forall f \in \mathcal{L} (V,W)$$if injective then $\left| f(S) \right|=\left| S \right|$
 ^rmk-la

> [!proposition|*]- Span of linear transformation is the linear transformation of the span
> $$f(\text{span }S)=\text{span }f(S)$$ 
 ^prp-la-lin-tra-span

> [!theorem|*]- If $S$ is linearly independent then linear transformation $f(S)$ is too
 ^thm-la-li-lr

> [!definition|*]- Rank and Nullity
> The nullity of a map $f$ is $\text{nullity}(f)=\dim \ker f$
> The rank of a map $f$ is $\text{rank}(f)=\dim \mathrm{Im} f$
> $0\leq\text{nullity}(f)\leq \dim V$
> $0\leq \text{rank}(f)\leq \dim W$
 ^def-la-rank-null

> [!theorem|*]- Rank nullity formula
> $$\text{rank}(f)+\text{nullity}(f)=\dim V$$
 ^thm-la-rank-null-form

> [!definition|*]- Matrix representations of a linear transformation
> Let $f \in \mathcal{L}(V,W)$, where $B_{V}$ is a base vector for $V$, $B_{W}$ is a basis vector for $W$.
> $B_{V}=\{ v_{1},v_{2},\dots,v_{n} \}$ and $B_{W}=\{ w_{1},w_{2},\dots,w_{m} \}$ where $w \in f(v_{i})=\sum^{M}_{j=1}a_{ji}w_{j}$
> The matrix $A=\left[ a_{ji} \right]_{\begin{array}1 1\leq i\leq n \\ 1\leq j\leq m\end{array}}$ is the matrix representation of $f$ with respect to $B_{V}$ with $B_{W}$
 ^def-la-mat-rep

