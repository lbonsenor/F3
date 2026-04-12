`Incisos del libro: 2.4, 5.1 al 5.5`
#### Conductores en equilibrio electrostático
Un buen conductor eléctrico contiene cargas que no se encuentran unidas a ningún átomo y debido a eso tienen la libertad de moverse en el interior del material. Cuando no existe ningún movimiento neto de carga, el conductor esta en equilibrio electrostático
*Propiedades:*
	1. En el interior del conductor: $\vec E=0$, si el conductor es solido o hueco
	2. Si un conductor aislado tiene carga, reside en su superficie
	3. $|\vec E|=\frac\sigma{\epsilon_0}\wedge\vec E\bot S\quad\quad\quad\vec E\text{ fuera del conductor}$ 
	4. En un conductor de forma irregular, la densidad de carga superficial es maxima en aquellos puntos donde el radio de curvatura de la superficie es menor
	![[Figura-2.16 1.png]]
**Ejemplo:** *Una esfera dentro de un cascarón esférico*
	![[Ejemplo-2.7.png]]![[Ejemplo-2.7(1).png]]
#### Corriente eléctrica
La cantidad de flujo de las cargas eléctricas depende del material a través del cual pasan las cargas y de la $\Delta V$ que existe de un extremo al otro del material. Siempre que hay un flujo neto, se dice que existe una *corriente* eléctrica

> [!info] Analogía: Flujo de agua y la corriente
> EL flujo de agua en un tubo de fontanería puede ser cuantificado mediante la especificación de la cantidad de agua que emerge de un grifo durante un intervalo de tiempo $(L/min)$ 
> 
> La corriente puede ser caracterizada para describir la cantidad de agua que pasa por determinada ubicación

La corriente se define como la tasa a la cual circula la carga a través de una superficie y se mide en Coulombs sobre segundo $(\frac Cs)$ 
$$I_{prom}=\frac{\Delta Q}{\Delta t}$$
> [!example] Corriente
> $$I\equiv\frac{dQ}{dt}\quad\quad\quad[I]=\text{Ampere}\rightarrow A$$

En cualquier conductor, la dirección de la corriente es la opuesta a la dirección del flujo de los electrones. Es común referirse a una carga en movimiento como un portador de carga móvil

* Si los extremos de un alambre conductor se conectan para formar una espira, todos los puntos en la espira estarán con el mismo potencial eléctrico $\Rightarrow \vec E_{int}=\vec E_{ext}=0\Rightarrow$ no existe transporte neto.
* Si los extremos del alambre están conectados a una batería, los puntos de la espira no estarán con el mismo potencial, haciendo que se establezca una corriente

**Modelo microscópico de la corriente**
	![[Figura-5.2.png]]$\begin{cases}\Delta x=\text{longitud entre las dos secciones transversales circulares}\\ n=\text{la densidad de carga}\\ A\Delta x=\text{volumen del segmento}\\ nA\Delta x=\text{el numero de portadores}\\ \Delta t=\text{intervalo de tiempo requerido para que se muevan por un desplazamiento igual a la longitud del segmento}\end{cases}$
	$$\Rightarrow \Delta Q=(nA\Delta x)q\quad\quad\quad\text{(Carga total en la seccion)}$$
	Si los portadores se mueven con una rapidez $\vec v_d$  (rapidez de arrastre) paralelos al eje del cilindro $\Rightarrow \Delta x=v_d\Delta t$ $$\Rightarrow \Delta Q=(nAv_d\Delta t)q\quad\Rightarrow\quad I_{prom}=\frac{\Delta Q}{\Delta t}=n\cdot q\cdot v_d\cdot A$$
	**Ejemplo:** *Rapidez de arrastre en un alambre de cobre*
		![[Ejemplo-5.1.png]]
#### Resistencia
Considere un conductor de área de sección transversal $A$ que transporta una corriente $I$. La **densidad de corriente $J$** en el conductor se define como la corriente por unidad de área. 
Dado que la corriente es $I=nqv_dA$, la densidad de corriente s igual a 

>[!question] Densidad de Corriente
>$$J=\frac IA=nqv_d\quad\quad\quad[J]=\frac{A}{m^2}$$

Esta expresión solo es validad si la densidad de corriente es uniforme y solo si la superficie del área de sección transversal $A$ es perpendicular a la dirección de la corriente. Si no es el caso, en algunos materiales la densidad de corriente es proporcional al campo eléctrico $$J=\sigma E\quad\quad\sigma=\text{conductividad del conductor}$$
> [!info] Ley de Ohm
> Para muchos materiales (incluyendo la mayor parte de los metales) la razón de la densidad de corriente al campo eléctrico es una constante $\sigma$ que es independiente del campo eléctrico que produce la corriente.

Los materiales que cumplen esta relación entre $E$ y $J$, se conocen como materiales *óhmicos*

> [!warning]
> La ley de Ohm no es una ley fundamental de la naturaleza, sino más bien una relación empírica válida únicamente para ciertas situaciones

![[Figura-5.5.png]]
En esta figura, se mantiene una diferencia potencial $\Delta V=V_b-V_a$. Si se supone que el campo es uniforme.
$$\Delta V=E\ell\quad\quad\Rightarrow\quad\quad J=\sigma\frac{\Delta V}\ell$$ 
Ya que $J=\frac IA$, la diferencia de potencial a través del alambre es $$\Delta V=\frac\ell\sigma J=\bigg(\frac\ell{\sigma A}\bigg)I=R\ I$$
La cantidad $R=\frac{\ell}{\sigma A}$ se conoce como la resistencia del conductor y es definida como la razón de la diferencia de potencial aplicada a un conductor a la corriente que pasa por el mismo

Al estudiar los circuitos eléctricos utilizará esta ecuación una y otra vez. Con este resultado se observa que la resistencia tiene unidades del SI de volts por ampere. Un volt por ampere $(\frac VA)$ se define como un **ohm** $(\Omega)$:

>[!example] Resistencia
>$$R\equiv\frac{\Delta V}{I}\quad\quad\quad[R]=\text{Ohm}\Rightarrow\Omega$$ 

El inverso de la conductividad es la **resistividad** $\rho$:

>[!example] Resistividad
> $$\rho=\frac1\sigma\quad\quad[\rho]=\Omega\cdot m$$

Ya que $R=\frac{\ell}{\sigma A}$, es posible expresar la resistencia a lo largo de la longitud $\ell$ de un bloque uniforme de material de la forma $$R=\rho\frac\ell A$$
**Ejemplos**
	*Resistencia de alambre de nicromo*
		![[Ejemplo-5.2.png]]![[Ejemplo-5.2B.png]]
	*Resistencia radial de un cable coaxial*
		![[Ejemplo-5.3.png]]![[Ejemplo-5.3(1).png]]
#### Modelo de conducción eléctrica
1. *Componentes físicos*
	Piense en un conductor como un arreglo regular de átomos más un conjunto de electrones libres. Aunque estan unidos a sus atomos respectivos cuando estos no forman parte de un solido, obtienen movilidad cuando los atomos libres se condensan en un solido
2. *Comportamiento de los componentes* 
	1. En ausencia de un campo eléctrico, los electrones libres se mueven al azar a través del conductor (similar al movimiento de moléculas de un gas en un recipiente)
	2. Cuando es aplicado un campo eléctrico, los electrones libres se arrastran lentamente en una dirección opuesta a la del campo eléctrico, con una rapidez de arrastre promedio $v_d$ que es mucho mas pequeña que $v_{promedio}$ entre colisiones.
	3. El movimiento del electron despues de una colisión es independiente de su movimiento antes de la colisión

Cuando un electron libre tal que  $\begin{cases}m_e=\text{masa}\\q=\text{carga }(=-e)\end{cases}$ se somete a un campo electrico $\vec E$
$$\vec a=\frac{\sum\limits\vec F}{m}=\frac{q\vec E}{m_e}$$
Ya que el campo eléctrico es uniforme, la aceleración es constante, entonces la velocidad del electron en un tiempo muy breve $t$ (inmediatamente antes de que se presente la siguiente colision) es
$$\vec v_f=\vec v_i+\vec at=\vec v_i+\frac{q\vec E}{m_e}t$$
Sea $\tau$ el intervalo de tiempo promedio entre colisiones sucesivas
$$\vec v_{f,\ prom}=\vec v_d=\frac{q\vec E}{m_e}\tau$$
Por lo tanto, la corriente promedio en el conductor esta dada por
$$I_{prom}=nq\bigg(\frac{qE}{m_e}\tau\bigg)A=\frac{nq^2E}{m_e}\tau A$$
$$J=\frac{nq^2E}{m_e}\tau\quad\Rightarrow\quad\sigma=\frac{nq^2\tau}{m_e}\quad\Rightarrow\quad\rho=\frac1\sigma=\frac{m_e}{nq^2\tau}$$

$\tau$ esta relacionado con la distancia promedio entre colisiones tal que $\tau=\frac{\ell_{prom}}{v_{prom}}$
#### Resistencia y temperatura
En un intervalo limitado de temperatura, la resistividad de un conductor varía prácticamente de manera lineal con la temperatura, de acuerdo con la expresión
$$\rho=\rho_0[1+\alpha(T-T_0)]\quad\quad
\begin{cases}
\rho=\text{resistividad a cierta temperatura } T \\
\rho_0=\text{resistividad en alguna temperatura de referencia }T_0 \\
\alpha=\text{coeficiente de temperatura de resistividad}=\frac{1}{\rho_0}\frac{\Delta p}{\Delta T}
\end{cases}$$
La variación en la resistencia de una muestra es
$$R=R_0[1+\alpha(T-T_0)]$$
#### Superconductores
Existe una clase de metales y de compuestos cuya resistencia disminuye hasta cero cuando llegan a una cierta **temperatura crítica** $T_c$, los cuales se conocen como **superconductores**

![[Figura-5.10.png]]