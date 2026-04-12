`Incisos del Libro: 5.6, 6.1, 6.2, 6.3, 6.5`
#### Potencia Eléctrica
![[Figura-5.11.png]]
En los circuitos eléctricos, la energía $T_{ET}$ se transfiere de una fuente, como una batería
La rapidez a la cual el sistema pierde energía potencial eléctrica conforme a una carga $Q$ a traves del resistor es: $$\frac{dU}{dt}=\frac d{dt}(Q\Delta V)=\frac{dQ}{dt}\Delta V=I\Delta V$$
>[!question] Potencia
>$$P=I\Delta V=I^2R=\frac{(\Delta V)^2}{R}\quad\quad\quad[P]=\text{Watt}\Rightarrow W$$

**Ejemplos**
	*Energia en un calentador eléctrico*
		![[Ejemplo-5.4.png]]
	*Vinculacion entre electricidad y termodinámica*
		![[Ejemplo-5.5A.png]]![[Ejemplo-5.5B.png]]
#### Fuerza Electromotriz $(\text{fem})$
Una batería se le conoce como fuente de fuerza electromotriz (fem). La fem $\mathcal E$ de una batería es el voltaje máximo posible que esta puede suministrar entre sus terminales

>[!error] Cuidado
>Una fuerza electromotriz no es una fuerza, sino una diferencia de potencial en $\text{V}$

En una batería existe una resistencia al flujo de las cargas dentro de la misma, o mejor dicho **resistencia interna** $r\approx 0$. En este caso, $\mathcal E$ es equivalente al **voltaje en circulo abierto** $$\Delta V=\mathcal E-Ir$$
En base a esto, se observa que
>[!question] FEM
>$$\mathcal E=IR+Ir$$

**Ejemplo**
	*Voltaje entre las terminales de una batería*
		![[Ejemplo-6.1.png]]![[Ejemplo-6.1A.png]]![[Ejemplo-6.1B.png]]
	*Igualacion de carga*
		![[Ejemplo-6.2.png]]![[Ejemplo-6.2(1).png]]

#### Resistores en Serie y en Paralelo
![[Figura-6.3.png]]
>[!info] En este caso: $\begin{cases}\color{black}R_{eq}=R_1+R_2+R_3+...\\ \color{black}I=I_1=I_2 \\ \color{black}\Delta V=\Delta V_1+\Delta V_2 \end{cases}$ 


![[Figura-6.5.png]]
>[!info] En este caso: $\begin{cases}\color{black}\frac1{R_{eq}}=\frac1{R_1}+\frac1{R_2}+\frac1{R_3}+...\\ \color{black}I=I_1+I_2 \\\color{black}\Delta V=\Delta V_1=\Delta V_2\end{cases}$ 

**Ejemplos**
	*Encuentre la resistencia equivalente*
		![[Ejemplo-6.4.png]]![[Ejemplo-6.4B.png]]
	*Tres resistores en paralelo*
		![[Ejemplo-6.5.png]]![[Ejemplo-6.5C.png]]
#### Leyes de Kirchhoff
> [!info] Leyes de Kirchhoff
> 1. **Ley de la unión**. En cualquier union, la suma de las corrientes debe ser igual a 0: $$\sum\limits_\text{union}I=0$$
> 2. **Ley de la espira**. La suma de las diferencias de potencial a traves de todos los elementos alrededor de cualquier espira de un circuito cerrado debe ser igual a 0:$$\sum\limits_\text{circuito cerrado}\Delta V=0$$

*Explicación grafica*
	![[Figura-6.12.png]]![[Figura-6.13.png]]
**Estrategia para resolución de problemas**
	![[Estrategia_Kirchhoff.png]]![[Estrategia_Kirchhoff2.png]]
**Ejemplo**
	*Circuito de una sola espira*
		![[Ejemplo-6.6.png]]
	*Circuito de varias espiras*
		![[Ejemplo-6.7.png]]![[Ejemplo-6.7(1).png]]![[Ejemplo-6.7(2).png]]