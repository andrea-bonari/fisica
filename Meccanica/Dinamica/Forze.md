### Forza peso
>[!note]
>La forza peso è la forza a cui è soggetto ogni corpo in prossimità della superficie terrestre: $$\overrightarrow{F}_{P}=m\cdot \overrightarrow{g}$$

In presenza della sola forza peso il moto dell'oggetto è un moto di caduta libera.

>[!tip] Bilancia
>La bilancia è un dinamometro che misura il peso, infatti usa come unità di misura della forza $K_{gp}=9.81\text{ N}$, e restituisce di conseguenza la massa in $K_{gp}$

>[!tip] Forza gravitazionale sulla luna
>La forza gravitazionale sulla superficie lunare equivale a circa $\frac{1}{6}$ di quella terrestre: $$g_{L}=\approx \frac{1}{6}g$$

### Reazione vincolare
>[!note]
>La reazione vincolare è la forza che due oggetti a contatto si scambiano perpendicolarmente alla superficie di contatto: $$\overrightarrow{N}$$

### Forze di attrito
>[!note]
>Le forze di attrito sono le forze che due corpi a contatto si scambiano parallelamente alla superficie di contatto. Si distinguono in forza di attrito statico e dinamico.
>
>Il caso statico si verifica quando due corpi a contatto sono in quiete relativa: $$0\leq ||\overrightarrow{F}_{AS}||< ||\overrightarrow{F}_{AS_{max}}|| =\mu_{S}||\overrightarrow{N}||$$
>Dove $\mu_{S}<1$ è il coefficiente di attrito statico e dipende dalla natura delle superfici a contatto.
>
>Il caso dinamico si verifica quando due corpi a contatto sono in stato di moto relativo:
>$$||\overrightarrow{F}_{AD}||=\mu_{D}||\overrightarrow{N}||$$
>Dove $\mu_{D}<1$ è il coefficiente di attrito dinamico. Si ha che: $$\mu_{D}<\mu_{S}<1$$

### Tensione
>[!note]
>La tensione è la forza esercitata da una fune parallela alla sua direzione. È una forza di trazione. La tensione di una esercitata da una fune tra collegata tra due corpi, di massa $M$ in movimento e $m$ in trazione, è definita come: $$||\overrightarrow{T}||= \frac{M}{M+m}||\overrightarrow{F}||$$
>![[Pasted image 20240305130032.png | center]]

>[!tip] Fune
>Le funi sono degli strumenti che permettono di trasmettere forze da un punto all'altro.
>
>In questo corso avremo come ipotesi che le funi siano di massa trascurabile, inestendibili e lisce.

### Forza elastica
>[!note]
>La forza elastica è la forza esercitata da una molla vincolata a un punto fisso per tornare in posizione di riposo. Identifichiamo con il punto $O$ l'estremo della molla quando a riposo. Se noi indichiamo con $x$ l'ascissa del punto libero allora: $$\overrightarrow{F}_{e}=-kx\hat{u}_{x}\qquad [k]= \frac{\text{N}}{\text{m}}$$
>dove $k$ è la costante elastica della molla e dipende dalla rigidità e forza della molla. Questa è detta legge di Hooke.
>![[Pasted image 20240305130616.png | center]]

>[!tip]
>Si ha che per molle in serie: $$\frac{1}{k_{\text{eq}}}= \sum\limits_{i=1}^{n} \frac{1}{k_{i}}$$
>Mentre per molle in parallelo: $$k_{\text{eq}}= \sum\limits_{i=1}^{n}k_{i}$$

Considerando che l'equazione del moto e considerando $x''(t)=a(t)$ si ricava l'EDO del secondo ordine: $$x''(t)+\omega^{2}x(t)=0$$
Dove $\omega^{2}:= \frac{k}{m}$. Si dimostra facilmente che questa ha soluzione: $$x(t)=A\cos(\omega t+\varphi)$$
Che è l'equazione del moto armonico con periodo $T= 2\pi\sqrt{\frac{m}{k}}$.

### Forze ad azioni centripeta
>[!note]
>Nel caso di un moto circolare uniforme, dal punto di vista dinamico, un moto circolare uniforme è creato da:
>1. Moto di un corpo vincolato ad una fune (tensione fune)
>2. Moto di un corpo lungo un binario esterno circolare (reazione vincolare)
>3. Moto circolare di un auto (attrito statico)
>
>Avendo un raggio $R$ in ciascuno di questi moti, si ha che: $$a_{n}= \frac{v^{2}}{R}= \omega^{2}R\neq0$$
>Siccome l'accelerazione centripeta è non nulla, deve esistere una forza ad azione centripeta in tutti questi casi.

>[!tip]
>Se un sistema di riferimento è inerziale allora non esiste la forza centrifuga. Essa è considerata una forza apparente: $$\overrightarrow{F}_{cf}=-m \frac{v_{0}^{n}}{R}\hat{u}_{n}$$
>