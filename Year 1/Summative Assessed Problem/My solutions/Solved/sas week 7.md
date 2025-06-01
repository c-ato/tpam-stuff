[[1SAS_Sheet 4_SUM_2024.pdf]]

\section{}
\subsubsection{$$\sum^{\infty}_{n=1} \frac{1}{(n+1)(n+3)}$$}
$$
\sum^{\infty}_{n=1} \frac{1}{(n+1)(n+3)}=\sum^{\infty}_{n=1} \frac{1}{2(n+1)}- \frac{1}{2(n+3)} 
$$
$$
\frac{1}{2} \sum^{N}_{n=1}\frac{1}{n+1} -\frac{1}{n+3} =s_{N}=
$$
$$
\frac{1}{2}\begin{pmatrix}
\frac{1}{2} - \frac{1}{4}  \\
\frac{1}{3} - \frac{1}{5} \\
\frac{1}{4} - \frac{1}{6} \\
\frac{1}{5} - \frac{1}{7} \\
\vdots \\   
 \frac{1}{N-2+1} -  \frac{1}{N-2+3}  \\    
\frac{1}{N-1+1} -  \frac{1}{N-1+3}  \\ 
\frac{1}{N+1} -  \frac{1}{N+3}  
\end{pmatrix}= \frac{1}{2}\left( \frac{1}{2}+\frac{1}{3}-\frac{1}{N+2}-\frac{1}{N+3} \right)=s_{N}
$$
$\therefore$ the series does converge as:
$$
\lim_{ N \to \infty } s_{N}=s=\frac{1}{2}\left( \frac{1}{2}+\frac{1}{3} \right)= \frac{5}{12}
$$
\subsubsection{$$\sum^{\infty}_{n=1} \frac{1}{n(n+1)(n+2)}$$}
$$
\sum^{\infty}_{n=1} \frac{1}{n(n+1)(n+2)}=\sum^{\infty}_{n=1} \frac{1}{2n}+ \frac{1}{2(n+2)} - \frac{1}{n+1}
$$
$$
\sum^{N}_{n=1}\frac{1}{2n}+ \frac{1}{2(n+2)} - \frac{1}{n+1}=s_{N}= 
$$
$$
\begin{matrix} \\
\frac{1}{2} + \frac{1}{6} - \frac{1}{2} \\
\frac{1}{4} + \frac{1}{8} - \frac{1}{3} \\
\frac{1}{6} + \frac{1}{10} - \frac{1}{4} \\
\frac{1}{8} + \frac{1}{12} - \frac{1}{5} \\
\vdots \\   
\frac{1}{2N-4}+\frac{1}{2N}-\frac{1}{N-1}+\\
\frac{1}{2N-2}+\frac{1}{2N+2}-\frac{1}{N}+\\
\frac{1}{2N}+\frac{1}{2N+4}-\frac{1}{N+1}
\end{matrix}
$$
$$
=\frac{1}{4}+ \frac{1}{2N+4}-\frac{1}{N+1}+ \frac{1}{2N+2}
$$
$$
\lim_{ N \to \infty } \frac{1}{4}+ \frac{1}{2N+4}-\frac{1}{N+1}\to \frac{1}{4}
$$

\section{}
\subsection{Prove that if $|x|<1$ then $$\sum^{\infty}_{n=1}x^{n}=\frac{1}{1-x}$$}
$$
\sum^{N+1}_{n=1}x^{n}=S_{N+1}=xS_{N}+1
$$
$$
\sum^{N}_{n=1}x^{n}=S_{N}
$$
$$
S_{N+1}-S_{N}=xS_{N}+1-S_{N}=x^{N+1}\implies S_{N}(x-1)=x^{N+1}-1
$$
$$
S_{N}= \frac{1-x^{N+1}}{1-x}\implies \lim_{ N \to \infty } \frac{1-x^{N+1}}{1-x}\to \frac{1}{1-x} \because \lim_{ N \to \infty } x^{N}\to 0 \iff |x|<1
$$
\subsection{Prove that the series $$\sum^{\infty}_{n=1}(-1)^{n} \frac{3^{n}}{2^{2n}}$$ converges, and find its sum}
$$
\sum^{\infty}_{n=1}(-1)^{n} \frac{3^{n}}{2^{2n}}= \sum^{\infty}_{n=1} \left( -\frac{3}{4} \right)^{n}= \frac{1}{1--\frac{3}{4}}=\frac{4}{7}
$$
\section
\subsubsection{By appealing to the appropriate definition, prove that the series $$\sum^{\infty}_{n=1} \frac{2n+1}{n^{2}(n+1)}$$ converges, and find its sum}
$$
\sum^{\infty}_{n=1} \frac{2n+1}{n^{2}(n+1)}=\sum^{\infty}_{n=1} \frac{1}{n^{2}} -\frac{1}{n+1} + \frac{1}{n}
$$
$$
\sum^{N}_{n=1} \frac{1}{n^{2}} + \frac{1}{n} - \frac{1}{n+1}=S_{N}=
$$
$$
\begin{pmatrix}
\frac{1}{1} + \frac{1}{1} -\frac{1}{2} \\
\frac{1}{4} + \frac{1}{2} -\frac{1}{3} \\
\frac{1}{9} + \frac{1}{3} -\frac{1}{4} \\
\frac{1}{16} + \frac{1}{4} -\frac{1}{5} \\
\vdots \\
\frac{1}{N^{2}}+\frac{1}{N}-\frac{1}{N+1}\\
\end{pmatrix} = \sum^{N}_{n=1} \frac{1}{n^{2}}+1 -\frac{1}{N+1}=S_{N}
$$
Given that $\sum^{\infty}_{n=1} \frac{1}{n^{2}}= \frac{\pi^{2}}{6}$
$$
\lim_{ N \to \infty } S_{N}\to \frac{\pi^{2}}{6}+1
$$
\subsubsection{Use the Comparison Test to give an alternative proof that the series in Part (i) converges (you don’t need to conclude anything about its sum)}
$$
0<\sum^{\infty}_{n=1}\frac{2n+1}{n^{2}(n+1)}\leq \sum^{\infty}_{n=1} \frac{2n+2}{n^{2}(n+1)}=\sum^{\infty}_{n=1}\frac{2}{n^{2}} \forall n \in \mathbb{N}
$$
$$
\sum^{\infty}_{n=1} \frac{2}{n^{2}}= 2 \sum^{\infty}_{n=1}\frac{1}{n^{2}} = \frac{\pi^{2}}{3}
$$
$\therefore$ by comparison test, $\sum^{\infty}_{n=1} \frac{2n+1}{n^{2}(n+1)}$ converges

\subsubsection{Again by appealing again to the appropriate definition, prove that $$\sum^{\infty}_{n=1} \frac{1}{n^{2}(n+1)}= \frac{\pi^{2}}{6}-1$$}
$$
\sum^{\infty}_{n=1} \frac{1}{n^{2}(n+1)}=\sum^{\infty}_{n=1} \frac{1}{n^{2}}+\frac{1}{n+1}-\frac{1}{n}
$$
$$
\sum^{N}_{n=1} \frac{1}{n^{2}}+\frac{1}{n+1}-\frac{1}{n}=S_{N}=
$$
$$
\begin{pmatrix}
\frac{1}{1} + \frac{1}{2} -\frac{1}{1} \\
\frac{1}{4} + \frac{1}{3} -\frac{1}{2} \\
\frac{1}{9} + \frac{1}{4} -\frac{1}{3} \\
\frac{1}{16} + \frac{1}{5} -\frac{1}{4}  \\
\vdots \\
\frac{1}{N^{2}}+\frac{1}{N+1}-\frac{1}{N}\\
\end{pmatrix} = \frac{1}{4}+\frac{1}{9}+\frac{1}{16}\dots \frac{1}{N^{2}}= \sum^{N}_{n=1} \frac{1}{n^{2}}-1
$$
\section{Study carefully the proof (from the notes/lectures) that $$\sum^{\infty}_{n=1} \frac{1}{n^{2}}$$ converges. For which values of $\alpha \in \mathbb{R}$ does this convergence proof adapt to the series$$\sum^{\infty}_{n=1} \frac{1}{n^{\alpha}}\,?$$Write down a complete proof for such values of $\alpha$}
$$
\alpha \in \mathbb{N}
$$
`\begin{proof}`
$$
S_{N}= \sum^{N}_{n=1} \frac{1}{n^{\alpha}}
$$
This is strictly increasing so it is enough to show it convergence by the MCT if it is bounded.
$$
S_{N}= \sum^{N}_{n=1} \frac{1}{n^{\alpha}}<\sum^{2^{N}}_{n=1} \frac{1}{n^{2}}=S_{2^{N}}
$$
Hence it is enough to to show that $(S_{2^{N}})$ is bounded. Observe that:
$$
\sum^{2^{j}}_{n=2^{j-1}+1} \frac{1}{n^{\alpha}}\leq(2^{j}-2^{j-1})\times \frac{1}{(2^{j-1}+1)^{\alpha}}
$$
Since for each j the above sum consists of $2^{j}-2^{j-1}$ terms of which the largest is $\frac{1}{(2^{j-1}+1)^{\alpha}}$. Since $2^{j-1}+1>2^{j-1}$.
$$
\sum^{2^{j}}_{n=2^{j-1}+1} \frac{1}{n^{\alpha}}\leq(2^{j}-2^{j-1})\times \frac{1}{(2^{j-1})^{\alpha}}= \frac{2^{j-1}}{(2^{j-1})^{\alpha}}= \left( \frac{1}{2} \right)^{(\alpha-1)(j-1)}=\left( \frac{1}{2}^{(\alpha-1)} \right)^{(j-1)}
$$
So now we can write:
$$
S_{2^{N}}=1+ \sum^{N}_{j=1}\left( \sum^{2^{j}}_{n=2^{j-1}+1} \frac{1}{n^{\alpha}} \right)\leq 1 + \sum^{N}_{j=1}\left( \frac{1}{2} ^{(\alpha-1)}\right)^{(j-1)}
$$
The latter will only converge if the constant $(\alpha-1)>0\implies\alpha>1$, else the power becomes negative (or 0 in which it becomes an infinite addition of constants which naturally tends to infinity) where by the partial sum can be written in the form $\sum^{N}_{n=1}(2^{k})^{n}$, where $k>0 \in \mathbb{R}$ which's geometric sum is know to tend to infinity.

Continuing, finding what the latter partial geometric sum converges to, provides the upper bound to be:
$$
S_{2^{N}}\leq 1+ \sum^{\infty}_{j=1}\left( \frac{1}{2}^{(\alpha-1)} \right)^{j-1}=1+ \frac{1}{1-\frac{1}{2}^{(\alpha-1)}}\to l\iff\alpha<1
$$
`\end{proof}`
\section{Which of the following series converge? Justify your answers. You may use standard series convergence tests provided you make it clear that you are doing so.}
\subsubsection{$$\sum^{\infty}_{n=1} \frac{n^{4}}{4^{n}}$$}
Using the ratio test:
$$
\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}}\to r
$$
$$
\lim_{ n \to \infty } \frac{\frac{(n+1)^{4}}{4^{n+1}}}{\frac{n^{4}}{4^{n}}}= \lim_{ n \to \infty } \frac{(n+1)^{4}}{4n^{4}}=\lim_{ n \to \infty } \frac{1}{4}\left( \frac{n+1}{n}\right)^{4}\to \frac{1}{4}
$$

\subsubsection{$$\sum^{\infty}_{n=1} \frac{1000^{n}}{n!}$$}
$$
\lim_{ n \to \infty } \frac{\frac{1000^{n+1}}{(n+1)!}}{\frac{1000^{n}}{n!}}=\lim_{ n \to \infty } \frac{1000}{n+1}\to 0
$$
$\therefore$ by ratio test, this converges

\subsubsection{$$\sum^{\infty}_{n=1} \frac{3^{n}+4^{n}}{3^{n}+5^{n}}$$}
> [!lemma|*]- $\sqrt[ n ]{ x^{n}+y^{n} }< \sqrt[ n ]{ x^{n} }+\sqrt[ n ]{ y }$
> Given $x,y>0 \in \mathbb{R}$ and $n\in \mathbb{N}$
> $$\sqrt[ n ]{ x^{n}+y^{n} }^{n}< (\sqrt[ n ]{ x^{n} }+\sqrt[ n ]{ y })^{n}$$
 > $$x^{n}+y^{n}< \sum^{n}_{k=1} \begin{pmatrix} n \\ k\end{pmatrix} \sqrt[ n ]{ x^{n} }^{n-k}\sqrt[ n ]{ y^{n} }^{k}=x^{n}+y^{n}+ \sum^{n-1}_{k=2} \begin{pmatrix} n \\ k\end{pmatrix} \sqrt[ n ]{ x^{n} }^{n-k}\sqrt[ n ]{ y^{n} }^{k}$$
 > $$ \sum^{n-1}_{k=2} \begin{pmatrix} n \\ k\end{pmatrix} \sqrt[ n ]{ x^{n} }^{n-k}\sqrt[ n ]{ y^{n} }^{k}>0$$
 ^lem-
 
$$
\sum^{\infty}_{n=1} \frac{3^{n}+4^{n}}{3^{n}+5^{n}}<\sum^{\infty}_{n=1} \frac{2\times4^{n}}{5^{n}}
$$
$$
r=\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}} =\lim_{ n \to \infty } \frac{ \frac{2\times4^{n+1}}{5^{n+1}}}{ \frac{2\times4^{n}}{5^{n}}}=\frac{4}{5} <1
$$
$\therefore$ by the comparison and ratio test, this converges.

\subsubsection{$$\sum^{\infty}_{n=1} \frac{2^{n}(n!)^{2}}{(2n)!}$$}
$$
\lim_{ n \to \infty } \frac{\frac{2^{n+1}((n+1)!)^{2}}{(2(n+1))!}}{\frac{2^{n}(n!)^{2}}{(2n)!}}= \lim_{ n \to \infty }\frac{2(n+1)^{2}}{(2n+1)(2n+2)}= \lim_{ n \to \infty }\frac{n+1}{2n+1}\to \frac{1}{2} <1
$$
$\therefore$ by the ratio test, this converges

\section{Which of the following series converge? Justify your answers. You may use standard series convergence tests provided you make it clear that you are doing so.}

\subsubsection{$$\sum^{\infty}_{n=1}(-1)^{n}$$}
Consider the partial sum:
$$
S_{2N}=\sum^{2N}_{n=1}=(-1)^{n}=1-1+1\dots+(-1)^{2N-1}+(-1)^{2N}=0\therefore \lim_{ N \to \infty } S_{2N}\to0
$$
$$
S_{2N+1}=\sum^{2N+1}_{n=1}=(-1)^{n}=1-1+1\dots+(-1)^{2N}+(-1)^{2N+1}=-1\therefore \lim_{ N \to \infty } S_{2N}\to0
$$
$\therefore$ as there exists 2 limits from the 2 partial sums, this series does not converge.

\subsubsection{$$\sum^{\infty}_{n=1} \frac{n\sqrt[  ]{ n }+9n}{6n^{2}}$$}
$$
0<\sum^{\infty}_{n=1} \frac{n\sqrt[  ]{ n }+9n}{n^{2}+4n+1}> \sum^{\infty}_{n=1} \frac{n\sqrt[  ]{ n }}{n^{2}}=\sum^{\infty}_{n=1} \frac{1}{\sqrt[  ]{ n }}= \infty
$$
By comparison test, this shows the series diverges.

\subsubsection{$$\sum^{\infty}_{n=1}(\sqrt[  ]{ n+1 }-\sqrt[  ]{ n-1 })^{3}$$}
$$
\sum^{\infty}_{n=1}(\sqrt[  ]{ n+1 }-\sqrt[  ]{ n-1 })^{3}=\sum^{\infty}_{n=1}\left( \frac{(\sqrt[  ]{ n+1 }-\sqrt[  ]{ n-1 })(\sqrt[  ]{ n+1 }+\sqrt[  ]{ n-1 })}{(\sqrt[  ]{ n+1 }+\sqrt[  ]{ n-1 })} \right)^{3}$$
$$
=\sum^{\infty}_{n=1}\left( \frac{1}{(\sqrt[  ]{ n+1 }+\sqrt[  ]{ n-1 })} \right)^{3}< \sum^{\infty}_{n=1}\frac{1}{\sqrt[  ]{ n }^{3}}= \sum^{\infty}_{n=1} \frac{1}{n^{1.5}}
$$
It is give for the family of series 
$$
\sum^{\infty}_{n=1} \frac{1}{n^{\alpha}}\to l
$$
Given that $\alpha>1$, this gives that the original series is bounded above as by comparison test, satisfying the MCT and $\therefore$ also converges.

\section{Summative: Which of the following series converge? Justify any assertions that you make. You may appeal directly to the definition or use standard series convergence tests, provided you make it clear that you are doing so.}
\subsubsection{$$\sum^{\infty}_{n=1}\left( (n+1)^{\frac{1}{4}}-n^{\frac{1}{4}} \right)$$}
$$
\sum^{N}_{n=1}\left( (n+1)^{\frac{1}{4}}-n^{\frac{1}{4}} \right)=-1+(N+1)^{\frac{1}{4}}=S_{N}
$$
$$
\lim_{ N \to \infty } S_{N}\to S=\infty
$$
$\therefore S$ tends to infinity and does not converge.

\subsubsection{$$\sum^{\infty}_{n=1} \frac{1+n+n^{2}}{1+n^{2}+3n^{4}}$$}
$$
0<\sum^{\infty}_{n=1} \frac{1+n+n^{2}}{1+n^{2}+3n^{4}}\leq \sum^{\infty}_{n=1} \frac{4n^{2}}{n^{4}}= \sum^{\infty}_{n=1} \frac{4}{n^{2}}=\frac{1}{4}\sum^{\infty}_{n=1} \frac{1}{n^{2}}=\frac{\pi^{2}}{24}
$$
This series is strictly increasing as it is the sum of positives, and is bounded above so by the MCT, this convergence.

\subsubsection{$$\sum^{\infty}_{n=1} \frac{n^{n}}{4^{n}n!}$$}
Using the ratio test:
$$
\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}}\to r
$$
$$
\lim_{ n \to \infty } \frac{\frac{(n+1)^{n+1}}{4^{n+1}(n+1)!}}{\frac{n^{n}}{4^{n}n!}}= \lim_{ n \to \infty } \frac{(n+1)^{n+1}}{4n^{n}(n+1)}=\lim_{ n \to \infty } \frac{(n+1)^{n}}{4n^{n}}=\frac{1}{4} \lim_{ n \to \infty } \left( 1+\frac{1}{n} \right)^{n}\to\frac{e}{4}<
$$
\section{Extra*}

\setcounter{section}{1}
\section{Prove that $$\sum^{N}_{n=1} \frac{n}{2^{n}}=2-2^{-N}(N+2)$$for all $N \in \mathbb{N}$\nDeduce that$$\sum^{\infty}_{n=1} \frac{n}{2^{n}}=2$$In this question you may use without proof that $n2^{-1}\to 0$; indeed we proved this in Problem Sheet 1.]}
`\begin{proof}` Base step: let $N=1$
$$
\sum^{N}_{n=1} \frac{n}{2^{n}}=2-2^{-N}(N+2) =
\sum^{1}_{n=1} \frac{n}{2^{n}}=\frac{1}{2}= 2-2^{-1}(1+2)=2-\frac{3}{2}=\frac{1}{2}
$$
Inductive step: 

Suppose that: $$\sum^{N}_{n=1} \frac{n}{2^{n}}=2-2^{-N}(N+2)$$
is true, now consider for:
$$
\sum^{N+1}_{n=1} \frac{n}{2^{n}}=\frac{N+1}{2^{N+1}}+\sum^{N}_{n=1}\frac{n}{2^{n}}= \frac{N+1}{2^{N+1}} +2-2^{-N}(N+2)
$$
$$
= 2^{-(N+1)}(N+1) +2-2^{-N}(N+2)= 2+2^{-N-1}(N+1) -2^{-N-1}(2(N+2))
$$
$$
=2+2^{-N-1}((N+1) -(2(N+2)))=2-2^{-N-1}( N+3)
$$
$$
\sum^{N=N+1}_{n=1} \frac{n}{2^{n}}=2-2^{-N}(N+2)=2-2^{-(N+1)}((N+1)+2)=2-2^{-N-1}( N+3)
$$
$\therefore$ by mathematical induction we have shown equivalence in inducting the next term, and substituting directly to the partial sum formula $\forall N \in \mathbb{N}$ the validity of this partial sum.
$$
\therefore \lim_{ N \to \infty } \sum^{N}_{n=1} \frac{n}{2^{n}}=\lim_{ N \to \infty } 2-2^{-N}(N+2)=2-\lim_{ N \to \infty } 2^{-N}N+\lim_{ N \to \infty } 2\times2^{-N}\to \sum^{\infty}_{n=1} \frac{n}{2^{n}}=2-0-0
$$
`\end{proof}`

\section{Suppose that $a_{1},a_{2},a_{3}\dots$ are positive real numbers for which $$\frac{a_{n+1}}{a_{n}}\leq \frac{1}{2} \forall n \in \mathbb{N},$$
\subsubsection{Prove that $a_{n}<\left( \frac{1}{2} \right)^{n-1}a_{1}\forall n \in \mathbb{N}$. 

\subsubsection{Using the Comparison Test, or otherwise, deduce that $$\sum^{\infty}_{n=1}a_{n}$$converges}

$$
a_{2}\leq \frac{1}{2}a_{1},a_{3}\leq \frac{1}{2}a_{2}\implies a_{3}\leq \frac{1}{2}\left( \frac{1}{2}a_{1} \right)=\left( \frac{1}{2} \right)^{2}a_{1}
$$
Assume that 
$$a_{n+k}\leq \left( \frac{1}{2} \right)^{(n+k)-n}a_{n}=\left( \frac{1}{2} \right)^{k}a_{n}$$

Now lets prove this for $a_{n+k+1}$
$$
a_{n+k+1}\leq \frac{1}{2} a_{n+k}
$$
$$
\frac{1}{2}\max\{ a_{n+k} \}=\frac{1}{2}\left( \frac{1}{2} \right)^{k}a_{n}=\left( \frac{1}{2} \right)^{k+1}a_{n}\therefore a_{n+k+1}\leq \left( \frac{1}{2} \right)^{k+1} a_{n}
$$
Now let $n=1$ and we have proven the statement $\forall k\in \mathbb{N}$:
$$
a_{1+k}\leq \left( \frac{1}{2} \right)^{k} a_{1}
$$
This can be rewritten as:
$$
a_{n}\leq \left( \frac{1}{2} \right)^{n-1} a_{1}
$$

\subsection{}
$$
0<\sum^{\infty}_{n=1}a_{n}\leq \sum^{\infty}_{n=1} \left( \frac{1}{2} \right)^{n-1}a_{1}=a_{1}\sum^{\infty}_{n=1}\left( \frac{1}{2} \right)^{n-1}=a_{1}\sum^{\infty}_{n=0}\left( \frac{1}{2} \right)^{n}=a_{1}\left( \frac{1}{1-\frac{1}{2}} \right)=2a_{1}
$$
$$
0<\sum^{\infty}_{n=1}a_{n}\leq 2a_{1}
$$
$\therefore$ by MCT this will converge as it is strictly increasing ($a_{n}$ are positive numbers) and bounded ($0<$ as is positive numbers, and $\leq2a_{1}$).