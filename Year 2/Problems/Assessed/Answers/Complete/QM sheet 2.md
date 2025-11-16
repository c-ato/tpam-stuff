A particle of mass $m$ is incident on a potential barrier of width $L$ and height $V_{0}$. The potential is zero on both sides of the barrier. The particle has energy $E$, which is greater than the height of the barrier, $E > V_{0}$. 

Write down expressions for the wavenumbers and wavefunctions in each of the three regions of space (across the barrier and on each side of it). [3]

![[QM sheet 2 2025-11-06 16.31.56.excalidraw]]

$$\Psi_{1}(x)=Ae^{ ik_{1}x }+Be^{ -ik_{1}x }\qquad \Psi_{2}(x)=Ce^{ ik_{2}x }+De^{ -ik_{2}x }\qquad \Psi_{3}=Ee^{ ik_{2}x }$$
$$k_{1}=\frac{\sqrt[  ]{ 2mE }}{\hbar}\qquad k_{2}=\frac{\sqrt[  ]{ 2m(E-V_{0}) }}{\hbar}$$
$$\Psi_{1}(0)=\Psi_{2}(0)=A+B=C+D\qquad\Psi_{1}'(0)=\Psi_{2}'(0)=Ak_{1}-Bk_{1}=Ck_{2}-Dk_{2} $$
$$\Psi_{2}(L)=\Psi_{3}(L)=Ce^{ ik_{2}L }+De^{ -ik_{2}L }=Ee^{ ik_{1}L }\qquad\Psi_{2}'(L)=\Psi_{3}'(L)=k_{2}Ce^{ ik_{2}L }-k_{2}De^{ -ik_{2}L }=k_{1}Ee^{ ik_{1}L } $$
By applying the appropriate boundary conditions at both of the edges of the barrier, derive a set of equations to relate the coeicients of the wavefunctions in the diferent regions. [3]
$$\implies A= \frac{C}{2}\left( \frac{k_{1}+k_{2}}{k_{1}} \right)+\frac{D}{2}\left( \frac{k_{1}-k_{2}}{k_{1}} \right)\qquad B=\frac{C}{2}\left( \frac{k_{1}-k_{2}}{k_{1}} \right)+\frac{D}{2}\left( \frac{k_{1}+k_{2}}{k_{1}} \right)$$
$$\implies C= \frac{E}{2} \left( \frac{k_{2}+k_{1}}{k_{2}} \right)e^{ iL(k_{1}-k_{2}) }\qquad D= \frac{E}{2} \left( \frac{k_{2}-k_{1}}{k_{2}} \right)e^{ iL(k_{1}+k_{2}) }$$
$$A= \frac{E}{4}\left( \frac{k_{1}+k_{2}}{k_{1}} \right)\left( \frac{k_{2}+k_{1}}{k_{2}} \right)e^{ iL(k_{1}-k_{2}) }+\frac{E}{4}\left( \frac{k_{1}-k_{2}}{k_{1}} \right)  \left( \frac{k_{2}-k_{1}}{k_{2}} \right)e^{ iL(k_{1}+k_{2}) }$$
$$B=\frac{E}{4}\left( \frac{k_{1}-k_{2}}{k_{1}} \right) \left( \frac{k_{2}+k_{1}}{k_{2}} \right)e^{ iL(k_{1}-k_{2}) }+\frac{E}{4}\left( \frac{k_{1}+k_{2}}{k_{1}} \right)\left( \frac{k_{2}-k_{1}}{k_{2}} \right)e^{ iL(k_{1}+k_{2}) }$$
$$A= \frac{E}{4k_{1}k_{2}}\left( \left(k_{1}+k_{2} \right)^{2}e^{ iL(k_{1}-k_{2}) }- \left( k_{1}-k_{2} \right)^{2} e^{ iL(k_{1}+k_{2}) } \right) $$
$$B=\frac{E}{4k_{1}k_{2}}\left(k_{1}+k_{2}\right)\left( k_{1}-k_{2} \right) \left( e^{ -iLk_{2} }-e^{ iLk_{2} } \right)e^{ iLk_{1} }$$

Hence show that, if the height of the barrier is $$V_{0}=E-\frac{\pi^{2}\hbar^{2}}{2mL^{2}}$$then there is no reflection from the barrier for this particle. [4]

$$V_{0}=E-\frac{\pi^{2}\hbar^{2}}{2mL^{2}}\implies k_{2}=\frac{\sqrt[  ]{ 2m\left( E-\left( E-\frac{\pi^{2}\hbar^{2}}{2mL^{2}} \right) \right) }}{\hbar}=\frac{\pi}{L}$$
$$B=\frac{E}{4k_{1}k_{2}}\left(k_{1}+k_{2}\right)\left( k_{1}-k_{2} \right) \left( e^{ -i\pi }-e^{ i\pi } \right)e^{ iLk_{1} }$$
$$B=\frac{E}{4k_{1}k_{2}}\left(k_{1}+k_{2}\right)\left( k_{1}-k_{2} \right) \left( -1-(-1) \right)e^{ iLk_{1} }=\frac{E}{4k_{1}k_{2}}\left(k_{1}+k_{2}\right)\left( k_{1}-k_{2} \right) \left( 0 \right)e^{ iLk_{1} }=0$$



