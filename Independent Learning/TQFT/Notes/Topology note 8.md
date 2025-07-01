---
Note number: 8
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf
Title Stem: Topology
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%20
tags:
  - maths
  - physics
  - topology
  - quantum
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%209" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=81" class="button">Go to PDF Page 81
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%207" class="button">Previous
	</a> 
</div>

![[Topology note 7#^def-top-eul-char]] 

> [!theorem|*]- Euler Characteristic on Good Graph used.
> Euler Characteristic of any surface is Independent of the Good Graph used to calculate it.
 ^thm-top-eul-char-good-gra

> [!theorem|*]- Euler Characteristic is Topologically Invariant
> The Euler characteristic is a topological invariant that allows us to distinguish whether or not two surfaces are homomorphic. Surfaces that have the same Euler characterisitic are not necessarily homeomorphic, but if they are both orientable (or non-orientable), then they are. 
 ^thm-eul-char-inv

> [!theorem|*]- Identification Polygons are Good Graphs
> It is important to notice that an identification polygon is a good graph of a surface that has a vertex at every end of edge and there is exactly one face. Therefore, identification polygons are good graphs on a surface and can be used to compute the Euler characteristic
 ^thm-top-iden-polyg-good-gra

![[0. Topology Notes (pre project).pdf#page=85&rect=203,479,396,692|0. Topology Notes (pre project), p.85]]

$$2-2+1=1$$

> [!definition|*]- Connected Sums
> If you are given two surfaces you can take the connected sum of the two surfaces to give one single surface. To take the connected sum you remove a disc from each surface and connect up the two resulting boundary circles by a cylinder. Connected sums are denoted by the $\#$ sign such that $A\#B$ would be the connected sum of surfaces $A$ and $B$ (assuming that the operation $\#$ is well-defined).
> ![[0. Topology Notes (pre project).pdf#page=85&rect=93,181,503,279|0. Topology Notes (pre project), p.85]]
 ^def-top-conn-sum

![[0. Topology Notes (pre project).pdf#page=88&rect=165,442,434,740|0. Topology Notes (pre project), p.88]]

> [!theorem|*]- Well Defined Connected Sum
> To show that the operation of connected sums is well defined we must show that given two sets that are path connected, regardless of where the discs were took out of in each set; you will obtain the same resulting surface (same in the sense of homomorphic of course).
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
> There are $3$ equivalent definitions:
> 1. Any closed surface is homomorphic either to (No two of the following are homomorphic):
> - Sphere $(S^{2})$
> - The sphere with a finite number of handles added
> - The sphere with a finite number of disks replaced by Mobius strips.
> 2. Any closed surface is homomorphic either to (No two of the following are homomorphic):
> - The sphere 
> - A connected sum of tori 
> - A connected sum of projective planes
> 3. Any closed surface is homomorphic either to (No two of the following are homomorphic):
> - The sphere 
> - A connected sum of tori 
> - A connected sum of a tori and one projective plane 
> - A connected sum of a tori and two projective planes
 ^thm-top-class-thm
