### Forza peso
>[!note]
>La forza peso è la forza esercitata dalla terra sui corpi posti in prossimità della superficie terrestre: $$\overrightarrow{F_{P}}=m\cdot \overrightarrow{g}$$

questo perché $\overrightarrow{a}=\overrightarrow{g}$.

>[!tip] Bilancia
>La bilancia è un dinamometro che misura il peso, infatti usa come unità di misura della forza $K_{gp}=9.81\text{ N}$, e restituisce di conseguenza la massa in $K_{gp}$

>[!tip] Forza gravitazionale sulla luna
>La forza gravitazionale sulla superficie lunare equivale a circa $\frac{1}{6}$ di quella terrestre: $$g_{L}=\approx \frac{1}{6}g$$
### Reazione vincolare
>[!note]
>La forza esercitata su un oggetto da un altro oggetto a contatto in direzione perpendicolare alla superficie di contatto è detta reazione vincolare.
>$$\overrightarrow{N}$$
>
>In un piano perpendicolare abbiamo che $\overrightarrow{N}=-\overrightarrow{F_{P}}$, essendo che il moto in quiete non è soggetto ad accelerazione:
>$$\overrightarrow{a}=0\iff \overrightarrow{F}=0\iff \overrightarrow{N}+\overrightarrow{F_{P}}=0\iff \overrightarrow{N}=-\overrightarrow{F_{P}}$$

### Forza di attrito statico
>[!note]
>La forza di attrito statico è la forza esercitata su un oggetto da un altro oggetto a contatto in direzione parallela alla superficie di contatto: $$0\leq F_{AS}< F_AS_{max}=\mu_{s}N$$Dove $\mu_{s}<1$ è il coefficiente di attrito statico.

>[!tip]
>$\mu_{s}$ dipende solo dalla natura della superficie di contatto e non dall'area di contatto.

### Forza di attrito dinamico
>[!note]
>La forza di attrito dinamico è la forza esercitata su un oggetto da un altro oggetto a contatto in direzione parallela alla superficie di contatto, e di verso opposto alla velocità, quando i due corpi sono in uno stato di moto relativo: $$F_{AD}=\mu_{d}N$$
>Dove $\mu_{d}<1$ è il coefficiente di attrito dinamico.
>Il coefficiente $\mu_{d}$ è sempre leggermente minore di $\mu_{s}$ ed è il coefficiente caratteristico delle due superfici di contatto: $$\mu_{d}<\mu_{s}<1$$

### Tensione
>[!note]
>La tensione è la forza esercitata da una fune. Bisogna ricordare che agisce sempre in direzione parallela alla fune ed è una forza di trazione. Attraverso una fune è possibile trasmettere della forza da un punto all'altro.
>![[Pasted image 20240305130032.png]]

Durante lo svolgimento di esercizi assumeremo che:

##### Massa della fune trascurabile
In questo modo possiamo assumere il sistema come un unico oggetto la cui massa è la somma delle singole masse soggette alla forza: $$M_\text{tot}=M+m_\text{filo}+m\qquad m_\text{filo}=0\Longrightarrow M_\text{tot}=M+m$$
##### Fune inestendibile (non elastica)
La fune funge da trasmettitore di forza e $M,m_\text{filo},m$ subiranno la stessa accelerazione $\overrightarrow{a}$ in quanto unite. Quindi lo spostamento del punto $A$ sarà uguale allo spostamento del punto $B$: $$\triangle s_{A}=\triangle s_{B}$$
##### Fune liscia
Assumeremo che quando un filo scorre non è soggetto a forza di attrito per rendere più facili gli esercizi.

---

Fatte le seguenti ipotesi possiamo dire che $$\overrightarrow{F}= \frac{M+m}{M}\overrightarrow{T}\iff \overrightarrow{T}= \frac{M}{M+m}\overrightarrow{F}$$
>[!tip]
>La tensione è nulla se la massa grande tende a zero, mentre coincide con la forza $F\sim F$ quando la massa grande è molto maggiore della massa piccola $M>>m$

### Forza elastica
>[!note]
>La forza elastica è la forza esercitata da una molla vincolata a un punto fisso per tornare in posizione di riposo. Identifichiamo con il punto $O$ l'estremo della molla quando a riposo. Se noi indichiamo con $x$ l'ascissa del punto libero allora: $$\overrightarrow{F_{e}}=-kx\overrightarrow{u_{x}}\qquad [K]= \frac{[F]}{[X]}= \frac{N}{m}$$
>![[Pasted image 20240305130616.png]]
>$k$ è la costante elastica della molla e dipende dalla rigità e forza della molla.

Abbiamo che l'accorciamento/allungamento rispetto alla posizione di riposo è direttamente proporzionale alla forza esercitata dalla molla.

Possiamo notare che in un sistema massa molla come nell'immagine, avremo proiettato su $u_{x}$: $$-kx=ma$$
Solo che $x$ e $a$ dipendono entrambi dal tempo, e formano quindi un equazione differenziale:
$$-kx(t)=mx''(t)$$
Che avrà come soluzione $$x(t)=A\cos(\omega t+\varphi)\qquad \text{con }\omega^{2}= \frac{k}{m}$$
Questa equazione è detta equazione del moto armonico. Le due costanti $A$ e $\varphi$ si possono ricavare imponendo le condizioni $$\begin{cases}
x(0)=x_{0} \\
v(0)=0
\end{cases}$$
