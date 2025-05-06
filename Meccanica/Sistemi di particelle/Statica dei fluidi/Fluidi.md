>[!note]
>I fluidi sono corpi che non hanno forma propria, rientrano quindi in questa categorizzazioni i liquidi e gli aeriformi. Definiamo un liquido perfetto come un fluido incomprimibile, indilatabile e non viscoso.

### Forze di volume
>[!note]
>Consideriamo una porzione di fluido, avente volume $V$ e superficie $S$. Si distinguono le forze agenti su questa porzione di fluido in:
>- Forze di volume: forze con azione a distanza o forze apparenti. Esse agiscono su ogni punto del fluido in virtù del fatto che ha una massa, una carica elettrica o un altra proprietà fisica
>- Forze di superficie: forze di contatto, esercitate sulla porzione di fluido in esame attraverso la superficie che la racchiude. Possono essere esercitate dalla parete di un recipiente piuttosto che da un altro tipo di diaframma fisico, oppure dalle porzioni stesse di fluido circostanti.

### Pressione e sforzo di taglio
>[!note]
>Consideriamo una parte di superficie infinitesima $\text{d}S$, definiamo un versore normale uscente $\hat{u}_{n}$, e consideriamo la risultante delle forze applicate, allora: 
>$$\text{d}\overrightarrow{F}_\text{ris}=\text{d}\overrightarrow{F}_{n}\hat{u}_{n}+\text{d}\overrightarrow{F}_{t}\hat{u}_{t}$$
>Definiamo la pressione come: $$p=\lim_{S\to0} \frac{F_{n}}{S}= \frac{\text{d}F_{n}}{\text{d}S}\qquad [p]=\text{Pa}$$
>Definiamo lo sforzo di taglio come: $$\overrightarrow{T}=\lim_{S\to0} \frac{F_{t}}{S}\hat{u}_{t}= \frac{\text{d}F_{t}}{\text{d}S}\hat{u}_{t}\qquad [\overrightarrow{T}]=\text{Pa}$$

Si ha che gli sforzi di taglio sono nulli se:
- Il fluido è in condizione statiche
- Il fluido è non viscoso

>[!tip] Unità di misura della pressione
>Alcune unità di misura della pressione oltre al pascal sono: $$\begin{align*}
&1\text{ bar}=10^{5}\text{ Pa}\\
&1\text{ atm}=101325\text{ Pa}= 1.01325\text{ bar}\\
&1\text{ mmHg}=1\text{ torr}= \frac{1}{760}\text{ atm}\simeq 133.3\text{ Pa}
\end{align*}$$

### Teorema di isotropia della pressione
>[!note]
>Si ha che la pressione è identica su ogni faccia della superficie di un fluido, e non dipende dall'orientazione presa. La pressione può essere considerata una funzione della sola posizione, cioè una proprietà di ciascun punto del fluido.

>[!example] Dimostrazione
>Consideriamo, all'interno di un fluido in equilibrio, un volumetto prismatico:
>![[Pasted image 20250429230445.png|center]]
>Supponiamo che la base sia quadrata di lato $L$ e di altezza pari a $L\tan\alpha$. Il volume sarebbe: $$V= \frac{L\cdot L\cdot L\tan\alpha}{2}\propto L^{3}$$
>Mentre la superficie sarebbe $S_\text{tot}\propto L^{2}$. Per $L\to0$, allora $V$ è infinitesimo di ordine superiore rispetto ad $S$. Possiamo quindi trascurare le forze di volume, e consideriamo solo le forze di superficie.
>
>Consideriamo che il prisma è in equilibrio meccanico, e quindi: $$\overrightarrow{F}_\text{ris}= \overrightarrow{F}_{x}+\overrightarrow{F}_{y}+\overrightarrow{F}=0$$
>Lungo $x$ abbiamo che $F_{x}+\overrightarrow{F}\cdot\hat{u}_{x}=0$, e quindi $F_{x}=F\sin\alpha$, analogamente, lungo $y$ si ha $F_{y}=F\cos\alpha$. Sempre analogamente, $S_{x}=S\sin\alpha$ e $S_{y}= S\cos\alpha$. Calcolando quindi le pressioni sulle tre facce: $$p= \frac{F}{S}\qquad p_{x}= \frac{F_{x}}{S_{x}}= \frac{F\sin\alpha}{S\sin\alpha}= p\qquad p_{y}= \frac{F_{y}}{S_{y}}= \frac{F\cos\alpha}{S\cos\alpha}=p$$
>È quindi dimostrato che la pressione è identica sulle facce del prisma e non dipende dall'orientazione della superficie presa.
