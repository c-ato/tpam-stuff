[[data3.pdf]]

\section{Eight measurements of the volume of a block of iron had a mean value of $26.52cm^{3}$ and a mean square deviation $0.025cm^{6}$. Fifteen measurements of the volume of a block of aluminium gave the corresponding results $8.72cm^{3}$ and $0.058cm^{6}$. If the densities of iron and aluminium are $7.88gcm^{-3}$ and $2.70gcm^{-3}$, respectively, what is the best estimate of the total mass of the two blocks and the corresponding error in the measurement?}

$e(x)$ is the error of $x$, $\mu(x)$ is the mean.
$n_{i}=8,n_{a}=15,\mu(V_{i})=26.52,\mu(V_{a})=8.72,\rho_{i}=7.88,\rho_{a}=2.7$
We convert the MSD to variance and then root it to obtain $\sigma$.
$$
\sigma=\sqrt[  ]{ \sigma^{2} }=\sqrt[  ]{ \frac{MSD\times n}{n-1} }\implies \frac{\sigma}{\sqrt[  ]{ n }}=\sqrt[  ]{ \frac{MSD}{n-1} }
$$
$$
e(V_{i})=\frac{\sigma_{i}}{\sqrt[  ]{ n_{i} }}= \frac{\sqrt[  ]{ \frac{\cancel{ n_{i} }\times 0.025}{n_{i}-1} }}{\cancel{ \sqrt[  ]{ n_{i} } }}= \frac{\sqrt[  ]{ 70 }}{140}=0.0597\dots cm^{3}\implies e(M_{i})=e(V_{i})\rho_{i}=0.470\dots g
$$
$$
e(V_{a})=\frac{\sigma_{a}}{\sqrt[  ]{ n_{a} }}= \frac{\sqrt[  ]{ \frac{\cancel{ n_{a} }\times 0.058}{n_{a}-1} }}{\cancel{ \sqrt[  ]{ n_{a} } }}= \frac{\sqrt[  ]{ 2030 }}{700}=0.0643\dots cm^{3}\implies e(M_{a})=e(V_{a})\rho_{a}=0.173\dots g
$$
$$
\mu(M_{i})=\mu(V_{i})\rho_{i}=208.97\dots g
$$
$$
\mu(M_{a})=\mu(V_{a})\rho_{a}=23.544 g
$$
$$
\mu(M_{i})+\mu(M_{a})=\mu(M_{i}+M_{a})=232.52\dots g
$$$$
e(M_{i})+e(M_{a})=e(M_{i}+M_{a})=0.644\dots g
$$
The error is $0.644g$ and the mean is $232g$ of the 2 blocks together (at 3sf).

\section{Six measurements of the length of a wire had a mean value of $527.3cm$ with mean square deviation $0.01cm^{2}$. Twelve measurements of its diameter had a mean value of $0.062cm$ with a mean square deviation of $1.2 \times 10^{-6}cm^{2}$. If the resistivity is known to be $44.2 \times 10^{-6}\Omega cm$, what is the best estimate of the resistance of the wire and the corresponding error in the measurement?}
$\mu(L)=525.3,\mu(d)=0.062$
$$
\frac{\rho L}{A}=R
$$
$$
\mu(R)=\rho\frac{\mu(L)}{\mu(A)}=\rho\frac{\mu(L)}{\pi\left( \frac{\mu\left( d \right)}{2} \right)^{2}}=7.719\dots\Omega
$$
$$
e(R)=\mu(R)\frac{\sigma(R)}{\mu(R)}=\mu(R)\sqrt[  ]{\left( \frac{\frac{\sigma(L)}{\sqrt[  ]{ n_{L} }}}{\mu(L)} \right)^{2}+\left( 2\frac{\frac{\sigma(d)}{\sqrt[  ]{ n_{d} }}}{\mu(d)} \right)^{2}  }
$$
$n_{L}=6,n_{d}=12$ and we convert the MSD to variance and then root it to obtain $\sigma$.
$$
\sigma=\sqrt[  ]{ \sigma^{2} }=\sqrt[  ]{ \frac{MSD\times n}{n-1} }\implies \frac{\sigma}{\sqrt[  ]{ n }}=\sqrt[  ]{ \frac{MSD}{n-1} }
$$
$$
e(R)=\mu(R)\sqrt[  ]{ \frac{ \frac{0.01}{n_{L}-1} }{\mu(L)^{2}} +4\frac{ \frac{ 1.2\times 10^{-6}}{n_{d}-1} }{\mu(d)^{2}} }=0.0822\dots\Omega
$$

\section{The following table shows average life expectancy at age 10 in the United Kingdom versus year:

Find the line of best fit, $y = ax + b$, to this data. Determine the sample correlation coefficient, $r_{xy}$ , and the errors σ(a) and $\sigma(b)$ on the regression parameters. Plot the data and the line of best fit.}
$$
\langle xy \rangle =\langle x^{2} \rangle +b\langle x \rangle\qquad \langle y \rangle=a\langle x \rangle +b 
$$
$$
a= \frac{\langle xy \rangle -\langle x \rangle \langle y \rangle }{\langle x^{2} \rangle -\langle x \rangle ^{2}}\qquad b= \frac{\langle x^{2} \rangle \langle y \rangle -\langle x \rangle \langle xy \rangle }{\langle x^{2} \rangle -\langle x \rangle ^{2}}
$$
$$
\langle x \rangle = \frac{1}{N}\sum^{N}_{i=1}x_{i}=1982.5\qquad \langle y \rangle = \frac{1}{N}\sum^{N}_{i=1}y_{i}=66.137\dots\,\langle y^{2} \rangle =\frac{1}{N}\sum^{N}_{n=1}y^{2}_{i}=4384.008\dots
$$
$$
\langle x^{2} \rangle = \frac{1}{N}\sum^{N}_{i=1}x^{2}_{i}=3930712.5\qquad \langle xy \rangle = \frac{1}{N}\sum^{N}_{i=1}x_{i}y_{i}=131180.446\dots
$$
$$
s^{2}_{x}=\langle x^{2} \rangle -\langle x \rangle ^{2}=406.25\qquad s^{2}_{y}=\langle y^{2} \rangle -\langle y \rangle ^{2}=9.792\dots\qquad s_{xy}=\langle xy \rangle -\langle x \rangle \langle y \rangle =62.144\dots
$$
$$
\therefore a=\frac{s_{xy}}{s_{x}^{2}}=0.152\dots\qquad b=\frac{\langle x^{2} \rangle \langle y \rangle -\langle x \rangle \langle xy \rangle }{s_{x}^{2}}-237.128
$$
$$
r_{xy}= \frac{s_{xy}}{s_{x}s_{y}}=0.985\dots
$$
$$
\sigma(y)=\sqrt[  ]{ s^{2}_{y}- \frac{s^{2}_{xy}}{s^{2}_{x}s^{2}_{y}} }=2.970\dots
$$
$$
\sigma(a)= \frac{1}{\sqrt[  ]{ N }s_{x}}\sigma(y)=0.039\dots\qquad\sigma(b)=\sigma(a)\sqrt[  ]{ \langle x^{2} \rangle  }=78.082\dots
$$
