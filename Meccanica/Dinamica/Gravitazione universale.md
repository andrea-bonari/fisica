>[!note]
>Siamo due oggetti puntiformi di massa $M$ e $m$ posti ad una distanza $r$. Su questi corpi si esercita una forza centrale: $$\overrightarrow{F}_{g}=-G \frac{Mm}{r^{2}}\hat{u}_{r}$$
>Con $G=6.67\cdot 10^{-11} \frac{\text{N}\cdot\text{m}^{2}}{\text{Kg}^{2}}$ costante di gravitazione universale, e versore $\hat{u}_{r}$ rivolto dalla massa $m$ a $M$, o viceversa.
>![[Pasted image 20250324142157.png|center]]

>[!tip] Forza centrale
>Definiamo come forza centrale una forza $\overrightarrow{F}$ conservativa rivolta sempre verso un punto fisso $O$ il cui modulo dipende solo dalla distanza: $$\overrightarrow{F}=-f(r)\hat{u}_{r}$$
>Si ha che il momento di una forza centrale è sempre nullo rispetto ad $O$. Inoltre la sua velocità areorale è costante.

La forza peso non è altro che la forza gravitazionale: $$\overrightarrow{F}_{g}= G \frac{M_{T}m}{r^{2}}\hat{u}_{n}= G \frac{M_{T}m}{(R_{T}+h)^{2}}\hat{u}_{n}= m\overrightarrow{g}\qquad l<< r\simeq 6400\text{ Km}$$
Riguardo l'energia potenziale si ha che: $$L_{\overrightarrow{F}_{g}}^{AB}= \left(-G \frac{Mm}{r_{A}}\right)-\left(- G \frac{Mm}{r_{B}}\right)=U_{g}(A)-U_{g}(B)$$
### Leggi di Keplero
>[!note]
>Le leggi di Keplero affermano che:
>1. I pianeti compiono orbite ellittiche attorno al sole con esso uno dei due fuochi.
>2. Il raggio vettore che collega il sole al pianeta spazza aree uguali in tempi uguali (velocità areorale costante).
>3. Il quadrato dei periodi di rivoluzione è proporzionale al cubo del semiasse maggiore dell'ellisse ($T^{2}=kR^{3}$).

### Moto orbitale
>[!note]
>Assegniamo a un punto materiale $P$ in orbita momento angolare $\overrightarrow{L}$ e energia meccanica $E_\text{mecc}$ costante. Si ha che se l'energia meccanica è positiva, avrà una traiettoria iperbolica, se l'energia meccanica è nulla avrà una traiettoria parabolica, e se è negativa avrà traiettoria ellittica. Inoltre se $E_\text{mecc}$ è pari al valore di energia potenziale efficace minima $U_{\text{eff}}= \frac{L^{2}}{2mr^{2}}- G \frac{Mm}{r}$ avrà traiettoria circolare.

>[!example] Dimostrazione
>Sia per ipotesi il momento angolare $\overrightarrow{L}$ costante: $$\overrightarrow{L}=\overrightarrow{r}\times\overrightarrow{p}= rp_{\perp}\hat{u}_{z}$$
>Che in coordinate polari è: $$\overrightarrow{L}=\overrightarrow{r}\times(r'\hat{u}_{r}+r\theta'\hat{u}_{\theta})=mr^{2}\theta'\hat{u}_{z}$$
>Studiamo il moto al variare dell'energia meccanica $E$: $$\begin{align*}
>E&=  \frac{1}{2}mv^{2}- G \frac{Mm}{r}= \underbrace{\frac{1}{2}mr'^{2}}_{E_{k,r}}+ \underbrace{\frac{1}{2}mr^{2}\theta'^{2}}_{E_{k,t}}- G \frac{Mm}{r}
>\end{align*}$$
>Abbiamo che: $$E_{k,t}= \frac{1}{2}mr^{2}\theta'^{2}\cdot \frac{r^{2}}{r^{2}}\cdot \frac{m}{m}= \frac{L^{2}}{2mr^{2}}$$
>E quindi: $$E= \frac{1}{2}mr'^{2}+ \frac{L^{2}}{2mr^{2}}-G \frac{Mm}{r}$$
>Definiamo un energia potenziale efficace: $$U_{\text{eff}}= \frac{L^{2}}{2mr^{2}}- G \frac{Mm}{r}\Longrightarrow E= \frac{1}{2}mr'^{2}+ U_{\text{eff}}(r)$$
>Consideriamo il caso in cui $E>0$, abbiamo che $r\geq r_{\min}$ e $E_{k,r}(r_{\min})=0$, e quindi $P$ può raggiungere $r\to\infty$ seguendo come traiettoria un iperbole.
>Consideriamo il caso in cui $E=0$, abbiamo che $r\geq r_{a}$, e $P$ può raggiungere $r\to\infty$ seguendo come traiettoria una parabola.
>Consideriamo il caso in cui $E<0$, abbiamo che $r_{c}\leq r<< r_{d}$ e $P$ ha quindi ha una traiettoria ellittica con punto $c$ perielio e $d$ afelio.
>Infine, consideriamo il caso in cui $E=U_{\text{eff},\min}$ per cui la traiettoria è una circonferenza.
