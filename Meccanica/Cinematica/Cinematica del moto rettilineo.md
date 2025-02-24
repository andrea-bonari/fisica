>[!note]
>La cinematica del moto rettilineo è lo studio della cinematica con legge oraria: $$x=x(t)$$

Siano $t_{1}$ e $t_{2}$ due istanti di tempo con $t_{2}>t_{1}$, e $x_{1}=x(t_{1})$ e $x_{2}=x(t_{2})$ le rispettive posizioni nei due istanti di tempo. Lo spostamento è definito come: $$\Delta x=x_{2}-x_{1}$$
Il segno dello spostamento determina se esso è concorde con l'asse.
### Velocità
>[!note]
>Sia $t$ un generico istante. Possiamo definire la velocità istantanea come: $$v(t)= \frac{\text{d}}{\text{d}t} x(t)\qquad [v]= \frac{\text{m}}{\text{s}}$$

>[!example] Dimostrazione
>Si considerino i due istanti $t_{2},t_{1}$ con $t_{2}>t_{1}$, e le rispettive posizioni $x_{1}$ e $x_{2}$, la velocità media è definita come: $$\langle v\rangle= \frac{x_{2}-x_{1}}{t_{2}-t_{1}}= \frac{\Delta x}{\Delta t}\qquad [\langle v\rangle]= \frac{\text{m}}{\text{s}}$$
>Facendo tendere $t_{2}$ a $t_{1}$ si ottiene: $$\lim_{t_{2}\to t_{1}} \frac{x_{2}-x_{1}}{t_{2}-t_{1}}=\lim_{\Delta t\to 0} \frac{\Delta x}{\Delta t}$$
>Che per definizione è la derivata di $x(t)$ rispetto a $t$.

### Accelerazione
>[!note]
>Sia $t$ un generico istante. Possiamo definire l'accelerazione istantanea come: $$a(t)= \frac{\text{d}}{\text{d}t} v(t) =\frac{\text{d}^{2}}{\text{d}{t}^{2}} x(t)\qquad [a]= \frac{\text{m}}{\text{s}^{2}}$$

>[!example] Dimostrazione
>Si considerino i due istanti $t_{2},t_{1}$ con $t_{2}>t_{1}$, e le rispettive velocità istantanee $v_{1}$ e $v_{2}$, l'accelerazione media è definita come: $$\langle a\rangle= \frac{v_{2}-v_{1}}{t_{2}-t_{1}}= \frac{\Delta v}{\Delta t}\qquad [\langle a\rangle]= \frac{\text{m}}{\text{s}^{2}}$$
>Facendo tendere $t_{2}$ a $t_{1}$ si ottiene: $$\lim_{t_{2}\to t_{1}} \frac{v_{2}-v_{1}}{t_{2}-t_{1}}= \lim_{\Delta t\to 0} \frac{\Delta v}{\Delta t}$$
>Che per definizione è la derivata di $v(t)$ rispetto a $t$, e di conseguenza la derivata seconda di $x(t)$ rispetto a $t$.

### Problema inverso
>[!note]
>È possibile applicare il Teorema Fondamentale del Calcolo Integrale per risalire dall'accelerazione alla velocità istantanea, conoscendo la condizione iniziale $v_{0}=v(t_{0})$ dove $t_{0}$ è un istante generico fissato: $$v(t)-v_{0}=\int_{t_{0}}^{t}a(t)\text{ d}t$$
>Analogamente, conoscendo la condizione iniziale $x_{0}=x(t_{0})$ dove $t_{0}$ è un istante generico fissato: $$x(t)-x_{0}=\int_{t_{0}}^{t}v(t)\text{ d}t$$

### Moti particolari
>[!note] Moto Rettilineo Uniformemente Accelerato
>Avendo un accelerazione costante $a\in\mathbb{R}$, è possibile ricavare la velocità utilizzando il problema inverso: $$v(t)=v_{0}+a(t-t_{0})$$
>Analogamente, nota la velocità, è possibile ricavare la legge oraria: $$x(t)=x_{0}+v_{0}(t-t_{0})+ \frac{1}{2}a(t-t_{0})^{2}$$

>[!note] Moto di caduta libera
>Il moto di caduta libera è un MRUA rivolto verso il basso, con accelerazione costante di: $$g= 9.81 \frac{\text{m}}{\text{s}^{2}}$$
>Tutti i corpi in prossimità della superficie terrestre sono soggetti a questo moto.

>[!note] Moto Rettilineo Uniforme
>Avendo un accelerazione nulla, si ha una velocità costante $v\in\mathbb{R}$. È possibile quindi ricavare la legge oraria: $$x(t)=x_{0}+v_{0}(t-t_{0})$$

### Ascissa curvilinea
>[!note]
>È possibile considerare un ascissa sdraiata su una curva per rappresentare moti non rettilinei con una legge oraria $s=s(t)$. Tutte le definizioni precedenti sono analoghe per l'ascissa curvilinea.
>![[Pasted image 20240223131150.png]]
>

