>[!note]
>Definiamo l'entropia $S$ come una funzione di stato che misura la variazione del disordine o della disponibilità di energia in un sistema termodinamico. Per una trasformazione reversibile tra due stati $i$ e $f$, la variazione di entropia è definita come: $$\Delta S=\int_{i}^{f} \frac{\delta Q_\text{rev}}{T}\qquad [S]= \frac{\text{J}}{\text{K}}$$

>[!example] Dimostrazione
>Consideriamo due trasformazioni reversibili $\text{I}$ e $\text{II}$ che collegano gli stessi stati $i$ e $f$. Componiamo un ciclo $\text{I}$ da $i$ a $f$, e $\text{II}$ da $f$ a $i$. Essendo entrambe reversibili possiamo applicare l'integrale di Clausius: $$\oint \frac{\delta Q}{T}=\int_{i}^{f} \frac{\delta Q_\text{I}}{T}+\int_{f}^{i} \frac{\delta Q_\text{II}}{T}=0$$
>Percorrendo $\text{II}$ si ha che: $$\int_{i}^{f} \frac{\delta Q_\text{I}}{T}=\int_{i}^{f} \frac{\delta Q_\text{II}}{T}$$
>Dato che le trasformazioni sono arbitrarie, questo implica che esiste una funzione $S$ detta entropia tale che: $$\Delta S= S(f)-S(i)=\int_{i}^{f} \frac{\delta Q_\text{rev}}{T}$$

Se la trasformazione è reversibile, ma l'integrale è difficoltoso, si può calcolare $\Delta S$ come l'integrale di Clausius su una trasformazione reversibile diversa, purché congiunga gli stessi dati iniziali e finali.

Osserviamo inoltre, che per trasformazioni reversibili infinitesime vale: $$\frac{\delta Q}{T}=\text{d}S$$
### Principio di aumento dell'entropia
>[!note]
>Si ha per il secondo principio della termodinamica (forma globale) che l'entropia dell'universo non può mai diminuire, quindi per ogni trasformazione termodinamica si ha: $$\Delta S_{U}\geq0$$
>Si ha che l'uguaglianza vale solo nel caso di trasformazioni reversibili.

>[!example] Dimostrazione
>Siccome un sistema isolato non scambia calore: $$\delta Q=0$$
>Dalla relazione generale: $$\int_{i}^{f} \frac{\delta Q}{T}\leq \Delta S$$
>Segue che: $$\Delta S\geq0$$
>
>Inoltre consideriamo una macchina monoterma che scambia calore $Q_{T}$ con un termostato a temperatura $T_{0}$. Se la macchina completa un ciclo si ha: $$\Delta S_\text{sistema}=0$$
>L'unico contributo a $\Delta S_{U}$ viene quindi dall'ambiente: $$\Delta S_{U}= \frac{Q_{T}}{T_{0}}$$
>Però, siccome $Q=-Q_{T}$: $$\Delta S_{U}=- \frac{Q}{T_{0}}$$
>Applicando il principio di aumento dell'entropia: $$0\leq - \frac{Q}{T_{0}}\Longrightarrow Q\leq0\Longrightarrow L=Q\leq0$$
>Quindi è impossibile per una macchina monoterma compiere lavoro netto positivo, cioè abbiamo dimostrato l'enunciato di Kelvin-Planck partendo dal principio di aumento dell'entropia.

### Significato dell'entropia
>[!note]
>L'entropia è una grandezza fisica che:
>- Non è direttamente misurabile, né suggerita intuitivamente dall'esperienza
>- Fornisce un criterio quantitativo per l'irreversibilità dei processi
>- Consente di stabilire la direzione naturale dei fenomeni fisici
>- Quantifica l'energia inutilizzabile nei processi irreversibili.

>[!example] Dimostrazione
>Consideriamo un ciclo composto da:
>
>- trasformazione $\text{I}$: generica (possibilmente irreversibile) da $i\to f$,
>- trasformazione $\text{II}$: reversibile da $f\to i$.
>  
>La variazione di entropia dell’universo nel ciclo completo è: $$\Delta S_U = \Delta S_{\text{sistema}}^{(\text{I})} + \Delta S_{\text{ambiente}}^{(\text{I})} + \Delta S_{\text{sistema}}^{(\text{II})} + \Delta S_{\text{ambiente}}^{(\text{II})}$$
>Poiché il ciclo riporta il sistema nello stato iniziale: $$\Delta S_{\text{sistema}}^{(\text{I})} + \Delta S_{\text{sistema}}^{(\text{II})} = 0$$
>Quindi: $$\Delta S_U = \Delta S_{\text{ambiente}}^{(\text{I})} + \Delta S_{\text{ambiente}}^{(\text{II})}$$
>Se $\text{I}$ , anche l’ambiente torna nel suo stato iniziale: $\Delta S_{\text{ambiente}} = 0$.  
>Se I è irreversibile, l’ambiente aumenta la propria entropia, e quindi il ciclo lascia una traccia irreversibile nell'ambiente.
>
>Consideriamo il trasferimento di calore $|Q|$ da un termostato caldo ($T_{2}$) a uno freddo ($T_{1}<T_{2}$): $$\Delta S_U = \frac{|Q|}{T_1} - \frac{|Q|}{T_2} = |Q| \left( \frac{1}{T_1} - \frac{1}{T_2} \right) > 0$$
>Il trasferimento spontaneo avviene dal caldo al freddo.  
>L'inverso (dal freddo al caldo senza lavoro) implicherebbe: $$\Delta S_U < 0$$
>Che è impossibile.
>
>Per una macchina di Carnot irreversibile tra $T_2 > T_1$:
>- Assorbe calore $Q_2$ da $T_2$
>- Compie lavoro $L_{\text{irrev}}$
>- Cede calore $Q_1 = Q_2 - L_{\text{irrev}}$ a $T_1$
>
>L’entropia dell’universo: $$\Delta S_U = -\frac{Q_1}{T_1} + \frac{Q_2}{T_2} = -\frac{L_{\text{irrev}} - Q_2}{T_1} + \frac{Q_2}{T_2}$$
>Espressa come differenza rispetto al lavoro reversibile: $$\Delta S_U = -\frac{L_{\text{irrev}}}{T_1} + Q_2 \left( \frac{1}{T_2} + \frac{1}{T_1} \right)$$
>Da cui segue: $$\Delta S_U = \frac{L_{\text{rev}} - L_{\text{irrev}}}{T_1} \Rightarrow \Delta L = L_{\text{rev}} - L_{\text{irrev}} = T_1 \Delta S_U$$
