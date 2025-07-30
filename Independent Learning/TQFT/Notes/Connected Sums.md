---
tags:
  - maths
  - maths/topology
aliases:
  - connected sum
---

> [!definition|*]- Connected Sums
> If you are given two [[surfaces]] you can take the connected sum of the two [[surfaces]] to give one single [[Surfaces|surface]]. To take the connected sum you remove a disc from each [[Surfaces|surface]] and connect up the two resulting boundary circles by a cylinder. Connected sums are denoted by the $\#$ sign such that $A\#B$ would be the connected sum of [[surfaces]] $A$ and $B$ (assuming that the operation $\#$ is well-defined).
> ![[0. Topology Notes (pre project).pdf#page=85&rect=93,181,503,279|0. Topology Notes (pre project), p.85]]
 ^def-top-conn-sum

![[0. Topology Notes (pre project).pdf#page=88&rect=165,442,434,740|0. Topology Notes (pre project), p.88]]

> [!theorem|*]- Well Defined Connected Sum
> To show that the operation of connected sums is well defined we must show that given two sets that are [[Connectedness|path connected]], regardless of where the discs were took out of in each set; you will obtain the same resulting [[Surfaces|surface]] (same in the sense of [[Morphisms|homomorphic]] of course).
 ^thm-top-wel-def-conn-sum

> [!example|*]- $\mathbb{R} P^{2}\#T=\mathbb{R} P^{2}\#\mathbb{R} P^{2}\#\mathbb{R} P^{2}$
> Connected sum of the projective plane and a torus:
> ![[0. Topology Notes (pre project).pdf#page=88&rect=87,161,511,346|0. Topology Notes (pre project), p.88]]
> ![[0. Topology Notes (pre project).pdf#page=89&rect=53,128,531,747|0. Topology Notes (pre project), p.89]]
 ^exm-top-tor-hash-proj-plane

> [!theorem|*]- Connected Sums are Associative
> $(S_{1}\#S_{2})\#S_{3}=S_{1}\#(S_{2}\#S_{3})$. This naturally follows for well defined connected sums.
 ^thm-top-conn-sum-assoc

> [!theorem|*]- Euler's Characteristic of a Connected Sum
> $\chi(A\#B)=\chi(A)+\chi(B)-2$
 ^thm-top-eul-char-conn-sum

> [!theorem|*]- Classification Theorem
> There are $3$ [[Equivalence|equivalent]] definitions:
> 1. Any closed [[Surfaces|surface]] is [[Morphisms|homomorphic]] either to (No two of the following are [[Morphisms|homomorphic]]):
> - Sphere $(S^{2})$
> - The sphere with a finite number of handles added
> - The sphere with a finite number of disks replaced by Mobius strips.
> 2. Any closed [[Surfaces|surface]] is [[Morphisms|homomorphic]] either to (No two of the following are [[Morphisms|homomorphic]]):
> - The sphere 
> - A connected sum of tori 
> - A connected sum of projective planes
> 3. Any closed [[Surfaces|surface]] is [[Morphisms|homomorphic]] either to (No two of the following are [[Morphisms|homomorphic]]):
> - The sphere 
> - A connected sum of tori 
> - A connected sum of a tori and one projective plane 
> - A connected sum of a tori and two projective planes
 ^thm-top-class-thm
