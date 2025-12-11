[[LIHW2.pdf]]

1. Let $\mathbb{E}^{3}$ denote the usual Euclidean space with basis B = $\{i, j, k\}$ which is orthonormal with respect to the Euclidean dot product. A generic element of $\mathbb{E}^{3}$ is denoted $\vec{a}$; its representation in the basis $B$ is $\vec{a}=a_{1}\mathbf{i}+a_{2}\mathbf{j}+a_{3}\mathbf{k}$, with the vector of coordinates denoted by $\mathbf{a}$, i.e., $\varphi_{B}(\vec{a})=\mathbf{a}$, where $\varphi_{B}$ is the coordinate map with respect to the basis $B$. 
   
   For any vectors $\vec{a},\vec{b}$ in $\mathbb{E}^{3}$, we define the following standard operations: 
   
   - the dot product: $$\vec{a}\cdot \vec{b}=a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}=\mathbf{a}^{T}\mathbf{b}=\mathbf{b}^{T}\mathbf{a}$$
   - the cross product (or vector product): $$\vec{a}\times \vec{b}=(a_{2}b_{3}-a_{3}b_{2})\mathbf{i}+(a_{3}b_{1}-a_{1}b_{3})\mathbf{j}+(a_{1}b_{2}-a_{2}b_{1})\mathbf{k}$$
Let $f ∈ \mathcal{L}(\mathbb{E}^{3})$ be defined via $f(\vec{v})=\vec{c}\times \vec{v}$ , where $\vec{c}=c_{1}\mathbf{i}+c_{2}\mathbf{j}+c_{3}\mathbf{k}$ is a given vector with $c_{i}\neq 0,i=1,2,3$. 

(a) Find the matrix representation $A$ of $f$ with respect to the basis $B$. Write down the corresponding commutative diagram. 

$$f(\vec{v})=(v_{2}c_{3}-v_{3}c_{2})\mathbf{i}+(v_{3}c_{1}-v_{1}c_{3})\mathbf{j}+(v_{1}c_{2}-v_{2}c_{1})\mathbf{k}$$
$$\implies A\begin{pmatrix}
v_{1} \\
v_{2} \\
v_{3}
\end{pmatrix}=\begin{pmatrix}
c_{2}v_{3}-c_{3}v_{2} \\
c_{3}v_{1}-c_{1}v_{3} \\
c_{1}v_{2}-c_{2}v_{1}
\end{pmatrix}\therefore A=\begin{pmatrix}
0 & -c_{3} & c_{2} \\
c_{3} & 0 & -c_{1} \\
-c_{2} & c_{1} & 0
\end{pmatrix}$$
![[LA sheet 2 2025-12-04 09.45.33.excalidraw]]

(b) Find $\ker A$ and hence derive $\ker f$ . State the rank of $f$. 

$$A\mathbf{v}=\begin{pmatrix}
c_{2}v_{3}-c_{3}v_{2} \\
c_{3}v_{1}-c_{1}v_{3} \\
c_{1}v_{2}-c_{2}v_{1}
\end{pmatrix}=\mathbf{0}$$
$$c_{3}v_{1}-c_{1}v_{3}0\implies v_{3}=v_{1}\frac{c_{3}}{c_{1}}\qquad c_{1}v_{2}-c_{2}v_{1}=0\implies v_{2}=v_{1} \frac{c_{2}}{c_{1}}$$
Check if valid solution
$$c_{2}v_{3}-c_{3}v_{2}= c_{2} v_{1} \frac{c_{3}}{c_{1}}-c_{3} v_{1} \frac{c_{2}}{c_{1}}=0$$
$$\therefore \ker A=\text{span }\{ \mathbf{v} \}=\text{span }\left\{ \begin{pmatrix}
v_{1} \\
v_{1} \frac{c_{2}}{c_{1}} \\
v_{1} \frac{c_{3}}{c_{1}}
\end{pmatrix} \right\}= \text{span }\left\{ \begin{pmatrix}
c_{1} \\
c_{2} \\
c_{3}
\end{pmatrix} \right\}  $$
$\therefore$ by the result $\ker f\cong \ker A$ so:
$$\ker f=\text{span }\{ c_{1}\mathbf{i}+c_{2}\mathbf{j}+c_{3}\mathbf{k} \}$$
the $\text{rank }f$ is given by the rank nullity relation:
$$\text{rank}f+\text{nullity}f=\text{rank}f+1=\dim\mathbb{E} ^{3}=3\therefore \text{rank}f=2$$
If further reasoning is required consider that it has a basis of 3 vectors.

(c) Check directly (through calculations) that, for all $x \in \mathbb{R}^{3}$, $$\mathbf{c}^{T}A\mathbf{x}=\mathbf{x}^{T}A\mathbf{x}=0$$Deduce that $f(\vec{v})\perp \text{span }\{ \vec{c},\vec{v} \}$. 

$$\mathbf{c}^{T}\overset{ =\mathbf{z} }{ (A\mathbf{x}) }=\mathbf{x}^{T}\overset{ =\mathbf{z} }{ (A\mathbf{x}) }\qquad \mathbf{z}=\begin{pmatrix}
c_{2}x_{3}-c_{3}x_{2} \\
c_{3}x_{1}-c_{1}x_{3} \\
c_{1}x_{2}-c_{2}x_{1}
\end{pmatrix}$$
$$\mathbf{c}^{T} \mathbf{z}=\begin{pmatrix}
c_{1} & c_{2} & c_{3}
\end{pmatrix}\begin{pmatrix}
c_{2}x_{3}-c_{3}x_{2} \\
c_{3}x_{1}-c_{1}x_{3} \\
c_{1}x_{2}-c_{2}x_{1}
\end{pmatrix}=\textcolor{orange}{\cancel{ c_{1}c_{2}x_{3} }}\cancel{- c_{1}c_{3}x_{2} }\textcolor{purple}{\cancel{ +c_{2}c_{3}x_{1} }}\textcolor{orange}{\cancel{ -c_{1}c_{2}x_{3} }}\cancel{ +c_{1}c_{3}x_{2} }\textcolor{purple}{\cancel{- c_{2}c_{3}x_{1} }}$$
$$=0$$
$$\mathbf{x}^{T} \mathbf{z}=\begin{pmatrix}
x_{1} & x_{2} & x_{3}
\end{pmatrix}\begin{pmatrix}
c_{2}x_{3}-c_{3}x_{2} \\
c_{3}x_{1}-c_{1}x_{3} \\
c_{1}x_{2}-c_{2}x_{1}
\end{pmatrix}=x_{1}c_{2}x_{3}-x_{1}c_{3}x_{2}+x_{2}c_{3}x_{1}-c_{1}x_{2}x_{3}+c_{1}x_{3}x_{2}-c_{2}x_{3}x_{1}$$
$$=c_{1}(-x_{2}x_{3}+x_{3}x_{2})+c_{2}(x_{1}x_{3}-x_{3}x_{1})+c_{3}(-x_{1}x_{2}+x_{2}x_{1})=c_{1}(0)+c_{2}(0)+c_{3}(0)=0$$
$$\mathbf{x}^{T}A\mathbf{x} \cong \vec{x}\cdot f(\vec{x})=\vec{x}\cdot \vec{c}\times\vec{x}=0$$
We see that for $\vec{x}\in \mathbb{R}^{3},\vec{x}\cdot f(\vec{x})=\vec{x}\cdot \vec{c}\times\vec{x}=0$, so $\vec{x}\perp f(\vec{x})$ or in the questions case $\vec{v}\perp f(\vec{v})$. Alternatively we may consider that $\vec{c} \times \vec{x}$ produces a vector that is normal to both, which is then dotted with one of the vectors that it is normal to it, $\vec{x}$ so the dot product always result $0$.

(d) Let $S=\{ \mathbf{y}\in \mathbb{R}^{3}:\mathbf{c}^{T}\mathbf{y}=0 \}$. Show that
- i. $\text{col }A\leq S;$
$$\text{col }A=\text{span }\left\{ \begin{pmatrix}
0 \\
c_{3} \\
-c_{2}
\end{pmatrix},\begin{pmatrix}
-c_{3} \\
0 \\
c_{1}
\end{pmatrix}, \begin{pmatrix}
c_{2} \\
-c_{1} \\
0
\end{pmatrix} \right\} $$

To verify lets first check if using $\mathbf{y}\in \text{col }A$ satisfies $S$:
$$\begin{matrix}
\begin{pmatrix}
c_{1}  & c_{2}  & c_{3}
\end{pmatrix} \begin{pmatrix}
0 \\
c_{3} \\
-c_{2}
\end{pmatrix}=c_{1}0+c_{2}c_{3}-c_{3}c_{2}=0 \\
\begin{pmatrix}
c_{1}  & c_{2}  & c_{3}
\end{pmatrix}  \begin{pmatrix}
-c_{3} \\
0 \\
c_{1}
\end{pmatrix}=-c_{1}c_{3}+c_{2}0-c_{3}c_{1}=0 \\
\begin{pmatrix}
c_{1}  & c_{2}  & c_{3}
\end{pmatrix} \begin{pmatrix}
c_{2} \\
-c_{1} \\
0
\end{pmatrix}=c_{1}c_{2}-c_{2}c_{1}+c_{3}0=0
\end{matrix}$$
We see it satisfies for all $\mathbf{y}\in \text{col }A$ so now we can check the subspace criteria through their closure conditions under scalar multiplication and scalar multiplication. We will use the properties of the dot product.
$$\mathbf{y}_{1},\mathbf{y}_{2}\in \text{col }A\qquad \mathbf{c}\cdot(a\mathbf{y}_{1})=a(\mathbf{c}\cdot \mathbf{y}_{1})=a(0)=0\qquad \mathbf{c}\cdot(\mathbf{y}_{1}+\mathbf{y}_{2})=\mathbf{c}\cdot \mathbf{y}_{1}+\mathbf{c}\cdot \mathbf{y}_{2}=0+0=0$$
We can see in both cases they satisfy closure and so $\text{col }A\leq S$
- ii. $\dim S= 2$

As we know $\text{rank}f=2$, it means $\dim\text{col }A=2$, so $S\geq \text{col }A\implies \dim S\geq \dim\text{col }A= 2$. $S$ contains $\mathbf{y}\in \mathbb{R}^{3}$, this means if we start with some arbitrary vector, $\mathbf{y}_{1}$ that satisfies $S$ then this vector is normal to $\mathbf{c}$ by the definition of the dot product. If we choose this to be a bases vector of $S$ we may then find the next subsequent normal vector, $\mathbf{y}_{2}$ (we know that this at least exists as $\dim S\geq 2$) to $\mathbf{c}$ from their cross product. 

Once we have $\mathbf{c},\mathbf{y}_{1}$ and $\mathbf{y}_{2}$ we have a set of 3 normal vectors that span $\mathbb{R}^{3}$ as we have 3 linearly independent vectors. If we were to suppose another normal vector to $\mathbf{c}$ exists that isn't a linear combination of $\mathbf{y}_{1},\mathbf{y}_{2}$ then we have a bases of $S$ that has $3$ vectors and the $\mathbb{R}^{3}$ with $4$ vectors, however this is a contradiction as $\dim \mathbb{R}^{3}=3$ and 4 vector bases $\implies \dim \mathbb{R}^{3}=4$, so $\dim S< 3$. We then are left with the only possibility that satisfies $2\leq\dim S<3$ which is $\dim S=2$.

Now as we shown that $\text{col }A$ satisfied the subspace criteria of $S$, we then can use the bases vectors of $\text{col }A$ for $S$ and as they have the same dimensions means they have the same number of bases vectors, and by only using the bases vectors of $\text{col }A$ for $S$, there is no linearly independent vectors left in $S$ so $\text{col }A=S$.

(e) Without performing any calculations, explain why $λ = 0$ is an eigenvalue of $f$ . What is its geometric multiplicity?

The kernel is non-trivial so $f(\vec{0})=0\cdot\vec{0}$ is the only vector that satisfies this out of the linear combinations of the vector spanning the kernel.
$$\gamma(\lambda)=\dim(\ker E_{\lambda})=\dim( f-\lambda I)\qquad \gamma(0)=\dim(\ker f)=1$$
