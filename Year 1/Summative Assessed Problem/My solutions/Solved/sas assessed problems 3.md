[[1SAS_Sheet 2_2024_SUM.pdf]]
1i)
`\begin{proof}`Given $\epsilon>0$ and 
$$
|\frac{1+n-2024n^{2}+n^{3}}{3+49n^{2}+4n^{3}}-\frac{1}{4}|<\epsilon
$$
$$
|\frac{1+n-2024n^{2}+n^{3}}{3+49n^{2}+4n^{3}}-\frac{1}{4}|=|\frac{4(1+n-2024n^{2}+n^{3})-(3+49n^{2}+4n^{3})}{4(3+49n^{2}+4n^{3})}|
$$
$$
= |\frac{-(8145 n^2 - 4 n - 1)}{12+196n^{2}+16n^{3}}|=|\frac{\frac{1}{n^{3}}+\frac{4}{n^{2}}-\frac{8145}{n}}{\frac{12}{n^{3}}+\frac{196}{n}+16}|<\epsilon$$ 
Using algebra of limits:
$$\because \lim_{ n \to \infty } \frac{1}{n}\to0\implies \lim_{ n \to \infty } |\frac{\frac{1}{n^{3}}+\frac{4}{n^{2}}-\frac{8145}{n}}{\frac{12}{n^{3}}+\frac{196}{n}+16}|=| \frac{0}{16}|=0<\epsilon
$$
$$
\therefore\frac{1+n-2024n^{2}+n^{3}}{3+49n^{2}+4n^{3}}-\frac{1}{4}\to 0\implies \frac{1+n-2024n^{2}+n^{3}}{3+49n^{2}+4n^{3}}\to \frac{1}{4}
$$
`\end{proof}`
1ii)
`\begin{proof}` Given $\epsilon>0$ and
$$
|\frac{7n^{4}-3n^{2}\sin(2n)+n}{5n^{4}+7n-4}- \frac{7}{5}|<\epsilon
$$
$$
|\frac{35n^{4}-15 n^2 sin(2 n) +5n-(35n^{4}+49n-28)}{25 n^4 + 35 n - 20)}|=| \frac{-\frac{15\sin2n}{n^{2}}-\frac{44}{n^{3}}+\frac{28}{n^{4}}}{25+\frac{35}{n^{3}}} |
$$
Using algebra of limits:
$$
\lim_{ n \to \infty } \frac{1}{n}\to 0 \wedge \lim_{ n \to \infty } \frac{\sin n}{n}\to1\implies \lim_{ n \to \infty } | \frac{-\frac{15\sin2n}{n^{2}}-\frac{44}{n^{3}}+\frac{28}{n^{4}}}{25+\frac{35}{n^{3}}-\frac{20}{n^{4}}} |\to |\frac{0}{25}|=0<\epsilon
$$
$$
\therefore \frac{7n^{4}-3n^{2}\sin(2n)+n}{5n^{4}+7n-4}- \frac{7}{5}\to 0\implies\frac{7n^{4}-3n^{2}\sin(2n)+n}{5n^{4}+7n-4} \to \frac{7}{5}
$$
`\end{proof}`
1iii)
`\begin{proof}`
$$
\frac{n-1}{n^{2}+1}+\frac{n-1}{n^{2}+2}+\dots+ \frac{n-1}{n^{2}+n}=\sum a_{n}
$$
$$
max\{ a_{n} \}=\frac{n-1}{n^{2}+1},min\{ a_{n} \}=\frac{n-1}{n^{2}+n}
$$
$$
\therefore n \frac{n-1}{n^{2}+1}\geq \sum a_{n} \geq n \frac{n-1}{n^{2}+n}
$$
$$
\lim_{ n \to \infty } n \frac{n-1}{n^{2}+1}= \lim_{ n \to \infty } \frac{1-\frac{1}{n}}{1+\frac{1}{n^{2}}}\to1
$$
$$
\lim_{ n \to \infty } n \frac{n-1}{n^{2}+n}= \lim_{ n \to \infty } \frac{1-\frac{1}{n}}{1+\frac{1}{n}} \to 1
$$
Applying ![[ra note 2.1#^thm-squeeze]]
$$
\therefore \lim_{ n \to \infty } \sum a_{n} \to 1
$$
`\end{proof}`
2i)
`\begin{proof}`Given that $\frac{1}{\infty}=0$ and using ![[sas note#^thm-sas-alg-lim]]
$$
\frac{1}{\infty}=0\implies \infty=\frac{1}{0}\therefore a_{n}\to \infty \implies \frac{1}{a_{n}}\to \frac{1}{\infty}=0
$$
`\end{proof}`
2ii)`\begin{proof}`Given that $0=\frac{1}{\infty}$ and using ![[sas note#^thm-sas-alg-lim]]
$$
0=\frac{1}{\infty}\implies \frac{1}{0}=\infty\therefore a_{n}\to 0 \implies \frac{1}{a_{n}}\to \frac{1}{0}=\infty
$$
`\end{proof}`
2iii)
`\begin{proof}`$\forall n\exists b_{n}-a_{n}=c_{n}>0\to p>0$. 

Else $\exists p<0$ to set for contradiction. Suppose for $n\geq N$
$$
|c_{n}-p|< p
$$
$$
\implies0 < c_{n}< 2p\textreferencemark \because c_{n}<2p<0\implies 0< c_{n} <0
$$
`\end{proof}`
2iv)
`\begin{proof}` Suppose $(a_{n}+b_{n})\to l,(a_{n}-b_{n})\to m$ and using ![[sas note#^thm-sas-alg-lim]]
$$
\frac{(a_{n}+b_{n})+(a_{n}-b_{n})}{2}=a_{n}\to \frac{l+m}{2}
$$
$$
\frac{(a_{n}+b_{n})-(a_{n}-b_{n})}{2}=b_{n}\to \frac{l-m}{2}
$$
$\therefore$ for $a_{n},b_{n}\exists$ a limit, and therefore by the definition of convergence where a limit exists they converge. ![[sas note#^def-sas-conv]]   `\end{proof}`
2v)
`\begin{proof}` Let $(a_{n}+b_{n})\to l,(a_{n}b_{n})\to m$ to set for contradiction
$$
\frac{a_{n}+b_{n}}{a_{n}b_{n}}=\frac{1}{a_{n}}+\frac{1}{b_{n}}=\frac{l}{m}
$$
$$
a_{n}b_{n}\to m\implies a_{n}\to\frac{m}{b_{n}}\implies \frac{b_{n}}{m}+\frac{1}{b_{n}}\to\frac{l}{m}\implies \left( \frac{1}{m} \right)b^{2}_{n}-\left( \frac{l}{m} \right)b_{n}+1\to0
$$
$$
b_{n}\to\frac{\frac{l}{m}\pm \sqrt[  ]{ \frac{l}{m}^{2}-4\cdot\left( \frac{1}{m} \right) }}{2 \frac{1}{m}}=\frac{l\pm \sqrt[  ]{ l^{2}-4m }}{2}
$$
$$
\implies a_{n}\to \frac{-l \mp \sqrt[  ]{ l^{2}-4m }}{2}
$$
![[sas note#^thm-sas-uniq-lim]]
$\therefore \textreferencemark$ as $a_{n}$ and $b_{n}$ have 2 limits each.
`\end{proof}`

3i)
`\begin{proof}`
base step: 
$$
a_{1}=0\implies a_{2}=\frac{2}{5}
$$
Inductive step:

Assume from the previous $0\leq a_{n}\leq 1$ and observe for each term of:
$$
(a_{n}^{2}+2a_{n}+2)\,,\, a_{n}^{2}\leq 1 \iff a_{n}\leq 1\,,\, 2a_{n}\leq 2\because a_{n}\leq 1\therefore a_{n}^{2}+2a_{n+1}\leq 3
$$
$$
\implies (a_{n}^{2}+2a_{n}+2)\leq 5 \implies \frac{1}{5}(a_{n}^{2}+2a_{n}+2)\leq 1\implies a_{n+1}\leq 1
$$
$$
\therefore \forall n \in\mathbb{R}, a_{n}\leq 1
$$
`\end{proof}`
3ii)
$$
a_{n+2}-a_{n+1}=\frac{1}{5}(a_{n+1}^{2}+2a_{n+1}+2)-\frac{1}{5}(a_{n}^{2}+2a_{n}+2)=\frac{1}{5}(a_{n+1}^{2}+2a_{n+1}-2a_{n}-a_{n}^{2})
$$
$$
\implies\frac{1}{5}(a_{n+1}(a_{n+1}+a_{n}+2)-a_{n}(a_{n+1}+a_{n}+2))\implies \frac{1}{5}(a_{n+1}+a_{n}+2)(a_{n+1}-a_{n})
$$
3iii)
`\begin{proof}` Given the base step from 3i) assume $a_{n+1}\geq a_{n}$. Then evaluate each factor such:
$$
(a_{n+1}+a_{n}+2)> 0 \because \forall n \in\mathbb{R},a_{n}\geq0\wedge (a_{n+1}-a_{n})\geq0\because a_{n+1}\geq a_{n}
$$
$$
\implies a_{n+2}-a_{n}\geq 0 \forall n \in\mathbb{R}
$$
$\therefore$ by the sequence is a monotone sequence that increases ![[sas note 2#^def-sas-mono]] 3iv) and from 3i) it is given as bounded $\therefore$ by the MCT ![[sas note 2#^thm-sas-MCT]] the sequence has a limit s.t.
$$
n\to \infty\implies a_{n}\to a\implies a=\frac{1}{5}(a^{2}+2a+2)\implies a= 2\,or\,1
$$
Whereby the limit adopts the properties of its convergent sequence s.t. $a_{n}\leq 1$, it follows $a_{n}\to 1$
`\end{proof}`
4)
`\begin{proof}`
Base step:
$$
n=1\implies a_{1}=0\implies a_{2}=\frac{2}{5}\implies \frac{2}{5}\leq \frac{2}{5}
$$
Inductive step: Let $n=k+1$
$$
a_{k+2}-a_{k+1}\leq \frac{1}{2}\left( \frac{4}{5} \right)^{k+1} 
$$
$$
a_{k+2}-a_{k+1}=\frac{1}{5}(a_{k+1}+a_{k}+2)(a_{k+1}-a_{k})
$$
$$
\because a_{n}\leq 1 \implies max\{(a_{k+1}+a_{k}+2)\}=4\implies a_{k+2}-a_{k+1}\leq\frac{4}{5}(a_{k+1}-a_{k})
$$
Case 1:
$$
\frac{4}{5}(a_{k+1}-a_{k})\geq \frac{1}{2}\left( \frac{4}{5} \right)^{k+1} \implies a_{k+1}-a_{k}\geq \frac{1}{2}\left( \frac{4}{5} \right)^{k}\textreferencemark\because a_{n+1}-a_{n}\leq \frac{1}{2}\left( \frac{4}{5} \right)^{n} 
$$
Case 2:
$$
 \implies a_{k+1}-a_{k}\leq \frac{1}{2}\left( \frac{4}{5} \right)^{k}
$$

$\therefore$ by mathematical induction we have proved $\forall n \in \mathbb{N}$ this equality stands
`\end{proof}`
5i)
$$
\text{Given }0<a_{n}+1<a_{n}+2\implies a_{n+1}=\frac{a_{n}+1}{a_{n}+2}=1 - \frac{1}{a_{n}+2}<1
$$
5ii)
$$
a_{n+2}= 1-\frac{1}{a_{n+1}+2},a_{n+2}-a_{n+1}= -\frac{1}{a_{n+1}+2}+\frac{1}{a_{n}+2}
$$
$$
=\frac{a_{n+1}-a_{n}}{(a_{n+1}+2)(a_{n}+2)}
$$
5iii)
`\begin{proof}`Given $a_{n}\geq 0\wedge a_{1}=0\implies a_{2}=\frac{1}{2} \therefore$ assume:
$$a_{n+1}\geq a_{n}\forall n \in \mathbb{N}$$
Let $p(n)$ be defined by:
$$p(n)=a_{n+2}-a_{n+1}=\frac{a_{n+1}-a_{n}}{(a_{n+1}+2)(a_{n}+2)}\geq 0$$
It follows that $(a_{n+1}+2)\wedge(a_{n+}+2)>0$ and that $(a_{n+1}-a_{n})>0\therefore p(n)> 0\therefore a_{n}$ is monotone sequence that increases. ![[sas note 2#^def-sas-mono]]
5iv) It is then bounded above given by part i and using the MCT as it is a increasing sequence and bounded above, a limit exists:
![[sas note 2#^thm-sas-MCT]] 
$$
\therefore a_{n}\to a\implies a =1- \frac{1}{a+2}\implies a= \frac{-1\pm \sqrt[  ]{ 5 }}{2}, \because a_{n}>0\implies a>0\therefore a\to \frac{-1+\sqrt[  ]{ 5 }}{2}
$$
`\end{proof}`
5v)
$$
a_{n+2}-a_{n+1}=\frac{a_{n+1}-a_{n}}{(a_{n+1}+2)(a_{n}+2)}\leq \frac{1}{4}(a_{n+1}-a_{n})
$$
$$

a_{n+2}-a_{n+1}=\frac{a_{n+1}-a_{n}}{(a_{n+1}+2)(a_{n}+2)}-\frac{1}{4}(a_{n+1}-a_{n})\leq 0
$$
$$
 \frac{1}{(a_{n+1}+2)(a_{n}+2)}-\frac{1}{4} = \frac{4-(a_{n+1}+2)(a_{n}+2)}{4(a_{n+1}+2)(a_{n}+2)}\leq 0
$$
$$
4-(a_{n+1}+2)(a_{n}+2)\leq 0\implies4\leq(a_{n+1}+2)(a_{n}+2)=4+2(a_{n+1}+a_{n})+a_{n}a_{n+1}
$$
$$
\implies 2(a_{n+1}+a_{n})+a_{n}a_{n+1}\geq 0
$$
It is also given by  
$$\forall n \in\mathbb{R},a_{n}>0\implies 2(a_{n+1}+a_{n})\wedge a_{n}a_{n+1}>0\implies 2(a_{n+1}+a_{n})+a_{n}a_{n+1}\geq 0$$
$$
\therefore a_{n+2}-a_{n+1} \leq \frac{1}{4}(a_{n+1}-a_{n})
$$
6)
$a_{1}=0,a_{2}=\frac{1}{2},a_{3}=\frac{3}{5},a_{4}=\frac{8}{13},a_{5}=\frac{21}{34}$
`\begin{proof}` Base step:
$$
n= 1 \implies a_{1}=0\implies a_{2}=\frac{1}{2}\implies \frac{1}{2}\leq \frac{c}{4}\implies2\leq c
$$

Inductive step: Let $n=k+1$
$$
0\leq a_{n+1}-a_{n}\leq \frac{c}{4^{n}}
$$
$$
a_{k+1}-a_{k}\leq \frac{1}{4}(a_{k}-a_{k-1})
$$
Case 1: 
$$
\frac{1}{4}(a_{k}-a_{k-1})\geq \frac{c}{4^{k+1}}\implies a_{k}-a_{k-1}\geq \frac{c}{4^{k}}\textreferencemark  \because 0\leq a_{n+1}-a_{n}\leq \frac{c}{4^{n}}
$$
Case 2:
$$
\frac{1}{4}(a_{k}-a_{k-1})\leq \frac{c}{4^{k+1}}\implies a_{k}-a_{k-1}\leq \frac{c}{4^{k}}
$$
$\therefore$ by mathematical induction we have proved $\forall n \in \mathbb{N}$ this equality stands
`\end{proof}`
As $a_{n}$ converges by MCT as an increasing sequence its differences will only decrease, as such the largest difference give will be given by the first difference, thus giving the upper bound to solve the equality, such that $c=2$.

# EXTRA

1)
`\begin{proof}` Given that $a_{n}\to l$, use the AoL such that $a_{n}b_{n}\to l\times 0=0$ `\end{proof}`

2)
`\begin{proof}` Given $a_{n}\to l\implies a_{n+1}\to l\therefore\text{ by AoL: } a_{n+1}-a_{n}\to l-l=0$ `\end{proof}`

3)
An increasing sequence of real numbers which is not bounded above diverges (does not converge).
`\begin{proof}` Suppose for contradiction there exists a convergence (limit),$a_{n}\to l\wedge\epsilon>0  \,s.t.\, |a_{n}-l|<\epsilon$$\implies l-\epsilon<a_{n}<l+\epsilon \textreferencemark$ as is bounded above `\end{proof}`

4,5 and 6)written in a book
