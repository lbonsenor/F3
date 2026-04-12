`Incisos del libro: 4.1 al 4.7, 6.4`

>[!danger] FALTAN LOS INCISOS 4.6, 4.7
#### Capacitancia 
Un **capacitor** se conoce como la combinación de dos conductores, y si llevan carga de igual magnitud y signo opuesto existe una diferencia de potencial $\Delta V$ entre ellos
![[Figura-4.1.png]]

>[!example] Capacitancia
>$$C\equiv\frac{Q}{\Delta V}\quad\quad\quad[C]=\text{Farad}\Rightarrow\text{F}=\frac CV$$

Como el farad es una unidad muy grande. En la practica se utilizaran microfarads $(1\mu \text{F}=10^{-6}\text{ F})$ y picofarads $(1\text{pF}=10^{-9}\text{ F})$ 

>[!success] Calculo de Capacitancia
>$\text{En una esfera de radio }a\text{ con carga y aislada}:$
>$$C=\frac{Q}{\Delta V}=\frac{Q}{k_eQ/a}=\frac{a}{k_e}=4\pi\epsilon_0a$$
>$\text{En dos placas de igual area }A\text{ separadas por una distancia }d:$
>$$C=\frac{\epsilon_0A}d$$
>$\text{En un capacitor cilindrico de radio }a\text{ y }b\text{ con carga }Q:$
>$$C=\frac{\ell}{2k_e\ln(b/a)}$$
>$\text{En un capacitor esferico de radios }a\text{ y }b:$
>$$C=\frac{ab}{k_e(b-a)}$$

>[!info] Energía almacenada en un capacitor con carga
>$\text{Para cualquier capacitor}$
>$$U_E=\frac{Q^2}{2C}=\frac12Q\Delta V=\frac12C(\Delta V)^2$$
#### Capacitores en Paralelo y en Serie 
![[Figura-4.6.png]] ![[Figura-4.7.png]]
>[!info] $\text{En paralelo: }\color{black}\begin{cases}C_{\text{eq}}=C_1+C_2 \\ \Delta V=\Delta V_1=\Delta V_2 \\ Q_{\text{tot}}=Q_1+Q_2=C_1\Delta V_1+C_2\Delta V_2\end{cases}$

![[Figura-4.8.png]]

>[!info] $\text{En serie: }\color{black}\begin{cases}\frac{1}{C_{\text{eq}}}=\frac1{C_1}+\frac1{C_2} \\ \Delta V=\Delta V_1+\Delta V_2=\frac{Q_1}{C_1}+\frac{Q_2}{C_2}\\ Q_{\text{tot}}=Q_1=Q_2\end{cases}$

*Capacitancia equivalente*
	![[Ejemplo-4.13.png]]![[Ejemplo-4.13(1).png]]

#### Capacitores con material dieléctrico
Un **dieléctrico** es un material no conductor, como el hule, el vidrio o el papel encerado. 
El efecto que causa un dieléctrico en un capacitor es una disminución en la diferencia de potencial y un aumento en la capacitancia. Los voltajes con o sin dieléctrico están relacionados mediante un factor $\kappa$ tal que $$\Delta V=\frac{\Delta V_0}\kappa\quad\wedge\quad C=\kappa C_0$$
![[Figura-4.13.png]]

>[!warning] Cuando el el capacitor esta lleno de material dieléctrico: $\color{black}C=\kappa\frac{e_0A}d$

>[!note] Energía almacenada antes y después de una inserción de un dieléctrico
>$$U=\frac{Q_0^2}{2\kappa C_0}=\frac{U_0}{\kappa}$$
#### Circuitos RC en serie
![[Figura-6.16.png]]
>$\mathcal E-\frac qC-iR=0$
>$I_{\text{inicial}}=\frac{\mathcal E}R$
>$Q_\max=C\mathcal E$
>$q(t)=C\mathcal E(1-e^{-t/RC})=Q_\max(1-e^{-t/RC})$
>$i(t)=\frac{\mathcal E}Re^{-t/RC}$
>$\tau=RC\quad\quad\text{constante de tiempo del circuito}$

La constante de tiempo representa el intervalo de tiempo durante el cual la corriente disminuye hasta $1/e$ de su valor inicial; es decir, en un intervalo de tiempo $\tau$, la corriente decrece a $i=e^-1I_i=0.368I_i$. Después de un intervalo de tiempo $2\tau$, la corriente decrece a $i=e^{-2}I_i=0.135I_i$ y así sucesivamente.

De igual manera. en un intervalo de tiempo $\tau$, la carga aumenta de cero a $C\mathcal E(1-e^{-1})=0.632C\mathcal E$
![[Figura-6.17.png]]
