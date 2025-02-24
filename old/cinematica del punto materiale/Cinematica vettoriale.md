>La cinematica vettoriale si usa per descrivere il moto in modo molto più accurato rispetto al metodo dell'ascissa curvilinea.

Definiamo un vettore posizione con origine all'origine e con vertice un punto in un instante:
$$\overrightarrow{r}=\overrightarrow{OP}(t)$$
>[!note] Legge oraria nella cinematica vettoriale
>$$\overrightarrow{r}=\overrightarrow{r}(t)\equiv x(t)\overrightarrow{u}_{x}+y(t)\overrightarrow{u}_{y}\iff\begin{cases}
x=x(t) \\
y=y(t)
\end{cases}$$

## Spostamento
>[!note]
>Considero $t_{1},t_{2}$ con $t_{2}>t_{1}$, allora $$\overrightarrow{r}_{1}=\overrightarrow{r}(t_{1})\quad \overrightarrow{r}_{2}=\overrightarrow{r}(t_{2})$$
>$$\triangle \overrightarrow{r}\equiv \overrightarrow{r}_{2}- \overrightarrow{r_{1}}$$
>
>Il vettore $\triangle \overrightarrow{r}$ è un [vettore differenza](https://andrea-bonari.github.io/MAT-03/Geometria/Retta.html#Vettore_differenza).

## Velocità media vettoriale
>[!note]
>Analogamente alla velocità media:
>$$<\overrightarrow{v}>\equiv\frac{\triangle \overrightarrow{r}}{\triangle t}$$
>
>Notiamo che $<\overrightarrow{v}>||\triangle\overrightarrow{r}$

## Velocità vettoriale istantanea
>[!note] Rappresentazione cartesiana
>Analogamente alla velocità istantanea:
>$$\overrightarrow{v}(t_{1})\equiv\lim_{\triangle t\to 0} \frac{\triangle \overrightarrow{r}}{\triangle t}= \frac{d \overrightarrow{r}}{dt}\bigg|_{t_{1}}$$

>[!tip] Base intrinseca
>Introduco la coppia di vettori tra loro ortogonali $\hat{u_{t}}$ e $\hat{u_{n}}$, ($\hat{u_{t}}\perp\hat{u_{n}}$).
>$\hat{u_{t}}$ è un versore tangente al punto $s(t)$ e orientato come tale, mentre $\hat{u_{n}}$ è rivolto verso il centro di curvatura (centro di una circonferenza che approssima più la curva sul punto di raggio $\rho\cdot r$).

>[!note] Rappresentazione intrinseca
>La velocità vettoriale è tangente alla traiettoria e può essere vista come $$\overrightarrow{v}= x'(t)\overrightarrow{u_{x}}+y'(t)\overrightarrow{u_{y}}=s'(t)\overrightarrow{u_{t}}$$
>
>Inoltre possiamo definire come velocità scalare $|\overrightarrow{v}|$

## Accelerazione media vettoriale
>[!note]
>Analogamente all'accelerazione media:
>$$<\overrightarrow{a}>= \frac{\triangle \overrightarrow{v}}{\triangle t}$$
>
>Notiamo che $<\overrightarrow{a}>||<\overrightarrow{v}>||\triangle\overrightarrow{v}$

## Accelerazione vettoriale istantanea
>[!note] Rappresentazione cartesiana
>Analogamente alla velocità vettoriale istantanea:
>$$\overrightarrow{a}=\overrightarrow{v}\text{ }'(t)=\overrightarrow{r}\text{ }''(t)$$

>[!note] Rappresentazione intrinseca
>$$\overrightarrow{a}=v'(t)\overrightarrow{u_{t}}+ \frac{v^{2}}{\rho}\overrightarrow{u_{n}}$$
>Siccome il termine $a_{n}$ ha come direzione il centro di curvatura lo possiamo definirlo come accelerazione centripeta.

### Riepilogo rappresentazioni
| Valore                   | Rappresentazione cartesiana                                    | Rappresentazione intrinseca                                         |
| ------------------------ | -------------------------------------------------------------- | ------------------------------------------------------------------- |
| Legge oraria vettoriale  | $$\begin{cases}r_x=x(t)\\r_y=y(t)\end{cases}$$                 |                                                                     |
| Velocità vettoriale      | $$\begin{cases}v_x=x'(t)\\v_y=y'(t)\end{cases}$$               | $$\begin{cases}v_t=v=s'(t)\\v_n=0\end{cases}$$                      |
| Accelerazione vettoriale | $$\begin{cases}a_x=v'(t)=x''(t)\\a_y=v'(t)=y''(t)\end{cases}$$ | $$\begin{cases}a_t=v'=s''(t)\\a_n = \frac{v^{2}}{\rho}\end{cases}$$ |
### Riepilogo dei moti
| accelerazione tangenziale ($a_t$) | accelerazione normale ($a_n$) | moto                                     |
| --------------------------------- | ----------------------------- | ---------------------------------------- |
| $0$                               | $\forall$                     | moto uniforme curvilineo                 |
| $0$                               | $\text{const}$                | moto circolare uniforme                  |
| $0$                               | $0$                           | moto rettilineo uniforme                 |
| $\text{const}$                    | $0$                           | moto rettilineo uniformemente accelerato |
| $\forall$                         | $0$                           | Moto rettilineo vario                    |
### Problema inverso
Analogamente al problema inverso nella cinematica del moto rettilineo possiamo dire che: $$\begin{cases}
v_{x}(t)-v_{0x}=\int^{t}_{t_{0}}a_{x}(t)\text{dt} \\
v_{y}(t)-v_{0y}=\int^{t}_{t_{0}}a_{y}(t)\text{dt}
\end{cases}\iff\begin{cases}
x(t)-x_{0}=\int^{t}_{t_{0}}v_{x}(t)\text{dt} \\
y(t)-y_{0}=\int^{t}_{t_{0}}v_{y}(t)\text{dt}
\end{cases}$$

Applicando al modo uniformemente accelerato (MUA)
$$\overrightarrow{a}=\text{const}$$
$$\begin{cases}
v_{x}(t)=v_{0x}+a_{x}(t-t_{0}) \\
v_{y}(t)=v_{0y}+a_{y}(t-t_{0})
\end{cases}\iff\begin{cases}
x=x_{0}+v_{0x}(t-t_{0})+ \frac{1}{2}a_{x}(t-t_{0})^{2} \\
y=y_{0}+v_{0y}(t-t_{0})+ \frac{1}{2}a_{y}(t-t_{0})^{2}
\end{cases}$$
## Moto del proiettile
>[!note]
>Il moto del proiettile è il moto soggetto ad una accelerazione verticale verso il basso pari a $g=9.81 m/s^{2}$, questo moto particolare segue una traiettoria parabolica.

Siccome l'accelerazione verticale è soltanto verso il basso possiamo assumere che il vettore accelerazione $\overrightarrow{a}=0\overrightarrow{u_{x}}-g \overrightarrow{u_{y}}$, di conseguenza sull'asse $y$ avremo un moto rettilineo uniformemente accelerato, mentre sull'asse $x$ avremo un moto rettilineo uniforme.

Se assumiamo che $x_{0}=0$, $y_{0}=0$ e $t_{0}=0$:
$$\begin{cases}
x=v_{0}\cos(\alpha)t & \text{MRU} \\
y=v_{0}\sin(\alpha)t- \frac{1}{2}gt^{2}&\text{MRUA}
\end{cases}\iff\begin{cases}
v_{x}=v_{0}\cos\alpha \\
v_{y}=v_{0}\sin\alpha - gt
\end{cases}$$
