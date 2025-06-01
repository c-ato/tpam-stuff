1. 
- (a) Given vectors $\mathbf{a}=(1,2,3),\mathbf{b}=(-3,0,1)$ and $\mathbf{c}=(1,2,2)$
	- (i) $5\mathbf{a}-\mathbf{c}$
$$
=(4,8,13)
$$
- .
	- (ii) $(\mathbf{a\cdot c})\mathbf{a}$
$$
=(11,22,33)
$$
- .
	- (iii) $(\mathbf{a\times b})+\mathbf{c}$
$$
(3,-8,8)
$$
- (b) Suppose that $\mathbf{a}=(1,2,3)$ is a vector. Determine the scalar equation of the plane $\Pi$ perpendicular to $\mathbf{a}$ containing the point $P=(2,1,-2)$.
$$
x+2y+3z=d\qquad \overset{ P }{ \implies } 2+2-6=-2=d \therefore \Pi=x+2y+3z=-2
$$
- (c) Which of the following statements are true and which are false? For any statements that are false, provide a brief explanation as to why this is the case.
	- (i) Given any complex number $z ∈ \mathbb{C}, \mathrm{Re}(z)=\mathrm{Re}(\bar{z})$

This is true as complement only changes the sign of the imaginary part and not the real - $z=x+iy$, $\bar{z}=z-iy$
- 
	- (ii) Given any complex number $z ∈ \mathbb{C}, \bar{z}z$ is an integer.

Yes as there is no imaginary component $z\bar{z}=(x+iy)(x-iy)=x^{2}+y^{2}$

- .
	- (iii) Given any complex number $z ∈ \mathbb{C}$, the principal value $Arg(z)$ of $arg(z)$ satisfies $Arg(z) ∈ [0, 2π]$.

No it satisfies $Arg(z) \in(-\pi,\pi]$

- (d) Give an example of a system of two real simultaneous linear equations in two variables that has no solutions. (You do not need to justify your answer.)
$$
\begin{matrix}
x+y=1 \\
x+y=4
\end{matrix}
$$
- (e) Using the augmented matrix and row operations, find the solution set of the following system of real simultaneous linear equations: $$\begin{array}{}
x & + & 3y & + & 2z & = & 1 \\
 &  & 5y & + & 3z & = & -3 \\
3x & + & 4y & + & 3z & = & 6
\end{array}$$
$$
\left[ \begin{array}{lll|r}
1 & 3 & 2 & 1 \\
0 & 5 & 3 & -3 \\
3 & 4 & 3 & 6
\end{array} \right] \qquad \left[ \begin{array}{lll|r}
1 & 3 & 2 & 1 \\
0 & 5 & 3 & -3 \\
0 & -5 & -3 & 3
\end{array} \right]  \qquad \left[ \begin{array}{lll|r}
1 & 3 & 2 & 1 \\
0 & 5 & 3 & -3 \\
0 & 0 & 0 & 0
\end{array} \right]   \qquad \left[ \begin{array}{lll|r}
1 & 3 & 2 & 1 \\
0 & \frac{5}{3} & 1 & -1 \\
0 & 0 & 0 & 0
\end{array} \right] 
$$
$$
y=k\in \mathbb{R}\qquad\frac{5}{3}k+z=-1\implies z=-1-\frac{5}{3}k
$$
$$
x+3k+2z=x+3k-2-\frac{10}{3}k=x-2-\frac{1}{3}k=1\implies x=3+\frac{k}{3}
$$
2. 
- (a) $\mathbf{A}$, $\mathbf{B}$ and $\mathbf{C}$ are matrices in $\mathcal{M}_{nn}(\mathbb{R})$ such that $\det(A) = 2, \det(B) = -\frac{1}{2}$ and $\det(C) = \frac{1}{4}$ . Determine the value of $\det(C^{3} · B^{-1} · A^{2} · (B^{T} )^{2} · C^{T} · (A^{-1})^{3})$. 
$$
\det C^{3} · \det B^{-1} · \det A^{2} · \det (B^{T} )^{2} · \det C^{T} · \det (A^{-1})^{3}= 2^{-6}\cdot -2^{1} \cdot 2^{2}\cdot 2^{-4}\cdot 2^{-2}\cdot 2^{-3}=-2^{-10}
$$
- (b) Use Cramer’s rule to solve the system of simultaneous linear equations:$$\begin{matrix}4x_{1} & - & 6x_{2} & = & 2 \\-5x_{1} & + & 9x_{2} & = & 5\end{matrix}$$
$$
\begin{pmatrix}4 & -6 \\-5 & 9\end{pmatrix}\begin{pmatrix}
x_{1} \\
x_{2}
\end{pmatrix}=\begin{pmatrix}2\\5\end{pmatrix}
$$
$$
x_{1}=\frac{\det\begin{pmatrix}2 & -6 \\5 & 9\end{pmatrix}}{\det\begin{pmatrix}4 & -6 \\-5 & 9\end{pmatrix}}=\frac{38}{6} \qquad x_{2}=\frac{\det\begin{pmatrix}4 & 2 \\-5 & 5\end{pmatrix}}{\det\begin{pmatrix}4 & -6 \\-5 & 9\end{pmatrix}}= \frac{30}{6}
$$
- (c) Let $V = \mathcal{M}_{nn}(\mathbb{R})$ be the vector space of $n × n$ matrices. Prove or disprove that the set $W = \{\mathbf{A}\in\mathcal{M_{mn}}(\mathbb{R}) : \mathbf{A} = \mathbf{A}^{2}\}$ is a subspace of $V$. 

Only vectors satisfying this are $\mathbf{I}$ and $\mathbf{0}$ so lets observe for scalar multiplication:
$$
(2\mathbf{I})^{2}=4\mathbf{I^{2}}=4\mathbf{I}\neq 2\mathbf{I}
$$
$\therefore$ does not meet the criteria for a vector space and thus cannot be a subspace.

- (d) Let $V=\mathbb{R}^{3}$ and $U$ be a subspace of $V$ defined by $$U=\{ (x,y,z)\in \mathbb{R}^{3}:2x-3y+z=0 \}$$Determine a basis for $U$.
$$
3y-2x=z \therefore U=\{ (x,y,3y-2x)\in \mathbb{R}^{3}:2x-3y+z=0 \}
$$
$$
3y-2x=z \therefore U=\{ (x(1,0,-2)+y(0,1,3))\in \mathbb{R}^{3}:2x-3y+z=0 \}
$$
$$
U=\text{span}\{ (1,0,-2),(0,1,3) \}
$$
- (e) Prove or disprove whether the following mappings are linear:
	- (i) $T:\mathbb{R} ^{3}\to \mathbb{R}^{2}$ defined by $T((x,y,z))=(x,x+y)$
$$
T(x(1,0,0)+y(0,1,0)+z(0,0,1))=(x,x+y)=x(1,1)+y(0,1)
$$
$$
T(x(1,0,0))+T(y(0,1,0))+T(z(0,0,1))=(x,x)+(0,y)=x(1,1)+y(0,1)
$$
$$
\therefore T(\mathbf{v}_{1}+\mathbf{v}_{2}\dots)=T(\mathbf{v}_{1})+T(\mathbf{v}_{2})\dots
$$
This satisfies the conditions for linear transformation
- .
	- (ii) $T:\mathbb{R} ^{2}\to \mathbb{R}^{2}$ defined by $T((x,y))=(y^{2},x^{2})$
$$
\lambda T((x,y))=\lambda(y^{2},x^{2})\qquad T(\lambda(x,y))=T((\lambda x,\lambda y))=(\lambda^{2}y^{2},\lambda^{2}x^{2})=\lambda^{2}(y^{2},x^{2})
$$
$$
\therefore \lambda T((x,y))\neq T(\lambda(x,y))
$$
This shows that this is not a linear transformation.

- (f) Sketch the conic section defined by $$y^{2}+8x-6y+8-0$$and determine its type and eccentricity.

Sidewards parabola and has $e=1$

3. 
- (a) Suppose that $z=1-i$
	- (i) Calculate $z^{6}$ in both modulus-argument form and exponential form, giving the principal value of the argument.
$$
z=\sqrt[  ]{ 2 } e^{ i \frac{3\pi}{4} }\qquad z^{6}=8e^{ i \frac{\pi}{2} }=8i
$$
- .
	- (ii) What is the smallest choice of $n\in \mathbb{N}$ so that $z^{n}\in \mathbb{N}$
$n=0,4$
- 
	- (iii) Find all the fourth roots of z. Present your answers in exponential form giving the principal value of the argument.
$$
z^{\frac{1}{4}}=\sqrt[ 8 ]{ 2 } e^{ -i \frac{13\pi}{16} }\qquad\sqrt[ 8 ]{ 2 } e^{ -i \frac{5\pi}{16} }\qquad\sqrt[ 8 ]{ 2 } e^{ i \frac{3\pi}{16} }\qquad\sqrt[ 8 ]{ 2 } e^{ i \frac{11\pi}{16} }
$$
- (b) Suppose that $$\mathbf{A}=\begin{pmatrix}1 & 1 & 5 \\2 & 2 & 3 \\0 & 0 & 1\end{pmatrix}$$Use the Gaussian Elimination Algorithm to determine whether $\mathbf{A}$ is invertible or not. In particular, if $\mathbf{A}$ is invertible then determine $\mathbf{A}^{-1}$.
$$
\begin{array}{lll|r}1 & 1 & 5 & 1 \\2 & 2 & 3 & 3 \\0 & 0 & 1 & 1\end{array}\qquad\begin{array}{lll|r}1 & 1 & 0 & -4 \\2 & 2 & 0 & 0 \\0 & 0 & 1 & 1\end{array}\qquad\begin{array}{lll|r}1 & 1 & 0 & -4 \\1 & 1 & 0 & 0 \\0 & 0 & 1 & 1\end{array}
$$
This matrix is not invertible as $-4\neq 0$.

- (c) Suppose that $\mathbf{A},\mathbf{B}$ and $\mathbf{C}$ are matrices so that:
	- (1) $\mathbf{A\cdot B}$ is defined and is a $5 \times 3$ matrix
	- (2) $\mathbf{C\cdot A}$ is defined and is a $3 \times 3$ matrix
- Determine the dimensions of each of the matrices $\mathbf{A},\mathbf{B}$ and $\mathbf{C}$. Justify your answer

$\mathbf{A}$ has 5 rows from (1), and 3 columns from $(2)$, $\mathbf{B}$ has 3 columns from $(1)$ and 5 columns and $\mathbf{A}$, $\mathbf{C}$ has 3 rows from (2) and 5 columns from $\mathbf{A}$.

- (d) Suppose that $\mathbf{A}=\begin{pmatrix}a & b \\c & d\end{pmatrix}$ is a $2\times 2$ matrix such that $a,b,c,d>0 \in \mathbb{R}$. Prove that $\mathbf{A}\neq \mathbf{A}^{-1}$

Let $\mathbf{A}\neq \mathbf{I}$ or $\mathbf{A}\neq \mathbf{0}$ as these are trivial cases
$$
AA=A^{2}=A A^{-1}=I\qquad \therefore A^{2}=I\implies A=I^{\frac{1}{2}}=I \textreferencemark  \because A\neq I
$$
4. 
- (a) Determine the eigenvalues of the matrix $$\mathbf{A}=\begin{pmatrix}1 & 0 & 0 \\2 & 6 & -6 \\1 & 2 & -1\end{pmatrix}$$
$$
\mathbf{A}\underline{x}=\lambda\underline{x}\implies (\mathbf{A}-\lambda\mathbf{I})\underline{x}=0
$$
$$
\det\begin{pmatrix}1-\lambda & 0 & 0 \\2 & 6-\lambda & -6 \\1 & 2 & -1-\lambda\end{pmatrix}=(1-\lambda)((6-\lambda)(-1-\lambda)+12)=(1-\lambda)(\lambda^{2}-5\lambda-6)
$$
$$
=(1-\lambda)(\lambda-6)(\lambda+1)=0 \therefore \lambda=\pm 1,6
$$
- (b) Let $U$ and $W$ be subspaces of a vector space $V$.
	- (i) Prove that $U ∩W$ is a subspace of $V$.

As $U$ and $W$ are subspaces of $V$, they must also be subsets:
$$
U\subseteq V\land W\subseteq V \therefore (U\cap W)\subseteq V
$$
Hence we may then show that the subset $U\cap W$ is a subspace $\iff$ it satisfies closure under vector addition, vector scalar multiplication and is non-empty:

Both $U$ and $W$ are subspaces of $V$ so they must have a $\mathbf{0}$ vector and an identity vector $\mathbf{I}$ so are non empty:
$$
\mathbf{0,I}\in V\therefore\mathbf{0,I}\in U\qquad \mathbf{0,I}\in W
$$
Let $\mathbf{x,y}\in U \cap W\therefore \mathbf{x,y}\in U\land \mathbf{x,y}\in W$. Due to $U$ and $W$ being subspaces we then know that for $\mathbf{x,y}$ they satisfy closure under vector addition: 
$$\mathbf{x+y}\in U\qquad\mathbf{x+y}\in W\therefore \mathbf{x+y}\in (U\cap W)$$
Let $\mathbf{x}\in U \cap W\therefore \mathbf{x}\in U\land \mathbf{x}\in W$. Let $\lambda \in \mathbb{F}$. Due to $U$ and $W$ being subspaces we then know that $\mathbf{x}$ satisfies closure under vector scalar multiplication with $\lambda$:
$$
\mathbf{\lambda x}\in U\qquad\mathbf{\lambda x}\in W\therefore \mathbf{\lambda x}\in (U\cap W)
$$ 
- .
	- (ii) Prove that $U +W$ is a subspace of $V$ where $U+W=\{ \mathbf{u+w:u}\in U,\mathbf{w}\in W \}$

Both $U$ and $W$ are subspaces of $V$ so they must have a $\mathbf{0}$ vector and an identity vector $\mathbf{I}$ so are non empty:
$$
\mathbf{0,I}\in V\therefore\mathbf{0,I}\in U\qquad \mathbf{0,I}\in W
$$
Let $\mathbf{x+y}\in U + W$ so $\mathbf{x=u_{1}+w_{1},\,y=u_{2}+w_{2}}$ where $\mathbf{u_{1},u_{2}\in}U$ and $\mathbf{w_{1},w_{2}\in}W$. Then $\mathbf{x+y=(u_{1}+w_{1})+(u_{2}+w_{2})=(u_{1}+u_{2})+(w_{1}+w_{2})}\in U + W$. Due to $U$ and $W$ being subspaces we then know that they satisfy closure under vector addition $\mathbf{u_{1}+u_{2}=u_{T}}\in U$ and $\mathbf{w_{1}+w_{2}=w_{T}}\in W$ they satisfy closure under vector addition: 
$$\mathbf{x+y}=\mathbf{u_{T}+w_{T}}\in U+W$$
Let $\lambda\mathbf{x}\in U + W\therefore \mathbf{x=u_{1}+w_{1}}$. Let $\lambda \in \mathbb{F}$. Due to $U$ and $W$ being subspaces we then know that $\mathbf{u_{1},w_{1}}$ satisfy closure under vector scalar multiplication with $\lambda$:
$$
\mathbf{\lambda x=\lambda u_{1}+\lambda w_{1}}\in U+W\qquad \lambda \mathbf{u_{1}} \in U\qquad \lambda \mathbf{w_{1}}\in W
$$
- (c) Let $P_{2}$ be the vector space of real polynomials of order 2 defined by $$P_{2}=\{ a_{0}+a_{1}x+a_{2}x^{2}:a_{0},a_{1},a_{2}\in \mathbb{R} \}$$What are the coordinates of $\mathbf{v}\in P_{2}$ given by $\mathbf{v}=x^{2}+4x-3$ with respect to the ordered basis $\{ e_{1},e_{2},e_{3} \}$ given by $$e_{1}=x^{2}-2x+5\qquad e_{2}=2x^{2}-3x\qquad e_{3}=x+3$$
$$
\lambda_{1}e_{1}+\lambda_{2}e_{2}+\lambda_{3}e_{3}=(\lambda_{1}+2\lambda_{2})x^{2}+(-2\lambda_{1}-3\lambda_{2}+\lambda_{3})x+(5\lambda_{1}+3\lambda_{3})
$$
$$
\begin{matrix}
\lambda_{1} & + & 2\lambda_{2} & + & 0 & = & 1 \\
-2\lambda_{1} & + & -3\lambda_{2} & + & \lambda_{3} & = & 4 \\
5\lambda_{1} & + & 0 & + & 3\lambda_{3} & = & -3
\end{matrix}\qquad\begin{matrix}
\lambda_{1} & + & 2\lambda_{2} & + & 0 & = & 1 \\
0 & + & \lambda_{2} & + & \lambda_{3} & = & 6 \\
5\lambda_{1} & + & 0 & + & 3\lambda_{3} & = & -3
\end{matrix}
$$
$$
\begin{matrix}
\lambda_{1} & + & 2\lambda_{2} & + & 0 & = & 1 \\
0 & + & \lambda_{2} & + & \lambda_{3} & = & 6 \\
0 & + & -10\lambda_{2} & + & 3\lambda_{3} & = & -8
\end{matrix}\qquad \begin{matrix}
\lambda_{1} & + & 2\lambda_{2} & + & 0 & = & 1 \\
0 & + & \lambda_{2} & + & \lambda_{3} & = & 6 \\
0 & + & 0 & + & 13\lambda_{3} & = & 52
\end{matrix}
$$
$$
13\lambda_{3}=52 \iff\lambda_{3}=4\implies\lambda_{2}=2\implies\lambda_{1}=-3
$$
$\therefore(-3,2,4)$

- (d) Consider the vector space of $2\times 2$ real matrix $V=\mathcal{M}_{22}(\mathbb{R})$.
	- (i) What is the dimension of $V$? Write down the standard basis for $V$
$$
\lambda_{1},\lambda_{2},\lambda_{3},\lambda_{4}\in \mathbb{R}
$$
$$
\lambda_{1}\begin{pmatrix}1 & 0 \\0 & 0\end{pmatrix}+\lambda_{2}\begin{pmatrix}0 & 1 \\0 & 0\end{pmatrix}+\lambda_{3}\begin{pmatrix}0 & 0 \\1 & 0\end{pmatrix}+\lambda_{4}\begin{pmatrix}0 & 0 \\0 & 1\end{pmatrix}=\begin{pmatrix}\lambda_{1} & \lambda_{2} \\\lambda_{3} & \lambda_{4}\end{pmatrix}=\mathbf{0}=\begin{pmatrix}0 & 0 \\0 & 0\end{pmatrix}
$$
$$
\iff \lambda_{1}=\lambda_{2}=\lambda_{3}=\lambda_{4}=0
$$
This set of matrices are linearly independent and also spans $\mathcal{M}_{22}(\mathbb{R})$ so this gives the set of basis vectors:
$$
\mathcal{M}_{22}(\mathbb{R})=\text{span}\left\{ \begin{pmatrix}1 & 0 \\0 & 0\end{pmatrix},\begin{pmatrix}0 & 1 \\0 & 0\end{pmatrix},\begin{pmatrix}0 & 0 \\1 & 0\end{pmatrix},\begin{pmatrix}0 & 0 \\0 & 1\end{pmatrix} \right\} 
$$
Hence $\dim V=4$ as there are $4$ basis vectors.
- .
	- (ii) Consider the linear transformation $T:V\to V$ defined by $T(\mathbf{A})=\mathbf{M\cdot A}$ where $\mathbf{M}=\begin{pmatrix}1 & -1 \\ -2 & 2\end{pmatrix}$. Find a basis and dimension of the kernel of $T$ and a basis and dimension of the image $T$
$$
\mathbf{M\cdot A}=\begin{pmatrix}1 & -1 \\ -2 & 2\end{pmatrix}\begin{pmatrix}\lambda_{1} & \lambda_{2} \\\lambda_{3} & \lambda_{4}\end{pmatrix}=\begin{pmatrix}\lambda_{1}-\lambda_{3} & \lambda_{2}-\lambda_{4} \\-2\lambda_{1}+2\lambda_{3} & -2\lambda_{2}+2\lambda_{4}\end{pmatrix}=\begin{pmatrix}0 & 0 \\0 & 0\end{pmatrix}
$$
$$
\lambda_{1}=\lambda_{3}\qquad\lambda_{2}=\lambda_{4}\qquad A=\begin{pmatrix}\lambda_{1} & \lambda_{2} \\\lambda_{1} & \lambda_{2}\end{pmatrix}=\lambda_{1}\begin{pmatrix}1 & 0 \\1 & 0\end{pmatrix}+\lambda_{2}\begin{pmatrix}
0 & 1 \\
0 & 1
\end{pmatrix}
$$
$$
\therefore \ker(T)=\left\{ \begin{pmatrix}1  & 0 \\1 & 0\end{pmatrix},\begin{pmatrix}0 & 1 \\0 & 1\end{pmatrix} \right\} \therefore \dim(\ker(T))=2
$$
$$
\mathbf{M\cdot A}=\begin{pmatrix}\lambda_{1}-\lambda_{3} & \lambda_{2}-\lambda_{4} \\-2\lambda_{1}+2\lambda_{3} & -2\lambda_{2}+2\lambda_{4}\end{pmatrix}=\begin{pmatrix}x & y \\
-2x & -2y\end{pmatrix}=x\begin{pmatrix}1 & 0 \\-2 & 0\end{pmatrix}+y\begin{pmatrix}0 & 1 \\0 & -2\end{pmatrix}
$$
$$
\therefore \text{im }T=\left\{ \begin{pmatrix}1 & 0 \\-2 & 0\end{pmatrix},\begin{pmatrix}0 & 1 \\0 & -2\end{pmatrix} \right\} \therefore \dim(\text{im}(T))=2
$$
- (e) This question involves the rotation transform given by $$x=\tilde{x}\cos (a)-\tilde{y}\sin(\alpha)$$and$$y=\tilde{x}\sin(\alpha)+\tilde{y}\cos(\alpha)$$where the value of the rotation angle $\alpha$ is chosen to eliminate the cross term $xy$. Determine an expression for $$-2x^{2}+2\sqrt[  ]{ 3 }xy-4=0$$
$$
xy=\tilde{x}\tilde{y}\cos ^{2}\alpha-\tilde{x}\tilde{y}\sin ^{2}\alpha+\tilde{x}^{2}\sin\alpha \cos\alpha-\tilde{y}^{2}\cos\alpha \sin\alpha=0\qquad
$$
$$
x^{2}=\tilde{x}^{2}\cos ^{2}\alpha-2\tilde{x}\tilde{y}\cos\alpha \sin\alpha+\tilde{y}^{2}\sin ^{2}\alpha
$$
$$
-2x^{2}+2\sqrt[  ]{ 3 }xy-4=0=-2\tilde{x}^{2}\cos ^{2}\alpha+4\tilde{x}\tilde{y}\cos\alpha \sin\alpha-2\tilde{y}^{2}\sin ^{2}\alpha+2\sqrt[  ]{ 3 }\tilde{x}\tilde{y}\cos ^{2}\alpha
$$
$$
-2\sqrt[  ]{ 3 }\tilde{x}\tilde{y}\sin ^{2}\alpha+2\sqrt[  ]{ 3 }\tilde{x}^{2}\sin\alpha \cos\alpha-2\sqrt[  ]{ 3 }\tilde{y}^{2}\cos\alpha \sin\alpha-4=0
$$
$$
\tilde{x}\tilde{y}:4\cos\alpha \sin\alpha+2\sqrt[  ]{ 3 }(\cos ^{2}\alpha-\sin ^{2}\alpha)=0\implies2\sin(2\alpha)=-2\sqrt[  ]{ 3 }\cos(2\alpha)
$$
$$
\alpha=-\frac{\pi}{3}\qquad -2\tilde{x}^{2}\cos ^{2}\alpha-2\tilde{y}^{2}\sin ^{2}\alpha+2\sqrt[  ]{ 3 }\tilde{x}^{2}\sin\alpha \cos\alpha-2\sqrt[  ]{ 3 }\tilde{y}^{2}\cos\alpha \sin\alpha-4=0
$$
$$
\,- \frac{\tilde{x}^{2}}{2}-\frac{3\tilde{y}^{2}}{2}+\frac{3\tilde{x}^{2}}{2} -\frac{3\tilde{y}^{2}}{2}-4=\tilde{x}^{2}-3\tilde{y}^{2}-4=0\implies \tilde{x}^{2}-3\tilde{y}^{2}=4
$$
This is a hyperbola with $e=\sqrt[  ]{ 1+\frac{1}{9} }=\frac{\sqrt[  ]{ 10 }}{3}$.