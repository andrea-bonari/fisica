>[!note]
>Non tutte le coordinate termodinamiche sono indipendenti. In generale si ha che, per un sistema termodinamico di massa totale fissata, con $C$ specie chimiche, può essere descritto da al più $N$ coordinate termodinamiche indipendenti, con $$N=C+1$$
>Se aggiungiamo, oltre alla conservazione della massa totale, il vincolo della coesistenza nel sistema di un numero $F$ fissato di fasi distinte: $$N=C-F+2$$
>Questa relazione è nota come Regola delle Fasi di Gibbs.
>La legge matematica che mette in relazione i valori delle diverse coordinate termodinamiche di un sistema è detta legge di stato (o equazione di stato). Essa è sempre determinata in modo sperimentale.

>[!tip]
>Per un sistema idrostatico, l'equazione di stato è: $$f(p,V,T)=0$$

### Equazioni di stato dei gas ideali
>[!note]
>I gas ideali tendono a comportarsi nello stesso modo se la pressione è sufficientemente bassa e la temperatura è sufficientemente alta. Si ha quindi l'equazione di stato dei gas ideali: $$pV= nRT=Nk_{B}T$$
>Con $n$ numero di moli, $R= 8.3145\space \frac{\text{J}}{\text{mol}\cdot\text{K}}=0.082\space \frac{\text{l}\cdot\text{atm}}{\text{mol}\cdot\text{K}}$ costante universale dei gas ideali, $N$ numero di molecole e $k_{B}= \frac{R}{N_{A}}=1.38066\cdot 10^{-23} \frac{\text{J}}{\text{K}}$ costante di Boltzmann

>[!example] Dimostrazione
>Per studiare il comportamento dei gas, è possibile utilizzare un cilindro con pistone mobile:
>![[Pasted image 20250507162303.png]]
>
>Si ha che il volume è dato da: $$V=\pi r^{2}h$$
>Mentre, un termometro misura la temperatura $T$ e un manometro misura la pressione $p$. Ne deduciamo la legge di Boyle: $$p= \frac{\text{cost}}{V}\qquad \text{se }T\text{ è costante}$$
>La legge di Gay-Lussac: $$p=\text{cost}\cdot T\qquad\text{se }V\text{ costante}$$
>Legge di Charles: $$V=\text{cost}\cdot T\qquad\text{se }p\text{ costante}$$
>Adesso prendiamo un sistema termodinamico inizialmente determinato dalla terna $(p_{0},V_{0},T_{0})$ e poi fargli raggiungere un nuovo stato con pressione $p$ e volume $V$ tramite la successione descritta qui sotto. Facciamo variare il volume da $V_{0}$ a $V$, mantenendo costante la pressione. Usando la legge di Charles: $$\frac{V}{V_{0}}= \frac{T^{*}}{T_{0}}$$
>Con $T^{*}$ nuova temperatura. Facciamo adesso variare la pressione da $p_{0}$ a $p$ mantenendo costante il volume. Usando la legge di Gay-Lussac: $$\frac{p}{p_{0}}= \frac{T}{T^{*}}$$
>Moltiplicando membro a membro le due equazioni scritte otteniamo: $$\frac{pV}{p_{0}V_{0}}= \frac{T}{T_{0}}\Longrightarrow \frac{pV}{T}= \frac{p_{0}V_{0}}{T_{0}}$$
>L'equazione di stato per un gas perfetto è dunque del tipo $\frac{pV}{T}=\text{cost}$.
>Usando la legge di Avogadro si può scrivere, misurando la materia in moli ($1\text{ mol}= N_{A}=6.022\cdot 10^{23}$ atomi): $$V_{0}=n V_{m}$$
>Con $V_{m}$ volume di una mole di gas alla temperatura $T_{0}$ e temperatura $P_{0}$ e $n$ è il numero di moli di gas che costituiscono il sistema. Quindi: $$\frac{pV}{T}= n\cdot\underbrace{ \frac{p_{0}V_{m}}{T_{0}}}_{R}$$
>Con $R= 8.3145\space \frac{\text{J}}{\text{mol}\cdot\text{K}}=0.082\space \frac{\text{l}\cdot\text{atm}}{\text{mol}\cdot\text{K}}$ costante universale dei gas ideali. Si ricava quindi l'equazione di stato dei Gas Ideali: $$pV=nRT$$
>Volendo esprimere in termini di numero di molecole $N=N_{A}\cdot n$, definiamo la costante di Boltzmann $k_{B}= \frac{R}{N_{A}}=1.38066\cdot 10^{-23} \frac{\text{J}}{\text{K}}$ e scrivere: $$pV=Nk_{B} T$$

>[!tip] Legge di Avogadro
>Si ha che volumi uguali di gas diverse, nelle stesse condizioni di temperatura e pressione, contengono la stessa quantità di materia.

### Dilatazione termica dei solidi e liquidi
>[!note]
>Si ha che solidi e liquidi possono essere descritti come sistemi termodinamici, caratterizzati da una legge di stato diversa da quella dei gas perfetti. In particolare, il volume dipende dalla temperatura, anche se in modo mene marcato rispetto ai gas.
>In generale: $$V=f(T)$$con $p$ fissato.

>[!tip] Approssimazione della legge di dilatazione cubica
>Per intervalli di temperatura non troppo ampi, la dilatazione volumica può essere approssimata con una relazione lineare: $$V=V_{0}(1+ \beta(T-T_{0}))$$
>Con $V_{0}$ volume alla temperatura $T_{0}$, e $\beta$ coefficiente di dilatazione cubica. $\beta$ è definito come: $$\beta= \frac{1}{V} \left(\frac{\partial V}{\partial T}\right)\space\bigg|_{p=\text{cost}}$$
>e dipende dalla temperatura.

>[!tip] Approssimazione della legge di dilatazione lineare
>Per un solido, anche ogni dimensione lineare si dilata con la temperatura: $$l=l_{0}(1+\alpha(T-T_{0}))$$
>Con $l_{0}$ lunghezza alla temperatura $T_{0}$ e $\alpha$ coefficiente di dilatazione lineare. $\alpha$ è definito come: $$\alpha= \left(\frac{1}{l} \frac{\partial l}{\partial T}\right)\space\bigg|_{p=\text{cost}}$$
>Si ha inoltre per i materiali omogenei che $\beta= 3\alpha$.

 