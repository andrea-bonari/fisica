>[!note]
>Definiamo come macchina termica un sistema termodinamico che compie una trasformazione ciclica per cui il lavoro netto prodotto è positivo (ciclo termico). Viceversa, definiamo una macchina frigorifera come un sistema termodinamico che compie una trasformazione ciclica con lavoro netto negativo (ciclo frigorifero). Siccome dopo ogni ciclo, il sistema termodinamico ritorna nello stato di partenza si ha: $$Q=L=Q_\text{ass}+Q_\text{ced}=|Q_\text{ass}|-|Q_\text{ced}|$$
>Definiamo il rendimento di una macchina termica come: $$\eta= \frac{L}{|Q_\text{ass}|}= \frac{Q}{|Q_\text{ass}|}=1- \frac{|Q_\text{ced}|}{|Q_\text{ass}|}$$
>Definiamo l'efficienza del ciclo frigorifero come: $$\omega= \frac{|Q_\text{ass}|}{|L|}= \frac{|Q_\text{ass}|}{|Q_\text{ass}|-|Q_\text{ced}|}$$

### Interazioni con l'ambiente e termostati
>[!note]
>L'interazione termica tra sistema e ambiente in una trasformazione termodinamica è spesso descritta come interazione del sistema con uno più termostati, o sorgenti di calore. In particolare le trasformazioni isoterme possono essere viste come interazioni con un singolo termostato, le trasformazioni tra due temperature diverse richiedono almeno due termostati, e le trasformazioni quasistatiche sono descritte come interazioni con una successione infinita di termostati.
>
>È possibile costruire un ciclo termodinamico che produca lavoro utilizzando un solo termostato (macchina monoterma).

Nel caso di un gas perfetto in cui le trasformazioni sono reversibili è possibile realizzare una trasformazione isoterma che produce lavoro positivo, ma non è possibile tornare allo stato iniziale usando solo curve adiabatiche, l'unico modo è ripercorrere la stessa isoterma al contrario. Si ha quindi che ciclo con un solo termostato non può produrre lavoro netto, sono necessari almeno due termostati a temperatura diversa.

### Il ciclo di Carnot
>[!note]
>Il più semplice ciclo termodinamico che impiega solo due termostati per produrre lavoro è il ciclo di Carnot. È costituito da due trasformazioni isoterme, a temperature $T_{1}$ e $T_{2}$, congiunte da due trasformazioni adiabatiche. Si ha che: $$\eta_\text{Carnot}=1- \frac{T_{1}}{T_{2}}$$

>[!example] Dimostazione
>Studiamo nel dettaglio il ciclo di Carnot svolto da un gas perfetto con trasformazioni reversibili. Assumendo $T_{1}<T_{2}$, i contributi di lavoro e calore scambiati si possono dettagliare come: 
>
>| Trasformazione| Valori|
>|-|-|
>| Isoterma $AB$ | $$L_{AB}=Q_{AB}=nRT_{1}\log \frac{V_{B}}{V_{A}}<0$$  |
>| Adiabatica $BC$ | $$L_{BC}=- \Delta U_{BC}=nc_{V}(T_{1}-T_{2})<0\quad Q_{BC}=0$$ | 
>| Isoterma $CD$ | $$L_{CD}=Q_{CD}=nRT_{2}\log \frac{V_{D}}{V_{C}}>0$$ |
>| Adiabatica $DA$ | $$L_{DA}=- \Delta U_{DA}=nc_{V}(T_{2}-T_{1})>0\quad Q_{DA}=0$$ |
>
>![[Pasted image 20250519130752.png|center]]
>
>Si ha quindi che: $$\begin{align*}
>L_{AB}&= Q_{AB}=nRT_{1}\log \frac{V_{B}}{V_{A}}=nRT_{1}\log \frac{V_{C}}{V_{D}}=\\
>&=- \frac{T_{1}}{T_{2}}\left(nRT_{2}\log \frac{V_{D}}{V_{C}}\right)=- \frac{T_{1}}{T_{2}}L_{CD}=- \frac{T_{1}}{T_{2}}Q_{CD} 
>\end{align*}$$
>Si può valutare il lavoro netto svolto dal ciclo come: $$\begin{align*}
>L&= Q=|Q_\text{ass}|-|Q_\text{ced}|=Q_{AB}+Q_{BC}+Q_{CD}+Q_{DA}=\\
>&= - \frac{T_{1}}{T_{2}}Q_{CD}+0+Q_{CD}+0=Q_{CD} \left(1- \frac{T_{1}}{T_{2}}\right)=nRT_{2}\log \frac{V_{D}}{V_{C}}\cdot\left(1- \frac{T_{1}}{T_{2}}\right)>0
>\end{align*}$$
>La macchina di Carnot preleva del calore dalla sorgente calda, ne converte una parte in lavoro, mentre la parte rimanente è ceduta alla sorgente a temperatura più fredda. Il rendimento del ciclo di Carnot reversibile, svolto da un gas perfetto è: $$\eta_\text{Carnot} = \frac{L}{|Q_\text{ass}|}= \frac{Q_{CD}\left(1- \frac{T_{1}}{T_{2}}\right)}{Q_{CD}}=1- \frac{T_{1}}{T_{2}}$$

### Il ciclo frigorifero di Carnot
>[!note]
>Percorrendo il ciclo di Carnot in senso inverso otteniamo un ciclo frigorifero. Se il ciclo è composto da trasformazioni reversibili di un gas perfetto le espressioni dei contributi di calore scambiato rimangono uguali in modulo a quelle ricavate sopra, ma cambiano di segno. Si ha che: $$\omega_\text{Carnot}= \frac{T_{1}}{T_{2}-T_{1}}$$

>[!example] Dimostrazione
>Assumendo come prima $T_{1}<T_{2}$: 
>
>| Trasformazione| Valori|
>|-|-|
>| Isoterma $DC$ | $$L_{DC}=Q_{DC}=nRT_{2}\log \frac{V_{C}}{V_{D}}<0$$  |
>| Adiabatica $CB$ | $$L_{CB}=- \Delta U_{CB}=nc_{V}(T_{2}-T_{1})>0\quad Q_{CB}=0$$ | 
>| Isoterma $BA$ | $$L_{BA}=Q_{BA}=nRT_{1}\log \frac{V_{A}}{V_{B}}>0$$ |
>| Adiabatica $AD$ | $$L_{AD}=- \Delta U_{AD}=nc_{V}(T_{1}-T_{2})>0\quad Q_{AD}=0$$ |
>
>Poiché gli stati $A,B,C,D$ sono sempre gli stessi del ciclo di Carnot, valgono le relazioni precedenti, in particolare: $$L_{BA}=Q_{BA}=- \frac{T_{1}}{T_{2}}L_{DC}=- \frac{T_{1}}{T_{2}}Q_{DC}$$
>Al contrario della macchina termica, la macchina frigorifera assorbe calore dalla sorgente fredda e cede calore alla sorgente calda: $$|Q_\text{ass}|=|Q_{BA}|\qquad |Q_\text{ced}|=|Q_{DC}|$$
>Si nota che $|Q_\text{ass}|<|Q_\text{ced}|$, il lavoro del ciclo è negativo e quindi fornito dall'esterno al sistema termodinamico: $$L=|Q_\text{ass}|-|Q_\text{ced}|=Q_{BA}+Q_{DC}=Q_{BA} \left(1-  \frac{T_{2}}{T_{1}}\right)$$
>Per il primo principio, il calore ceduto alla sorgente calda sarà il calore sottratto alla sorgente fredda sommato al lavoro fornito al sistema, convertito in calore. Si ha che: $$\omega_\text{Carnot}= \frac{|Q_\text{ass}|}{|L|}= \frac{Q_\text{ass}}{-L}= \frac{Q_\text{BA}}{-Q_\text{BA}\left(1- \frac{T_{2}}{T_{1}}\right)}= \frac{T_{1}}{T_{2}-T_{1}}$$

