`Incisos del libro: 1.4, 1.5`
La fuerza electrostática actúa a distancia al igual que la gravitatoria, solo que con una intensidad 20 órdenes de magnitud superior
![[Campo_Electrico.png]]

El campo eléctrico es una suerte de emanación que permea todo el espacio alrededor de una carga
$\vec E(\vec r)=\lim\limits_{q_0\rightarrow0}\frac{\vec F_{q_0}(\vec r)}{q_0}=k_e\frac{q}{r^2}\color{pink}\hat r\quad\quad\quad\hat r\text{ con origen en la carga }q$  

Para obtener el campo eléctrico producido por un conjunto de cargas puntuales, se aplica el principio de superposicion
![[Cargas_Puntuales]]
$\vec E(\vec r)=\vec E_1(\vec r)+\vec E_2(\vec r)+...$
$$
\quad\quad\quad\Rightarrow\vec E(\vec r)=\sum\limits^N_{i=1}k_e\frac{q_i}{|\vec r-\vec r_i|^2}\underbrace{\frac{(\vec r-\vec r_i)}{|\vec r-\vec r_i|}}_{\hat r_i(\vec r)}
$$
Distribución Continua de Carga
	Distribución Lineal
		![[Distribucion_Lineal]]
		$\lambda(x)=\frac{dq}{dx}\quad\quad\quad\lambda=\frac{Q}{L} \text{si es homogénea}$
		$$\vec E(\vec r)=\int\limits_Ck_e\frac{\vec r-\vec {r'}(x)}{|\vec r-\vec {r'}(x)|^3}\underbrace{\lambda(x)dx}_{dq}$$
	Distribución Superficial
		![[Distribucion_Superficial]] $dq=\sigma(\vec {r'})dA$ 
		$$\vec E(\vec r)=\iint\limits_Sk_e\frac{\vec r-\vec {r'}}{|\vec r-\vec {r'}|^3}\sigma(\vec {r'})dA$$
	Distribución Volumétrica
		![[Distribucion_Volumetrica]]
		$dq=\rho(\vec {r'})dV$	
		$$\vec E(\vec r)=\iiint\limits_Vk_e\frac{\vec r-\vec {r'}}{|\vec r-\vec {r'}|^3}\rho(\vec {r'})dV$$
Líneas de Campo Eléctrico
	![[Lineas_Campo.png]]
	![[Lineas_Campo2.png]]![[Lineas_Campo3.png]]