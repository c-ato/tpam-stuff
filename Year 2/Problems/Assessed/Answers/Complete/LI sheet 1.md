1. 
   (a)
Starting with $\vec{u}_{1}=\vec{v}_{1}$ and then using properties of linearity $\vec{u}_{2}$ is
$$\vec{u}_{2}=\vec{v}_{2}-\sum^{1}_{j=1} \frac{\left< \vec{v}_{2},\vec{u}_{j} \right> }{\left< \vec{u}_{j},\vec{u}_{j} \right> }\vec{u}_{j}=\vec{v}_{2}-\frac{\left< \vec{v}_{2},\vec{v}_{1} \right> }{\left< \vec{v}_{1},\vec{v}_{1} \right> }\vec{v}_{1}$$
$$\left< \vec{u}_{1},\vec{u}_{2} \right> =\left< \vec{v}_{1}, \vec{v}_{2}-\frac{\left< \vec{v}_{2},\vec{v}_{1} \right> }{\left< \vec{v}_{1},\vec{v}_{1} \right> }\vec{v}_{1}\right>= \left< \vec{v}_{1}, \vec{v}_{2}\right> -\frac{\left< \vec{v}_{2},\vec{v}_{1} \right> }{\left< \vec{v}_{1},\vec{v}_{1} \right> }\left< \vec{v}_{1},\vec{v}_{1}\right>=\left< \vec{v}_{1},\vec{v}_{2} \right> -\left< \vec{v}_{2},\vec{v}_{1} \right>   $$
$$\left< \vec{v}_{1},\vec{v}_{2} \right> -\left< \vec{v}_{1},\vec{v}_{2} \right>=0$$
Suppose that for $B_{l}:=\{ \vec{u}_{1},\vec{u}_{2},\dots,\vec{u}_{l} \}$ and the following is true $\left< \vec{u}_{i},\vec{u}_{j} \right>=0 \forall i,j\leq l\in \mathbb{N},i\neq j$
Then we need to show this stands for $B_{l+1}$ and the additional vector is given by
$$\vec{u}_{l+1}=\vec{v}_{l+1}-\sum^{l+1}_{j=1} \frac{\left< \vec{v}_{l+1},\vec{u}_{j} \right> }{\left< \vec{u}_{j},\vec{u}_{j} \right> }\vec{u}_{j}$$
Then consider $\left< \vec{u}_{l+1},\vec{u}_{m} \right>$ for a $1\leq m\leq l \in \mathbb{N}$
$$\left< \vec{u}_{l+1},\vec{u}_{m} \right>=\left< \vec{v}_{l+1}-\sum^{l+1}_{j=1} \frac{\left< \vec{v}_{l+1},\vec{u}_{j} \right> }{\left< \vec{u}_{j},\vec{u}_{j} \right> }\vec{u}_{j},\vec{u}_{m} \right>=\left< \vec{v}_{l+1},\vec{u}_{m} \right>-\sum^{l+1}_{j=1} \left( \frac{\left< \vec{v}_{l+1},\vec{u}_{j} \right> }{\left< \vec{u}_{j},\vec{u}_{j} \right> } \left< \vec{u}_{j},\vec{u}_{m} \right> \right)
$$
Note that when $j\neq m$ we have $\left< \vec{u}_{j},\vec{u}_{m} \right>=0$ so, a term only appears when $j=m$ so the summation simplifies to
$$=  \left< \vec{v}_{l+1},\vec{u}_{m} \right>-\frac{\left< \vec{v}_{l+1},\vec{u}_{m} \right> }{\left< \vec{u}_{m},\vec{u}_{m} \right> } \left< \vec{u}_{m},\vec{u}_{m} \right> =\left< \vec{v}_{l+1},\vec{u}_{m} \right>- \left< \vec{v}_{l+1},\vec{u}_{m} \right> =0$$
This set is then only defined for $l\leq k-1$
     (b)
The first 2 orthonormal basis vectors will be the same as the original basis but the rest will be defined as the procedure
	(c)
The first $m$ vectors of the orthonormal basis will be the same as the first $m$ of the original and the rest will be generated as per the procedure

2. 
   (a)
Let $P=a_{0}+a_{1}x+a_{2}x^{2}$ and $p_{1}=1$ and $p_{2}=x$
$$p_{3}=P-\sum^{2}_{j=1} \frac{\left< P,p_{j} \right>  }{\left< p_{j},p_{j} \right>}p_{j}=a_{0}+a_{1}x+a_{2}x^{2} - \frac{\int ^{1}_{-1} a_{0}+a_{1}x+a_{2}x^{2} \, dx }{\int ^{1}_{-1} 1 \, dx }-\frac{\int ^{1}_{-1} a_{0}x+a_{1}x^{2}+a_{2}x^{3} \, dx }{\int ^{1}_{-1} x^{2} \, dx }x$$
$$=a_{0}+a_{1}x+a_{2}x^{2}-\left( \frac{2a_{0}+\frac{2a_{2}}{3}}{2} \right)-\left( \frac{\frac{2a_{1}}{3}}{\frac{2}{3}} \right)x=a_{0}+a_{1}x+a_{2}x^{2}-a_{0}-\frac{a_{2}}{3}-a_{1}x=a_{2}x^{2}- \frac{a_{2}}{3}$$
Monic: $a_{2}=1$
$$x^{2}-\frac{1}{3}$$
	(b)
Proposition 6.5
$$\mid\mid \vec{v}^{\perp}_{U} \mid\mid=\mid\mid \vec{v}-\vec{v}^{\parallel}_{U} \mid\mid\leq \mid\mid \vec{v}-\vec{z} \mid\mid \forall \vec{z} \in U$$

$$\mid\mid q-p^{*} \mid\mid\leq \mid\mid q-p \mid\mid \forall \vec{z} \in U$$
Construct parallel polynomial to $U$
$$p^{*}=\sum_{j=1}^{3} \frac{\left< q,p_{j} \right>  }{\left< p_{j},p_{j} \right>  }p_{j}= \frac{\int ^{1}_{-1} x^{3} \, dx }{\int ^{1}_{-1} 1 \, dx }+\frac{\int ^{1}_{-1} x^{4} \, dx }{\int ^{1}_{-1} x^{2} \, dx }x+\frac{\int ^{1}_{-1} x^{5}-\frac{1}{3}x^{3} \, dx }{\int ^{1}_{-1} x^{4}-\frac{2}{3}x^{2}+\frac{1}{9} \, dx }\left( x^{2}-\frac{1}{3} \right)$$
$$0+\frac{3}{5}x+0=p^{*}$$