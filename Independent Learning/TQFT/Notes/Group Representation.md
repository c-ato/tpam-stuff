---
tags:
  - maths/algebra
  - maths/vectors
  - maths/geometry
aliases:
  - fundamental representation
  - spin representation
  - subrepresentation
  - representation
---
> [!definition|*]- Group Representation
> This is a homomorphism that takes a group, $G$, and converts it into a general linear group, that is a linear transformation or matrix, $Q:G\to GL(V)$ where $V$ is the vector space the transformation acts on, and is called the representation space.
 ^def-alg-group-rep

> [!definition|*]- Subrepresentation
> Given a representation $Q:G\to GL(V)$, a subrepresentation is defined if there is some subspace $W$ of the vector space $V$ where $\forall g \in G$ and $\forall w \in W$,  $Q(g)w\in W$. That is to say that $W$ is invariant under $Q$, it can alternatively be described as closed under $Q$.
 ^def-alg-sub-rep

> [!definition|*]- Fundamental Representation
> We require that there are no subrepresentation, that is irreducible, except for the cases of the subspaces being trivial - the zero vector, $\{ 0 \}$, or the entire vector space, $V$.
 ^def-alg-fund-rep

> [!definition|*]- Spin Representation
> This is a group representation of the spin group, $Q:\text{Spin}(n)\to GL(S)$, where $S$ is a complex vector space called the spinor space. For spin groups these representations are often irreducible.
 ^def-alg-spin-rep
