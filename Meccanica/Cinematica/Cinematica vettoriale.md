>[!note]
>La cinematica vettoriale è lo studio di un moto con legge oraria: $$\overrightarrow{r}=\overrightarrow{r}(t)\qquad \overrightarrow{r}\in\mathbb{R}^{n}$$
>È un metodo alternativo all'ascissa curvilinea per dare più dettaglio a un moto nel piano o nello spazio.

Il vettore posizione $\overrightarrow{r}$ è definito come il segmento $\overline{OP}$. Più nel dettaglio $$\overrightarrow{r}(t)=x(t)\hat{u}_{x}+y(t)\hat{u}_{y}$$
Siano $t_{1}$ e $t_{2}$ due istanti di tempo con $t_{2}>t_{1}$, e $\overrightarrow{r}_{1}=\overrightarrow{r}(t_{1})$ e $\overrightarrow{r}_{2}=\overrightarrow{r}(t_{2})$ le rispettive posizioni nei due istanti di tempo. Lo spostamento è definito come: $$\Delta \overrightarrow{r}=\overrightarrow{r}_{2}-\overrightarrow{r}_{1}$$
### Rappresentazione intrinseca
>[!note]
>In un generico punto $\overrightarrow{P}(t)$, si introduce un versore $\hat{u}_{t}$, tangente alla traiettoria in quel punto, e un versore $\hat{u}_{n}$ perpendicolare a $\hat{u}_{t}$ e rivolto verso il centro di curvatura della traiettoria.
>Il centro di curvatura è il centro di un cerchio tangente alla traiettoria in $\overrightarrow{P}(t)$ di raggio di curvatura $\rho$ tale da approssimare la traiettoria in $\overrightarrow{P}(t)$.
>
>![[Pasted image 20250221120138.png]]

### Velocità istantanea vettoriale
>[!note]
>Sia $t$ un generico istante. Possiamo definire la velocità istantanea come: $$\overrightarrow{v}(t)= \frac{\text{d}}{\text{d}t} \overrightarrow{r}(t)\qquad [\overrightarrow{v}]= \frac{\text{m}}{\text{s}}$$
>In base alla rappresentazione usata si calcola in modo diverso. In rappresentazione cartesiana: $$\overrightarrow{v}(t)= \underbrace{x'(t)}_{v_{x}(t)}\hat{u}_{x}+\underbrace{y'(t)}_{v_{y}(t)}\hat{u}_{y}$$
>In rappresentazione intrinseca:
>$$\overrightarrow{v}(t)=|\overrightarrow{r}\space'(t)|\hat{u}_{t}$$
>

>[!example] Dimostrazione
>Si considerino i due istanti $t_{2},t_{1}$ con $t_{2}>t_{1}$, e le rispettive posizioni $\overrightarrow{r}_{1}$ e $\overrightarrow{r}_{2}$, la velocità media è definita come: $$\langle \overrightarrow{v}\rangle= \frac{\overrightarrow{r}_{2}-\overrightarrow{r}_{1}}{t_{2}-t_{1}}= \frac{\Delta x}{\Delta t}\qquad [\langle \overrightarrow{v}\rangle]= \frac{\text{m}}{\text{s}}$$
>Facendo tendere $\overrightarrow{r}_{2}$ a $\overrightarrow{r}_{1}$ si ottiene: $$\lim_{t_{2}\to t_{1}} \frac{\overrightarrow{r}_{2}-\overrightarrow{r}_{1}}{t_{2}-t_{1}}=\lim_{\Delta t\to 0} \frac{\Delta \overrightarrow{r}}{\Delta t}$$
>Che per definizione è la derivata di $\overrightarrow{r}(t)$ rispetto a $t$.
>
>In rappresentazione cartesiana si calcola con la regola del prodotto, e siccome i versori sono costanti si ottiene: $$\overrightarrow{v}= \frac{\text{d}}{\text{d}t} \overrightarrow{r}(t)= \frac{\text{d}}{\text{d}t} \bigg(x(t)\hat{u}_{x}+y(t)\hat{u}_{y} \bigg)= x'(t)\hat{u}_{x}+y'(t)\hat{u}_{y}$$
>In rappresentazione intrinseca: $$\overrightarrow{v}(t)=\lim_{\Delta t\to 0} \frac{\Delta \overrightarrow{r}}{\Delta t}=\lim_{\Delta t\to0} \frac{|\Delta \overrightarrow{r}|}{\Delta t}\hat{u}_{t}=\lim_{\Delta t\to0} \frac{\Delta s}{\Delta t}\hat{u}_{t}=s'(t)\hat{u}_{t}$$

### Accelerazione istantanea vettoriale
>[!note]
>Sia $t$ un generico istante. Possiamo definire l'accelerazione istantanea come: $$\overrightarrow{a}(t)= \frac{\text{d}}{\text{d}t} \overrightarrow{v}(t) =\frac{\text{d}^{2}}{\text{d}{t}^{2}} \overrightarrow{r}(t)\qquad [\overrightarrow{a}]= \frac{\text{m}}{\text{s}^{2}}$$
>In base alla rappresentazione usata si calcola in modo diverso. In rappresentazione cartesiana: $$\overrightarrow{a}(t)= \underbrace{v'_{x}(t)}_{a_{x}(t)}\hat{u}_{x}+\underbrace{v'_{y}(t)}_{a_{y}(t)}\hat{u}_{y}$$
>In rappresentazione intrinseca: 

>[!example] Dimostrazione
>Si considerino i due istanti $t_{2},t_{1}$ con $t_{2}>t_{1}$, e le rispettive velocità istantanee $\overrightarrow{v}_{1}$ e $\overrightarrow{v}_{2}$, l'accelerazione media è definita come: $$\langle \overrightarrow{a}\rangle= \frac{\overrightarrow{v}_{2}-\overrightarrow{v}_{1}}{t_{2}-t_{1}}= \frac{\Delta \overrightarrow{v}}{\Delta t}\qquad [\langle \overrightarrow{a}\rangle]= \frac{\text{m}}{\text{s}^{2}}$$
>Facendo tendere $t_{2}$ a $t_{1}$ si ottiene: $$\lim_{t_{2}\to t_{1}} \frac{\overrightarrow{v}_{2}-\overrightarrow{v}_{1}}{t_{2}-t_{1}}= \lim_{\Delta t\to 0} \frac{\Delta \overrightarrow{v}}{\Delta t}$$
>Che per definizione è la derivata di $\overrightarrow{v}(t)$ rispetto a $t$, e di conseguenza la derivata seconda di $\overrightarrow{r}(t)$ rispetto a $t$.
>
>In rappresentazione cartesiana si calcola con la regola del prodotto, e siccome i versori sono costanti si ottiene: $$\overrightarrow{a}= \frac{\text{d}}{\text{d}t} \overrightarrow{v}(t)= \frac{\text{d}}{\text{d}t} \bigg(v_{x}(t)\hat{u}_{x}+v_{y}(t)\hat{u}_{y} \bigg)= v'_{x}(t)\hat{u}_{x}+v'_{y}(t)\hat{u}_{y}$$
>In rappresentazione intrinseca: $$\overrightarrow{a}= \frac{\text{d}}{\text{d}t} \overrightarrow{v}(t)= \frac{\text{d}}{\text{d}t} \bigg(|\overrightarrow{r}\space'(t)| \hat{u}_{t} \bigg)= \frac{\text{d}}{\text{d}t} |\overrightarrow{r}\space'(t)|\cdot\hat{u}_{t}+|\overrightarrow{r}\space'(t)|\cdot \underbrace{\frac{\text{d}}{\text{d}t} \hat{u}_{t}}_{\neq0\text{ sse non è costante}}$$

