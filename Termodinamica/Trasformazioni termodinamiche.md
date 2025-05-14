>[!note]
>Una trasformazione termodinamica è un qualsiasi processo che porta un sistema termodinamico da uno stato di equilibrio iniziale $i$ a uno stato di equilibrio finale $f$. Durante la trasformazione, in generale, il sistema può non essere in equilibrio. In tal caso le coordinate termodinamiche non sono definite durante la trasformazione.

>[!tip] Trasformazioni quasistatiche
>Si definisce quasistatica una trasformazione che porta un sistema termodinamico da uno stato iniziale a uno finale passando attraverso infiniti stati di equilibri intermedi, infinitamente vicini da loro.

Affinché avvenga una trasformazione termodinamica è in qualche modo necessario che il sistema si squilibrato rispetto all'ambiente.

### Trasformazioni reversibili e irreversibili
>[!note]
>Le trasformazioni termodinamiche possono essere categorizzate come:
>- Irreversibili: una trasformazione da $i$ a $f$ tale per cui non è possibile riportare (tramite un altra trasformazione) il sistema in $i$ e anche l'ambiente nel suo stato iniziale.
>- Reversibili: una trasformazione da $i$ a $f$ tale per cui è possibile riportare sia il sistema sia l'ambiente nello stato originario.
>  
>  Affinché una trasformazione sia reversibile è necessario che la trasformazione sia quasistatiche, e che non agiscano forze dissipative.

### Rappresentazione grafica
>[!note]
>Per un sistema idrostatico, si utilizza il piano di Clapeyron $(p,V)$ per rappresentare lo stato termodinamico. Si possono quindi rappresentare le trasformazioni in un grafico. Siccome le coordinate termodinamiche non sono definite durante la trasformazione si usa rappresentarle come linee ondulate o bande che uniscono il punto iniziale e finale.

### Trasformazioni notevoli
>[!note]
>Alcune trasformazioni termodinamiche particolari acquisiscono un nome specifico:
>- Trasformazioni isocore: trasformazioni a volume costante
>- Trasformazioni isobare: trasformazioni a pressione costante
>- Trasformazioni isoterme: trasformazioni a temperatura costante
>
>Inoltre si definisce ciclo termodinamico una successione di trasformazioni termodinamiche connesse tra loro in cui lo stato finale coincide con lo stato iniziale.

### Lavoro di una trasformazione termodinamica
>[!note]
>Definiamo il lavoro di una trasformazione termodinamica come: $$L=\int_{V_{i}}^{V_{f}}p_\text{est}\text{ d}V$$
>Dove $V_{i}$ e $V_{f}$ sono rispettivamente volume iniziale e finale del sistema.

>[!example] Dimostrazione
>Consideriamo un elemento di superficie $\text{d}S$ sulla frontiera del sistema termodinamico, che durante una trasformazione termodinamica si sposta di un tratto $\text{d}\overrightarrow{r}$, mentre sulla superficie $\text{d}S$ agiscono forze di pressione sia dall'interno sia dall'esterno. In questo spostamento infinitesimo, applicando il teorema delle forze vive a questo tratto di frontiera si ha: $$\delta L_\text{tot} = \text{d}E_{k}=0$$
>Dove $\delta L_\text{tot}$ è il lavoro infinitesimo netto fatto da tutte le forze, sia dall'interno che dall'esterno. Infatti, la frontiera, in quanto superficie ideale, non ha massa e la sua energia cinetica rimane costantemente nulla, così come le sue variazioni infinitesime. Considerando separatamente i contributi $\delta L_\text{est}$ e $\delta L_\text{sistema}$ si ha: $$\delta L_\text{est}+\delta L_\text{sistema}=0\iff \delta L_\text{sistema}= -\delta L_\text{est}$$
>Poiché in generale, durante una trasformazione termodinamica, le coordinate termodinamiche del sistema, potrebbero non essere ben definite, si preferisce procedere basandoci solo sulle forze esterne. La forza agente sulla superficie dall'esterno è $\text{d}\overrightarrow{F}_\text{est}=-p_{\text{est}}\text{d}S\hat{u}_{n}$, perciò: $$\delta L_\text{est}=\text{d}\overrightarrow{F}_\text{est}\cdot \text{d}\overrightarrow{r}=- p_\text{est}\text{d}S(\text{d}\overrightarrow{r}\cdot\hat{u}_{n})=-p_\text{est}\text{d}V$$
>Dove $\text{d}V$ è una variazione infinitesima di volume del sistema termodinamico in corrispondenza della superficie $\text{d}S$. Integrando su tutta la frontiera e su tutta la trasformazione termodinamica possiamo dire: $$L=\int_{V_{i}}^{V_{f}}p_\text{est}\text{ d}V$$
>Dove $V_{i}$ e $V_{f}$ sono rispettivamente volume iniziale e finale del sistema.

Consideriamo dei casi notevoli. In caso di pressione costante si ha: $$L=p_\text{est}(V_{f}-V_{i})$$
Nel caso in cui il sistema si può espandere liberamente nel vuoto si ha $p_\text{est}=0$ e quindi: $$L=0$$
Nel caso in cui la trasformazione termodinamica allora $p_\text{est}=p(V)$ e quindi: $$L=\int_{V_{i}}^{V_{f}}p(V)\text{ d}V$$
Inoltre nel caso il gas considerato sia un gas perfetto possiamo dire per le trasformazioni quasistatiche notevoli:
- Trasformazioni isocore: $L=0$
- Trasformazioni isobare: $L=p(V_{f}-V_{i})$
- Trasformazioni isoterme: $L=n\cdot RT\cdot\log \frac{V_{f}}{V_{i}}$
