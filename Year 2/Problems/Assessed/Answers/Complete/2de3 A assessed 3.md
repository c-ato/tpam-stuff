1. 
a)
$$y=\sum^{\infty}_{n=0}a_{n}(x-x_{0})^{n}\qquad y'=\sum^{\infty}_{n=0,1}na_{n}(x-x_{0})^{n-1}\qquad y''=\sum^{\infty}_{n=0,1,2}n(n-1)(x-x_{0})^{n-2}$$
$$x_{0}=0\qquad y''-xy'-y=\sum^{\infty}_{n=2}n(n-1)a_{n}x^{n-2}-\sum^{\infty}_{n=0}na_{n}x^{n}-\sum^{\infty}_{n=0}a_{n}x^{n}$$
$$=\sum^{\infty}_{n=0}(n+2)(n+1)a_{n+2}x^{n}-\sum^{\infty}_{n=0}na_{n}x^{n}-\sum^{\infty}_{n=0}a_{n}x^{n}=0$$
$$(n+2)(n+1)a_{n+2}-(n+1)a_{n}=0$$
$$a_{n+2}= \frac{a_{n}}{n+2}\qquad a_{2k}=\frac{a_{0}}{2^{k}k!}\qquad a_{2n+1}= \frac{a_{1}}{\frac{(2k+1)!}{2^{k}k!}}=\frac{a_{1}2^{k}k!}{(2k+1)!}$$
$$y=\sum^{\infty}_{k=0} \frac{a_{0}}{2^{k}k!}x^{2n}+\sum^{\infty}_{k=0} \frac{a_{1}2^{k}k!}{(2k+1)!}x^{2k+1}$$
b)
$$x_{0}=1\qquad y''-xy'-y$$
$$=\sum^{\infty}_{n=2}n(n-1)a_{n}(x-1)^{n-2}-[(x-1)+1]\sum^{\infty}_{n=0,1}na_{n}(x-1)^{n-1}-\sum^{\infty}_{n=0}a_{n}(x-1)^{n}$$
$$=\sum^{\infty}_{n=2}n(n-1)a_{n}(x-1)^{n-2}-\sum^{\infty}_{n=0}na_{n}(x-1)^{n}-\sum^{\infty}_{n=1}na_{n}(x-1)^{n-1}-\sum^{\infty}_{n=0}a_{n}(x-1)^{n}$$
$$=\sum^{\infty}_{n=0}(n+2)(n+1)a_{n+2}(x-1)^{n}-\sum^{\infty}_{n=0}na_{n}(x-1)^{n}-\sum^{\infty}_{n=0}(n+1)a_{n+1}(x-1)^{n}-\sum^{\infty}_{n=0}a_{n}(x-1)^{n}=0$$
$$(n+2)(n+1)a_{n+2}-na_{n}-(n+1)a_{n+1}-a_{n}=0$$
$$a_{n+2}=\frac{a_{n+1}+a_{n}}{n+2}$$
$$a_{2}=\frac{a_{1}+a_{0}}{2}\qquad a_{3}=\frac{a_{2}+a_{1}}{3}=\frac{3a_{1}+a_{0}}{6}$$
$$y=\sum^{\infty}_{n=0}a_{n}(x-1)^{n}$$
$$=a_{0}\left( 1+\frac{(x-1)^{2}}{2}+\frac{(x-1)^{3}}{6} +\dots\right)+a_{1}\left(( x-1)+\frac{(x-1)^{2}}{2}+ \frac{(x-1)^{3}}{2}+\dots \right)$$
