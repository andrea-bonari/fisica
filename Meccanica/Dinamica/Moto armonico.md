>[!note]
>Un moto armonico è un moto periodico con periodo $T$ di equazione: $$x(t)=A\cos(\omega t+\varphi)$$
>Dove $A$ è detta ampiezza, $\omega$ è detta pulsazione e $\varphi$ è detta fase iniziale.
>Il periodo di oscillazione $T$ è definito come: $$T= \frac{2\pi}{\omega}$$
>La frequenza dell'oscillazione è definito come: $$f= \frac{1}{T}\qquad [f]=\text{Hz}$$

>[!tip]
>Il valore del periodo $T$ aumenta al crescere di $m$ e al decrescere di $k$.

È possibile ricavare i valori di $A$ e $\varphi$ imponendo le condizioni: $$\begin{cases}
x(0)=x_{0} \\
v(0)=0
\end{cases}$$
>[!tip]
>In un moto armonico si ha che: $$\begin{cases}
>x(t)=A\cos(\omega t+\varphi) \\
>v(t)=-\omega A\sin(\omega t+\varphi) \\
>a(t)=-\omega^{2}A\cos(\omega t+\varphi)
>\end{cases}$$
>Si ha che tra le tre equazioni, si ha una quadratura di fase, e quindi sono sfasate di $\frac{\pi}{2}$.

### Moto del pendolo
>[!note]
>Definiamo un pendolo come una massa $m$ vincolata ad una fune di massa $L$. Definiamo la legge oraria rispetto l'angolo come: $$\theta=\theta(t)$$
>![[Pasted image 20250310161609.png|center]]
>Si ha che la legge oraria del moto è: $$\theta(t)=\theta_{0}\cos(\omega_{P}t)\qquad \omega_{P}=\sqrt{ \frac{g}{L}}$$
>Con periodo: $$T= 2\pi\sqrt{\frac{L}{g}}$$

>[!example] Dimostrazione
>Come condizione iniziale del moto si ha che: $$\begin{cases}
>\theta(0)=\theta_{0} \\
>\theta'(0)=0
>\end{cases}$$
>Si ha una forza peso $m\overrightarrow{g}$ e una tensione della fune $T$. Si ha quindi, che l'equazione del moto, proiettata sulla base intrinseca è: $$\overrightarrow{T}+m\overrightarrow{g}=m\overrightarrow{a}\Longrightarrow\begin{cases}
>ma_{n}=||\overrightarrow{T}||-m||\overrightarrow{g}||\cos\theta \\
>ma_{t}=-m||\overrightarrow{g}||\sin\theta
>\end{cases}$$
>Dall'equazione del moto tangenziale: $$\begin{align*}
>&ma_{t}= -m g\sin\theta&\Longrightarrow\\ &-g\sin\theta=L\alpha&\Longrightarrow\\ &-g\sin\theta=L\theta'' 
>\end{align*}$$
>Che è un equazione differenziale. Per l'ipotesi di piccola oscillazione, se $\theta<<1$, allora $\sin\theta\simeq\theta$. Allora: $$-g\theta=L\theta''$$
>Questa equazione è l'equazione di un moto armonico: $$\theta''+\omega^{2}_{P}\theta=0\qquad \omega_{P}=\sqrt{ \frac{g}{L}}$$
