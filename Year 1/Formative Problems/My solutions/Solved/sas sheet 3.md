[[1SAS_Sheet 3_2024.pdf]]

1-2aii complete with wang

2bi)
$$
a_{2n+1}=\frac{1}{2}\left( 1+\frac{1}{a_{2n}} \right)\implies b_{n+1}=a_{2n+2}=\frac{1}{2}\left( 1+\frac{1}{a_{2n+1}} \right)=\frac{1}{2}\left( 1+\frac{1}{\frac{1}{2}\left( 1+\frac{1}{a_{2n}} \right)} \right)
$$$$
=\frac{1}{2}\left( 1+\frac{2}{ \frac{a_{2n}+1}{a_{2n}} } \right)=\frac{1}{2}\left( 1+\frac{2a_{2n}}{{a_{2n}+1}{} } \right) \overset{ a_{2n}=b_{n} }{ \implies } b_{n+1}= \frac{1}{2}\left( 1+\frac{2b_{n}}{{b_{n}+1}{} } \right) 
$$
2bii)
$$
b_{n+1}= \frac{1}{2}\left( 1+\frac{2b_{n}}{{b_{n}+1}{} } \right) ,b_{n+2}= \frac{1}{2}\left( 1+\frac{2b_{n+1}}{{b_{n+1}+1}{} } \right) 
$$
$$
b_{n+2}-b_{n+1}=\frac{1}{2}\left( \left( 1+\frac{2b_{n+1}}{{b_{n+1}+1}{} } \right)  -\left( 1+\frac{2b_{n}}{{b_{n}+1}{} } \right) \right)=\frac{b_{n+1}}{{b_{n+1}+1}{} }   -\frac{b_{n}}{{b_{n}+1}{} } = \frac{1}{b_{n}+1}- \frac{1}{b_{n+1}+1}
$$
$$
\therefore b_{n+2}-b_{n+1} = \frac{b_{n+1}-b_{n}}{(b_{n+1}+1)(b_{n}+1)}
$$
Base step:
$a_{1}=\frac{1}{2}\implies a_{2}=b_{1}=\frac{3}{2}\implies b_{2}=\frac{11}{10}$ 
Inductive step: 
Assume that $0< b_{n+1}<b_{n}$

$$
\therefore (b_{n+1}-b_{n})\leq0,(b_{n+1}+1)>0,(b_{n}+1)>0\implies  b_{n+2}-b_{n+1} = \frac{b_{n+1}-b_{n}}{(b_{n+1}+1)(b_{n}+1)}\leq 0 \forall n \in \mathbb{N}
$$

2biii)
Given that the original sequence is bounded (above and below), its subsequence (and limits) are also bounded (above and below), and as this subsequence follows $0< b_{n+1}<b_{n}\forall n \in \mathbb{N},$ it is a monotone sequence that is decreasing, s.t. the MCT now applies and a limit exists, $\therefore$ we can take and solve for:

$$
b= \frac{1}{2}\left( 1+\frac{2b}{{b+1}{} } \right)\implies (2b-1)(b+1)-2b=0=2b^{2}-b-1\implies b= 1\,or\,-\frac{1}{2}\overset{ b_{n}>0 }{ \implies }b=1
$$

2biv)
$$
c_{n}=\frac{1}{2}\left( 1+ \frac{1}{b_{n}} \right)\implies c_{n+1}=\frac{1}{2}\left( 1+ \frac{1}{b_{n+1}} \right)
$$
base step:
$b_{1}=\frac{3}{2}\implies c_{1}=\frac{5}{6},b_{2}=\frac{11}{10}\implies c_{2}=\frac{21}{22}$
Inductive step: 
Assume that $c_{n+1}>c_{n}>0$
$$
\therefore c_{n+1}-c_{n}= \frac{1}{2}\left( \frac{1}{b_{n+1}}-\frac{1}{b_{n}} \right)=\frac{1}{2}\left( \frac{b_{n}-b_{n+1}}{b_{n+1}b_{n}} \right)
$$

From before $\implies (b_{n+1}b_{n})>0\because b_{n}>0 \forall n \in \mathbb{N}\wedge(b_{n}-b_{n+1})\geq 0 \therefore\forall n \in \mathbb{N}$
$$
c_{n+1}-c_{n}=\frac{1}{2}\left( \frac{b_{n}-b_{n+1}}{b_{n+1}b_{n}} \right)\geq0\implies c_{n+1}\geq c_{n}
$$
$\therefore c_{n}$ is a monotone sequence (increasing) that is bounded (inherited as a subsequence of a sequence) s.t. $\exists c_{n}\to c$.
$$
c_{n}=\frac{1}{2}\left( 1+ \frac{1}{b_{n}} \right)\to c= \frac{1}{2}\left( 1+\frac{1}{1} \right)=1
$$
3i)
`\begin{proof}`
$$
a_{n}\geq n \min \overset{ k=n }{ \left\{  \sum^{n}_{k=1} \frac{1}{n+k}  \right\} }= n\left( \frac{1}{2n} \right)=\frac{1}{2}\qquad a_{n}\leq \overset{ n=1 }{ n\max \left\{  \sum^{n}_{k=1} \frac{1}{n+k}  \right\} }= 1
$$
$$
\therefore \frac{1}{2}\leq a_{n} \leq 1
$$
`\end{proof}`
3ii)
$\frac{1}{n+k}>0\therefore a_{n}\leq a_{n+1}\forall n \in \mathbb{R}\therefore a_{n}$ is a monotone sequence (strictly increasing).
3iii)
$\therefore$ by MCT $a_{n}$ converges as it is a monotone series and bounded above, s.t. $a_{n} \to l$

4i)
`\begin{proof}`Let $n_{q}=2k$ being the even cases s.t. $a_{n_{q}}=\cos \left( \frac{(2q)^{2}\pi}{2} \right)=\cos(2q^{2}\pi)$ where $\forall k\in \mathbb{N},\cos(2\pi k)=1\implies a_{n_{k}}\to1$

Now consider the odd case s.t. $n_{p}=2p+1\implies a_{n_{p}}=\cos \left( \frac{(2p+1)^{2}\pi}{2} \right)$
$=\cos\left( \frac{2(p^{2}+p)\pi+\pi}{2} \right)=\cos\left( p^{2}+p+\frac{\pi}{2} \right)=-\sin((p^{2}+p)\pi)$. 

Suppose $p$ is even s.t. $p=2m\implies\sin(2(2m^{2}+m)\pi)$ where $\forall k \in \mathbb{N},\sin(2\pi k)=0$. 

Now suppose $p$ is odd s.t. $p=2m+1\implies\sin(2(2m^{2}+3m+1)\pi)$ where $\forall k \in \mathbb{N},\sin(2\pi k)=0$.

$\therefore \forall p \in \mathbb{N},-\sin((p^{2}+p)\pi)=0\therefore a_{n_{p}}\to 0$

The 2 subsequence ($a_{n_{p}}$ and $a_{n_{q}}$) have two different limits and $\therefore$ $a_{n}$ does not`\end{proof}`

4ii)
$$\forall p \in \mathbb{N},p_{n+1}>p_{n}>0\therefore p_{n+1}-p_{n}>0 \land \min\{ p_{n+1}-p_{n} \}=1$$ $$
\max\left\{  \frac{1}{p_{n+1}-p_{n}}  \right\} =\frac{1}{\min\{ p_{n+1}-p_{n} \}}=1\geq a_{n}>0
$$
Now given the ![[sas note 3#^thm-sas-BW]] $\exists a_{n_{k}}\to l\,s.t.\, 1\geq l\geq 0$

4iii)
`\begin{proof}`![[sas note 3#^def-sas-subseq]] 
![[sas note#^def-sas-tend-inf]]
Suppose, for contradiction, that $a_{n_{k}}\to l \land \exists \epsilon>0 \,s.t.\,|a_{n_{k}-1}-l|<\epsilon \iff l-\epsilon<a_{n_{k}}<l+\epsilon$

Now consider that for any $A>0$ there exists a $N \in \mathbb{N},$ s.t. $\forall n>N,a_{n}>A$.

Now given the definition of a subsequence, where $n_{k}$ is strictly increasing it then leads that $\exists n_{k}>N\therefore\textreferencemark \because \exists a_{n_{k}}>A>0$, where $A=\epsilon$ satisfying the conditions for tending to infinity.`\end{proof}`

# Extra

1i)

![[1SAS Notes.pdf#page=22|1SAS Notes, p.22]]

$$
b_{n}=\left( 1 - \frac{1}{n} \right)^{n}=\sum^{n}_{k=0}\begin{pmatrix}
n \\
k \\
\end{pmatrix}\left( -\frac{1}{n} \right)^{k}
$$
If k is even then it follows the same as:
$$
\lim_{ n \to \infty } \left( \sum^{n}_{k=0}\begin{pmatrix}
n \\
k \\
\end{pmatrix}\left( \frac{1}{n} \right)^{k} \right)\to e
$$
Else k is odd and it follows that 
$$
\lim_{ n \to \infty } \left( -\sum^{n}_{k=0}\begin{pmatrix}
n \\
k \\
\end{pmatrix}\left( \frac{1}{n} \right)^{k}\right)\to-e
$$
$\therefore$ there exists 2 limits within the same sequence, which means it does not converge.

Whereas, if you take a change of variable such that $n=-k$ s.t.
$$
\left( 1+\frac{1}{k} \right)^{-k}=\left( \left( 1+\frac{1}{k} \right)^{k} \right)^{-1}\to e^{-1}
$$
Only if $k\to \infty$ but it does not as only $n\to \infty\implies k\to-\infty$
1ii)

$$
a_{n-1}b_{n}=\left( 1+\frac{1}{n-1} \right)^{n-1}\left( 1-\frac{1}{n} \right)^{n}=\frac{\left( 1+\frac{1}{n-1} \right)^{n}\left( 1-\frac{1}{n} \right)^{n}}{1+\frac{1}{n+1}}=\frac{\left( 1+\frac{1}{n-1}-\frac{1}{n}-\frac{1}{n^{2}-n} \right)^{n}}{1+ \frac{1}{n-1}}$$
$$
=\frac{1^{n}}{1+\frac{1}{n-1}}=\frac{1}{\frac{n}{n-1}}=\frac{n-1}{n}=1-\frac{1}{n}
$$

1iii)
Consider change of variable $n=2m$
$$
c_{n}=\left( 1+\frac{(-1)^{n}}{n} \right)^{n}=\left( 1+\frac{(-1)^{2m}}{2m} \right)^{2m}=\left( 1+\frac{1}{2m} \right)^{2m}
$$
$$
\lim_{ n \to \infty } 2m\to \infty \implies \lim_{ m \to \infty } \left( 1+ \frac{1}{2m} \right)^{2m}\to e
$$
Now consider change of variable $n=2m+1$
$$
c_{n}=\left( 1+\frac{(-1)^{n}}{n} \right)^{n}=\left( 1+\frac{(-1)^{2m+1}}{2m+1} \right)^{2m+1}=\left( 1-\frac{1}{2m+1} \right)^{2m+1}=\left( 1-\frac{1}{n} \right)^{n}
$$
Now using part 1i), we know this does not converge as there are 2 subsequence with different limits $(e,e^{-1})$.

2i)

![[sas note#^def-sas-bound-seq]] 

![[sas note 2#^def-sas-mono]] 

Suppose a sequence $a_{n}>0(\in \mathbb{R},\forall n \in \mathbb{N})$ is unbounded then it follows that, for some arbitrary $M>0$:
$$
\forall n>N\exists a_{n}>M
$$
It is enough to prove there exists a monotone subsequence.

Let the first term of the subsequence be $a_{n_{k}}$, and as $M$ is arbitrary, let $M=k\therefore\forall n>N_{1}\exists a_{n_{k}}>k$, and the for next term of the subsequence $a_{n_{k+1}}$ where $M=\max\{ a_{n_{k}},k+1 \}\exists \forall n>N_{2}\exists$ $a_{n_{k+1}}>\max\{ a_{n_{k}},k+1 \}$. 


2ii)
For the above, as $k\to \infty$, the lower bound will also tend to infinity forcing $a_{n_{k}}$ to as well - comparison test

3)
$(-1)^{n}$ and $(-1)^{n+1}$
$k+1=n\implies(-1)^{n}=(-1)^{k+1}$
$k-1=n\implies(-1)^{n+1}=(-1)^{k}$
