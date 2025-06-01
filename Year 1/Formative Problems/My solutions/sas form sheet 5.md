1[[1SAS_Sheet 5_2024.pdf]]
1i)
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n+1}}{1+\log n}
$$
By the alternating series test it is enough to show that the following sequence is decreasing and $\to 0$
$$
a_{n}= \frac{1}{1+\log n} 
$$
$$
\log (n+1)>\log n \forall n \therefore a_{n+1}>a_{n} \forall n \in \mathbb{R}
$$
$$
\lim_{ n \to \infty } \log n\to \infty \therefore \text{ by AoL } \lim_{ n \to \infty } \frac{1}{1+\log n}\to 0
$$
$\therefore$ we have satisfied the convergence criteria of an alternating sequence.

1ii)
$$
\sum^{\infty}_{n=3}\frac{1}{n(\log n)(\log(\log n))}
$$
Suppose the integral test:
$$
\int^{n}_{3} \frac{1}{n(\log n)(\log(\log n))}  \, dx =\log (\log (\log n))
$$
$$
\lim_{ n \to \infty } \log(\log(\log n))\to \infty
$$
1iii)
$$
\sum^{\infty}_{n=1}\left( \frac{1}{n^{3}}+\frac{1}{n^{3}+1}+\dots+\frac{1}{n^{3}+n} \right)
$$
By MCT it is enough to show that this converges if it is bounded above as it is already strictly increasing as it is the sum of positives.
$$
\sum^{\infty}_{n=1}\left( \frac{1}{n^{3}}+\frac{1}{n^{3}+1}+\dots+\frac{1}{n^{3}+n} \right)<\sum^{\infty}_{n=1} \frac{n}{n^{3}}=\sum^{\infty}_{n=1}\frac{1}{n^{2}}= \frac{\pi^{2}}{2}
$$
$\therefore$ converges
1iv)
$$
\sum^{\infty}_{n=1} n^{-3/2}\sin \frac{n\pi}{12}
$$
This will alternate due to the $\sin$ function, thus we may use the absolutely convergent test and comparison test such that we only need to prove that the following converges, which already belongs to family of infinite sums who's convergent properties are known:
$$
\sum^{\infty}_{n=1} \left| n^{-3/2}\sin \frac{n\pi}{12} \right|< \sum^{\infty}_{n=1} \frac{1}{n^{3/2}}\subset \sum^{\infty}_{n=1} \frac{1}{n^{\alpha}}\to l \iff\alpha>1
$$
$\therefore$ converges
1v)
$$
\sum^{\infty}_{n=1}\left( \frac{n^{3}+4n^{2}+17n+1}{2n^{3}-n^{2}+1} \right)^{n}\cos(n)
$$
We may use absolute convergence and root test s.t.
$$
\sum^{\infty}_{n=1}\left| \left( \frac{n^{3}+4n^{2}+17n+1}{2n^{3}-n^{2}+1} \right)^{n}\cos(n) \right| <\sum^{\infty}_{n=1}  \left( \frac{n^{3}+4n^{2}+17n+1}{2n^{3}-n^{2}+1} \right)^{n}
$$
$$
a_{n}=\left( \frac{n^{3}+4n^{2}+17n+1}{2n^{3}-n^{2}+1} \right)^{n}\qquad r=\lim_{ n \to \infty }  \sqrt[ n ]{ a_{n} }=\lim_{ n \to \infty }  \frac{n^{3}+4n^{2}+17n+1}{2n^{3}-n^{2}+1} 
$$
$$
=\lim_{ n \to \infty } \frac{1+\frac{4}{n}+\frac{17}{n^{2}}+\frac{1}{n^{3}}}{2-\frac{1}{n}+\frac{1}{n^{3}}}\to \frac{1}{2}<1
$$
$\therefore$ it converges as $r<1$
2)
$$
\sum^{\infty}_{n=2} \frac{1}{n(\log n)^{1+\epsilon}}
$$
$$
\lim_{ n \to \infty } \int ^{n}_{2} \frac{1}{n(\log n)^{1+\epsilon}} \, dx =\lim_{ n \to \infty } \left[ -\frac{1}{(\log(n))^{\epsilon}} \right]^{n}_{2}=0-\left( -\frac{1}{(\log (2))^{\epsilon}} \right)=\frac{1}{(\log (2))^{\epsilon}}
$$
$\therefore$ the series also converges
 3i)
 $$
\sum^{\infty}_{n=1} \frac{(-1)^{n}(n!)^{2}}{(2n)!}
$$
Using the absolute convergence test and then the ratio test:
$$
r=\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}}= \lim_{ n \to \infty }  \frac{\frac{((n+1)!)^{2}}{(2(n+1))!}}{\frac{(n!)^{2}}{(2n)!}}=\lim_{ n \to \infty } \frac{(n+1)^{2}}{(2n+1)(2n+2)}=\lim_{ n \to \infty } \frac{1+\frac{1}{n}}{2\left( 2+\frac{1}{n} \right)}= \frac{1}{4}<1
$$
$\therefore$ it does converge
3ii)
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n}x^{n}}{n 5^{n}}
$$
Using AC test and ratio test:
$$
r=\lim_{ n \to \infty } \frac{\frac{x^{n+1}}{(n+1)5^{n+1}}}{\frac{x^{n}}{n5^{n}}}=\lim_{ n \to \infty } \frac{nx}{5(n+1)}\to \left|  \frac{x}{5} \right| < 1
$$
Suppose $r=1\implies x=5$:
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n}}{n}
$$
Which converges by AS test, now suppose $x=-5$
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n}(-\cancelto{ 1 }{ 5 })^{n}}{n\cancel{ 5 }^{n}}=\sum^{\infty}_{n=1} \frac{(-1)^{2n}}{n}=\sum^{\infty}_{n=1} \frac{1}{n}=\infty
$$
$$
\therefore S := \{ x \in(-5,5] \}
$$
3iii)
$$
\sum^{\infty}_{n=1} \sin ^{2}\left( \frac{1}{n} \right)
$$
$$
\sin x\leq x\implies\sin ^{2}\left( \frac{1}{n} \right)\leq \frac{1}{n^{2}}
$$
$$
\therefore 0< \sum^{\infty}_{n=1} \sin ^{2}\left( \frac{1}{n} \right)\leq \sum^{\infty}_{n=1} \frac{1}{n^{2}}= \frac{\pi^{2}}{6}
$$
$\therefore$ by MCT, this converges as sum of positives (square of the reals) so is strictly increasing and is bounded above
4i)
$$
\sum^{\infty}_{n=1} \frac{n}{2n+1}
$$
Using the null sequence test we show it does not converge when $a_{n}\not\to 0$:
$$
\lim_{ n \to \infty }  \frac{n}{2n+1}\to \frac{1}{2}
$$
4ii)
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n+1}}{\sqrt[  ]{ n }}
$$
By AS test, this converges as $\lim_{ n \to \infty }\frac{1}{\sqrt[  ]{ n }}\to 0$
4iii)
$$
\sum^{\infty}_{n=1} \frac{10^{n}(n!)^{3}}{(3n)!}
$$
Using ratio test:
$$
r=\lim_{ n \to \infty } \frac{\frac{10^{n+1}((n+1)!)^{3}}{(3n+3)!}}{\frac{10^{n}(n!)^{3}}{(3n)!}}=\lim_{ n \to \infty }  \frac{10(n+1)^{2}}{3(3n+1)(3n+2)}=\lim_{ n \to \infty } \frac{10\left( 1+\frac{1}{n} \right)^{2}}{3\left( 3+\frac{1}{n} \right)\left( 3+\frac{2}{n} \right)}\to \frac{10}{27}<1
$$
$\therefore$ this series converges

4iv)
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n+1}\cos ^{2}(n)}{n^{2}}
$$
We may use AC, and show it converges instead:
$$
0<\sum^{\infty}_{n=1} \frac{\cos ^{2}(n)}{n^{2}}< \sum^{\infty}_{n=1} \frac{1}{n^{2}}= \frac{\pi^{2}}{6}
$$
$\therefore$ by MCT, the absolute converges as is the sum of positives (strictly increasing) and is bounded above, $\therefore$ the original sequence will also converge as it is absolutely convergent.

5i)
$$
\sum^{\infty}_{n=1} \frac{(-1)^{n}}{n}
$$
5ii)
$$
a_{n}=\lambda_{n}= \frac{(-1)^{n}}{\sqrt[  ]{ n }}
$$
5iii)

6i)
$$
\sum^{\infty}_{n=1} \frac{a_{n}}{1+a_{n}^{2}}
$$
Using the integration test:
$$
\sum^{\infty}_{n=1} \frac{a_{n}}{1+a_{n}^{2}}\implies \int ^{n}_{1} \frac{a_{x}}{1+a_{x}^{2}} \, dx= \frac{1}{2} \frac{dn}{da_{n}} \ln(1+a_{x})  

$$
7)
$$
\sum^{\infty}_{n=0} (-1)^{n} \frac{x^{n}}{2^{n}\sqrt[  ]{ n+1 }}
$$
Using absolute convergence, where for any arbitrary $l\in \mathbb{R}$:
$$
\sum^{\infty}_{n=0} \frac{x^{n}}{2^{n}\sqrt[  ]{ n+1 }}= l \iff |x|<2 
$$
Case 1, $x=-2$
$$
\sum^{\infty}_{n=0} (-1)^{n} \frac{(-2)^{n}}{2^{n}\sqrt[  ]{ n+1 }}\overset{ m=n+1 }{ = }\sum^{\infty}_{m=1} \frac{1}{\sqrt[  ]{ m }}\to \infty \because \sum^{\infty}_{n=1} \frac{1}{n^{\alpha}}\to l\iff \alpha>1
$$
Case 2, $x=2$
$$
\sum^{\infty}_{n=0} (-1)^{n} \frac{2^{n}}{2^{n}\sqrt[  ]{ n+1 }}=\sum^{\infty}_{n=0} (-1)^{n} \frac{1}{\sqrt[  ]{ n+1 }}\overset{ m=n+1 }{ = } \sum^{\infty}_{m=1} \frac{(-1)^{m-1}}{\sqrt[  ]{ m }}\to l
$$
$\because$ it fits the criteria for the AS test.

$\therefore$ the convergence set for this series is, $S:=\{ -2<x\leq 2 \}$

8)
$$
\sum^{\infty}_{n=0} \frac{n^{n}}{7^{n}n!}x^{n}
$$
Using ratio test:
$$
r=\lim_{ n \to \infty } \frac{\frac{(n+1)^{n+1}}{7^{n+1}(n+1)!}x^{n+1}}{\frac{n^{n}}{7^{n}n!}x^{n}}= \lim_{ n \to \infty }  x\frac{(n+1)^{n}}{7n^{n}}=\frac{x}{7} \lim_{ n \to \infty } \left( 1+\frac{1}{n} \right)^{n}\to \left| \frac{xe}{7} \right| < 1
$$
$$
\therefore |x|< \frac{7}{e}
$$
Using 
$$
a_{n} = \frac{n^{n}}{e^{n}n!}< \frac{n^{n}}{n\cdot n!}= \frac{n^{n-1}}{n!}\overset{ m=n-1 }{ = } \frac{(m+1)^{m}}{(m+1)!}
$$
Case 1, $x=- \frac{7}{e}$:
$$
\sum^{\infty}_{n=0} \frac{n^{n}}{7^{n}n!}\left(- \frac{7}{e} \right)^{n}=\sum^{\infty}_{n=0}(-1)^{n} \frac{n^{n}}{e^{n}n!}
$$
By AS test, this converges if $|a_{n}|$ tends to 0, so it is enough by MCT, where it is bounded below by $0$ (naturally as are absolutes) and strictly decreasing.

Let $n=1$ and then $n=2$
$$
a_{1}=\frac{1}{e}\qquad a_{2}=\frac{2}{e^{2}}=\frac{2}{e} \frac{1}{e}> \frac{2}{3} \frac{1}{e}> \frac{1}{e}=a_{1}
$$
$\therefore$ suppose for $k$ the below holds true.
$$
a_{k}>a_{k+1} \iff\frac{k^{k}}{e^{ k }k!}>\frac{(k+1)^{(k+1)}}{e^{ (k+1) }(k+1)!}=\frac{(k+1)^{k}}{e^{ (k+1) }k!}
$$
$$
\implies k^{k}> \frac{(k+1)^{k}}{e}\implies \left( 1+\frac{1}{k} \right)^{k}<e= \lim_{ h \to \infty } \left( 1+\frac{1}{h} \right)^{h}
$$
Now consider $k+1$ and this will also be true as the definition of $e$ is given by this limit to infinity so $\forall k<\infty$ this will be true, or in other words $\forall k\in \mathbb{R}$.

Case 2, $x=\frac{7}{e}$ using comparison test:
$$
\sum^{\infty}_{n=0} \frac{n^{n}}{7^{n}n!} \left( \frac{7}{e} \right)^{n}= \sum^{\infty}_{n=0} \frac{n^{n}}{e^{n}n!}=\sum^{\infty}_{n=0} \frac{n^{(n-1)}}{e^{n}(n-1)!}=\sum^{\infty}_{n=0} \frac{1}{e^{ n }} \frac{n}{n-1} \frac{n}{n-2}\dots \frac{n}{2} \frac{n}{1}
$$
$$
\sum^{\infty}_{n=0} \frac{n^{n}}{e^{ n }n!}< \sum^{\infty}_{n=0} \frac{n(n-1)}{e^{ n }}< \sum^{\infty}_{n=0} \frac{n^{2}}{e^{n}}
$$
Ratio test:
$$
r=\lim_{ n \to \infty } \frac{\frac{(n+1)^{2}}{e^{(n+1)}}}{\frac{n^{2}}{e^{n}}}=\lim_{ n \to \infty } \frac{\left( 1+\frac{1}{n} \right)^{2}}{e}=\frac{1}{e}< \frac{1}{2}<1
$$
$\therefore$ upper comparison converges which means the actual series also converges by MCT $\therefore$ giving the convergence set as $S:=\left\{  |x|\leq \frac{7}{e}  \right\}$