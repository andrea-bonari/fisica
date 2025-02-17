## Moto armonico
>[!note]
>Definiamo nell'equazione del moto armonico $x(t)=A\cos(\omega t+\varphi)$: $$\begin{align*}A&:\text{Ampiezza del moto}\\
\varphi&:\text{Fase iniziale del moto}\\
\omega&:\text{Pulsazione}\\
(\omega t+\varphi)&:\text{Fase del moto}\end{align*}$$
>Aggiungiamo inoltre le condizioni: $$\begin{cases}
x=A\cos(\omega t+ \varphi) \\
x(0)=x_{0} \\
v(0)=0
\end{cases}$$
>E ricaviamo $\varphi=0$ e $x_{0}=A$, e infine:
>$$x=x_{0}\cos(\omega t)$$ 
>
>Questa legge oraria è periodica nel tempo: $$\exists T:\qquad x(t+T)=x(t)$$
>Ricaviamo quindi che il periodo del moto è uguale a $$T= \frac{2\pi}{\omega}$$
>
>Definiamo come frequenza: $$f\equiv \frac{1}{T}\qquad [f]=\text{Hz}$$

Ricaviamo al velocità e l'accelerazione:
$$v=-\omega x_{0}\sin(\omega t)\qquad a=-\omega^{2}x_{0}\cos(\omega t)$$

>[!tip]
>$\begin{cases}
>v(t)&\text{ e }&x(t) \\
>a(t)&\text{ e }&v(t) \\
>\end{cases}$ sono in quadratura di fase, cioè sono sfasate di $\frac{\pi}{2}$.
>Infatti $a(t)$ e $x(t)$ sono in opponenza di fase.

## Moto circolare uniforme
>[!note]
>Esistono 3 tipologie di casi reali:
>1. Moto di un corpo vincolato ad una fune (tensione fune)
>2. Moto di un corpo lungo binari circolare (reazione vincolare)
>3. Moto circolare di un auto (attrito statico)
>
>Non esiste Moto Circolare Uniforme senza una forza centripeta $F_{N}\neq 0$
>Vale la formula $$\overrightarrow{a}=a_{n}\hat{u_{n}}= \frac{v_{0}^{2}}{R}\hat{u_{n}}$$

## Moto del pendolo
>[!note]
>Definiamo la legge oraria del moto del pendolo come $$\theta=\theta(t)$$
>Dalle forze presenti nell'immagine ricaviamo la formula $$\overrightarrow{T}+m\overrightarrow{g}=m\overrightarrow{a}$$
>La proiettiamo: $$\begin{align}\hat{u_{n}}\\\hat{u_{t}}\end{align}\begin{cases}T-m\overrightarrow{g}\cos\theta&=ma_{n} \\
-mg\sin\theta&=ma_{t}\end{cases}$$
>E dall'accelerazione tangenziale ricaviamo $$-g\sin\theta=L\alpha=L\theta''$$
>Supponiamo di avere $\theta<<1$ e quindi $\sin\theta\sim\theta$:
>$$-g\theta=L\theta''$$
>Questa equazione differenziale è formalmente uguale a quella del moto armonico, e quindi:
>$$\theta''+\omega^{2}_{P}\theta=0\qquad \omega_{P}=\sqrt{\frac{g}{L}}$$
>Questa è sempre un equazione del moto armonico, analogamente quindi al moto armonico ricaviamo la legge oraria $$\theta=\theta_{0}\cos(\omega_{P}t)$$

>[!tip]
>Analogamente al moto armonico, la velocità angolare e accelerazione saranno: $$\omega=-\omega\theta_{0}\sin(\omega_{P}t)\qquad \alpha=-\omega^{2}\theta_{0}\cos (\omega_{P}t)$$ 

Analogamente, possiamo ricavare la tensione variante nel tempo proiettando su $u_{t}$:
	$$T=m\overrightarrow{g}\cos\theta+ma_{n}=m\overrightarrow{g}\cos\theta+m\theta''$$

Andiamo a studiare i casi limite della tensione:
- $t=0\Rightarrow\begin{cases}\theta=\theta_{0}\\ \theta'=0\end{cases}$: tensione minima$$T=mg\cos\theta_{0}$$
- $t= \frac{T}{4}\Rightarrow\begin{cases}\theta=0\\\omega=-\theta_{0}\omega_{P}\end{cases}$: tensione massima $$T=m\overrightarrow{\theta}+m\omega^{2}L$$

