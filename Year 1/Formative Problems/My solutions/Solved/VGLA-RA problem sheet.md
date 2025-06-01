[[year1intro-qus.pdf|question sheet here]]

1a)
$$
a_{n}=2n+1\implies \sum^{n}_{1}(2n-1)\text{ Let n=3 }\implies \sum^{3}_{1}(2n-1)=9
$$
Thus supposed $p(k)$ is true and $p(k+1)$ is to be proved:
$$

\sum^{k}_{j=1}(2j-1)=k^{2}
$$
$$
\sum^{k+1}_{j=1}(2j-1)=
\sum^{k}_{j=1}(2j-1)+2k+1=k^{2}+2k+1=(k+1)^{2}
$$
$\because$p(k) and p(k+1) are true, by induction all values of k are true

1b)

Let $r = 4$ for the height of a red block, and $b = 5$ for the height of a blue and n is some constructed height. 

Let $s$ be the number of red blocks and let $t$ be the number of blue blocks.

Suppose $n=12=3r+0b$ and $n=13=2r+1b$

Base step 1: Let $k= sr+tb$ s.t $k+1=(s-1)r+(t+1)b$, where $s \in\mathbb{N}\geq 1$ and $t\in\mathbb{N}_{0}\geq 0$.

Now suppose $n = 15= 0r+3b$ and $n=16=4r+0b$

Base step 2: When $s=0$ let $k= 0r+tb$ s.t $k+1=4r+(t-3)b$ where $s =0$ and $t\in\mathbb{N}\geq 3$.

This gives that the smallest $N$ that can be constructed by base step 2 is $15$ fulfilled by the smallest condition of $t=3$ where $k=15$ and $k+1=16$.

Thus it follows by the reverse of base step 1 from $15$, the smallest $N$ that can be constructed that for all $k\geq N$, is $k=12\therefore N=12$

$\therefore$ By the principles of mathematical induction all values $k\geq 12$ can be constructed by some combination of r and b

1c)

Should you do this for a pack of size 1 the remaining is a $\varnothing \ne$ any dog type

2a)
$$
|x+2|>x^{2}-1\implies \begin{matrix}
x+2>x^{2}-1 \\
-(x+2)>x^{2}-1\,:\text{ No real solution}
\end{matrix}
$$
$$
\implies \frac{1+ \sqrt[  ]{ 13 }}{2}<x< \frac{1+ \sqrt[  ]{ 13 }}{2}
$$
2b)
$$
\frac{x^{2}-1}{x^{3}+x^{2}-6x}= \frac{(x+1)(x-1)}{}\leq 0
$$
3a) $$
(A\cap B)\cap C=A\cap(B\cap C)
$$
proof:
$$
(A\cap B)=A+B-(A\cup B)\,,\,(B\cap C)=B+C-(B\cup C)
$$
$$
(A+B-(A\cup B))\cap C=A\cap(B+C-(B\cup C))
$$
$$
(A+B)\cap C-(A\cup B)\cap C=A\cap(B+C)-A\cap(B\cup C)
$$
$$
\cancel{ A\cap C }+B\cap C-(A\cup B)\cap C=A\cap B+\cancel{ A\cap C }-A\cap(B\cup C)
$$
$$
B\cap C-(A\cup B)\cap C=A\cap B-A\cap(B\cup C)
$$
$$
(A\cup B)\cap C=(A\cup B)+C-(A\cup B)\cup C\,,\,A\cap(B\cup C)=A+B \cup C -A\cup(B\cup C)
$$
$$
B\cap C-((A\cup B)+C-(A\cup B)\cup C)=A\cap B-(A+B \cup C -A\cup(B\cup C))
$$
$$\cancel{ 
A\cup B\cup C }+B\cap C-A\cup B-C=\cancel{ A\cup B\cup C }+A\cap B-B\cup C-A
$$
$$
B\cap C-A\cup B-C=A\cap B-B\cup C-A
$$
$$
\cancel{ B }+\cancel{ C }-B\cup C-A\cup B-\cancel{ C }=\cancel{ A }+\cancel{ B }-A\cup B-B\cup C-\cancel{ A }
$$
$$
-B\cup C-A\cup B\equiv-A\cup B-B\cup C
$$
$$
\therefore\text{ initial equation is correct}
$$

3b)
$$
A\cap(B\cup C)=(A∩B)∪(A∩C)
$$
proof:
$$
A\cap(B\cup C)=(A∩B)+(A∩C)-(A∩B)\cap(A∩C)
$$
$$
A+(B\cup C)-A\cup B\cup C=A+B-A\cup B+A+C-A\cup C-A\cap (B\cap C)
$$
$$
\cancel{ A }+(B\cup C)-A\cup B\cup C=\cancel{ A }+B-A\cup B+\cancel{ A }+C-A\cup C-(\cancel{ A } +B\cap C-A\cup (B\cap C))
$$
$$
B\cup C-A\cup B\cup C=B+C-B\cap C-A\cup B-A\cup C+A\cup(B+C-B\cup C)
$$
$$
B\cup C-A\cup B\cup C=B\cup C\cancel{ -A\cup B-A\cup C+A\cup B+A\cup C }-A\cup B\cup C
$$
$$
\because B\cup C - A\cup B \cup C\equiv B\cup C - A\cup B\cup C
$$
$$
\text{This proves initial statement is true}
$$
3c)
$$
A − (B ∩ C) = (A − B) ∪ (A − C)
$$
proof:
$$
A\cap(B\cap C)'=(A\cap B')\cup(A\cap C')
$$
$$
A\cap(B\cap C)'=A( B'\cap C')
$$
$$
\because A\cap(B\cap C)'\equiv A( B\cap C)'
$$
$$
\text{This proves the initial statement}
$$
4a)
$$
(x,y)=(w,z)\therefore (w,z):=\{ \{ w \},\{ w,z \} \}=\{ \{ x \},\{ x,y \} \}
$$
Case 1:
$$
\{ x \}=\{ w,z \}\implies x=w=z\implies(w,z)=\{ \{ x \} \}\neq (x,y) \textreferencemark 
$$
Case 2:
$$
\{ x \}=\{ w \}\implies x=w\,,\,\{ x,y \}=\{ w,z \}\implies y=z\implies (w,z)=\{ \{ x \},\{ x,y \} \}=(x,y)
$$
4b)
$$
A:=\{ x \in X:x \not\in x \}
$$
$$A\in X|\implies A \in A \therefore \textreferencemark \text{(is a contradiction)} \because x\not\in x.\text{ Else }A \notin X \implies A\in X \because x\not\in x\,\textreferencemark .$$
4c) 
$$
x \in A\cup B\cup C\,,\,A,B,C \in \cup(A,B,C)\therefore  \cup(A,B,C)\subseteq A\cup B\cup C
$$
$$
\text{ and } A\cup B\cup C \subseteq \cup(A,B,C) \implies A\cup B\cup C \equiv \cup(A,B,C) 
$$
4d)
$$
\cap C=0\,,\,\cup C=\mathbb{R}
$$
4e)
$$
D=\{ \mathbb{N},\mathbb{P} \}
$$
5a)
Yes, $\forall x$ expressed as a decimal, will have a value at its 3rd decimal place, $\therefore\forall x,f:x\mapsto y=[0,9]$ 

5b) $f:x \mapsto 9^{x}$
	i)$$x=-3\implies f(-3)=9^{-3}= \frac{1}{9^{3}}=\frac{1}{729}$$
	ii) $$f\left( -\frac{5}{2} \right)=9^{-5/2}= \frac{1}{3^{5}} $$
	iii) $$f\left( -\frac{1}{2} \right)=9^{-1/2}=\frac{1}{3} $$
	iv) $$f\left( \frac{1}{2} \right)=9^{1/2}=3 $$
	v) $$f\left( \frac{3}{2} \right)=9^{3/2}=27 $$
	vi) $$f(x)=9^{x}=81\implies x=2 $$

5c)
	i)$$f:x^{2}\mapsto y$$
	ii) $$f:x^{2}\mapsto y$$
	iii) $$f:x^{2}\mapsto y$$
5d)
$$
f:x^{2}\mapsto y\text{, not injective either}
$$

5e)
$$
f:x^{2}\mapsto y\text{, not surjective either}
$$

5f)
Suppose $f:X\mapsto Y$ is injective, such that if $x_{1}=x_{2}\implies f(x_{1})=f(x_{2})$ else if $x_{1}\neq x_{2} \implies f(x_{1})= f(x_{2})\textreferencemark$ or $x_{1}=x_{2}\implies f(x_{1})\neq f(x_{2})\textreferencemark$ as this opposes that the definition of an injective function where $\forall y\in Y, \exists x \in X$ $\therefore$ if $x_{1}\neq x_{2}\implies f(x_{1})\neq f(x_{2}).$ This proves that these all are equivalent.

6a)
$$
\forall y\in Y, \exists x \in X,f:X\mapsto Y
$$$$
\forall z \in Z,\exists y \in Y,g:Y \mapsto Z
$$
$$
\therefore \forall z \in Z,\exists x \in X,g\circ f:X \mapsto Z
$$
6b)
$$
f(x)=x^{2}+1\,,\,g(x)=2x\implies f\circ g=4x^{2}+1\neq g\circ f=2x^{2}+2
$$

6c)
Yes: $f(x)=|x|,g(x)=x^{2}\implies g \circ f(x)=x$

