[[example.pdf]]

1. A forced damped pendulum has an equation $$\frac{d^{2}\theta}{dt^{2}}+6 \frac{d\theta}{dt}+25\sin \theta=R\cos 4t$$When $R\ll 1$, find the approximate solution for the attractor and transients. Using the two choices $$p\equiv \frac{d\theta}{dt}\qquad P=\frac{d\theta}{dt}+3\theta$$find the fundamental equations and propose which of these is more useful for the attractor and which is more useful for the transients; with an explanation for your choice. On what scale is the error?
$$
\frac{d^{2}\theta}{dt^{2}}+6 \frac{d\theta}{dt}+25\theta=R\cos 4t \because R\ll 1\therefore \sin \theta\approx \theta
$$
$$
\frac{d^{2}\theta}{dt^{2}}+6 \frac{d\theta}{dt}+25\theta=0\qquad\theta=C\sin 4t+D\cos 4t
$$
$$
\frac{d\theta}{dt}=4C\cos4t-4D\sin 4t\qquad\frac{d^{2}\theta}{dt^{2}}=-16C\sin 4t-16D\cos 4t
$$
$$
(25C-24D-16C)\sin4t+(25D+24C-16D)\cos 4t=R\cos 4t
$$
$$
9C-24D=0\implies C=\frac{8}{3}D\qquad 9D+24C=73D=R\therefore D=\frac{R}{73}\therefore C=\frac{8R}{219}
$$
$$
\theta=\frac{8R}{219}\sin 4t+\frac{R}{73}\cos 4t\qquad p=\frac{d\theta}{dt}=\frac{32R}{219}\cos 4t-\frac{4R}{73}\sin 4t
$$
$$
P=\frac{d\theta}{dt}+3\theta=\frac{32R}{219}\cos 4t-\frac{4R}{73}\sin 4t+\frac{8R}{73}\sin 4t+\frac{3R}{73}\cos 4t=\frac{4R}{73}\sin 4t+\frac{41R}{219}\cos 4t
$$
$$
P=\frac{d\theta}{dt}+3\theta\implies \frac{dP}{dt}=\frac{d^{2}\theta}{dt^{2}}+3\frac{d\theta}{dt}=\frac{d^{2}\theta}{dt^{2}}+3P-9\theta \therefore \frac{d^{2}\theta}{dt^{2}}=\frac{dP}{dt}-3P+9\theta
$$
$$
\frac{d^{2}\theta}{dt^{2}}+6 \frac{d\theta}{dt}+25\theta=R\cos 4t=\frac{dP}{dt}-3P+9\theta+6P-18\theta+25\theta=\frac{dP}{dt}+3P-9\theta=R\cos 4t
$$
$$
\therefore \frac{dP}{dt}=R\cos 4t+9\theta -3P
$$
$$
\frac{d\theta}{dt}=p \therefore \frac{dp}{dt}=\frac{d^{2}\theta}{dt^{2}}=R\cos 4t-6p-25\theta
$$
$p$ is likely better for attractor as is directly relates the rate of change of $\theta$ to $p$ so it may be easier to see how they behave.

$P$ is likely better for the transients as we have proportionality with $\theta$ in $P=\frac{d\theta}{dt}+3\theta$ so we may see how strong the attractor acts

Error scale is $O(\theta^{3})$ as we have $\sin \theta\approx \theta$ where in the expansion's next term would be of $\theta^{3}$.

2. Consider the map $$x_{n+1}=rx_{n}(1-x_{n})^{2}$$where $r > 0$ is a control parameter. Find all the possible 1-cycles and establish for which range of control parameter they are stable. How do you think this sequence of cycles continues? 
$$
x=rx(1-x)^{2}\qquad x=0\qquad 1=r(1-x)^{2}\implies x=1\pm \sqrt[  ]{ \frac{1}{r} }
$$
$$
\frac{df}{dx}=r(1-x)^{2}-2rx(1-x)=r(1-x)(1-x-2x)=r(1-x)(1-3x)
$$
$$
\implies 1>r\left( 3\left( x-\frac{2}{3} \right)^{2}-\frac{1}{3} \right)>-1 \therefore 3>r>-3
$$
$$
x_{1}=rx_{2}(1-x_{2})^{2}\qquad x_{2}=rx_{1}(1-x_{1})^{2}\implies x_{1}x_{2}=rx_{1}x_{2}(1-x_{2})^{2}\qquad x_{1}x_{2}=rx_{1}x_{2}(1-x_{1})^{2}
$$
$$
\pm(1-x_{1})=(1-x_{2}) \qquad x_{1}\neq x_{2}\therefore x_{1}-1=1-x_{2} \qquad x_{1}+x_{2}=2
$$
$$
x_{1}x_{2}=rx_{1}x_{2}(1-x_{1})^{2}\implies 1=r(1-x_{1})^{2}\implies x_{1}=1\pm \sqrt[  ]{ \frac{1}{r} }\therefore x_{2}=1\mp \sqrt[  ]{ \frac{1}{r} }
$$