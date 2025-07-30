---
tags:
  - maths
  - physics
  - maths/topology
  - quantum
  - maths/category
  - maths/algebra
aliases:
  - frobenius
  - Frobenius
---

> [!definition|*]- (Commutative) Frobenius Algebra (cFA)
> There are a few alternative definitions, I will focus on the categorical definition which is a sensible choice given we are dealing with [[categories]]
> 
> (Commutative) Frobenius alegbra (cFA) exists in a symmetric [[Monoidal Category|monoidal]] group (which a [[TQFT]] exists within) $(\mathcal{C},\otimes,I)$ where $I$ is the unit object. A Frobenius algebra is an object, $A \in \text{Obj}(\mathcal{C})$ equipped with the following structures:
> 
> - A multiplication [[Morphisms|morphism]] $m:A\otimes A\to A$
> - A unit [[Morphisms|morphism]] $\eta :I\to A$ These satisfy the usual associativity and unit axioms for an algebra
> 	- $m\circ (m\otimes id_{A} ​)$=$m\circ (id_{A} ​\otimes m)$ (associativity)
> 	- $m\circ (\eta \otimes id_{A} ​)$=$id_{A} ​=m\circ (id_{A} ​\otimes \eta )$ (unit laws)
> - A comultiplication [[Morphisms|morphism]] $\Delta :A\to A\otimes A$
> - A counit [[Morphisms|morphism]] $\varepsilon:A\to I$ These satisfy the usual coassociativity and counit axioms for a coalgebra:
> 	- $(\Delta \otimes id_{A} ​)\circ \Delta =(id_{A} ​\otimes \Delta )\circ \Delta$  (coassociativity)
> 	- $(ϵ\otimes id_{A} ​)\circ \Delta =id_{A} ​=(id_{A} ​\otimes ϵ)\circ \Delta$  (counit laws)
> - The Frobenius Axiom $(m\otimes id_{A} ​)\circ (id_{A} ​\otimes \Delta )=(id_{A} ​\otimes m)\circ (\Delta \otimes id_{A} ​)$
> - $m=m \circ \sigma_{A,A}$, where $\sigma_{A,A}$ is the symmetry [[Morphisms|isomorphism]], or in other words commutes the variables (commutative)
 ^def-cat-cFA

> [!theorem|*]- [[TQFT]] is [[Equivalence|equivalent]] to cFA
 ^thm-cat-cFA-equiv-TQFT

