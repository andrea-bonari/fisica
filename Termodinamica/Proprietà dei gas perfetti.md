>[!note]
>Si ha che le relazioni costitutive dei gas perfetti sono: $$\begin{align*}
>pV&= nRT\\
>U&= U(T)\end{align*}$$
>Possiamo inoltre scrivere la variazione di energia interna di un gas perfetto come: $$\Delta U= nc_{V}\Delta T$$
>Con $c_{V}$ calore molare a volume costante e $n$ numero di moli di gas.

>[!example] Dimostrazione
>L'esperimento di Joule del 1844 ha dimostrato che, durante un'espansione libera di un gas (senza scambio né di calore né lavoro), la temperatura e quindi l'energia interna del gas rimangono invariate.
>
>In particolare, si ha che il gas si espande liberamente da un recipiente all'altro, senza né compiere lavoro ($L=0$) né scambiare calore ($Q=0$). Inoltre non si osservano variazioni di temperatura ($\Delta T=0$), e quindi per il primo principio della termodinamica, anche l'energia interna rimane costante ($\Delta U=0$). Quindi, dato che il volume cambia ma l'energia interna no, si conclude che l'energia interna di un gas perfetto dipende solo dalla temperatura: $$U=U(T)$$
>Si ha quindi che le relazioni costitutive dei gas perfetti sono: $$\begin{align*}
>pV&= nRT\\
>U&= U(T)\end{align*}$$
>La variazione di energia interna di un gas perfetto può essere poi dettagliata ulteriormente ricordando che in una trasformazione isocora, essendo nullo il lavoro, essa è uguale al calore scambiato: $$\Delta U=mc_{V}^{*}\Delta T$$
>In realtà, nel caso dei gas, anziché il calore specifico $c^{*}$ si preferisce utilizzare il calore molare: $$c_{\alpha}= \frac{1}{n} \frac{\delta Q}{\text{d}T}\bigg|_{\alpha}$$
>Vale inoltre la relazione: $$c_{\alpha}=c_{\alpha}^{*}m_{m}$$
>Con $m_{m}$ massa molare. Perciò possiamo scrivere la variazione di energia interna di un gas perfetto come: $$\Delta U= nc_{V}\Delta T$$
>Con $c_{V}$ calore molare a volume costante e $n$ numero di moli di gas.

Si ha per i gas monoatomici che: $$c_{V,\text{monoatomici}}= \frac{3}{2}R$$
Mentre per i gas diatomici: $$c_{V,\text{diatomici}}= \frac{5}{2}R$$

### Relazione di Mayer
>[!note]
>La relazione di Mayer lega i valori del calore molare a pressione costante e a volume costante di un gas perfetto. È definita come: $$c_{p}=c_{V}+R$$
>Essa comporta, in ogni caso, che $c_{p}>c_{V}$ e che anche $c_{p}$ non dipende dalla temperatura.

>[!example] Dimostrazione
>Studiamo una trasformazione di un gas perfetto che avviene tra due stati $i$ e $f$ alla stessa pressione, mantenendo sempre costante la pressione esterna $p_\text{est}$. Se la pressione esterna è costante, il lavoro è definito come $L=p_\text{est} \Delta V$, per cui: $$Q= \Delta U+L= nc_{V} \Delta T+ p_\text{est} \Delta V$$
>Siccome $p_\text{est}=p_{i}=p_{f}$: $$\begin{align*}
>p_\text{est} \Delta V&= p_\text{est}(V_{f}-V_{i})=\\
>&= p_\text{est}V_{f}-p_\text{est}V_{i}=p_{f}V_{f}-p_{i}V_{i}\\
>&= nRT_{f}-nRT_{i}=nR\Delta T
>\end{align*}$$
>Se ne ricava allora: $$Q=nc_{V}\Delta T+nR \Delta T=n(c_{V}+R) \Delta T$$
>Applicando $c_{\alpha}= \frac{1}{n} \frac{\delta Q}{\text{d}T}\bigg|_{\alpha}$, ricaviamo la relazione di Mayer: $$c_{p}=c_{V}+R$$
>Comporta che $c_{p}>c_{V}$ e che $c_{p}$ non dipende dalla temperatura.

### Trasformazioni adiabatiche di gas perfetti
> [!note]  
> Una trasformazione adiabatica quasistatica di un gas perfetto è un processo in cui non avviene scambio di calore con l’esterno ($Q = 0$). Possiamo determinare le relazioni tra le variabili di stato sfruttando il Primo Principio della Termodinamica e l’equazione di stato dei gas perfetti. Queste sono dette equazioni di Poisson: $$\begin{align*}
>&TV^{\gamma-1}=\text{cost}\\
>&pV^\gamma=\text{cost}\\
>&Tp^{\frac{1-\gamma}{\gamma}}=\text{cost}
>\end{align*}$$
>Con $\gamma= \frac{c_{V}+R}{c_{V}}$.

>[!example] Dimostrazione
>Utilizzando l'espressione per $\Delta U$ nel caso di differenze infinitesime: $$\text{d}U=nc_{V}\text{d}T$$
>Si può riscrivere la forma differenziale del Primo Principio come: $$\delta Q=\text{d}U+pdV=nc_{V}\text{d}T+pdV$$
>Imponiamo allora che il calore scambiato sia nullo: $$nc_{V}\text{d}T+pdV=0$$
>In questa espressione compaiono tutte e tre le coordinate termodinamiche, ma come noto solo due di queste sono indipendenti. Applichiamo quindi l'equazione di stato dei gas perfetti, sostituendo: $p= \frac{nRT}{V}$ si ottiene: $$\frac{\text{d}T}{T}=- \frac{R}{c_{V}}\frac{\text{d}V}{V}$$
>Dove è stato semplificato $n$. A questo punto si integra tra uno stato iniziale e uno stato finale, si ricava: $$\frac{T}{T_{0}}=\left(\frac{V}{V_{0}}\right)^{- \frac{R}{c_{V}}}$$
>Da cui si conclude che in una tale trasformazione: $$TV^{\frac{R}{c_{V}}}=T_{0}V_{0}^{\frac{R}{c_{V}}}=\text{cost}$$
>Sostituendo $\gamma= \frac{c_{p}}{c_{V}}$, che nel caso di un gas perfetto è $\gamma= \frac{c_{V}+R}{c_{V}}$, si possono ricavare le equazioni di Poisson.

 Poiché $Q = 0$, dal Primo Principio:$$L = -\Delta U = -nc_V (T_f - T_i) = nc_V (T_i - T_f)$$
Se non sono note le temperature, ma sono noti pressione e volume iniziali e finali: $$L = \dfrac{c_V}{R} (p_i V_i - p_f V_f)$$
### Trasformazioni politropiche
>[!note]
>Le trasformazioni politropiche sono definite da una legge del tipo $$pV^\alpha=\text{cost}$$
>Che, tramite l'equazione di stato dei gas perfetti, può essere scritta come: $$TV^{\alpha-1}=\text{cost}\qquad tp^{\frac{1-\alpha}{\alpha}}=\text{cost}$$
>Dove per le trasformazioni adiabatiche $\alpha= \gamma= \frac{g_{p}}{c_{V}}$, per le trasformazioni isoterme $\alpha=1$, per le trasformazioni isobare $\alpha=0$ e per le trasformazioni isocore $\alpha\to\infty$. Si ha che per queste trasformazioni in generale: $$c_{\alpha}=c_{V}+ \frac{R}{1-\alpha}$$

>[!example] Dimostrazione
>Applichiamo l'equazione per il calore molare di una trasformazione generica di un gas perfetto, e sostituiamo $\delta Q=nc_{V}\text{d}T+pdV$: $$c_\alpha=c_{V}+ \frac{p}{n} \frac{\text{d}V}{\text{d}T}\bigg|_{\alpha}$$
>Usando l'equazione dei gas perfetti ci riduciamo alle sole variabili $T$ e $V$: $$\frac{p}{n}=R \frac{T}{V}\Longrightarrow c_{\alpha}=c_{V} + R \frac{T}{V}\frac{\text{d}V}{\text{d}T}\bigg|_{\alpha}$$
>Invertendo e derivando appropriatamente $TV^{\alpha-1}=C$ otteniamo: $$V= \frac{C^{\frac{1}{\alpha-1}}}{T^{\frac{1}{\alpha-1}}}\Longrightarrow \frac{\text{d}V}{\text{d}T}= - \frac{1}{\alpha-1}\frac{C^{\frac{1}{\alpha-1}}}{T^{\frac{1}{\alpha-1}}}$$
>Che sostituendo nell'equazione precedente: $$c_{\alpha}=c_{V}+RT \frac{T^{\frac{1}{\alpha-1}}}{C^{\frac{1}{\alpha-1}}}\cdot \left(- \frac{1}{\alpha-1}\right)\frac{C^{\frac{1}{\alpha-1}}}{T^{\frac{1}{\alpha-1}}}=c_{V}+ \frac{R}{1-\alpha}$$

Si osserva inoltre che il calore molare di una qualsiasi politropica è costante, e da esso si può ricavare immediatamente il calore scambiato lungo la trasformazione: $$Q=n c_{\alpha}\Delta T=cn_{V} \Delta T+ \frac{nR\Delta T}{1-\alpha}$$
Applicando il primo principio della termodinamica: $$L=Q-\Delta U=Q- nc_{V} \Delta T= \frac{nR \Delta T}{1-\alpha}$$
