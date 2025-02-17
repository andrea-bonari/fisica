Speculiamo sulle conseguenze della [[Leggi della dinamica#Seconda legge della dinamica|seconda legge della dinamica]].

>[!note] Lavoro elementare
>Definiamo il lavoro elementare di una forza $\overrightarrow{F}$ come $$dL\equiv \overrightarrow{F}\cdot d\overrightarrow{r}$$
>Dove $d\overrightarrow{r}$ è lo spostamento in un unità infinitesimale di tempo.

Quando una forza compie un lavoro positivo è detta forza motore, mentre quando il lavoro compiuto è negativo è detta forza resistiva.

>[!note] Lavoro di una forza su un corpo in moto da A a B
>$$L^{\overrightarrow{F}}_{AB}=\lim_{n\to\infty}\sum\limits_{k=1}^{n}\overrightarrow{F_{k}}\cdot \triangle \overrightarrow{r_{k}}=\int_{A}^{B}\overrightarrow{F_{k}}\cdot d\overrightarrow{r}$$
>Questa formula, nel caso in cui il moto sia rettilineo e la forza applicata è costante, allora la formula si semplifica in $$L_{AB}^{\overrightarrow{F}}=\lim_{n\to\infty}\sum\limits_{k=1}^{n}\overrightarrow{F_{k}}\cdot\triangle\overrightarrow{r_{k}}=\lim_{n\to\infty}\overrightarrow{F_{k}}\cdot\sum\limits^{n}_{k=1}\triangle\overrightarrow{r_{k}}=\overrightarrow{F_{k}}\cdot\lim_{n\to\infty}\sum\limits^{n}_{k=1}\triangle\overrightarrow{r_{k}}=\overrightarrow{F_{k}}\cdot \triangle\overrightarrow{r}$$
>Con $\triangle\overrightarrow{r}=\overrightarrow{r_{B}}-\overrightarrow{r_{A}}$
>Per quanto riguarda l'unità di misura:
>$$[L]=[F][\triangle r]=\text{N}\cdot\text{m}=\text{J}$$

>[!tip] Metodo di calcolo integrali di linea
>$$\int_{A}^{B}\overrightarrow{F_{k}}\cdot\triangle\overrightarrow{r}=\int_{A}^{B}F_{x}dx+\int_{A}^{B}F_{Y}dy=\int^{x_{B}}_{x^{A}}F_{x}(x)\text{d}x+\int^{y_{B}}_{y^{A}}F_{y}(y)\text{d}y$$

>[!tip] Proprietà di somma del lavoro
>$$\overrightarrow{F}=\overrightarrow{F_{1}}+\overrightarrow{F_{2}}+\cdots$$$$L^\overrightarrow{F}_{AB}=L^{\overrightarrow{F}_{1}}_{AB}+L^{\overrightarrow{F}_{2}}_{AB}+\cdots$$
>

## Teorema dell'energia cinetica
>[!note]
>Sia $\overrightarrow{F}$ la risultante delle forze applicate a un corpo che si muove da un punto $A$ a un punto $B$. Ricordando la seconda legge della dinamica:
>$$L^{\overrightarrow{F}}_{AB}=\int^{B}_{A}m\overrightarrow{a}\cdot d\overrightarrow{r}=\int^{B}_{A}m\overrightarrow{v}\text{ '}\cdot (\overrightarrow{v}\text{dt})= \frac{1}{2}m\cdot [v^{2}]^{B}_{A}= \frac{1}{2}mv^{2}_{B}- \frac{1}{2}m v^{2}_{A}$$
>Definendo l'energia cinetica del corpo come $$E_{k}= \frac{1}{2}mv_{k}^{2}$$
>Il lavoro diventa $$L_{AB}^{\overrightarrow{F}}=E_{k}(B)-E_{k}(A)$$

>[!tip]
>1. Per $L_{AB}^\overrightarrow{F}\neq0\Rightarrow$ variazione di energia cinetica, e quindi variazione di velocità.
>2. Se so calcolare $L^{\overrightarrow{F}}_{AB}$ posso calcolare $v_{B}$ nota $v_{A}$.

## Forze conservative
>[!note]
>Chiamo conservative, le forze che applicate in transito da $A$ a $B$ formano un lavoro che è indipendente dalla traiettoria scelta. E quindi il lavoro dipende soltanto dalle posizioni $A$ e $B$
>Una forza che gode di questa proprietà ha come formula: $$L^{\overrightarrow{F}}_{AB}=\int^{B}_{A}\overrightarrow{F}\cdot d\overrightarrow{r}=U(A)-U(B)$$
>Dove $U$ è l'energia potenziale associata a $\overrightarrow{F}$, ed è una funzione della posizione.

>[!abstract] Dimostrazione
>Sapendo matematicamente che $$U(P)=U(0)-\int^{P}_{0}\overrightarrow{F}\cdot d\overrightarrow{r}$$
>Possiamo definire
>$$\begin{align*}
\int_{A}^{B}\overrightarrow{F}\cdot d\overrightarrow{r}&=\int^{0}_{A}\overrightarrow{F}\cdot d\overrightarrow{r}+\int^{B}_{0}\overrightarrow{F}\cdot d\overrightarrow{r}\\
&=-\int^{A}_{0}\overrightarrow{F}\cdot d\overrightarrow{r}+\int^{B}_{0}\overrightarrow{F}\cdot d\overrightarrow{r}\\
&=\left[U(0)-\int^{A}_{0}\overrightarrow{F}\cdot d\overrightarrow{r}\right]-\left[U(0)-\int^{B}_{0}\overrightarrow{F}\cdot d\overrightarrow{r}\right]\\
&=U(A)-U(B)
\end{align*}$$

>[!tip] Osservazione
>Se $\overrightarrow{F}$ è una forza conservativa, allora il lavoro lungo un percorso chiuso è nullo.
>$$\int^{B}_{A}\overrightarrow{F}\cdot d\overrightarrow{r}=0\iff\text{il lavoro non dipende dalla traiettoria}\qquad A\equiv B$$

Due forze conservative che abbiamo visto sono la forza peso e la forza elastica, e in ciascuna definiamo $U$:
$$\begin{align*}U_{g}(y)=mgy&\quad\text{forza peso}\\
U_{e}(x)= \frac{1}{2}kx^{2}&\quad\text{forza elastica}\end{align*}$$

## Forze non conservative
La forza di attrito dinamico non è una forza conservativa

>[!abstract] Dimostrazione
>Per l'osservazione precedente una forza è conservativa se$$L^{\circlearrowleft}=\oint\overrightarrow{F}\cdot d\overrightarrow{r}=0$$
>Se applicata alla forza di attrito dinamica in un percorso chiuso
>$$L^{F_{AD}}_{\circlearrowleft}=\oint\overrightarrow{F_{AB}}\cdot d\overrightarrow{r}=-\overrightarrow{F_{AB}}\oint d\overrightarrow{r}=- F_{AB}\cdot \text{perimetro}<0$$
>E quindi non è conservativa, ma resistente.

## Energia meccanica
>[!note] Teorema di conservazione dell'energia meccanica
>In presenza di sole forze conservative, si conserva durante il moto, una nuova forma di energia, detta energia meccanica, data dalla somma di energia potenziale ed energia cinetica.

>[!abstract] Dimostrazione
>Dal teorema dell'energia cinetica$$L^{\overrightarrow{F}}_{AB}=E_{k}(B)-E_{k}(A)$$
>Prendiamo come ipotesi che la risultante $\overrightarrow{F}$ sia la somma di più forze conservative, possiamo quindi dire: $$L^{\overrightarrow{F_{1}}}_{AB}+L^\overrightarrow{F_{2}}_{AB}=E_{k}(B)-E_{k}(A)$$
>E quindi: $$\begin{align*}
&U_{1}(A)-U_{1}(B)+U_{2}(A)-U_{2}(B)=E_{k}(B)-E_{k}(A)\\
\Longrightarrow& U_{1}(A)+U_{2}(B)+E_{k}(A)=U_{1}(A)+U_{2}(B)+E_{k}(B)\\
\Longrightarrow& E_\text{mc}(A)=E_\text{mc}(B)
\end{align*}$$
>Definiamo quindi come energia meccanica $$E_\text{mc}(X)=E_{k}(x)+U$$

>[!tip]
>In presenza di forze conservative $U$  e $E_{k}$ si trasformano l'una nell'altra
>![[Pasted image 20240406170540.png]]

>[!note] Teorema di conservazione dell'energia meccanica per forze non conservative
>$$L^{F_\text{NonCons}}_{AB}\neq0\Rightarrow E(B)-E(A)\neq0$$
>Il lavoro $<0$ di forze non conservative accompagna una variazione di energia meccanica negativa, e viceversa.

## Problema inverso
Sapendo la definizione di energia potenziale possiamo ricavare la forza. $$\int^{B}_{A}\overrightarrow{F}\cdot d\overrightarrow{r}=U(A)-U(B)\iff\begin{cases}
F_{x}=- \frac{\partial U(x,y)}{\partial x} \\
F_{y}=- \frac{\partial U(x,y)}{\partial y}
\end{cases}$$
>[!tip] Punti di equilibrio
>Grazie a questa considerazione possiamo dire che se $$F_{x}=-U'(C)\neq0$$
>Con $C$ un punto sulla traiettoria, non avremo equilibrio. Al contrario se $$-U'(C)=0$$
>Avremo un **possibile** punto di equilibrio. Questo perché l'oggetto è in equilibrio solo se privo di velocità in quel momento.
>Nei punti di massimo si dice punto di equilibrio instabile, mentre nei punti di minimo si dice punto di equilibrio stabile. Se invece sul punto la funzione è costante, è detto punto di equilibrio indifferente.

## Potenza di una forza
>[!note]
>Si definisce la potenza di una forza ad un generico istante $t$ del moto come: $$P(t)= \frac{dL^{\overrightarrow{F}}}{dt}=\frac{\overrightarrow{F}\cdot d\overrightarrow{r}}{d\overrightarrow{t}}=\overrightarrow{F}\cdot \overrightarrow{v}$$
>Possiamo pensarlo come il tempo impiegato per lo spostamento
>$d\overrightarrow{r}$.
>Per quanto guarda le unità di misura:
>$$[P]= \frac{[L]}{[t]}= \frac{\text{j}}{\text{s}}=\text{W}$$
 
Il legame tra potenza e lavoro può anche essere esplicitato come integrale.

$$L^{\overrightarrow{F}}_{t_{1}t_{2}}=\int^{t_{2}}_{t_{1}}P(t)\text{d}t$$
Se $P$ è una costante possiamo quindi dire: $$L^{\overrightarrow{F}}_{t_{1}t_{2}}= P\triangle t$$