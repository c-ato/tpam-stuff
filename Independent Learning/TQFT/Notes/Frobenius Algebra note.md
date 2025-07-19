---
tags:
  - maths
  - physics
  - topology
  - quantum
---

> [!definition|*]- (Commutative) Frobenius Algebra (cFA)
> There are a few alternative definitions, I will focus on the categorical definition which is a sensible choice given we are dealing with categories
> 
> (Commutative) Frobenius alegbra (cFA) exists in a symmetric monoid_{A} l group (which a TQFT exists within) $(\mathcal{C},\otimes,I)$ where $I$ is the unit object. A Frobenius algebra is an object, $A \in \text{Obj}(\mathcal{C})$ equipped with the following structures:
> 
> - A multiplication morphism $m:A\otimes A\to A$
> - A unit morphism $\eta :I\to A$ These satisfy the usual associativity and unit axioms for an algebra
> 	- $m\circ (m\otimes id_{A} ​)$=$m\circ (id_{A} ​\otimes m)$ (associativity)
> 	- $m\circ (\eta \otimes id_{A} ​)$=$id_{A} ​=m\circ (id_{A} ​\otimes \eta )$ (unit laws)
> - A comultiplication morphism $\Delta :A\to A\otimes A$
> - A counit morphism $\varepsilon:A\to I$ These satisfy the usual coassociativity and counit axioms for a coalgebra:
> 	- $(\Delta \otimes id_{A} ​)\circ \Delta =(id_{A} ​\otimes \Delta )\circ \Delta$  (coassociativity)
> 	- $(ϵ\otimes id_{A} ​)\circ \Delta =id_{A} ​=(id_{A} ​\otimes ϵ)\circ \Delta$  (counit laws)
> - The Frobenius Axiom $(m\otimes id_{A} ​)\circ (id_{A} ​\otimes \Delta )=(id_{A} ​\otimes m)\circ (\Delta \otimes id_{A} ​)$
> - $m=m \circ \sigma_{A,A}$, where $\sigma_{A,A}$ is the symmetry isomorphism, or in other words commutes the variables (commutative)
 ^def-cat-cFA

> [!theorem|*]- TQFT is equivalent to cFA
> 
 ^thm-

