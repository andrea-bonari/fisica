Esaminiamo un sistema di riferimento $S$, e un ulteriore sistema di riferimento $S'$, che studiano entrambi la posizione di un punto $P$ nello spazio.

Supponiamo che il sistema $S'$ possa muoversi rispetto a $S$ di una velocità $\overrightarrow{V_{0'}}$ e ruotarsi di $\overrightarrow{\omega}$ misurate da $S$.

Possiamo dall'immagine ricavare che $$\overrightarrow{r}(t)=\overrightarrow{r}(t)\text{ }'+\overrightarrow{R}(t)$$

Possiamo quindi dire che: $$\frac{d\overrightarrow{r}}{dt}\bigg|_{S}= \frac{d\overrightarrow{r}\text{ }'}{dt}\bigg|_{S}- \frac{d\overrightarrow{R}}{dt}\bigg|_{S}$$
Ricordando di indicare che $S$ è il sistema riguardo al quale stiamo derivando.

Ricaviamo la formula 
$$\overrightarrow{v}=\overrightarrow{v}\text{ }'+\underbrace{(\overrightarrow{v_{0}}\text{ }'+\overrightarrow{\omega}\times \overrightarrow{r}\text{ }')}_{v_{\tau}}$$
Dove $v_{\tau}$ è detta velocità di trascinamento.

>[!tip]
In un moto di trascinamento traslatorio $(v'=0, \omega=0)$ abbiamo che:
$$\overrightarrow{v}=\overrightarrow{v_{\tau}}=\overrightarrow{v_{0}}\text{ }'$$
Mentre in un moto di trascinamento traslatorio ($v'=0, v'_{0}=0$) abbiamo che: $$\overrightarrow{v}=\overrightarrow{v_{0}}=\overrightarrow{\omega}\times\overrightarrow{r}\text{ }'=\omega r'\hat{r_{t}}$$

### Legame tra accelerazioni
Sapendo che:$$\overrightarrow{v}-\overrightarrow{v}\text{ }'=\overrightarrow{v_{0}}+\overrightarrow{\omega}+\overrightarrow{r}\text{ }'$$
Con lo stesso procedimento usato per la velocità ricaviamo:
$$\overrightarrow{a}=\overrightarrow{a}\underbrace{-(\overrightarrow{a_{0}}+\overrightarrow{\omega}+\overrightarrow{\omega}\times\overrightarrow{r}\text{ }'+\overrightarrow{\alpha}\times\overrightarrow{r}\text{ '})}
_{\overrightarrow{a_{\tau}}\text{ acc. trasferimento}}- \underbrace{2 \overrightarrow{\omega}\times\overrightarrow{v}\text{ }'}_{\overrightarrow{a_\text{co}}\text{ acc. Coriolis}}$$

>[!tip] Accelerazione di trascinamento
>Definiamo l'accelerazione di trascinamento come l'accelerazione di un punto $P$ solidale con $S'$ (in quiete in $S'$) rispetto a $S$: $$\begin{cases}
\overrightarrow{a}\text{ }'=0 \\
\overrightarrow{a_\text{co}}
\end{cases}$$
>Quindi l'accelerazione di Coriolis entra in gioco soltanto quando $\overrightarrow{v}\neq 0$, quindi se $P$ si sposta in $S'$ le accelerazioni $\overrightarrow{a_{\tau}}$ e $\overrightarrow{a_\text{co}}$ sono quantità che caratterizzano il moto di $S'$ rispetto ad $S$.

>[!tip]
>In caso di moto di trascinamento ($\overrightarrow{v}\text{ }'=0,\overrightarrow{a}\text{ }'=0$) traslatorio ($\overrightarrow{\omega}=0,\overrightarrow{\alpha}=0$):
>$$\overrightarrow{a}=\overrightarrow{a_{\tau}}=\overrightarrow{a_{0'}}+\overrightarrow{\omega}\times\overrightarrow{\omega}\times\overrightarrow{r}\text{ }'=\overrightarrow{\alpha}\times\overrightarrow{r}\text{ }'$$
>Mentre in caso di moto di trascinamento $(\overrightarrow{v}\text{ }'=0,\overrightarrow{a}\text{ }'=0)$ rotatorio ($\overrightarrow{a_{0'}}$):
>$$\overrightarrow{a_{\tau}}=\overrightarrow{\omega}\times\overrightarrow{\omega}\times\overrightarrow{r}\text{ }'+\overrightarrow{\alpha}\times\overrightarrow{r}\text{ }'=\overrightarrow{\omega}\times\overrightarrow{r}+\overrightarrow{a_{t}}=\overrightarrow{a_{n}}+\overrightarrow{a_{t}}=\overrightarrow{a}$$

>[!tip]
>Se $P$ è in quiete rispetto a $S'$, si muove di moto accelerato rispetto a $S$.
>Se $P$ è in quiete rispetto a $S$, si muove di moto accelerato rispetto a $S'$.

## Momento angolare
>[!note]
>Definiamo il momento angolare come il prodotto vettore tra i vettori posizione e la quantità di moto:
>$$\overrightarrow{L}=\overrightarrow{r}\times \overrightarrow{p}=\overrightarrow{r}\times(\overrightarrow{p_{||}}+\overrightarrow{p_{\perp}})=\overrightarrow{r}\times \overrightarrow{p_{\perp}}=rp\sin\theta \hat{u_{z}}$$
>Il versore $\hat{u_{z}}$ è uscente dal piano ottenuto dalla combinazione lineare dei due vettori.
>In caso di moto circolare uniforme: $$\overrightarrow{L}=\overrightarrow{r}mv_{0}\hat{u_{z}}$$In caso di moto rettilineo uniforme: $$\overrightarrow{L}=dmv_{0}\hat{u_{z}}$$

## Momento di una forza
>[!note]
>$$\overrightarrow{M}=\overrightarrow{r}\times\overrightarrow{F}=rF\sin\theta$$
>Il momento di una forza quantifica la capacità di una forza di porre in rotazione un oggetto rispetto a $O$.

