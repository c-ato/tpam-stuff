[[A34927_LCSeqSeries_QP_Main2024.pdf]]

1. 
- (a)
	- (i) Define what it means for a sequence $(a_{n})$ of real numbers to tend to infinity

Let $M>0\in \mathbb{R}\, \exists a_{n}>M\forall n>N \in \mathbb{N}$.

- .
	- (ii) Using the definition show that the sequence $(a_{n})$ given by $a_{n}=n^{3}$ tends to infinity.
$$
a_{N}=N^{3}>M \therefore N>\sqrt[ 3 ]{ M } \therefore a_{n}>M\forall n>\sqrt[ 3 ]{ M } \in \mathbb{N}
$$
- (b)
	- (i) Define what it means for a sequence $(a_{n})$ of real numbers to converge to a real number $\ell$.
$$
\left|a_{n}-\ell \right|<\varepsilon \forall n>N
$$
- .
	- (ii) Using the definition show that the sequence $(a_{n})$ given by $$a_{n}= \frac{n^{2}+3n+1}{2n^{2}-n+1}$$converges to $\frac{1}{2}$.
$$
\varepsilon>\left|\frac{n^{2}+3n+1}{2n^{2}-n+1}-\frac{1}{2} \right|=\left| \frac{2n^{2}+6n+2-2n^{2}+n-1}{4n^{2}-2n+2} \right|=\left| \frac{7n+1}{4n^{2}-2n+2} \right|\geq \left| \frac{7n}{4n^{2}} \right|=\frac{7}{4n}
$$
$$
\implies N> \frac{7}{4\varepsilon}
$$