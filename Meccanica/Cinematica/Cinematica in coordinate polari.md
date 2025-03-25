>[!note]
>La rappresentazione polare permette di rappresentare la legge oraria come $$\overrightarrow{r}: \begin{cases}
>r=r(t)\text{ coordinata radiale} \\
>\theta=\theta(t)\text{ coordinata angolare}
>\end{cases}$$
>Il legame tra la rappresentazione polare e cartesiana è il seguente: $$\begin{cases}
>x=r\cos\theta \\
>y=r\sin\theta
>\end{cases}$$
>Definiamo quindi un versore radiale $\hat{u}_{r}$, parallelo al vettore, e un versore trasversale $\hat{u}_{\theta}$ perpendicolare al versore radiale.

>[!tip] Velocità in coordinate polari
>Per definizione: $$\overrightarrow{v}= \frac{\text{d}}{\text{d}t} \overrightarrow{r}$$
>Introducendo un versore radiale: $$\frac{\text{d}}{\text{d}t} \bigg(r(t)\hat{u}_{r} \bigg)= \frac{\text{d}}{\text{d}t} \overrightarrow{r}\cdot \hat{u}_{r}+r\cdot \frac{\text{d}}{\text{d}t} \hat{u}_{r}$$
>Calcoliamo la derivata del versore: $$\begin{align*}
>\frac{\text{d}}{\text{d}t} \hat{u}_{r}&= \lim_{t_{2}\to t_{1}} \frac{\hat{u}_{t_{2}}-\hat{u}_{t_{1}}}{t_{2}-t_{1}}=\lim_{\Delta t\to0}\frac{\Delta \hat{u}_{r}}{\Delta t}=\lim_{\Delta t\to0}\frac{|\Delta \hat{u}_{r}|}{|\hat{u}_{r}|\Delta t}=\lim_{\Delta t\to0}\frac{|\Delta \overrightarrow{r}|}{||\overrightarrow{r}_{1}||\Delta t}\\
>&= \lim_{\Delta t\to0} \frac{|\Delta s|}{||\overrightarrow{r}_{1}||\Delta t}=\lim_{\Delta t\to0} \frac{\Delta \theta}{\Delta t}= \frac{\text{d}}{\text{d}t} \theta(t)
>\end{align*}$$
>La quantità $r\cdot\theta'(t)$ è detta componente trasversale della velocità. Quindi: $$\begin{cases}
v_{r}'=r'(t) \\
v_{\theta}'=r(t)\cdot\theta'(t)
\end{cases}$$

### Moto circolare
>[!note]
>Un moto circolare è un moto la cui traiettoria è una circonferenza di raggio $R$. Possiamo usare un ascissa curvilinea: $$\begin{align*}
s(t)&= R\cdot\theta(t)\qquad &[s]=\text{m}\qquad&[\theta]=\text{rad}\\
v(t)&= R\cdot \omega(t)\qquad &[v]= \frac{\text{m}}{\text{s}}\qquad&[\omega]= \frac{\text{rad}}{\text{s}}\\
a(t)&= R\cdot\alpha(t)\qquad &[v]= \frac{\text{m}}{\text{s}^{2}}\qquad &[\alpha]=\frac{\text{rad}}{\text{s}^{2}}
\end{align*}$$

Definiamo lo spostamento angolare $\Delta \theta$ analogamente al moto rettilineo: $$\Delta \theta=\theta_{2}-\theta_{1}$$
Definisco la velocità angolare media a istantanea come: $$\begin{align*}
\langle\omega\rangle&=  \frac{\theta_{2}-\theta_{1}}{t_{2}-t_{1}}\qquad [\langle\omega\rangle]= \frac{\text{rad}}{\text{s}}\\
\omega(t)&= \frac{\text{d}}{\text{d}t} \theta(t)
\end{align*}$$
Definisco l'accelerazione angolare media e istantanea come: $$\begin{align*}
\langle\alpha\rangle&= \frac{\omega_{2}-\omega_{1}}{t_{2}-t_{1}}\qquad [\langle\alpha\rangle]= \frac{\text{rad}}{\text{s}^{2}}\\
\alpha(t)&= \frac{\text{d}}{\text{d}t} \omega(t)=\frac{\text{d}^{2}}{\text{d}{t}^{2}} \theta(t)
\end{align*}$$
Anche il problema inverso è analogo al moto rettilineo.

### Moti circolari particolari
>[!note] Moto Circolare Uniforme
>Avendo un accelerazione nulla, si ha una velocità scalare costante $\omega_{0}\in\mathbb{R}$. È possibile quindi ricavare la legge oraria: $$\theta(t)=\theta_{0}+\omega_{0}(t-t_{0})$$
>In rappresentazione intrinseca possiamo dire che: $$\begin{cases}
>\overrightarrow{r}=-R\hat{u}_{n} \\
>\overrightarrow{v}=v_{0}\hat{u}_{t} \\
>\overrightarrow{a}= \frac{v^{2}_{0}}{\rho}\hat{u}_{n}
>\end{cases}$$
>Mentre in rappresentazione cartesiana: $$\overrightarrow{r}=R\cos(\omega_{0} t) \hat{u}_{x}+R\sin(\omega_{0}t)\hat{u}_{y}$$

>[!note] Moto Circolare non Uniforme
>Avendo un accelerazione costante $a_{0}\in\mathbb{R}$, è possibile ricavare la velocità utilizzando il problema inverso: $$\begin{align*}
>v(t)&= v_{0}+a_{0}(t-t_{0})\\
>x(t)&= x_{0}+v_{0}(t-t_{0})+ \frac{1}{2}a_{0}(t-t_{0})^{2}
>\end{align*}$$
>Si ha che: $$\begin{cases}
s(t)= \frac{1}{2}a_{0}t^{2} \\
\theta(t)= \frac{1}{2}\alpha t^{2}
\end{cases}$$

### Grandezze cinematiche angolari vettoriali
>[!note]
>Sia $\hat{u}_{z}$ il versore parallelo al piano del moto, orientato usando la regola della mano destra rispetto a $\theta$. È possibile descrivere un moto circolare con una grandezza vettoriale: $$\overrightarrow{\omega}=\theta'(t)\hat{u}_{z}$$

È immediato osservare che: $$\overrightarrow{v}=\overrightarrow{\omega}\times\overrightarrow{r}$$
Di conseguenza, derivando $\overrightarrow{v}$: $$\overrightarrow{a}=\overrightarrow{\alpha}\times\overrightarrow{r}+\overrightarrow{\omega}\times\overrightarrow{v}$$