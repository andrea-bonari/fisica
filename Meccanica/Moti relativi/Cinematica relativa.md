>[!note]
>Sia $S$ un sistema di riferimento inerziale caratterizzato da una coppia di assi coordinati $x$ e $y$, e sia $S'$ un sistema di riferimento in stato di moto relativo rispetto a $S$ caratterizzato da una coppia di assi coordinati $y'$ e $x'$. Assumiamo di conoscere la velocità di $S'$ rispetto all'origine di $S$ $\overrightarrow{V}_{0'}$ e la sua velocità angolare di $S'$ $\overrightarrow{\omega}$ attorno a $O'$ rispetto a $S$.
>![[Pasted image 20250325143039.png|center]]
>Osserviamo la posizione di un generico punto $P$. Sia $\overrightarrow{r}'$ il vettore posizione di $P$ rispetto a $S'$, $\overrightarrow{r}$ il vettore posizione di $P$ rispetto a $S$, e $\overrightarrow{R}$ il vettore posizione di $O'$ rispetto a $S$. Vale: $$\overrightarrow{r}(t)=\overrightarrow{r}\space'(t)+\overrightarrow{R}(t)$$

### Legge di trasformazione delle velocità
>[!note]
>È possibile esplicitare il legame di velocità tra sistemi di riferimento diversi con l'equazione: $$\overrightarrow{v}\space'=\overrightarrow{v}-(\overrightarrow{v}_{O'}+\overrightarrow{\omega}\times\overrightarrow{r}\space')$$
>Dove $\overrightarrow{v}_{\tau}=\overrightarrow{v}_{O'}+\overrightarrow{\omega}\times\overrightarrow{r}\space'$ è detta velocità di trascinamento ed è definita come la velocità di un punto $P$ solidale a $S'$ nel sistema di riferimento $S$.

>[!example] Dimostrazione
>Sappiamo che $\overrightarrow{r}\space'=\overrightarrow{r}-\overrightarrow{R}$, quindi per ricavare la velocità rispetto a $S$: $$\frac{\text{d}\overrightarrow{r}\space'}{\text{d}t}\bigg|_{S}=\frac{\text{d}\overrightarrow{r}}{\text{d}t}\bigg|_{S}-\frac{\text{d}\overrightarrow{R}}{\text{d}t}\bigg|_{S}$$
>E quindi: $$\begin{align*}
>\frac{\text{d}\overrightarrow{r}\space'}{\text{d}t}\bigg|_{S}&=  \frac{\text{d}}{\text{d}t} \left(x'\hat{u}_{x}'+y'\hat{u}_{y}' \right)= \underbrace{\frac{\text{d}x'}{\text{d}t}\hat{u}_{x}'+ \frac{\text{d}y'}{\text{d}t}\hat{u}_{y}'}_{\overrightarrow{v}\space'}+x'\frac{\text{d}\hat{u}_{x}'}{\text{d}t}+y'\frac{\text{d}\hat{u}_{y}'}{\text{d}t}\\
>&= \overrightarrow{v}\space'+ x' \frac{\text{d}\theta}{\text{d}t}\hat{u}_{\theta}+ y' \frac{\text{d}\theta}{\text{d}t}\hat{u}_{\theta}=\overrightarrow{v}\space'+x'\omega\hat{u}_{\theta}+y'\omega\hat{u}_{\theta}\\
>&=  \overrightarrow{v}\space'+ x'\overrightarrow{\omega}\times\hat{u}_{x}'+y'\overrightarrow{\omega}\times\hat{u}_{y}'=\overrightarrow{v}\space'+ \overrightarrow{\omega}\times \left(x'\hat{u}_{x}'+y'\hat{u}_{y}'\right)=\overrightarrow{v}\space'+\overrightarrow{\omega}\times\overrightarrow{r}\space'
>\end{align*}$$
>Dove $v'$ è la velocità di $P$ in $S'$. Si ha quindi che: $$\overrightarrow{v}\space'+\overrightarrow{\omega}\times\overrightarrow{r}\space'=\overrightarrow{v}-\overrightarrow{v}_{O'}$$
>E di conseguenza $$\overrightarrow{v}\space'=\overrightarrow{v}-(\overrightarrow{v}_{O'}+\overrightarrow{\omega}\times\overrightarrow{r}\space')$$

### Legge di trasformazione delle accelerazioni
>[!note]
>È possibile esplicitare il legame di accelerazione tra sistemi di riferimento diversi con l'equazione: $$\overrightarrow{a}\space'=\overrightarrow{a}-(\overrightarrow{a}_{O'}+\overrightarrow{\omega}\times\overrightarrow{\omega}\times\overrightarrow{r}\space'+\overrightarrow{\alpha}\times\overrightarrow{r}\space')-2\overrightarrow{\omega}\times\overrightarrow{v}\space'$$
>Dove $\overrightarrow{a}_{\tau}=(\overrightarrow{a}_{O'}+\overrightarrow{\omega}\times\overrightarrow{\omega}\times\overrightarrow{r}\space'+\overrightarrow{\alpha}\times\overrightarrow{r}\space')$ è detta accelerazione di trascinamento e corrisponde all'accelerazione misurata in $S$ di $P$ in quiete su $S'$, mentre $\overrightarrow{a}_\text{cor}=2\overrightarrow{\omega}\times\overrightarrow{v}\space'$ è detta accelerazione di Coriolis.

>[!example] Dimostrazione
>Sappiamo che $\overrightarrow{v}\space'=\overrightarrow{v}-(\overrightarrow{v}_{O'}+\overrightarrow{\omega}\times\overrightarrow{r}\space')$, quindi per ricavare la velocità rispetto a $S$: $$\frac{\text{d}\overrightarrow{v}\space'}{\text{d}t}\bigg|_{S}= \underbrace{\frac{\text{d}\overrightarrow{v}}{\text{d}t}\bigg|_{S}}_{\overrightarrow{a}}- \underbrace{\frac{\text{d}\overrightarrow{v}_{O'}}{\text{d}t}\bigg|_{S}}_{\overrightarrow{a}_{O'}}-\frac{\text{d}}{\text{d}t} \left(\overrightarrow{\omega}\times\overrightarrow{r}\space'\right)\bigg|_{S}$$
>Dove $\overrightarrow{a}$ è l'accelerazione di $P$ in $S$, e $\overrightarrow{a}_{O'}$ è l'accelerazione di $O'$ in $S$. Quindi: $$\begin{align*}
>\frac{\text{d}\overrightarrow{v}\space'}{\text{d}t}\bigg|_{S}&= \frac{\text{d}\overrightarrow{v}\space'}{\text{d}t}\bigg|_{S'}+\overrightarrow{\omega}\times\overrightarrow{v}\space'=\overrightarrow{a}\space'+\omega\times\overrightarrow{v}\space'
>\end{align*}$$
>Infine calcoliamo: $$\frac{\text{d}}{\text{d}t} \left(\overrightarrow{\omega}\times\overrightarrow{v}\space'\right)= \frac{\text{d}\overrightarrow{\omega}}{\text{d}t}\bigg|_{S}\times\overrightarrow{r}\space'+\overrightarrow{\omega}\times \frac{\text{d}\overrightarrow{r}\space'}{\text{d}t}\bigg|_{S}=\overrightarrow{\alpha}\times\overrightarrow{r}\space'+\overrightarrow{\omega}\times\left(\overrightarrow{v}\space'+\overrightarrow{\omega}\times\overrightarrow{r}\space'\right)$$
>Unendo il tutto otteniamo: $$\overrightarrow{a}\space'+\overrightarrow{\omega}\times\overrightarrow{v}\space'=\overrightarrow{a}-\overrightarrow{a}_{O'}-\overrightarrow{\alpha}\times\overrightarrow{r}\space'-\overrightarrow{\omega}\times\overrightarrow{v}\space'-\overrightarrow{\omega}\times\overrightarrow{\omega}\times\overrightarrow{r}\space'$$
>Che semplificato diventa: $$\overrightarrow{a}\space'=\overrightarrow{a}-(\overrightarrow{a}_{O'}+\overrightarrow{\omega}\times\overrightarrow{\omega}\times\overrightarrow{r}\space'+\overrightarrow{\alpha}\times\overrightarrow{r}\space')-2\overrightarrow{\omega}\times\overrightarrow{v}\space'$$



