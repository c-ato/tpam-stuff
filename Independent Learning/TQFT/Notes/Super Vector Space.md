---
tags:
  - maths
  - maths/category
  - maths/vectors
  - maths/algebra
aliases:
  - super vector spaces
---

> [!definition|*]- Super Vector Space ($\mathbb{Z}_{2}$-Graded Vector Space) 
> This is a vector space over a field $k$, and is equipped with the following:
> - a direct sum decomposition: $$V=V_{\bar{0}}\oplus V_{\bar{1}}$$
> 	- $V_{\bar{0}}$ is the even subspace as $\bar{0}$ is the set of all integers that correspond to $0$ in $\text{mod}(2)$ - this is also known as the bosonic subspace.
> 	- $V_{\bar{1}}$ is hence, the odd subspace, $\bar{1}$ is then the set of all integers that corresponds to $1$ in $\text{mod}(2)$ - this is also known as the fermionic subspace.
> - The degree of a vector is defined $\forall v \in V\exists \text{deg}(v)$ where it is defined as: $$\text{deg}(v)=\left\{ \begin{matrix}\bar{0} & \text{if }v \in V_{\bar{0}} \\ \bar{1} & \text{if }v \in V_{\bar{1}}\end{matrix} \right. $$
> 	- And as such any $v \in V$ can be uniquely written as a sum of its homogeneous components: $v=v_{\bar{0}}+v_{\bar{1}}$ where $v_{\bar{0}}\in V_{\bar{0}}$ and $v_{\bar{1}}\in V_{\bar{1}}$ 
> - The [[Functors|tensor product]] of two of these SVS is given as:
> $$V\otimes W=\sum^{1}_{k=0}(V\otimes W)_{\bar{k}}$$
> $$(V\otimes W)_{\bar{0}}=(V_{\bar{0}}\otimes W_{\bar{0}})\oplus (V_{\bar{1}}\otimes W_{\bar{1}})$$
> $$(V\otimes W)_{\bar{1}}=(V_{\bar{0}}\otimes W_{\bar{1}})\oplus (V_{\bar{1}}\otimes W_{\bar{0}})$$
> 
> - We will also have a super commutativity relation for the symmetry [[Morphisms|isomorphism]] $T:V\otimes W\to W\otimes V$ is given by: $$T(v\otimes w)=(-1)^{\text{deg}(v)\text{deg}(w)}(w\otimes v)$$
 ^def-vect-svs
