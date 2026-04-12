`Incisos del libro: 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.8
El campo eléctrico producido por cargas en reposo (campo electrostático) es conservativo para una carga puntual
$\vec E(\vec r)=\frac1{4\pi\epsilon_0}\frac q{|\vec r-\vec r_q|^3}(\vec r-\vec r_q)$
$\vec\nabla\times\vec E=\frac q{4\pi\epsilon_0}\vec\nabla\times\underbrace{\bigg(\frac{(\vec r-\vec r_q)}{|\vec r-\vec r_q|^3}\bigg)}_{=\ \vec0}=0$
Para un desplazamiento infinitesimal $d\vec s$ de una carga puntual $q$ inmersas en un campo eléctrico, el trabajo realizado por un campo eléctrico sobre la misma es $W_{\text{int}}=\vec F_e\cdot d\vec s=q\vec E\cdot d\vec s$, y el trabajo interno es igual al negativo de la variación de la energía potencial del sistema: $W_{\text{int}}=-\Delta U$
$$\text{Cambio en la energia potencial del sistema}:\Delta U=-q\int\limits_A^B\vec E\cdot d\vec s$$
Para una posición conocida de la carga de prueba en el campo, el sistema tiene una energía potencial $U$ relativa a la configuración $U=0$
$$\text{Potencial electrico}: V=\frac Uq$$
$$\text{Diferencia de Potencial}:\Delta V\equiv\frac{\Delta U}q=-\int\limits_A^B\vec E\cdot d\vec s$$

> [!warning] 
> Para que exista una *energía* potencial tenemos que tener un sistema de dos o más cargas

El trabajo realizado por un agente externo al desplazar una carga q a través de un campo eléctrico con una velocidad constante es $W=q\Delta V$
Ya que el potencial eléctrico es una medida de la energía potencial por unidad de carga, la unidad del SI, tanto del potencial eléctrico como de la diferencia de potencial, es joules por cada coulomb, que se define como un volt (V):

$$[V]=\text{Volt}\rightarrow V$$

El campo eléctrico es una medida de la relación de cambio del potencial eléctrico en función de la posición. Tambien existe una unidad de energía que es el **electrón volt** $(\text{eV})$, que se define como la energía que un sistema carga-campo gana o pierde cuando se desplaza una carga de magnitud $e$ a causa de una diferencia de potencial de $1\text{ V}$
$$1\text{ eV}=1.60\times10^{-19}\text{ C}\cdot\text{V}=1.60\times10^{-19}\text{ J}$$
#### Diferencia de Potencial en un campo eléctrico uniforme
![[Figura-3.2.png]] 
$$V_B-V_A=\Delta V=-\int\limits_A^B\vec E\cdot d\vec s=-Eds(\cos0°)=-\int\limits_A^BEds=\color{red}-Ed$$
Suponiendo que una carga $q$ se mueve desde $A$ hacia $B$; se puede calcular el cambio en la energía potencial $\Delta U=q\Delta V=-qEd$
![[Figura-3.3.png]] **OBS:** $\vec s$ no es paralelo a las líneas de campo
$\color{red}\Delta V\color{black}=-\int\limits_A^B\vec E\cdot d\vec s=-\vec E\cdot\int_A^Bd\vec s=-\vec E\cdot\vec s$
$\color{blue}\Delta U\color{black}=q\Delta V=-q\vec E\cdot\vec s$
**Campo eléctrico entre dos placas paralelas de carga opuesta**
	![[Ejemplo-3.1.png]]![[Figura-3.5.png]]
	![[Ejemplo-3.1C.png]]
**Movimiento de un protón en un campo eléctrico uniforme**
	![[Ejemplo-3.2.png]]
	![[Ejemplo-3.2C.png]]
#### Potencial eléctrico y energía potencial debidos a cargas puntuales
Para $n$ cargas puntuales: 
$$V=k_e\sum\limits_i^n\frac{q_i}{r_i}\quad\quad\quad k_e=\frac1{4\pi\epsilon_0}$$
$$U_n=\frac12\sum\limits\limits_{j=1}^nq_j\underbrace{\bigg(k_e\sum\limits\limits_{i=1\wedge i\ne j}^n\frac{q_i}{r_{ij}}\bigg)}_{V(\vec r_j)}$$
*Potencial eléctrico debido a dos cargas puntuales*
	![[Ejemplo-3.3A.png]]![[Ejemplo-3.3B.png]]
#### Obtención del valor del campo eléctrico a partir del potencial eléctrico
Si el campo eléctrico tiene sólo una componente $E_x$, entonces $\vec E\cdot d\vec s=E_xdx\Rightarrow dV=-E_xdx$
$$\Rightarrow E_x=-\frac{dV}{dx}$$
Esta ecuación es la afirmación matemática del hecho de que el campo eléctrico es una medida de la rapidez de cambio del potencial eléctrico con la posición
Las superficies equipotenciales asociadas con un campo eléctrico uniforme están constituidas por una familia de planos perpendiculares a las líneas de campo
![[Figura-3.11.png]]
Si la distribución de carga que origina un campo eléctrico tiene simetría esférica, tal que la densidad de carga volumétrica depende sólo de la distancia radial $r$, el campo eléctrico es radial $\Rightarrow E_r=-\frac{dV}{dr}$
#### Potencial eléctrico debido a distribuciones de carga continua
$$V=k_e\int\frac{dq}r\quad\quad\quad\quad dq=\begin{cases}\lambda(\vec{r'})dL'\quad\text{(1D)}\\\sigma(\vec{r'})dA'\quad\text{(2D)}\\\rho(\vec{r'})dV'\quad\text{(3D)}\\\end{cases}$$
$$U=\frac12\int\limits_{V'}\rho(\vec{r'})\ V(\vec{r'})\ dV'$$
*Estrategia para resolución de problemas: Calculo de Potencial Eléctrico*
	![[Calculo-V1.png]]![[Calculo-V2.png]]
<font color="#d83931"><b>Ejemplos:</b></font>
	*Potencial eléctrico debido a un dipolo*
		![[Ejemplo-3.4AB.png]]![[Ejemplo-3.4C.png]]
	*Potencial eléctrico debido a un anillo con carga uniforme*
		![[Ejemplo-3.5A.png]]![[Ejemplo-3.5B.png]]
	*Potencial eléctrico debido a un disco con carga uniforme*
		![[Ejemplo-3.6.png]]![[Ejemplo-3.6AB.png]]
	*Potencial eléctrico debido a una línea de carga finita*
		![[Ejemplo-3.7.png]]![[Ejemplo-3.7A.png]]