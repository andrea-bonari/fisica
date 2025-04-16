>[!note]
>Un sistema di particelle (SP) è definito come un inseme di punti materiali che interagiscono tra loro.

Per ogni sistema di particelle si classificano le forze applicate in:
- forze interne: le forze si scambiano tra particelle del sistema
- forze esterne: le forze si scambiano tra le particelle e il mondo esterno

>[!tip] Corpo rigido
>Esistono sistemi fisici chiamati corpi rigidi in cui la distanza tra i punti del sistema si conserva.

### Prima equazione cardinale della dinamica per SP
>[!note]
>Si un SP composto da $n$ masse, si ha che l'equazione del moto del sistema è definita da: $$\overrightarrow{F}^{E}= \frac{\text{d}\overrightarrow{p}_\text{tot}}{\text{d}t}$$
>Con $\overrightarrow{F}^{E}$ risultante delle forze esterne e $\overrightarrow{p}_\text{tot}$ quantità di moto totale del sistema di particelle.

>[!example] Dimostrazione
>Sia un SP composto da $n$ masse, si ha che l'equazione del moto del sistema è definita da: $$\begin{cases}
>\overrightarrow{F}_{1}=m_{1}\overrightarrow{a}_{1} \\
>\vdots \\
>\overrightarrow{F}_{n}=m_{n}\overrightarrow{a}_{n}
>\end{cases}$$
>Osserviamo che da queste equazioni è possibile esprimere: $$\begin{cases}
>\overrightarrow{F}_{1}^{E}+\overrightarrow{F}_{1}^{I}= \frac{\text{d}\overrightarrow{p}_{1}}{\text{d}t} \\
>\vdots \\
>\overrightarrow{F}_{n}^{E}+\overrightarrow{F}_{n}^{I}= \frac{\text{d}\overrightarrow{p}_{n}}{\text{d}t}
>\end{cases}$$
>Esprimendola come sommatoria: $$\sum\limits_{i=1}^{n}\overrightarrow{F}_{i}^{E}+\sum\limits_{i=1}^{n}\overrightarrow{F}_{i}^{I}=\sum\limits_{i=1}^{n} \frac{\text{d}\overrightarrow{p}_{i}}{\text{d}t}$$
>Sappiamo che per il principio di azione e reazione $\sum\limits_{i=1}^{n}\overrightarrow{F}_{i}^{I}=0$, e quindi introducendo $\overrightarrow{F}^{E}$ come risultante delle forze esterne, esprimiamo il tutto come: $$\overrightarrow{F}^{E}= \frac{\text{d}\overrightarrow{p}_\text{tot}}{\text{d}t}$$
>

### Seconda equazione cardinale della dinamica per SP
>[!note]
>Sia un SP composto da $n$ masse, si ha che l'equazione del moto del sistema è definita da: $$\overrightarrow{M}^{E}_{CE}= \frac{\text{d}\overrightarrow{L}_\text{tot}}{\text{d}t}$$
>Con $\overrightarrow{M}^{E}_{CE}$ momento risultante delle forze esterne al centro di massa e $\overrightarrow{L}_\text{tot}$ lavoro totale del sistema di particelle.

>[!example] Dimostrazione
>Sia un SP composto da $n$ masse, si ha che l'equazione del moto del sistema è definita da: $$\begin{cases}
>\overrightarrow{F}_{1}=m_{1}\overrightarrow{a}_{1} \\
>\vdots \\
>\overrightarrow{F}_{n}=m_{n}\overrightarrow{a}_{n}
>\end{cases}$$
>Osserviamo che da queste equazioni è possibile esprimere: $$\begin{cases}
>\overrightarrow{F}_{1}^{E}+\overrightarrow{F}_{1}^{I}= \frac{\text{d}\overrightarrow{p}_{1}}{\text{d}t} \\
>\vdots \\
>\overrightarrow{F}_{n}^{E}+\overrightarrow{F}_{n}^{I}= \frac{\text{d}\overrightarrow{p}_{n}}{\text{d}t}
>\end{cases}$$
>Esprimendola come sommatoria: $$\sum\limits_{i=1}^{n}\overrightarrow{F}_{i}^{E}+\sum\limits_{i=1}^{n}\overrightarrow{F}_{i}^{I}=\sum\limits_{i=1}^{n} \frac{\text{d}\overrightarrow{p}_{i}}{\text{d}t}$$
>Moltiplicando tutto per $\overrightarrow{r}_{i}$ si ha che: $$\sum\limits_{i=1}^{n}\overrightarrow{r}_{i}\times \overrightarrow{F}_{i}^{E}+\sum\limits_{i=1}^{n}\overrightarrow{r}_{i}\times\overrightarrow{F}_{i}^{I}=\sum\limits_{i=1}^{n}\overrightarrow{r}\times\frac{\text{d}\overrightarrow{p}_{i}}{\text{d}t}$$
>Sappiamo che per il principio di azione e reazione $\sum\limits_{i=1}^{n}\overrightarrow{F}_{i}^{I}=0$ e quindi lo è anche $\sum\limits_{i=1}^{n}\overrightarrow{r}_{i}\overrightarrow{F}_{i}^{I}=0$, e quindi introducendo $\overrightarrow{M}^{E}$ come risultante del momento delle forze esterne, esprimiamo il tutto come: $$\overrightarrow{M}^{E}= \frac{\text{d}\overrightarrow{L}_\text{tot}}{\text{d}t}$$
>
