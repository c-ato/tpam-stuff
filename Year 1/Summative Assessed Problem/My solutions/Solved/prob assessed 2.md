A quantum mechanical particle is confined to a region of the $x$-axis for which $0\leq x\leq a$ (where $a > 0$). The particle has a Probability Density Function (PDF) describing the position given by
$$P(x)=\left\{ \begin{array}{} Ax^{2}(a^{3}-x^{3})\quad \text{if }0\leq x\leq a\\0\quad\qquad\qquad \text{otherwise}\end{array} \right.$$

\section{For a PDF, $P(x)$, define $\langle x \rangle$, $\langle x^{2} \rangle$, var$(x)$ and std$(x)$. The sample space for $x$ can be assumed to be the entire $\mathbb{R}$ line here.}
$$
\langle x \rangle =\int ^{a}_{0} x(Ax^{2}(a^{3}-x^{3}))\,dx\qquad \langle x^{2} \rangle =\int ^{a}_{0} x^{2}(Ax^{2}(a^{3}-x^{3}))\,dx
$$
$$
var(x)= \langle x ^{2}\rangle-\langle x \rangle^{2}=\int ^{a}_{0}x^{2}(Ax^{2}(a^{3}-x^{3}))  \, dx-\left( \int ^{a}_{0} x(Ax^{2}(a^{3}-x^{3})) \, dx  \right)  ^{2}
$$
$$
std(x)=\sqrt[  ]{ var(x) }=\sqrt[  ]{ \int ^{a}_{0}x^{2}(Ax^{2}(a^{3}-x^{3}))  \, dx-\left( \int ^{a}_{0} x(Ax^{2}(a^{3}-x^{3})) \, dx  \right)^{2}   }
$$
\section{Calculate the value of $A$ such that the PDF is properly normalised.}
$$
1=\int ^{a}_{0} Ax^{2}(a^{3}-x^{3}) \, dx \iff1=A\int ^{a}_{0} x^{2}a^{3}-x^{5} \, dx =A\left[ \frac{x^{3}a^{3}}{3}- \frac{x^{6}}{6} \right]^{a}_{0} 
$$
$$
\iff \frac{1}{A}=\frac{a^{6}}{3}-\frac{a^{6}}{6}=\frac{a^{6}}{6}\therefore A=\frac{6}{a^{6}}
$$
\section{Calculate the expectation value of the position}
$$
\langle x \rangle =\int ^{a}_{0} x(Ax^{2}(a^{3}-x^{3}))\,dx=\frac{6}{a^{6}}\int ^{a}_{0} x^{3}a^{3}-x^{6}dx=\frac{6}{a^{6}}\left[ \frac{x^{4}a^{3}}{4}-\frac{x^{7}}{7} \right] ^{a}_{0}=\frac{6}{a^{6}} \frac{3a^{7}}{28}=\frac{9a}{14}
$$
\section{Calculate the standard deviation of the position}
$$
std(x)=\sqrt[  ]{ var(x) }=\sqrt[  ]{ \int ^{a}_{0}x^{2}(Ax^{2}(a^{3}-x^{3}))  \, dx-\left( \int ^{a}_{0} x(Ax^{2}(a^{3}-x^{3})) \, dx  \right)^{2}   }
$$
$$
\sqrt[  ]{\frac{6}{a^{6}} \int ^{a}_{0}x^{4}a^{3}-x^{7}  \, dx-\left(\frac{9a}{14}\right)^{2}   }=\sqrt[  ]{\frac{6}{a^{6}} \left( \frac{a^{8}}{5}-\frac{a^{8}}{8}  \right)   - \frac{81a^{2}}{196}   }=\sqrt[  ]{\frac{6}{a^{6}} \left( \frac{3a^{8}}{40}\right)   - \frac{81a^{2}}{196}   }
$$
$$
=\sqrt[  ]{ \frac{9a^{2}}{20}  - \frac{81a^{2}}{196}   }=\sqrt[  ]{ \frac{9a^{2}}{245} }=\frac{3a}{7\sqrt[  ]{ 5 }}
$$
\section{Calculate the value $m$ such that$$\frac{1}{2}=\int ^{m}_{0} P(x) \, dx$$ otherwise know as the median.}
$$
\frac{1}{2}=\int ^{m}_{0} Ax^{2}(a^{3}-x^{3}) \, dx=A\left[ \frac{x^{3}a^{3}}{3}- \frac{x^{6}}{6} \right]^{m}_{0} =\frac{6}{a^{6}}\left( \frac{m^{3}a^{3}}{3}-\frac{m^{6}}{6} \right)
$$
$$
a^{6}=2(2m^{3}a^{3}-m^{6})\iff 2(m^{3})^{2}-4a^{3}(m^{3})-a^{6}=0\iff m^{3}=\frac{4a^{3}\pm \sqrt[  ]{ 16a^{6} +8a^{6}}}{4}
$$
$$
=\left( 1\pm \frac{\sqrt[  ]{ 6 }}{2} \right)a^{3}\iff m= a\sqrt[ 3 ]{ 1\pm \frac{\sqrt[  ]{ 6 }}{2} }
$$
as $x>0\implies m=a\sqrt[ 3 ]{ 1+ \frac{\sqrt[  ]{ 6 }}{2} }$
