[[Assessed Problem Sheet 1.pdf]]

We consider an ideal gas, which follows the equations of state $pV = nRT$ and $U = \frac{3}{2}N k_{B}T$ , where the symbols have their usual meaning. We recall that the work done on the gas in a reversible transformation is - $\int p\, dV$ and the heat capacity $C_{V}$ is a constant such that $dQ=C_{V}dT$ in a transformation that keeps the volume constant. 

1. Give an expression of the work $W$ done on the system and the heat $Q$ transferred to the system in a isochoric transformation which changes the temperature from $T_{1}$ to $T_{2}$. [2]
$$
dU=dQ+dW=C_{V}dT-pdV\qquad pdV=0\because dV=0\therefore dU=dQ=C_{V}dT
$$
$$
U=\frac{3}{2}Nk_{B}T\therefore dU=Nk_{B}dT\therefore U=\int ^{T_{2}}_{T_{1}}  \, dU=\int ^{T_{2}}_{T_{1}} Nk_{B} \, dT  =Nk_{B}(T_{2}-T_{1})
$$
$$
Q=\int ^{T_{2}}_{T_{1}}  \, dQ =\int ^{T_{2}}_{T_{1}}C_{V}  \, dT=C_{V}(T_{2}-T_{1}) 
$$
2. Give an expression of the work $W$ done on the system and the heat $Q$ transferred to the system in an isothermal reversible expansion which changes the volume from $V_{1}$ to $V_{2}$. [2]
$$
dU=dQ+dW=CdT-pdV\qquad CdT=0, Q=0\because dT=0\therefore dU=dW=-pdV
$$
$$
pV=nRT\implies p=\frac{nRT}{V}\qquad W=\int ^{V_{2}}_{V_{1}}  \, dW=-\int ^{V_{2}}_{V_{1}} p \, dV =-\int ^{V_{2}}_{V_{1}} \frac{nRT}{V} \, dV=nRT\ln\left( \frac{V_{1}}{V_{2}} \right) 
$$
We now consider a cycle consisting of two isothermal transformations at temperatures $T_{1}$ and $T_{2}$ $(T_{2}>T_{1})$ and two isochoric transformations at volumes $V_{1}$ and $V_{2}$ $(V_{2}>V_{1})$

3. Draw the cycle on a $pV$ diagram. Indicate the direction of the cycle for it to produce net work. For each of the four segments of the cycle, indicate the sign of the work done by the system and the heat transferred to the system. [2]
![[pv cycle]]
4. Draw the cycle on a $VT$ diagram ($T$ on the abscissa). Indicate the direction of the cycle for it to produce net work. [2]
![[vt cycle]]
   
5. You have $2$ heat sources with temperatures $T_{1}$ and $T_{2}$. Can you operate the cycle above on an ideal gas in a reversible fashion? Explain why. [2]

Isothermal:
$$4\to 1:dU=dQ_{in}+dW_{on}=0\implies dQ_{on}=dW_{by}=pdV\implies Q_{on}^{4\to 1}=W_{by}^{4\to 1}=\int ^{V_{2}}_{V_{1}} \frac{nRT_{1}}{V} \, dV$$
$$=nRT_{1}\ln\left( \frac{V_{1}}{V_{2}} \right)$$
$$2\to 3:dU=dQ_{in}+dW_{on}=0\implies dQ_{on}=dW_{by}=pdV\implies Q_{on}^{2\to 3}=W_{by}^{2\to 3}=\int ^{V_{1}}_{V_{2}} \frac{nRT_{2}}{V} \, dV$$
$$=-nRT_{2}\ln\left( \frac{V_{1}}{V_{2}} \right)$$
$$W=W_{by}^{4\to 1}+W_{by}^{2\to 3}=(T_{1}-T_{2})nR\ln\left( \frac{V_{1}}{V_{2}} \right)\neq 0$$
Isochoric:
$$1\to 2:dU=dQ_{in}+dW_{on}=dQ_{in}=C_{V}dT\implies U=Q_{in}^{1\to 2}=C_{V}(T_{2}-T_{1})$$
$$3\to 4:\implies U=Q_{in}^{3\to 4}=-C_{V}(T_{2}-T_{1})$$
$$Q=Q_{in}^{1\to 2}+Q_{in}^{3\to 4}=0$$

$$
U=Q+W\neq 0 \therefore\text{ not reversible}
$$

The total $Q$ is $0$ as both isochoric changes are from the same two $T$, but reversed and has no dependence except on $T$. The total $W$ is not $0$, while the volume bounds are the same for the isothermal, there is also a dependence on $T$ that does vary with $4\to 1$ and $2\to 3$ so the terms do not cancel in the sum, this means the total $U$ is not $0$ and so is not reversible.
