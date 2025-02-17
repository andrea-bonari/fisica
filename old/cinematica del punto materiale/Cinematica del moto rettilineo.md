>[!note]
>Un moto rettilineo è un moto che si sviluppa su una singola asse.

## Legge oraria e spostamento
>[!note]
>Nel caso del moto rettilineo sappiamo che la legge oraria sarà: $$P(t)\iff\begin{cases}x=x(t)\\y=y\\z=z\end{cases}\Rightarrow x=x(t)$$

>[!tip] Spostamento
>Considero due tempo $t_{1},t_{2}$ con $t_{1}<t_{2}$ sia $x_{1}=x(t_{1}),x_{2}=x(t_{2})$ la posizione nei due istanti di tempo, allora lo spostamento $\triangle x$ viene definito come: $$\triangle x=x_{2}-x_{1}$$
>
>Possiamo osservare che se $\triangle x>0$ allora il moto è concorde con l'asse $x$, analogamente se $\triangle x<0$ il moto è discorde con l'asse $x$. 

## Velocità media
>[!note]
>La velocità media viene definita come il rapporto fra lo spostamento e l'intervallo di tempo: $$<V>\equiv \frac{x_{2}-x_{1}}{t_{2}-t_{1}}=\frac{\triangle x}{\triangle t}\qquad [V]=\frac{[\triangle x]}{[\triangle t]}= \frac{m}{s}$$

Possiamo dedurre che se lo spostamento è positivo, allora la velocità media è positiva e viceversa, quindi:$$\text{sgn}(<V>)=\text{sgn}(\triangle x)$$
## Velocità istantanea.
>[!note]
>La velocità istantanea è il limite del rapporto incrementale spazio su tempo con l'intervallo di tempo che tende a zero: $$v(t_{1})\equiv\lim_{t_{2}\to t_{1}} \frac{x_{2}-x_{1}}{t_{2}-t_{1}}=\lim_{\triangle t\to 0}\frac{\triangle x}{\triangle t}=x'(t_{1})$$
>
>Possiamo quindi dire che per trovare la velocità istantanea in punto $t_{1}$ basta calcolare la derivata della legge oraria.

## Accelerazione media
>[!note]
>L'accelerazione media viene definita come il rapporto fra la variazione di velocità e l'intervallo di tempo:
>$$<a>\equiv\frac{v_{2}-v_{1}}{t_{2}-t_{1}}=\frac{\triangle v}{\triangle t}\qquad [a]=\frac{[\triangle v]}{[\triangle t]}= \frac{m}{s^{2}}$$
>Se l'accelerazione è positiva allora la velocità media è positiva è viceversa.
## Accelerazione istantanea
>[!note]
>L'accelerazione istantanea è il limite del rapporto incrementale velocità su tempo con l'intervallo di tempo che tende a zero: $$a(t_{1})\equiv\lim_{t_{2}\to t_{1}}\frac{v_{2}-v_{1}}{t_{2}-t_{1}}=\lim_{\triangle t\to 0}\frac{\triangle v}{\triangle t}=v'(t_{1})=x''(t_{1})$$

---
>[!example]- Esercizio
>data la legge oraria$$x=t^{3}$$
>calcolare $<v>$ tra $1s$ e $2s$, e calcolare $a(t_{0})$ con $t_{0}=1s$
>---
>$$<v>=\frac{8-1}{2-1}=7 \frac{m}{s}$$
>$$a(t)=\frac{d}{dt}\underbrace{(3t^{2})}_{v'(t)}=6t\Rightarrow a(t_{0})=6$$

>[!tip] Problema inverso
>Avendo l'accelerazione e la velocità iniziale possiamo ricavare, integrando, la derivata prima della legge oraria: $$\begin{cases}a=a(t)\\v_{0}=v(t_{0}) & \end{cases}\Rightarrow\begin{cases}v=v(t)\\x_{0}=x(t_{0})\end{cases}\Rightarrow x=x(t)$$
>
>Possiamo trovarlo usando le seguenti formule:
>$$x(t)-x(t_{0})=\int^{t}_{t_{0}}v(t)\text{ dt}\Rightarrow x(t)=x(t_{0})+\int^{t}_{t_{0}}v(t)\text{ dt}$$
>$$v(t)-v(t_{0})=\int^{t}_{t_{0}}a(t)\text{ dt}\Rightarrow v(t)=v(t_{0})+\int^{t}_{t_{0}}a(t)\text{ dt}$$

---

## Moto Rettilineo Uniformemente Accelerato (MRUA)
>[!note]
>Un corpo si muove con un moto rettilineo uniformemente accelerato quando si sposta lungo una retta con accelerazione costante.
>$$\begin{cases}\text{let } a=\text{const}\\x_{0}=x(t_{0})\\v_{0}=v(t_{0})\\\text{let }t_{0}\end{cases}$$
>$$\Rightarrow v=v_{0}+\int^{t}_{t_{0}}a\text{ dt}=v_{0}+a(t-t_{0})$$
>$$\Rightarrow x= x_{0}+\iint^{t}_{t_{0}}a\text{ dt}=x_{0}+v_{0}(t-t_{0})+ \frac{1}{2}a(t-t_{0})^{2}\text{ dt}$$
>
>Possiamo quindi dire che la legge oraria del moto rettilineo uniformemente accelerato è: $$\begin{cases}x= x_{0}+v_{0}(t-t_{0})+ \frac{1}{2}a(t-t_{0})^{2}\\ v=v_{0}+a(t-t_{0})=x'(t)\\ a= v'(t)=x''(t)\end{cases}$$

## Moto Rettilineo Uniforme (MRU)
>[!note]
>Un corpo si muove con un moto rettilineo uniforme quando si sposta lungo una retta con una velocità costante, e di conseguenza con accelerazione nulla.
>$$\begin{cases}
x=x_{0}+v_{0}(t-t_{0})\\
v=v_{0} \\
a=0
\end{cases}$$

## Moto di caduta libera
>[!note]
>Tutti i corpi lasciati liberi di cadere in prossimità della superficie terrestre cadono verticalmente con un accelerazione costante indicata con $$g=9.81 \frac{m}{s^{2}}$$
>$g$ è per definizione positiva.

## Ascissa curvilinea
Vediamo ora un metodo per rappresentare scalarmente un moto nel piano. Introduciamo un oggetto ascissa multilinea (o rappresentazione intrinseca del moto). Questo componente si comporterà esattamente come un asse. 
![[Pasted image 20240223131150.png]]
In questo modo la legge oraria diventa $$s=s(t)$$
Possiamo quindi, in modo analogo a questo capitolo andare a definire le precedenti operazioni:
- Spostamento: $$\triangle s\equiv s(t_{2})-s(t_{1})\qquad t_{2}>t_{1}$$
- Velocità media: $$<v>\equiv  \frac{s_{2}-s_{1}}{t_{2}-t_{1}}= \frac{\triangle s}{\triangle t}$$
- Velocità istantanea:$$v(t_{1})\equiv \lim_{\triangle t\to 0} \frac{\triangle s}{\triangle t}=s'(t_{1})= \frac{ds}{dt}\bigg|_{t_{1}}$$
- Accelerazione media: $$<a>\equiv  \frac{v_{2}-v_{1}}{t_{2}-t_{1}}= \frac{\triangle v}{\triangle t}$$
- Accelerazione istantanea:$$a(t_{1})\equiv \lim_{\triangle t\to 0} \frac{\triangle v}{\triangle t}=v'(t_{1})=s''(t_{1})= \frac{dv}{dt}\bigg|_{t_{1}}$$

Tuttavia questa è solo una rappresentazione intrinseca alla traiettoria, e non permette quindi di recuperare la posizione rispetto a un sistema $Oxy$. In termini analitici manca una relazione tale per cui $$\begin{cases}
s=s(t) \\
x=x(s) \\
y=y(s)
\end{cases}$$
