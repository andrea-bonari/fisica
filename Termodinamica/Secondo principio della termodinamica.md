>[!note]
>Il primo principio della termodinamica afferma l'equivalenza tra calore e lavoro, ma nella pratica la trasformazione di calore in lavoro è difficile e non completamente efficiente. Per chiarire questi limiti nasce il secondo principio della termodinamica, che introduce un vincolo fondamentale. Secondo Kelvin-Plank è impossibile realizzare una trasformazione termodinamica ciclica che produca lavoro netto positivo estraendo calore da un unico termostato.


Si parla di un ciclo termodinamico, dove il sistema ritorna allo stato iniziale, quindi si ha $\Delta U=0$, inoltre abbiamo lavoro netto positivo quindi $L>0$. Ricordiamo infine che si ha un solo termostato. Dal punto di vista matematico, in un ciclo monoterma si ha: $$Q=L\leq 0$$
Dove se il ciclo è reversibile $Q=L=0$, mentre se non lo è $Q=L<0$.

Da questo principio possiamo ricavare che, per ottenere lavoro utile da una macchina termica è necessario operare tra due sorgenti di calore a temperature diverse. Inoltre le trasformazioni reali sono irreversibili a causa della presenza inevitabile di processi dissipativi.

Il secondo principio introduce una direzionalità nei fenomeni termici, come la propagazione del calore da corpi caldi a freddi.

### Enunciato di Clausius
>[!note]
>È impossibile realizzare una trasformazione termodinamica che produca come unico risultato il passaggio di calore da una sorgente a temperatura più fredda a una sorgente a temperatura più calda.

Come nel precedente enunciato riguarda trasformazioni in cui $\Delta U=0$, e dove $L=0$, e quindi: $$Q=L+\Delta U=0$$
Il trasferimento di calore da freddo a caldo non può avvenire spontaneamente, richiede apporto di lavoro, viceversa il flusso da caldo a freddo avviene naturalmente e senza lavoro esterno.

I due enunciati sono logicamente equivalenti, la negazione dell'uno implica la negazione dell'altro, e se si accetta uno dei due come assioma, l'altro si può dedurre come teorema.

>[!example] Dimostrazione
>Supponiamo che non valga l'enunciato di Kelvin-Planck, esiste una macchina termica ciclica $M$ che produce lavoro da un solo termostato a temperatura $T_{2}$. Essa in un ciclo estrae una quantità di calore $Q_{2}$ dal termostato e lo trasforma in lavoro $L_{M}=Q_{2}>0$.
>
>Affianchiamo a questa macchina termica una macchina frigorifera $F$, ad esempio un frigorifero di Carnot, che in ogni ciclo assorbe un lavoro $L_{F}=-L_{M}<0$ e trasferisce calore da un ulteriore termostato a temperatura $T_{1}<T_{2}$ al termostato $T_{2}$. Se essa estrae in un ciclo una quantità di calore $Q_{1}>0$ dalla sorgente a temperatura $T_{1}$, cederà alla sorgente di temperatura $T_{2}$ una quantità di calore $-Q_{1}-L_{M}=-Q_{1}-Q_{2}$.
>
>Facciamo funzionare entrambe le macchine assieme, in modo che svolgano un ciclo nello stesso tempo, e consideriamole come se fossero un unica macchina $F'$. Questa macchina complessiva non assorbe lavoro $L_{F'}=0$ e trasferisce una quantità di calore $Q_{1}$ dalla sorgente a temperatura $T_{1}$ alla sorgente $T_{2}>T_{1}$. In pratica, abbiamo costruito una macchina frigorifera che nega l'enunciato di Clausius. È quindi dimostrato che se non vale l'enunciato di Kelvin-Plank, non può valere neppure l'enunciato di Clausius.

### Teorema di Carnot
>[!note]
>Si ha che tutte le macchine termiche reversibili che lavorano tra gli stessi due termostati hanno lo stesso rendimento. Il rendimento di una macchina termica reversibile non può superare quello di una macchina reversibile di Carnot che lavora tra quelle stesse sorgenti. Questo teorema è sintetizzabile nella formula: $$\eta_{M}\leq\eta_{C}=1- \frac{T_{1}}{T_{2}}$$

>[!example] Dimostrazione
>Consideriamo due macchine termiche, $M$ e $C$, che lavorano tra gli stessi due termostati a temperature $T_{1}$ e $T_{2}$ con $T_{2}>T_{1}$. $M$ è una macchina generica, di cui non si conosce se sia reversibile o irreversibile, mentre $C$ è una macchina reversibile di Carnot. Dimensioniamo la macchina di Carnot in modo che in un ciclo assorba dalla sorgente a temperatura $T_{2}$ la stessa quantità di calore $Q_{2}$ che è assorbita, sempre in un ciclo, dalla macchina $M$.
>
>La macchina $M$, in un ciclo produce un lavoro $L_{M}>0$ e cede alla sorgente a temperatura $T_{1}$ una quantità di calore $Q_{1,M}=-Q_{2}+L_{M}<0$. Il suo rendimento è: $$\eta_{M}= \frac{L_{M}}{Q_{2}}$$
>La macchina $C$ in un ciclo produce lavoro $L_{C}>0$ e cede alla sorgente a temperatura $T_{1}$ una quantità di calore $Q_{1,C}=-Q_{2}+L_{C}<0$. Il suo rendimento è: $$\eta_{C}= \frac{L_{C}}{Q_{2}}$$
>Invertiamo ora il funzionamento della macchina $C$, facendola diventare una macchina frigorifera $\bar{C}$. Essendo $C$ reversibile, invertendone il funzionamento tutte le quantità di calore e lavoro scambiato in un ciclo semplicemente sbagliano segno. In un ciclo, perciò, sarà sempre ceduta alla sorgente a temperatura $T_{2}$ una quantità di calore $-Q_{2}$, e assorbita dalla sorgente a temperatura $T_{1}$ con una quantità di calore $Q_{1,\bar{C}}=-Q_{1,C}$. Il lavoro esercitato dall'esterno su $\bar{C}$ sarà $L_{\bar{C}}=-L_{C}$.
>
>Consideriamo adesso $M$ e $\bar{C}$ come un'unica macchina termodinamica. Il lavoro netto prodotto da questa macchina è $L'=L_{\bar{C}}+L_{M}=L_{M}-L_{C}$, ma il calore netto scambiato con la sorgente $T_{2}$ è a questo punto nullo. La macchina complessiva è dunque una macchina monoterma e il Secondo Principio impone che $L'\leq0$. Allora si ha $L_{M}\leq L_{C}$, e dividendo questa disuguaglianza per $Q_{2}$ e tenendo presente le espressioni dei rendimenti delle due macchine si ottiene direttamente: $$\eta_{M}\leq \eta_{C}$$
>Consideriamo infine due macchine termiche reversibili diverse $C_{1}$ e $C_{2}$ e ripetiamo il ragionamento fatto nei passaggi precedenti, prima considerando $C_{1}$ come incognita e $C_{2}$ come reversibile e poi viceversa. Otterremo dapprima $\eta_{C_{1}}\leq \eta_{C_{2}}$, e poi $\eta_{C_{2}}\leq \eta_{C_{1}}$. Consegue: $$\eta_{C_{1}}=\eta_{C_{2}}$$
>Cioè tutte le macchine reversibili che lavorano tra le stesse due sorgenti hanno lo stesso rendimento.
>
>Dalla relazione precedente è possibile dedurre, scrivendo $\eta_{C}$ in funzione di $Q_{1}$ e $Q_{2}$: $$\eta_{C}= \frac{L}{Q_{2}}= \frac{Q_{1}+Q_{2}}{Q_{2}}= 1+ \frac{Q_{1}}{Q_{2}}= 1- \frac{T_{1}}{T_{2}}$$
>Da cui si può ulteriormente dedurre: $$\frac{Q_{1}}{T_{1}}+ \frac{Q_{2}}{T_{2}}=0$$

### Teorema di Clausius
>[!note]
>In un ciclo termodinamico che lavora tra $N$ termostati, scambiando il termostato $i$-esimo, alla temperatura $T_{i}$ una quantità di calore $Q_{i}$, vale la relazione: $$\sum\limits_{i=1}^{N} \frac{Q_{i}}{T_{i}}\leq0$$
>L'uguaglianza vale per cicli composti da trasformazioni reversibili.

>[!example] Dimostrazione
>Consideriamo, oltre agli $N$ termostati, un ulteriore termostato alla temperatura $T_{0}$. Aggiungiamo, per ogni termostato $i$-esimo, una macchina reversibile di Carnot $C_{i}$ che lavora tra quest'ultimo e il termostato a temperatura $T_{0}$, ed è costruita in modo tale da scambiare in un ciclo con il termostato $T_{i}$ esattamente una quantità di calore $-Q_{i}$. A seconda dei casi, cioè a seconda dei segni del calore scambiato e a seconda se $T_{i}>T_{0}$ o viceversa, queste macchine di Carnot potranno essere frigorifere.
>Applicando il teorema di Clausius alla macchina $i$-esima $C_{i}$, che lavora tra $T_{i}$ e $T_{0}$ si ottiene: $$\frac{Q_{i}}{Q'_{i}}= \frac{T_{i}}{T_{0}}$$
>È possibile allora ricavare il calore $Q_{i}'$ scambiato dalla macchina $i$-esima con il termostato a temperatura $T_{0}$ come: $$Q_{i}'= T_{0} \frac{Q_{i}}{T_{i}}$$
>Si osserva che i vari termostati alle temperature $T_{i}$ diventano inessenziali, cioè potremmo far funzionare le macchine $C_{i}$ collegandole direttamente alla macchina $M$.
>Consideriamo allora una macchina termodinamica complessiva $M'$ che ingloba tutte le $M$  e tutte le $C_{i}$. Essa risulta essere una macchina monoterma, che scambia con la sorgente a temperatura $T_{0}$ una quantità di calore totale: $$Q_{0,\text{tot}}=\sum\limits_{i=1}^{N}Q_{i}'=T_{0}\sum\limits_{i=1}^{N} \frac{Q_{i}}{T_{i}}$$
>Per il secondo principio della termodinamica, nell'enunciato di Kelvin-Plank, per tale macchina monoterma vale: $$L=Q_{0,\text{tot}}=T_{0}\sum\limits_{i=1}^{N} \frac{Q_{i}}{T_{i}}\leq 0$$
>Da cui essendo $T_{0}\neq0$ è immediato ricavare: $$\sum\limits_{i=1}^{N} \frac{Q_{i}}{T_{i}}\leq0$$
>Se il ciclo considerato, svolto dalla macchina $M$, è reversibile, è possibile invertire il ciclo e riscrivere la disuguaglianza scambiando il segno a tutte le quantità di calore, da cui consegue che per una macchina reversibile essa deve valere con il segno uguale.
>

Questa disuguaglianza è detta disuguaglianza di Clausius, e in continuità si può generalizzare come: $$\oint \frac{\delta Q}{T}\leq0$$
Questo integrale lungo una data trasformazione termodinamica è detto integrale di Clausius.

