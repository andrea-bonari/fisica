## Coordinate polari
Un altro modo di rappresentare la legge oraria, utilizzato per il moto circolare (e orbitale) è la rappresentazione polare, che utilizza una quantità $r$ (modulo) e un angolo $\theta$ (positivo in senso antiorario):
$$\begin{cases}
r=r(t)&r=|\overrightarrow{r}| \\
\theta=\theta(t)
\end{cases}$$

Il legame tra la rappresentazione polare e la rappresentazione cartesiana è il seguente:
$$\begin{cases}
x=r\cos\theta \\
y=r\sin\theta
\end{cases}$$

>[!tip] Versori polari
>Il versore radiale $u_{r}$ è parallelo al vettore, mentre $u_{n}\perp u_{r}$ è orientato secondo la direzione della rotazione.

La velocità in coordinate polari si calcola nel seguente modo:
$$\overrightarrow{v}=\overrightarrow{r}\text{ }'(t)= \frac{d}{dt}r\overrightarrow{u_{r}}+r \frac{d\overrightarrow{u_{r}}}{dt}= \underbrace{r(t)\overrightarrow{u_{r}}}_\text{direzione radiale}+\underbrace{r\theta'(t)\overrightarrow{u_\theta}}_\text{direzione trasversale o azimutale}$$
## Moto circolare
>[!note]
>Nel moto circolare uniforme abbiamo $$\begin{cases}
r=R=\text{const} \\
\theta=\theta(t)
>\end{cases}\qquad [\theta]=\text{rad}$$
>Inoltre $s=s(t)=R\theta$

Definiamo quindi, analogamente al moto rettilineo:

>[!note] Spostamento angolare
>$$\triangle\theta=\theta(t_{2})-\theta(t_{1})=\theta_{2}-\theta_{1}$$

>[!note] Velocità angolare media
>$$<\omega>= \frac{\theta_{2}-\theta_{1}}{t_{2}-t_{1}}= \frac{\triangle\theta}{\triangle t}\qquad [\omega]= \text{rad/s}$$

>[!note] Velocità angolare istantanea
>$$w(t)=\lim_{\triangle t\to0} \frac{\triangle\theta}{\triangle t}=\theta'(t)$$

>[!note] Accelerazione angolare media
>$$<\alpha>= \frac{\omega_{2}-\omega_{1}}{t_{2}-t_{1}}=\frac{\triangle\omega}{\triangle t}\qquad [\alpha]= \text{rad/s}^{2}$$

>[!note] Accelerazione angolare istantanea
>$$\alpha(t)=\lim_{\triangle t\to0}\frac{\triangle\omega}{\triangle t}= \omega'(t)=\theta''(t)$$

In generale, tra la legge oraria in coordinate polari e la legge oraria con ascissa curvilinea
$$s=s(t)=R\omega(t)\qquad v=s'(t)=R\omega\qquad a=s''(t)=R\alpha$$

## Moto circolare uniforme
È un moto circolare con accelerazione nulla e velocità costante.
##### Rappresentazione scalare
$$\begin{cases}s=s(t)\iff s=s_{0}+ v_{0}(t-t_{0})\\\theta=\theta(t)\iff \theta=\theta_{0}+\omega(t-t_{0})\end{cases}$$
##### Rappresentazione vettoriale
- **Intrinseca**: $$\begin{cases}\overrightarrow{r}=-R\hat{u_{n}} \\
\overrightarrow{v}=v_{0}\hat{u_{t}} \\
\overrightarrow{a}= \frac{v_{0}^{2}}{R}\hat{u_{n}}\end{cases}$$
- **Polare**, Prendendo come riferimento la rappresentazione intrinseca: $$\begin{cases}
\hat{u_{r}}=-\hat{u_{n}} \\
\hat{u_{\theta}}=u_{t}
\end{cases}\Longrightarrow\begin{cases}\overrightarrow{r}=R\hat{u_{n}} \\
\overrightarrow{v}=v_{0}\hat{u_{t}} \\
\overrightarrow{a}=-\frac{v_{0}^{2}}{R}\hat{u_{n}}\end{cases}$$
- **Cartesiana**: $$\overrightarrow{r}=\overrightarrow{r}(t)\iff\begin{cases}
x=R\cos\theta \\
y=R\sin\theta
\end{cases}\quad\text{con}\quad \theta=\theta_{0}+\omega(t-t_{0})$$
nel caso particolare in cui $\theta_{0}=0$ e $t_{0}=0$:
$$\begin{cases}
x=R\cos(\omega_{0}t) \\
y=R\sin(\omega_{0}t)
\end{cases}$$
## Moto circolare uniformemente accelerato
>[!note]
>Siccome $v(t)=v_{0}+a_{0}(t-t_{0})$, $s(t)=s_{0}+v_{0}(t-t_{0})+ \frac{1}{2}a_{0}(t-t_{0})^{2}$ e supponendo di avere $$ \begin{cases}
t_{0}=0\text{ s} \\
s_{0}=0\text{ }\omega \\
v_{0}=0\text{ } \frac{\omega}{s}
\end{cases}\Longrightarrow\begin{cases}
s(t)= \frac{1}{2}a_{0}t^{2}&\text{con } s=R\theta \\
\theta(t)= \frac{1}{2} \frac{a_{0}}{R}t^{2}= \frac{1}{2}\alpha t^{2}
>\end{cases}$$
>
>Possiamo definire in posizione vettoriale intrinseca:
>$$\overrightarrow{r}= -R\overrightarrow{u_{n}}$$
>$$\overrightarrow{v}=v\overrightarrow{u_{t}}=a_{0}t\overrightarrow{u_{t}}$$
>$$\overrightarrow{a}=a_{t}\overrightarrow{u_{t}}+a_{u}\overrightarrow{u_{n}}=a_{t}\overrightarrow{u_{t}}+ \frac{v^{2}}{R}\overrightarrow{u_{n}}= a_{0}t+ \frac{at^{2}}{R}\overrightarrow{u_{n}}$$

## Grandezze angolari vettoriali in un moto circolare
>[!note]
>Possiamo descrivere un moto circolare con una grandezza vettoriale $$\overrightarrow{\omega}=\theta'(t)\overrightarrow{u_{z}}$$
>
>Questa rappresentazione ci da informazioni come il piano del moto, il verso di rotazione e la velocità angolare.
>
>Il segno di $\overrightarrow{\omega}$ dipende dal segno dello spostamento angolare $$\text{sgn}(\overrightarrow{\omega})=\text{sgn}(\triangle \theta)\Rightarrow \overrightarrow{v}=\overrightarrow{\omega}\times\overrightarrow{r}\Rightarrow |\overrightarrow{v}|= |\overrightarrow{\omega}||\overrightarrow{r}|\sin \frac{\pi}{2}=\omega R$$
>

>[!tip] Vettore accelerazione angolare
>$$\overrightarrow{\alpha}= \omega'(t)\overrightarrow{u_{z}}= \theta''(t)\overrightarrow{u_{z}}$$

