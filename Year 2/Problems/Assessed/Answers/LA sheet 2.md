[[LIHW2.pdf]]

1. Let $\mathbb{E}^{3}$ denote the usual Euclidean space with basis B = $\{i, j, k\}$ which is orthonormal with respect to the Euclidean dot product. A generic element of $\mathbb{E}^{3}$ is denoted $\vec{a}$; its representation in the basis $B$ is $\vec{a}=a_{1}\mathbf{i}+a_{2}\mathbf{j}+a_{3}\mathbf{k}$, with the vector of coordinates denoted by $\mathbf{a}$, i.e., $\varphi_{B}(\vec{a})=\mathbf{a}$, where $\varphi_{B}$ is the coordinate map with respect to the basis $B$. 
   
   For any vectors $\vec{a},\vec{b}$ in $\mathbb{E}^{3}$, we define the following standard operations: 
   
   - the dot product: $$\vec{a}\cdot \vec{b}=a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}=\mathbf{a}^{T}\mathbf{b}=\mathbf{b}^{T}\mathbf{a}$$
   - the cross product (or vector product): $$\vec{a}\times \vec{b}=(a_{2}b_{3}-a_{3}b_{2})\mathbf{i}+(a_{3}b_{1}-a_{1}b_{3})\mathbf{j}+(a_{1}b_{2}-a_{2}b_{1})\mathbf{k}$$
Let $f ∈ \mathcal{L}(\mathbb{E}^{3})$ be defined via $f(\vec{v})=\vec{c}\times \vec{v}$ , where $\vec{c}=c_{1}\mathbf{i}+c_{2}\mathbf{j}+c_{3}\mathbf{k}$ is a given vector with $c_{i}\neq 0,i=1,2,3$. 
	(a) Find the matrix representation $A$ of $f$ with respect to the basis $B$. Write down the corresponding commutative diagram. 
$$f(\vec{v})=(v_{2}c_{3}-v_{3}c_{2})\mathbf{i}+(v_{3}c_{1}-v_{1}c_{3})\mathbf{k}+(v_{1}c_{2}-v_{2}c_{1})\mathbf{k}$$
$$A=\begin{pmatrix}
0 & c_{3} & -c_{2} \\
-c_{3} & 0 & c_{1} \\
c_{2} & -c_{1} & 0
\end{pmatrix}$$

	(b) Find ker A and hence derive ker f . State the rank of f . (c) Check directly (through calculations) that, for all x ∈ R3, cT Ax = xT Ax = 0