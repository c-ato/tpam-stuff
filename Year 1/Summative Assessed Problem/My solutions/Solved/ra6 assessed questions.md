[[RA6.pdf]]

AQ1. (a) Let $X$ denote a subset of $\mathbb{R}$ and suppose that $−∞ < a < b < ∞$:
- (i) Define what it means for X to be a bounded set.
$$
X= \{\forall x \in X: a\leq x\leq b \}
$$
For all elements $x$ of $X$, $a\leq x\leq b$ 

- (ii) Define what it means for $f : X → \mathbb{R}$ to be a bounded function.
$$
\forall x \in X,a<f(x)<b
$$
- (iii) Define what it means for $P$ to be a partition of the interval $[a, b]$.

A partition of $P$ of $[a,b]$ is a finite set $P=\{ x_{0},x_{1},x_{2}\dots x_{n} \}$ s.t. $a=x_{0}<x_{1}<x_{2}<\dots<x_{n}=b$ where $n \in \mathbb{N}$.

- (iv) Define what it means for a bounded function $f : [a, b] → [0, ∞)$ to be integrable.

For $\varepsilon>0 \exists U(f,P)-L(f,P)<\varepsilon$

- (v) State Riemann’s Criterion for Integrability

$\forall \varepsilon>0 \exists U(f,P)-L(f,P)<\varepsilon$ is equivalent to $f$ being integrable

(b) Consider the function $f : [1, 6π] → [−9, 7000]$ defined by
$$
f(x)= \left\{ \begin{matrix}
x^{2},  & x<2\pi; \\
3+\sin x,  & x \in [2\pi,4\pi]; \\
e^{ -x },  & x>4\pi.
\end{matrix} \right. 
$$
- (i) Suppose that $x_{0} = 1, x_{1} = 2$ and $x_{2} = 4π$. For each $i ∈ \{1, 2\}$, find the interval $I_{i}$ such that $\{f (x) : x ∈ [x_{i−1}, x_{i}]\} = I_{i}$. Note that here an interval refers to any of $[a, b], (a, b], [a, b),$ or $(a, b),$ where $−∞ < a < b < ∞$.
$$
I_{1}=[1,4]\qquad I_{2}=[2,4\pi^{2})
$$
- (ii) Suppose that $P = \{1, 2, 4π, 6π\}$. Calculate the Riemann–Darboux sum $L(f, P )$.
$$
x_{1}=1\qquad x_{2}=2\qquad x_{3}=4\pi\qquad x_{4}=6\pi
$$
$$
L(f,P)=\sum_{i=1}^{3}=m_{i}(x_{i+1}-x_{i})
$$
where $m_{i}=\inf(f(x): x \in [x_{i},x_{i+1}])$
$$
\therefore m_{1}=\inf(I_{1})=1\qquad m_{2}=\inf(I_{2})=2\qquad m_{3}=\inf(f(x): x \in [4\pi,6\pi])=e^{ -6\pi }
$$
$$
\therefore L(f,P)=m_{1}(x_{2}-x_{1})+m_{2}(x_{3}-x_{2})+m_{3}(x_{4}-x_{3})=1(1)+2(4\pi-2)+2\pi(e^{ -6\pi })
$$

$$
L(f,P)=8\pi-3+2\pi e^{ -6\pi }=2\pi(4+e^{ -6\pi })-3
$$
- (iii) Suppose that $Q = \{1, 3, 5, 5π, 6π\}$ and $R = \{1, 3, 2π, 6π\}$. Calculate $U (f, Q ∪ R)$.
$$
Q\cup R=T=\{ 1,3,5,2\pi,5\pi,6\pi \}\qquad U(f,T)=\sum_{i=1}^{5}=M_{i}(x_{i+1}-x_{i})
$$
$$
x_{1}=1\qquad x_{2}=3\qquad x_{3}=5\qquad x_{4}=2\pi\qquad x_{5}=5\pi\qquad x_{6}=6\pi
$$

where $M_{i}=\sup(f(x): x \in [x_{i},x_{i+1}])$
$$
M_{1}=9\qquad M_{2}=25\qquad M_{3}=4\pi^{2}\qquad M_{4}=4\qquad M_{5}=e^{ -5\pi }
$$
$$
\therefore U(f,T)=M_{1}(x_{2}-x_{1})+M_{2}(x_{3}-x_{2})+M_{3}(x_{4}-x_{3})+M_{4}(x_{5}-x_{4})+M_{5}(x_{6}-x_{5})
$$
$$
=U(f,T)=9(2)+25(2)+4\pi^{2}(2\pi-5)+4(3\pi)+e^{ -5\pi }(\pi)=18+50+8\pi^{3}-20\pi^{2}+12\pi+e^{ -5\pi }\pi
$$
$$
U(f,T)=8\pi^{3}-20\pi^{2}+\pi(12+e^{ -5\pi })+68
$$
(c) Use Riemann’s Criterion to prove that $f : [12, 22] → \mathbb{R}$ defined by
$$
f(x)\left\{ \begin{matrix}
7,  &12\leq x\leq 15; \\
4,  &15<x<22; \\
15,  &x=22,
\end{matrix} \right. 
$$
$$
P_{\varepsilon}=\{ x \in[12,22] \}
$$
Let $\varepsilon>0$. For each $n \in \mathbb{N},$ using $P_{\varepsilon}$ of $[12,15,15+\delta,22-\delta,22]$. Let $\delta>0$. Now observe
$$
\varepsilon<U(f,P_{\varepsilon})-L(f,P_{\varepsilon})=\sum^{n-1}_{i=1}M_{i}(x_{i+1}-x_{1})-\sum^{n-1}_{i=1}m_{i}(x_{i+1}-x_{1})
$$
$$
=7(3)+7(\delta)+4(7-2\delta)+15(\delta)-(7(3)+4(\delta)+4(7-2\delta)+4(\delta))=14\delta
$$
$$
\therefore \varepsilon>U(f,P_{\varepsilon})-L(f,P_{\varepsilon})= 14\delta \iff \varepsilon>14\delta
$$
Let us now choose $\delta=\frac{\varepsilon}{28}$
$$
U(f,P_{\varepsilon})-L(f,P_{\varepsilon})=\frac{\varepsilon}{2}<\varepsilon
$$
Hence by Riemann's Criterion, this is integrable.