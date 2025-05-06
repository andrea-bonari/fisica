>[!note]
>Si ha che un fluido sottoposto soltanto alla forza peso, è statico se e solo se: $$\frac{\text{d}p}{\text{d}z}=-\rho g$$

>[!example] Dimostrazione
>Consideriamo un volumetto cilindrico di area $A$, direttrice parallela a $z$, altezza $\text{d}z$ e consideriamo $\overrightarrow{g}=-g\hat{u}_{z}$:
>![[Pasted image 20250429232114.png|center]]
>
>Consideriamo l'unica forza di volume come forza peso. Imponiamo l'equilibrio meccanico: $$\overrightarrow{F}_\text{ris}=0$$
>Abbiamo la forza peso: $$\text{d}\overrightarrow{P}=\text{d}m\cdot\overrightarrow{g}=\rho\cdot\text{d}V\overrightarrow{g}=-\rho\cdot A\cdot \text{d}z\cdot g\cdot\hat{u}_{z}$$
>Si hanno le forze di pressione sulle superficie laterali, che si annullano vicendevolmente per la simmetria cilindrica. Infine consideriamo le forze sulle superfici di base: $$\overrightarrow{F}_{p,\inf}= p(z) A\hat{u}_{z}\qquad \overrightarrow{F}_{p,\sup}=-p(z+\text{d}z) A \hat{u}_{z}$$
>Siccome il fluido è in equilibrio, si ha che: $$\overrightarrow{F}_\text{ris}=\text{d}\overrightarrow{P}+\overrightarrow{F}_{p,\inf}+\overrightarrow{F}_{p,\sup}=-\rho A \text{d}zg\hat{u}_{z}+p(z) A\hat{u}_{z}-p(z+\text{d}z)A\hat{u}_{z}=0$$
>Semplificando l'equazione si ha: $$\frac{p(z+\text{d}z)-p(z)}{\text{d}z}=-\rho g$$
>E quindi: $$\frac{\text{d}p}{\text{d}z}=-\rho g$$

### Legge di Stevino
>[!note]
>Considerando come $z_{1}$ la quota della superficie libera del liquido, a cui è presente una pressione $p(z_{1})=p_{0}$, e come $z_{2}$ la quota di profondità arbitraria $h$. Si ha che: $$p(h)=p_{0}+\rho gh$$

>[!example] Dimostrazione
>Se consideriamo un fluido incomprimibile consideriamo la densità $\rho$ costante, e quindi dall'equazione della statica dei fluidi pesanti: $$p(z_{2})-p(z_{1})=\int_{z_{1}}^{z_{2}}\frac{\text{d}p}{\text{d}z}\text{ d}z=\int_{x_{1}}^{x_{2}}\rho g \text{ d} z=\rho g(z_{1}-z_{2})$$
>Consideriamo la $z_{1}$ come la quota della superficie libera del liquido, con $p(z_{1})=p_{0}$, e come $z_{2}$ la quota di una profondità arbitraria $h$. Si ottiene: $$p(h)=p_{0}+\rho gh$$

>[!tip] Principio di Pascal
>Si ha che un incremento di pressione esercitato in un punto di un liquido si trasferisce identicamente su tutto il liquido

Come conseguenza della legge di Stevino si ha il principio dei vasi comunicanti: se recipienti di diversa forma e dimensione sono riempiti con il medesimo liquido e sono posti in comunicazione, il livello del liquido sarà lo stesso in ciascun recipiente.

