>[!note]
>Si ha che: $$\overrightarrow{L}=I_{z}\overrightarrow{\omega}\underbrace{-\omega\sum\limits_{i}m_{i} d_{i}\hat{u}_{d}}_{\overrightarrow{L}_{\perp}}$$
>Con $I_{z}=\sum\limits_{i}m_{i}d_{i}^{2}$ detto momento di inerzia assiale.

>[!example] Dimostrazione
>![[Pasted image 20250415174251.png]]
>Consideriamo un generico punto di massa $m_{i}$ con distanza $d_{i}$ dall'asse $z$. Siccome sta compiendo un moto circolare, e la velocità è tangente alla circonferenza, si ha che: $$\overrightarrow{v}_{i}=v\cdot \hat{u}_{t}=\omega d_{i}\hat{u}_{t}$$
>Scegliendo un generico punto da origine, e l'angolo formato $\beta$ tra l'asse $z$ e il vettore posizione, si ha che: $$\overrightarrow{v}_{i}=\omega r_{i}\sin\beta\hat{u}_{t}=\overrightarrow{\omega}\times\overrightarrow{r}_{i}$$
>Si ha che il momento angolare del corpo rigido è pari a: $$\overrightarrow{L}=\sum\limits_{i}\overrightarrow{r}_{i}\times m_{i}\overrightarrow{v}_{i}$$
>Definiamo la posizione come: $$\overrightarrow{r}_{i}=z_{i}\hat{u}_{z}+d_{i}\hat{u}_{d}$$
>E quindi: $$\begin{align*}
>\overrightarrow{L}&= \sum\limits_{i}m_{i}\left(\left(z_{i}\hat{u}_{t}+d_{i}\hat{u}_{d}\right)\times \omega d_{i}\hat{u}_{t}\right)=\sum\limits_{i}m_{i}(z_{i}\omega d_{i}(- \hat{u}_{d})+\omega d_{i}^{2}\hat{u}_{t})\\
>&=\underbrace{-\sum\limits_{i}\omega m_{i}d_{i}\hat{u}_{d}}_{\overrightarrow{L}_{\perp}}+\underbrace{\sum\limits_{i}\omega m_{i}d_{i}^{2}\hat{u}_{z}}_{\overrightarrow{L}_{z}}
>\end{align*}$$
>Più nel dettaglio: $$\overrightarrow{L}_{z}=\underbrace{\omega\hat{u}_{z}}_{\overrightarrow{\omega}}\cdot \underbrace{\left(\sum\limits_{i}m_{i}d_{i}^{2}\right)}_{\text{momento di inerzia assiale }I_{z}}=I_{z}\cdot\overrightarrow{\omega}$$

### Teorema di Poinsot
>[!note]
>Dato un punto $O$ arbitrario e un corpo rigido, esistono almeno 3 assi passanti per $O$ per cui il momento $\overrightarrow{L}_{\perp}$ è nullo. Questi si dicono assi di inerzia, e se il polo $O$ coincide con il centro di massa, si dicono assi centrali di inerzia.

### Conservazione del momento angolare
>[!note]
>Si ha che il momento angolare, in due generici istanti di tempo $t_{1}$ e $t_{2}$, si conserva: $$I_{1}\omega_{1}=I_{2}\omega_{2}$$

>[!example] Dimostrazione
>Dalla seconda equazione cardinale della dinamica, si ha: $$\overrightarrow{M}^{E}= \frac{\text{d}\overrightarrow{L}_{z}}{\text{d}t}+ \frac{\text{d}\overrightarrow{L}_{\perp}}{\text{d}t}$$
>Scomponiamo quindi: $$\overrightarrow{M}^{E}= M^{E}_{z}\hat{u}_{z}+M^{E}_{\perp}\hat{u}_{\perp}$$
>Per quanto riguarda a $\overrightarrow{M}^{E}_{z}$: $$M^{E}_{z}= \frac{\text{d}L_{z}}{\text{d}t}= \frac{\text{d}(I_{z}\omega)}{\text{d}t}=I_{z} \frac{\text{d}\omega}{\text{d}t}= I_{z}\alpha$$
>Dove $\alpha$ è l'accelerazione angolare, quindi se $\overrightarrow{M}^{E}_{z}$ il corpo resta in quiete oppure ruota con $\omega$ costante.
>Ricaviamo: $\omega$ e $\theta$: $$\alpha(t)= \frac{M^{E}(t)}{I}\space\Longrightarrow\space \omega(t)= \omega_{0}+\int_{0}^{t} \alpha \text{ d}t\space\Longrightarrow\space \theta(t)=\theta_{0}+\int_{0}^{t}\omega \text{ d}t$$
>Osserviamo che se $\alpha$ è costante, allora valgono le relazioni del MRUA.
>

### Teorema dell'energia cinetica e potenza
>[!note]
>Si ha che l'energia cinetica di un corpo rigido in moto rotatorio puro ad asse fisso è pari a: $$E_{k}=\frac{1}{2} I_{z} \omega^{2}$$
>Inoltre, definiamo la potenza come: $$P= \frac{\text{d}L^{E}}{\text{d}t}= \overrightarrow{M}^{E}\cdot \overrightarrow{\omega}$$

>[!example] Dimostrazione
>Si ha che: $$E_{k}=\sum\limits_{i} \frac{1}{2}m_{i}v_{i}^{2}$$
>Per un moto rotatorio puro ad asse fisso, $v_{i}^{2}=|\overrightarrow{\omega}\times \overrightarrow{r}_{i}|^{2}=\omega^{2}d_{i}^{2}$, e quindi: $$E_{k}=\sum\limits_{i} \frac{1}{2}m_{i}d_{i}^{2}\omega^{2}= \frac{1}{2}I_{z} \omega^{2}$$
>Quindi, la variazione di energia cinetica totale: $$L^{E}= \Delta E_{k}= \frac{1}{2}I_{z}\omega^{2}_{A}- \frac{1}{2} I_{z} \omega^{2}_{B}$$
>Calcolando la stessa quantità per una variazione infinitesima, si ha che: $$\partial L^{E}= \text{d}E_{k}= I_{z}\omega \text{ d}\omega= I_{z} \omega \alpha \text{ d}t= I_{z} \alpha \text{ d}\theta= M^{E}_{z} \text{ d}\theta$$
>Questo perché $\text{d} \omega= \alpha \text{ d}t$, $\text{d}\omega= \theta \text{ d}t$ e $M^{E}_{z}= I_{z} \alpha$.
>Infine definiamo la potenza come: $$P= \frac{\text{d}L^{E}}{\text{d}t}= \frac{\text{d}L^{E}}{\text{d}\theta}\cdot \frac{\text{d}\theta}{\text{d}t}=\overrightarrow{M}^{E}\cdot \overrightarrow{\omega}$$
>

### Calcolo del momento di inerzia
>[!note]
>Si ha che, per un solido omogeneo di densità uniforme, il momento di inerzia è calcolato come: $$I= M\cdot \frac{\int d^{2}\text{ d}V}{V}$$
>Siccome è definito tramite sommatorie e integrali, il momento di inerzia è additivo.

>[!example] Dimostrazione
>Si ha che, per un solido omogeneo di densità $\rho$ uniforme, l'elemento di massa $\text{d}m$ all'interno dell'integrale si può scrivere come $\text{d}m=\rho \text{ d}V$. da cui: $$I= \int d^{2}\text{ d}m=\int d^{2}\rho \text{ d}V= \rho\int d^{2}\text{ d} V= M \cdot \frac{\int d^{2} \text{ d}V}{V}$$

### Teorema di Huygens-Steiner
>[!note]
>Il momento di inerzia di un corpo rigido di massa $m$, rispetto ad un asse $z$ posta a distanza $D$ dal centro di massa, è dato da: $$I_{z}= I_{CM}+ mD^{2}$$
>Dove $I_{CM}$ è il momento di inerzia calcolato per un asse parallelo a $z$ e passante per il centro di massa.

>[!example] Dimostrazione
>Sia $z$ l'asse rispetto al quale vogliamo calcolare $I$, e sia $z'$ l'asse parallelo a $z$ passante per il centro di massa. Definiamo due sistemi di coordinate cartesiane con $y\equiv y'$ in modo che intersechino sia $z$ sia $z'$:
>![[Pasted image 20250416131212.png|center]]
>I quadrati della distanza $d$ di un punto $P$ qualsiasi di massa $\text{d}m$ dall'asse $z$ e della distanza $d'$ dello stesso punto dall'asse $z'$ sono dati da: $$\begin{align*}
>d^{2}&= x^{2}+y^{2}\\
>d'^{2}&= x'^{2}+y'^{2}
>\end{align*}$$
>Dalla costruzione geometrica in figura è semplice ricavare che $x=x'$ e $y=y'+D$:
>$$\begin{align*}
>d^{2}&= x^{2}+y^{2}=x'^{2}+(y'+D)^{2}=x'^{2}+y'^{2}+2Dy'+D^{2}\\
>&= d'^{2}+2Dy'+D^{2}
>\end{align*}$$
>Scrivendo ora il momento di inerzia relativo all'asse $z$ otteniamo: $$I= \int d^{2} \text{ d}m= \underbrace{\int d'^{2} \text{ d}m}_{I_{CM}}+\underbrace{\int 2Dy' \text{ d}m}_{0}+\underbrace{\int D^{2}\text{ d}m}_{MD^{2}}$$
