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
$$\therefore \ker A=\{ \mathbf{v} \}=\left\{ \begin{pmatrix}
v_{1} \\
v_{1} \frac{c_{2}}{c_{1}} \\
v_{1} \frac{c_{3}}{c_{1}}
\end{pmatrix} \right\}=\left\{ \frac{v_{1}}{c_{1}}\begin{pmatrix}
c_{1} \\
c_{2} \\
c_{3}
\end{pmatrix} \right\}=\left\{ \begin{pmatrix}
c_{1} \\
c_{2} \\
c_{3}
\end{pmatrix} \right\}  $$
$\therefore$ by the result $\ker f\cong \ker A$ so:
$$\ker f=\{ c_{1}\mathbf{i}+c_{2}\mathbf{j}+c_{3}\mathbf{k} \}$$
the $\text{rank }f$ is given by the rank nullity relation:
$$\text{rank}f+\text{nullity}f=\dim\mathbb{E} ^{3}=3\therefore \text{rank}f=2$$
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
We see that for $\vec{x}\in \mathbb{R}^{3},\vec{x}\cdot f(\vec{x})=\vec{x}\cdot \vec{c}\times\vec{x}=0$, so $\vec{x}\perp f(\vec{x})$ or in the questions case $\vec{v}\perp f(\vec{v})$.

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
$$\mathbf{c}^{T}\mathbf{y}=\mathbf{c\cdot y}=0$$
To verify lets first check if using $\mathbf{y}\in \text{col }A$ satisfies $S$:
$$\begin{matrix}
\begin{pmatrix}
c_{1} \\
c_{2} \\
c_{3}
\end{pmatrix}\cdot \begin{pmatrix}
0 \\
c_{3} \\
-c_{2}
\end{pmatrix}=c_{1}0+c_{2}c_{3}-c_{3}c_{2}=0 \\
\begin{pmatrix}
c_{1} \\
c_{2} \\
c_{3}
\end{pmatrix}\cdot \begin{pmatrix}
-c_{3} \\
0 \\
c_{1}
\end{pmatrix}=-c_{1}c_{3}+c_{2}0-c_{3}c_{1}=0 \\
\begin{pmatrix}
c_{1} \\
c_{2} \\
c_{3}
\end{pmatrix}\cdot \begin{pmatrix}
c_{2} \\
-c_{1} \\
0
\end{pmatrix}=c_{1}c_{2}-c_{2}c_{1}+c_{3}0=0
\end{matrix}$$
We see it satisfies for all $\mathbf{y}\in \text{col }A$ so now we can check the subspace criteria through their closure conditions under scalar multiplication and scalar multiplication. We will use the properties of the dot product.
$$\mathbf{y}_{1},\mathbf{y}_{2}\in \text{col }A\qquad \mathbf{c}\cdot(a\mathbf{y}_{1})=a(\mathbf{c}\cdot \mathbf{y}_{1})=a(0)=0\qquad \mathbf{c}\cdot(\mathbf{y}_{1}+\mathbf{y}_{2})=\mathbf{c}\cdot \mathbf{y}_{1}+\mathbf{c}\cdot \mathbf{y}_{2}=0+0=0$$
We can see in both cases they satisfy closure and so $\text{col }A\leq S$
- ii. $\dim S= 2$
$$$$