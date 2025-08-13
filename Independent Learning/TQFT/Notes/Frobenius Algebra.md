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

> [!definition|*]- (Commutative) Frobenius Algebra ((c)FA)
> There are a few alternative definitions, I will focus on the categorical definition which is a sensible choice given we are dealing with [[categories]]
> 
> (Commutative) Frobenius alegbra (cFA) exists in a symmetric [[Monoidal Category|monoidal]] category (which a [[TQFT]] exists within) $(\mathcal{C},\otimes,I)$ where $I$ is the unit object. A Frobenius algebra is an object, $A \in \text{Obj}(\mathcal{C})$ equipped with the following structures:
> 
> - A multiplication [[Morphisms|morphism]] $m:A\otimes A\to A$
> - A unit [[Morphisms|morphism]] $\eta :I\to A$. These satisfy the usual associativity and unit axioms for an algebra
> 	- $m\circ (m\otimes id_{A} ​)$=$m\circ (id_{A} ​\otimes m)$ (associativity)
> 	- $m\circ (\eta \otimes id_{A} ​)$=$id_{A} ​=m\circ (id_{A} ​\otimes \eta )$ (unit laws)
> - A comultiplication [[Morphisms|morphism]] $\Delta :A\to A\otimes A$
> - A counit [[Morphisms|morphism]] $\varepsilon:A\to I$, These satisfy a specific property, and the usual coassociativity and counit axioms for a coalgebra:
> 	- $\varepsilon$ must also define a non-degenerate bilinear form on $A$, given by $B( a,b )=\varepsilon(m(a\otimes b))$
> 	- $(\Delta \otimes id_{A} ​)\circ \Delta =(id_{A} ​\otimes \Delta )\circ \Delta$  (coassociativity)
> 	- $(ϵ\otimes id_{A} ​)\circ \Delta =id_{A} ​=(id_{A} ​\otimes ϵ)\circ \Delta$  (counit laws)
> - IF commutative, a symmetry isomorphism, $\sigma_{A,A}:A\otimes A\to A\otimes A$ (commutative law)
> - The Frobenius Axiom $(m\otimes id_{A} ​)\circ (id_{A} ​\otimes \Delta )=(id_{A} ​\otimes m)\circ (\Delta \otimes id_{A} ​)$
 ^def-cat-FA

> [!theorem|*]- [[TQFT]] is [[Equivalence|equivalent]] to cFA
 ^thm-cat-cFA-equiv-TQFT

> [!definition|*]- Super Frobenius Algebra (sFA)
> This builds off a super vector space with its grading, so let a sFA be $A=A_{\bar{0}}+A_{\bar{1}}$ where it is an object in the symmetric monoidal category of super vector spaces, $(sVect,\otimes,k)$ equipped with the following structures that respect the grading of the super vector space:
> - A multiplication [[Morphisms|morphism]] $m:A\otimes A\to A$, which satisfies $m(A_{\bar{i}}\otimes A_{\bar{j}})\subseteq A_{\bar{i}+\bar{j}\,\text{mod }2}$
> - A unit [[Morphisms|morphism]] $\eta :I\to A$ such that unit object is in the evens, $1_{A}\in A_{\bar{0}}$. These satisfy the usual associativity and unit axioms for an algebra
> 	- $m\circ (m\otimes id_{A} ​)$=$m\circ (id_{A} ​\otimes m)$ (associativity)
> 	- $m\circ (\eta \otimes id_{A} ​)$=$id_{A} ​=m\circ (id_{A} ​\otimes \eta )$ (unit laws)
> - A comultiplication [[Morphisms|morphism]] $\Delta :A\to A\otimes A$, which satisfies $\Delta(A_{\bar{k}})\subseteq (A\otimes A)_{\bar{k}}$
> - A counit [[Morphisms|morphism]] $\varepsilon:A\to I$, which is a super-trace meaning $\varepsilon(A_{\bar{1}})=0$. These satisfy a specific property, and the usual coassociativity and counit axioms for a coalgebra:
> 	- $\varepsilon$ must also define a super non-degenerate bilinear form on $A$, given by $B( a,b )=\varepsilon(m(a\otimes b))$
> 	- $(\Delta \otimes id_{A} ​)\circ \Delta =(id_{A} ​\otimes \Delta )\circ \Delta$  (coassociativity)
> 	- $(ϵ\otimes id_{A} ​)\circ \Delta =id_{A} ​=(id_{A} ​\otimes ϵ)\circ \Delta$  (counit laws)
> - A super-symmetry [[Morphisms|isomorphism]], $\sigma_{A,A}:A\otimes A\to A\otimes A$, that satisfies $m=m\circ\sigma_{A,A}$ such that element wise $m(a\otimes b)=(-1)^{\text{deg}(a)\cdot \text{deg}(b)}m(b\otimes a)$ (super commutative law)
> - The Frobenius Axiom $(m\otimes id_{A} ​)\circ (id_{A} ​\otimes \Delta )=(id_{A} ​\otimes m)\circ (\Delta \otimes id_{A} ​)$
 ^def-alg-sFA