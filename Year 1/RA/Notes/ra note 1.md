---
tags:
  - maths
  - analysis
---
Complete/Strong induction is when previously proven statements be used to prove a general expression or statement, more formally put
$$
\text{For all }f(i):\,i\leq k
$$
Example: Prove for every $n\geq 2$ has a prime factorisation.
$$
\text{Let }P(n)\text{ be the statement "n has a prime factorisation"}
$$
$$
\text{If }n=2\text{, 2 is prime so }P(2) \text{ is true}
$$
$$\text{
Indution step: Assume that }P(2),\,P(3)\dots P(k)\text{ are all true for } 
$$
$$
m\leq k,\text{ m has a prime factorisation}
$$
$\text{Consider k+1}$
$$
\text{If k+1 is prime, then we are done, else k+1 is prime. So there are }
$$
$$
2\leq k,k<k+1
$$
$$
k+1=k_{1}k_{2}
$$
$$
\text{Since }2\leq k,k_{2}\leq k,\,P(k_{1})\text{ and }P(k_{2})\text{ are true by hypothesis, }k_{1}
$$
$$
\text{ and }k_{2}\text{ have prime factorisations}
$$
---
Contraposition:
$$
P\to Q\iff Q¬\to P¬
$$

Prove $\sqrt[  ]{ 2 }$ is irrational.

Suppose $\sqrt[  ]{ 2 }=\frac{p}{q}$, a rational number
$$
\implies 2=\frac{p^{2}}{q^{2}}\iff 2q^{2}=p^{2}\therefore p=2n\implies 2q^{2}=4n^{2}
$$
$$
 q^{2}=2n^{2}\therefore \text{ q is even }\therefore \text{ q and p have a common factor of }2
$$
$$
\text{ which is a contradiction as should have none}
$$
$$
\sqrt[  ]{ n }=\frac{p}{q}
$$
$$
n=\frac{p^{2}}{q^{2}}\iff nq^{2}=p^{2}\therefore\text{ n is a factor of p such}
$$
$$
q^{2}=np^{2}\therefore\text{q and q have common factor of n}
$$

---
An irrational number to an irrational power can be rational:
If $\sqrt[  ]{ 2 }^{\sqrt[  ]{ 2 }}$ is rational then we are done, else it is not rational then, $(\sqrt[  ]{ 2 }^{\sqrt[  ]{ 2 }})^{\sqrt[  ]{ 2 }}=\sqrt[  ]{ 2 }^{2}=2$ which is rational

Lemma is something we prove to prove something bigger

Proposition is a baby theorem

Corollary is something that follows from a theorem

