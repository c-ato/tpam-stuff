[[SR,P 2024.pdf]]

1. A quantum mechanical wavefunction is given by $$\psi(x)=e^{ - \frac{x}{2} }\qquad 0\leq x<\infty$$The probability density is related to the wavefunction through $\rho(x)=\left| \psi(x) \right|^{2}$.
- (a) Show that this wavefunction is normalised.
$$
\int ^{\infty}_{0} \left| \psi \right|^{2} \, dx =\int_{0}^{\infty} e^{ -x } \, dx =\left[ -e^{ -x } \right] ^{\infty}_{0}=0-(-1)=1
$$
$$
=-0-\left(- \frac{1}{1} \right)=1
$$
- (b) Define the expectation value, $\langle x \rangle$, for a continuous distribution.
$$
\langle x \rangle =\int ^{b}_{a} x\rho(x) \, dx \text{ where }x \in [a,b]\text{ and the probability distribution is }\rho(x)
$$
- (c) Calculate the expectation value of position for this wavefunction.
$$
\int ^{\infty}_{0} x\left| \psi \right|^{2} \, dx =\int_{0}^{\infty} xe^{ -x } \, dx =\left[ -xe^{ -x }+\int ^{\infty}_{0} e^{ -x } \, dx \right]  =\left[ -e^{ -x }(x+1) \right] ^{\infty}_{0}=\left[ -\frac{x+1}{e^{ x }} \right] ^{\infty}_{0}
$$
2. A discrete distribution is given by $$P(x)=\frac{c}{x^{2}}\qquad x=\{ 1,2,\dots \}$$
- (a) Find the normalising constant, $c$.
$$
\sum^{\infty}_{x=1} \frac{c}{x^{2}}=c \sum^{\infty}_{x=1} \frac{1}{x^{2}}=\frac{c\pi^{2}}{6}=1 \iff c= \frac{6}{\pi^{2}}
$$
- (b) Define the expectation value, ⟨x⟩, for a discrete distribution.
$$
\sum^{b}_{x=a}xP(x)\text{ where }x,a,b\in \mathbb{N}: x \in[a,b] \text{ and the probability density function is }P(x)
$$
$$
\lim_{ N \to \infty } \sum^{N}_{x=1}xP(x)=\lim_{ N \to \infty }\sum^{N}_{x=1} \frac{6}{\pi^{2}} \frac{1}{x}= \frac{6}{\pi^{2}}\lim_{ N \to \infty }\sum^{N}_{x=1} \frac{1}{x}\approx\frac{6}{\pi^{2}}\lim_{ N \to \infty } \ln N\to \infty
$$
3. In a multiple choice question with $k$ possible answers, a student either knows the answer or does not. When they do not know the answer they guess. Let the probability that a student actually knows the answer be $p$.
- (a) What is the probability they get the correct answer if they guess?
$$
P(C|DK)=\frac{1}{k}
$$
- (b) Given that a student gets the question correct, what is the probability that they knew the answer?
$$
P(K|C)=\frac{p}{p+\frac{1-p}{k}}=\frac{kp}{kp+1-p}
$$
- (c) The odds ratio of an event is defined as $O(p)=\frac{p}{1-p}$. Show that as $k\to \infty$ the probability of knowing the answer given the student was correct can be written as $$P(K|C)\approx 1- \frac{O(1-p)}{k}$$and show that this requires that $p$ is not close to $0$. You may find the following approximation helpful $$\frac{1}{1+ax}\approx 1-ax\qquad ax\ll 1$$
$$
P(K|C)=\frac{p}{p+\frac{1-p}{k}}=\frac{kp}{kp+1-p}=1- \frac{p-1}{p(k-1)+1}=1- \frac{(p-1)O(1-p)}{p(k-1)+1} \frac{1-(1-p)}{1-p}=
$$
$$
=1- \frac{pO(1-p)}{pk+(1-p)}=1- \frac{O(1-p)}{k+\frac{1-p}{p}}\approx 1- \frac{O(1-p)}{k}
$$
If $p$ was close to 0 then we would not be able to ignore and approximate the $\frac{1-p}{p}$ term.

4. In an inertial frame $Σ$ event $B$ occurs after event $A$. The events take place at the same position and the time interval between the events is $T$.
- (a) By performing Lorentz transformation to the frame $\Sigma'$ which moves in the positive $x$-direction with velocity $v$ with respect to $Σ$, find the time interval $T '$ between the events in the frame $Σ'$.
$$
cT'=\gamma(cT-\beta(v) x)\implies T'=\gamma T= \frac{T}{\sqrt[  ]{ 1-\frac{v^{2}}{c^{2}} }}
$$
- (b) Calculate the interval $\Delta s^{2}_{AB}$ between the events. Explain why it is invariant under Lorentz transformation. Use the invariant interval to calculate the distance $D'$ between the events in the frame $Σ'$.
$$
\Delta x=vT\implies \Delta s^{2}=(cT)^{2}-(vT)^{2}=T^{2}(c^{2}-v^{2}\qquad D'=\gamma(x-\beta(v) cT)=\gamma\left( \frac{v}{c}cT \right)= \frac{vT}{1-\frac{v^{2}}{c^{2}}}
$$
5. Paul Atreides flies away from the planet Arrakis with speed $V = \frac{3c}{5}$. After flying for $τ = 2$ years (in his own frame) he receives a radio message from Arrakis telling him that his mission cannot be funded anymore and he must return. Paul performs an immediate U-turn and heads back to Arrakis with the same speed. When approaching the planet he discovers that the landing and communication system of the spaceship are broken so he misses the landing. It takes him a while before he is able to repair the communication system and stop. He makes a distress video call to Arrakis which is received $T = 13$ years after the first message was sent.
- (a) Draw the Minkowski space-time diagram of Paul’s journey. Use the start event at the origin, $E_{0} = (t_{0}, x_{0}) = (0, 0)$. Indicate 
	- (i) the event $E_{1} = (t_{1}, x_{1})$ when the fist message is sent, 
	- (ii) the event $E_{2} = (t_{2}, x_{2})$ when Paul receives it, 
	- (iii) the event $E_{3} = (t_{3}, x_{3})$ when Paul stops and sends his message, 
	- (iv) the event $E_{4} = (t_{4}, x_{4})$ when the Paul’s message is received on Arrakis

![[SR and P 2024 2025-06-05 12.18.01.excalidraw]]

- (b) Give the definition of proper time. Using this definition or an appropriate Lorentz transformation calculate the space-time coordinates of the event $E_{1} = (t_{1}, x_{1})$. State the relativistic effect behind this calculation. 

The time measured by a clock that has the same motion of the observer.
$$
\beta=\frac{V}{c}=\frac{3}{5}\qquad x=Vt\qquad ct'=\gamma(ct+\beta x)=\gamma\left( ct+\frac{3}{5} Vt \right)\implies t=\frac{ct'}{\gamma\left( c+\frac{3}{5}^{2} c \right)}
$$
$$
=\frac{25t'\sqrt[  ]{ 1-\frac{9}{25} }}{34}=\frac{20t'}{34}=\frac{40}{34}=1.17\dots \text{ years}
$$
The time for the signal from inertial frame appears to reach the rocket in less time than that perceived by the rocket.

- (c) Show that $t_{3}=10$ years.
$$
x'=0\qquad t'=2\qquad V'=\frac{(-V)-V}{1- \frac{(-V)(V)}{c^{2}}}=-\frac{2V}{1+\frac{V^{2}}{c^{2}}}=\frac{\frac{6c}{5}}{\frac{34}{25}}=\frac{30c}{34}\qquad \beta(V')=\frac{30}{34}\qquad\gamma(V')=\frac{17}{8}
$$
$$
ct''=\gamma(V')(ct'-\beta x')\implies t''=\frac{34}{8}
$$
6. A cosmic ray proton $p$ with energy $E_{1}$ hits a proton at rest with mass $m_{p} = 940 MeV$. As a result a $π$ meson with rest mass $m_{\pi} = 140 Mev$ is created in addition to the protons.
- (a) Write down the momenta of the protons $P_{1},P_{2}$ before the collision.
$$
E_{1}=\frac{mc^{2}}{\sqrt[  ]{ 1- \frac{u^{2}}{c^{2}} }}\implies u=c\sqrt[  ]{ 1-\left( \frac{mc^{2}}{E_{1}} \right)^{2}  }\implies\beta(u)=\frac{u}{c}=\sqrt[  ]{ 1-\left( \frac{mc^{2}}{E_{1}} \right)^{2}  }
$$
$$
P_{1}=\frac{m u}{\sqrt[  ]{ 1- \frac{u^{2}}{c^{2}} }}=\frac{E_{1}c^{2}}{u}=\frac{E_{1}c}{\sqrt[  ]{ 1-\frac{m^{2}c^{4}}{E_{1}^{2}}  }}=\frac{E_{1}c}{\beta(u)}\qquad P_{2}=0
$$
- (b) Assuming an observer moves along the direction of the cosmic ray proton with velocity $v$ write down the energy and momentum of each particle in the moving observer’s frame by using Lorentz transformation for energy and momentum. 

7. Consider playing a game multiple times. The probability that you win the game is p. You decide that you will play this game until you have won r games, and then immediately stop. Note that this means you stop playing the game as soon as you have won r games, and so the process stops on a win.
- (a) What is the probability that you have to play two games in order to win once
$$
(1-p)p
$$
- (b) What is the probability that you have to play $n$ games in order to win once $(r=1)$
$$
(1-p)^{n-1}p
$$
- (c) You decide you want to win twice $(r = 2)$. For the case $n = 2$ you require $\{win, win\}$. Write down the corresponding results for $n = 3$ and $n = 4$. 
$$
n=3:2(1-p)p^{2}\qquad n=4:3(1-p)^{2}p^{2}
$$
- (d) What is the probability that you have to play $n$ games to win twice?
$$
\sum^{n}_{k=2} (k-1)(1-p)^{n-2}p^{2}
$$
- (e) So far there have been $r −1$ wins after $n−1$ games, not necessarily ending with a win. The probability of this is $$P=\left( \begin{matrix}n-1 \\r-1\end{matrix} \right) (1-p)^{n-r}p^{r-1}$$Therefore, what is the probability that you stop after playing $n$ games with $r$ wins? 
$$
pP=f(n,r)=\left( \begin{matrix}n-1 \\r-1\end{matrix} \right) (1-p)^{n-r}p^{r}
$$
- (f) Use the above to show that$$\sum^{\infty}_{n=r} \frac{(n-1)!}{(n-r)!}(1-p)^{n}=\left( \frac{1-p}{p} \right)^{r}(r-1)!$$
$$
\sum^{\infty}_{n=r}f(n,r)=\sum^{\infty}_{n=R}\frac{(n-1)!}{(n-r)!(r-1)!}(1-p)^{n-r}p^{r}=\sum^{\infty}_{n=r}\frac{(n-1)!}{(n-r)!(r-1)!}(1-p)^{n}\left( \frac{p}{1-p} \right) ^{r}
$$
$$
\frac{1}{(r-1)!} \left( \frac{p}{1-p} \right) ^{r}\sum^{\infty}_{n=r}\frac{(n-1)!}{(n-r)!}(1-p)^{n}=1\implies\sum^{\infty}_{n=r} \frac{(n-1)!}{(n-r)!}(1-p)^{n}=\left( \frac{1-p}{p} \right)^{r}(r-1)!
$$
- (g) What is $⟨n⟩$? (Hint: use the above summation to aid you). 
$$
\langle n \rangle =\sum^{\infty}_{n=1}nf(n,f)=\frac{1}{(r-1)!} \left( \frac{p}{1-p} \right) ^{r}\sum^{\infty}_{n=r}\frac{(n-r+r)(n-1)!}{(n-r)!}(1-p)^{n}
$$
$$
=r+\sum^{\infty}_{n=r} \frac{(n-r)(n-1)!}{(n-r)!}(1-p)^{n}=r+\sum^{\infty}_{n=r} \frac{(n-1)!}{(n-r-1)!}(1-p)^{n}\qquad z=r+1
$$
$$
=r+\sum^{\infty}_{n=z-1} \frac{(n-1)!}{(n-z)!}(1-p)^{n}=r+\frac{(z-2)!}{}+\sum^{\infty}_{n=z} \frac{(n-1)!}{(n-z)!}(1-p)^{n}
$$