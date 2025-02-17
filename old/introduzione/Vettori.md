>[!tip]
>[Riferimento al corso di Geometria e algebra lineare](https://andrea-bonari.github.io/MAT-03)

>[!tip]
>Generalmente in fisica si usa la rappresentazione cartesiana, tuttavia può essere più facile la sua rappresentazione in colonna per una visualizzazione più chiara.

>[!note]
>Un vettore è una $n$-upla di numeri reali caratterizzato da norma, direzione e verso, può essere definito come vettore colonna o vettore riga: $$\overrightarrow{v}\in\mathbb{R}^{n}\qquad\overrightarrow{v}=\begin{pmatrix}v_{1}\\v_{2}\\\vdots\\v_{n}\end{pmatrix}$$

Un $n$-vettore descrive la posizione, quindi le coordinate, di un punto in uno spazio $n$-dimensionale. La norma (norma euclidea, norma 2) di un vettore è la lunghezza del vettore stesso, è definita con le seguenti notazioni e si calcola con la seguente formula
$$||\overrightarrow{v}||=|\overrightarrow{v}|=v=\sqrt{\sum\limits_{i=0}^{n}v_{i}^{2}}$$
### Rappresentazione quantitativa
>[!note]
>Un vettore nel piano può essere rappresentato dalla sua norma e da un angolo $\theta$
>$$\overrightarrow{v}=\{|\overrightarrow{v}|, \theta\}$$

### Rappresentazione cartesiana
>[!note]
>Dato un vettore $\overrightarrow{a}$:
>- $\overrightarrow{a}=\underbrace{\overrightarrow{a_{x}}+\overrightarrow{a_{y}}}_{\text{i componenti}}$
>- $\overrightarrow{a}=\underbrace{a_{x}\overrightarrow{u_{x}}+a_{y}\overrightarrow{u_{y}}}_{\text{le componenti}}$
>
>In generale vale $\overrightarrow{a}=|\overrightarrow{a}|\cos(\theta_{a})\overrightarrow{u_{x}}+|\overrightarrow{a}|\sin(\theta_{a})\overrightarrow{u_{y}}$
>
>$$\begin{cases}a_{x}=|\overrightarrow{a}|\cos\theta\\|\overrightarrow{a}|\sin\theta\end{cases}\iff\begin{cases}|\overrightarrow{a}|=\sqrt{a_{x}^{2}+a_{y}^{2}}\\\tan\theta= \frac{a_{y}}{a_{x}}\end{cases}$$

### Prodotto di un vettore per uno scalare
>[!note]
>Dati uno scalare $a\in\mathbb{R}$ e un vettore $\overrightarrow{v}\in\mathbb{R}^{n}$
>Il prodotto $n\cdot\overrightarrow{v}$ è $$n\cdot\begin{pmatrix}v_{1}\\v_{2}\\\vdots\\v_{n}\end{pmatrix}=\begin{pmatrix}n\cdot v_{1}\\ n\cdot v_{2}\\\vdots\\ n\cdot v_{n}\end{pmatrix}$$

### Somma e differenza
>[!note]
>Dati due vettori $a,b\in\mathbb{R}^{n}$
>$$a+b=\begin{pmatrix}a_{1}+b_{1}\\a_{2}+b_{2}\\\vdots\\a_{n}+b_{n}\end{pmatrix}$$

### Versori e normalizzazione
>[!note]
>Un vettore con norma unitaria viene definito versore e in simboli si indica:
>$$\widehat{v}\iff|\overrightarrow{v}|=1$$
>
>Per normalizzare un vettore si deve dividerlo per la norma
>$$\widehat{v}=\frac{\overrightarrow{v}}{|\overrightarrow{v}|}$$

### Prodotto scalare
>[!note]
>Il prodotto scalare tra due vettori da come risultato la somma del prodotto tra le singole componenti corrispondenti dei vettori
>$$\overrightarrow{v}\cdot\overrightarrow{w}=|\overrightarrow{v}||\overrightarrow{w}|\cdot\cos\theta=v_{1}w_{1}+v_{2}+w_{2}+\cdots+v_{n}w_{n}$$dove $\theta$ è l'angolo minimo tra i due vettori.
>
>Il valore risultante è la norma della proiezione di $v$ su $w$.

### Prodotto vettore
>[!note]
>Siano $\overrightarrow{a},\overrightarrow{b}$ due vettori, allora il prodotto vettore $\overrightarrow{a}\times\overrightarrow{b}=\overrightarrow{c}$ ha:
>- modulo: $|\overrightarrow{c}|=|\overrightarrow{a}||\overrightarrow{b}||\sin\theta|$ dove $\theta$ è l'angolo minimo.
>- direzione perpendicolare al piano su cui giaciono i due vettori.
>- Verso: determinato con regola della mano destra.
>
>Può essere calcolato con l'abuso di notazione:
>$$\overrightarrow{c}=\begin{vmatrix}\overrightarrow{i}&\overrightarrow{j}&\overrightarrow{k}\\a_{1}&a_{2}&a_{3}\\b_{1}&b_{2}&b_{3}\end{vmatrix}$$
>
>Valgono le proprietà:
>- $\overrightarrow{a}\times\overrightarrow{b}=\overrightarrow{c}\iff\overrightarrow{b}\times\overrightarrow{a}=-\overrightarrow{c}$

### Derivata di un vettore
>[!note]
>Dato un vettore $\overrightarrow{a}$ la sua derivata $\overrightarrow{a}\text{ }'$ equivale al vettore che ha come componenti le derivate dei componenti di $\overrightarrow{a}$:
>$$\frac{d}{dt} \begin{pmatrix}a_{1}(x)\\a_{2}(x)\\\vdots\\a_{n}(x)\end{pmatrix}=\begin{pmatrix}a_{1}'(x)\\a_{2}'(x)\\\vdots\\a'_{n}(x)\end{pmatrix}$$

### Integrale di un vettore
>[!note]
>Analogamente alla derivata di un vettore l'integrale di un vettore ha come componenti i componenti integrati del vettore:
>$$\int\begin{pmatrix}a_{1}(x)\\a_{2}(x)\\\vdots\\a_{n}(x)\end{pmatrix}=\begin{pmatrix}\int a_{1}(x)\\\int a_{2}(x)\\\vdots\\\int a_{n}(x)\end{pmatrix}$$
