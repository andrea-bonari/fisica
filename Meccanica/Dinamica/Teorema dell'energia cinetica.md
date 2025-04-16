>[!note]
>Il teorema dell'energia cinetica (o teorema delle forze vive) afferma che: $$L_\overrightarrow{F} ^{AB}= E_{k}(B)-E_{k}(A)$$
>Con: $$E_{k}= \frac{1}{2}m v^{2}$$

>[!example] Dimostrazione
>Sia $\overrightarrow{F}$ la risultante delle forze applicate ad un punto materiale. Si ha che: $$\begin{align*}
L_\overrightarrow{F}^{AB}&= \int_{A}^{B}\overrightarrow{F}\cdot\text{d}\overrightarrow{r}=\int_{A}^{B}m\overrightarrow{a}\cdot\text{d}\overrightarrow{r}\\&=\int_{A}^{B}m\overrightarrow{v}\space'\cdot \overrightarrow{v}\text{ d}t= \int_{A}^{B}\frac{\text{d}}{\text{d}t} \left( \frac{1}{2}m||\overrightarrow{v}||^{2}\right)\text{ d}t\\&= \frac{1}{2}mv_{B}^{2}- \frac{1}{2}mv_{A}^{2}=E_{k}(B)-E_{k}(A)
\end{align*}$$

Se sono in grado di calcolare $L^{AB}_{\overrightarrow{F}}$, il teorema offre la possibilità di determinare $\Delta E_{k}$.
Se $L_{\overrightarrow{F}}^{AB}\neq0\iff \Delta E_{k}\neq0$

### Energia potenziale
>[!note]
>Se $F$ è conservativa, allora: $$L_\overrightarrow{F}^{AB}= U(A)-U(B)$$
>Dove $U$ è l'energia potenziale, dipendente solo dalla posizione, associata alla forza $F$.

>[!tip]
>Una forza è detta conservativa quando il lavoro compiuto dalla forza non dipende dalla traiettoria. Il lavoro compiuto da una forza conservativa dipende solo dal punto iniziale e dal punto finale.

>[!example] Dimostrazione
>Se $\overrightarrow{F}$ è conservativa, è possibile introdurre una funzione scalare $U$ definita come: $$U(P)=U(O)-\int_{O}^{P} \overrightarrow{F}\cdot \text{d}\overrightarrow{r}$$
>Dove $O$ è un punto generico nello spazio, e $U(O)$ è un valore arbitrario. Questa definizione ha senso perché l'integrale non dipende dal percorso. A questo punto: $$\begin{align*}
>L_{\overrightarrow{F}}^{AB}&= \int_{A}^{B}\overrightarrow{F}\cdot \text{d}\overrightarrow{r}=\int_{A}^{O}\overrightarrow{F}\cdot \text{d}\overrightarrow{r}+\int_{O}^{B}\overrightarrow{F}\cdot \text{d}\overrightarrow{r}\\
>&= \left[U(O)-\int_{A}^{O}\overrightarrow{F}\cdot \text{d}\overrightarrow{r}\right]-\left[U(O)-\int_{O}^{B}\overrightarrow{F}\cdot \text{d}\overrightarrow{r}\right]\\
&= U(A)-U(B)
\end{align*}$$

Si ha che la forza peso e la forza elastica sono conservative: $$\begin{align*}
L_{m\overrightarrow{g}}^{AB}&=  mgy_{A}-mgy_{B}=U_{g}(A)-U_{g}(B)\\
L_{-kx}^{AB}&= \frac{1}{2}kx_{A}^{2}- \frac{1}{2}kx_{B}^{2}=U_{e}(A)-U_{e}(B)
\end{align*}$$
### Teorema di conservazione dell'energia meccanica
>[!note]
>Sia per ipotesi, la risultante di una forza composta da sole forze conservative. Definiamo la somma di tutte le energie potenziali e cinetica di un punto come energia meccanica. Si ha che essa si conserva attraverso il moto da un generico punto $A$ ad un generico punto $B$: $$E_\text{mecc}(B)=E_\text{mecc}(A)$$
>Con $E_{\text{mecc}}(P)=U(P)+E_{k}(P)$.

>[!example] Dimostrazione
>Sia $\overrightarrow{F}=\overrightarrow{F}_{1}+\overrightarrow{F}_{2}$ la risultante di forze conservative: $$\begin{align*}
>L_{\overrightarrow{F}_{1}}^{AB}+L^{AB}_{\overrightarrow{F}_{2}}&= E_{k}(B)-E_{k}(A)=U_{1}(A)-U_{1}(B)+U_{2}(A)-U_{2}(B)\\
>&\Rightarrow   U_{1}(B)+U_{2}(B)+E_{k}(B)= U_{1}(A)+U_{2}(A)+E_{k}(A)\\
>&\Rightarrow E_\text{mecc}(B)=E_\text{mecc}(A)
>\end{align*}$$

In presenza di forze conservative, l'energia potenziale si trasforma in cinetica.

Nel caso in cui siano presenti anche forze non conservative il teorema di conservazione dell'energia meccanica afferma che se è presente una variazione di energia meccanica allora esiste una forza non conservativa il cui lavoro è diverso da zero: $$\Delta E_{\text{mecc}}\neq0\iff \exists \overrightarrow{F}_{\text{NonCons}}:\quad L^{AB}_{\overrightarrow{F}}\neq0$$
E di conseguenza il teorema, in caso siano presenti forze non conservative, afferma che: $$\Delta E_\text{mecc}=L_{\overrightarrow{F}_\text{NonCons},\text{tot}}$$
### Potenza di una forza
>[!note]
>Si definisce potenza di una forza come: $$P(t)=\overrightarrow{F}(t)\cdot\overrightarrow{v}(t)\qquad [P]=\text{W}$$
>Si ha che la potenza di un lavoro è: $$P= \frac{L_{\overrightarrow{F}}^{\Delta \overrightarrow{r}}}{\Delta t}$$

>[!example] Dimostrazione
>$$P=\frac{\text{d}}{\text{d}t} L= \frac{\overrightarrow{F}\cdot \text{d}\overrightarrow{r}}{\text{d}t}=\overrightarrow{F}\cdot\overrightarrow{v}$$

