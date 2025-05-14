>[!note]
>Dati due corpi, posti inizialmente alla temperatura $T_{1}$ e $T_{2}$, mettendoli a contatto termico in un ambiente isolato, possiamo dire che: $$Q=c^{*}m\Delta T$$
>Dove $Q$ è la quantità di calore scambiato, e $c^{*}$ è il calore specifico della, cioè la capacità termica per unità di massa, rigorosamente definita come: $$c^{*}= \frac{1}{m} \frac{\partial Q}{\partial T}$$
>Il calore specifico dipende dalle condizioni in cui il trasferimento di calore è effettuato.

>[!example] Dimostrazione
>Scegliendo due corpi, posti inizialmente a temperatura $T_{1}$ e $T_{2}$, li metto in contatto termico (isolandoli dall'ambiente usando un calorimetro), si può misurare la temperatura di equilibrio. Si osserva sperimentalmente che il rapporto rimano costante: $$\frac{T_{1}-T_{\text{eq}}}{T_{\text{eq}}-T_{2}}=\text{cost}$$
>Analizzano diverse coppie di corpi si osserva che questa legge vale sempre, ma cambia il valore della costante. Ipotizzando che il corpo $1$ abbia ceduto una quantità di calore $|Q_{1}|=C_{1}(T_{1}-T_{\text{eq}})$ e il corpo $2$ ne abbia acquisito la quantità $|Q_{2}|=|Q_{1}|=C_{2}(T_{\text{eq}}-T_{2})$, dove $C_{1}$ e $C_{2}$ sono le capacità termiche dei due corpi, possiamo ricavare dall'equazione precedente: $$T_{\text{eq}}= \frac{C_{1}T_{1}+C_{2}T_{2}}{C_{1}+C_{2}}$$
>Con altri esperimenti nel calorimetro utilizzando corpi composti dalla stessa sostanza ma di massa di versa ci si accorge che: $$C=c^{*}m$$
>Dove $c^{*}$ è il calore specifico, cioè la capacità termica per unità di massa. Possiamo dire che il calore scambiato da un corpo specifico si può scrivere come: $$Q=C\Delta T=C(T_{f}-T_{i})$$
>È possibile quindi ricavare la temperatura di equilibrio imponendo: $$Q_{1}+Q_{2}=0$$
>Dove $T_{f}$ e $T_{i}$ sono le temperature finali e iniziali del processo di scambio termico. Da qui ricaviamo quindi la legge fondamentale della calorimetria: $$Q=c^{*}m \Delta T$$
>In realtà, il calore specifico $c^{*}$ dipende anche dalla temperatura, ed è possibile definirlo in modo più rigoroso: $$c^{*}= \frac{1}{m} \frac{\partial Q}{\partial T}$$
>In questo caso potremmo quindi ricavare la forma: $$Q=\int_{T_{i}}^{T_{f}}c^{*}(T)m \text{ d} T$$

In passato questa legge era adottata come definizione operativa del calore come grandezza fisica. Storicamente si è usata come unità di misura del calore la caloria, definita come la quantità di calore necessaria per scaldare (a pressione atmosferica) un grammo di acqua distillata da $14.5°\text{ C}$ a $15.5°\text{ C}$. Il calore specifico dell'acqua a pressione costante assume quindi il valore $c_{p}= 1\space\frac{\text{cal}}{\text{g } °\text{C}}$.

### Passaggi di stato
>[!note]
>Si ha che per far compiere ad una massa $m$ di una certa sostanza un passaggio di stato è necessario scambiare una quantità di calore pari a: $$Q=\lambda m$$
>Dove $\lambda$ è detto calore latente, caratteristico sia della sostanza impiegata sia dello specifico passaggio di stato. Se il passaggio è da solido a liquido, o da liquido a gassoso il calore andrà fornito al sistema. Nel caso inverso la stessa quantità di calore deve essere ceduta dal sistema all'ambiente.

Sperimentalmente, si prende una certa massa acqua $m$, e si fornisce ad esso una quantità di calore costante per unità di tempo. Inizialmente si noterà un incremento di temperatura $\Delta T = \frac{Q}{mc_{p}}$. Quando l'acqua raggiunge la temperatura di ebollizione $T_{v}=100°\text{ C}$, si osserva che la temperatura non aumenta più. Il calore qui è utilizzato per trasformare l'acqua da liquido a vapore. Se l'acqua fosse contenuta non in una pentola aperta ma in un cilindro chiuso da un pistone mobile per mantenere costante la pressione, si osserverebbe che la temperatura rimane costante fino a che l'acqua non è completamente trasformata in vapore. Nel caso dell'acqua, il calore latente di fusione è $\lambda_{f}\simeq 80 \space\frac{\text{cal}}{\text{g}}$, mentre il calore latente di vaporizzazione è $\lambda_{v}\simeq 540\space \frac{\text{cal}}{\text{g}}$.

### Termostato
>[!note]
>In termodinamica si denomina termostato un sistema con capacità termica tendente all'infinito, per cui nonostante gli venga fornito o sottratto calore la sua temperatura non varia.

È utilizzato per approssimare un sistema con capacità termica molto maggiore degli altri come termostato. Se si porta in contatto termico un corpo con capacità termica $C_{1}$ a temperatura $T_{1}$ con un sistema di capacità termica $C_{0}$ a temperatura $T_{0}$ è immediato vedere che se $C_{0}\gg C_{1}$: $$T_\text{eq}= \frac{C_{1}T_{1}+C_{0}T_{0}}{C_{1}+C_{0}}= \frac{\frac{C_{1}}{C_{0}}+T_{0}}{\frac{C_{1}}{C_{0}}+1}\simeq T_{0}$$
### Trasporto del calore
>[!note]
>Si ha che il calore può propagarsi in tre modi:
>- Conduzione: il calore si propaga senza movimento macroscopica di materia
>- Convezione: tramite movimento macroscopico della materia il fluido si rimescola portando fluido più caldo verso le pareti fredde e viceversa
>- Irraggiamento: il calore è trasportato per mezzo di onde elettromagnetiche.

Il trasferimento per conduzione è descritto dalla legge di Fourier: il calore si trasmesso nell'unità di tempo $\frac{\text{d}Q}{\text{d}t}$, in un punto $x_{0}$ è dato da: $$\frac{\text{d}Q}{\text{d}t}=-\kappa S \frac{\text{d}T}{\text{d}x}\bigg|_{x=x_{0}}$$
Dove $\kappa$ è la conducibilità termica. Supponendo la parete omogenea: $$\frac{\text{d}Q}{\text{d}t}=-\kappa S \frac{\Delta T}{D}$$
Dove $D$ è lo spessore della parete e $\Delta T$ è la differenza di temperatura tra gli estremi.

Il trasferimento per convezione è descritto dalla legge: $$\frac{\text{d}Q}{\text{d}t}=hS(T-T_{\infty})$$
Dove $h$ è coefficiente limitare, $T$ è la temperatura della parete e $T_{\infty}$ è la temperatura del fluido a grande distanza da essa.

Il trasferimento per irraggiamento è descritto dalla legge di Stefan-Boltzmann: $$\frac{\text{d}Q}{\text{d}t}=\varepsilon \sigma ST^{4}$$
Dove $S$ è la superficie emittente, $T$ la sua temperatura, $\sigma= 5.67\cdot 10^{-8}\space\frac{\text{W}}{\text{m}^{2}\cdot\text{K}^{4}}$ è la costante universale di Stefan-Boltzmann, e $\varepsilon$ è una costante che dipende dalle caratteristiche della superficie.
