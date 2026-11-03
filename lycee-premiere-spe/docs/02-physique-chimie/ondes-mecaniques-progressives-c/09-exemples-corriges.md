# Exemples corrigés

!!! warning "Mode d'emploi"
    Cache la solution, cherche seul, puis compare. Chaque exemple signale **le piège** à éviter.

## Exemple 1 : éclair et tonnerre

!!! example "Énoncé"
    Un orage : le tonnerre est entendu $6{,}0\ \mathrm{s}$ après l'éclair. Célérité du son : $343\ \mathrm{m\cdot s^{-1}}$. À quelle distance a frappé la foudre ?

**Solution.** La lumière arrive de façon quasi instantanée (célérité $\approx 3 \times 10^8\ \mathrm{m\cdot s^{-1}}$), donc $\tau \approx 6{,}0\ \mathrm{s}$ est le retard du son.

$$d = c\,\tau = 343 \times 6{,}0 = 2{,}058 \times 10^3\ \mathrm{m} \approx 2{,}1 \times 10^3\ \mathrm{m}$$

La foudre a frappé à environ $2{,}1\ \mathrm{km}$.

!!! warning "Piège"
    Garder **2 chiffres significatifs** (donnée $6{,}0$ s) : $2{,}1\ \mathrm{km}$, pas $2{,}058\ \mathrm{km}$.

## Exemple 2 : chronophotographie d'une corde

!!! example "Énoncé"
    Une impulsion se propage sur une corde. Entre deux photographies prises à $0{,}10\ \mathrm{s}$ d'intervalle, le sommet de l'impulsion s'est déplacé de $0{,}80\ \mathrm{m}$. Calculer $c$.

**Solution.** $c = \dfrac{d}{\Delta t} = \dfrac{0{,}80}{0{,}10} = 8{,}0\ \mathrm{m\cdot s^{-1}}$.

!!! warning "Piège"
    On suit le **sommet de la perturbation** (qui avance), pas un point matériel de la corde (qui monte et descend sur place).

## Exemple 3 : sonar

!!! example "Énoncé"
    Un sonar émet une impulsion ultrasonore vers le fond de la mer. L'écho est reçu $0{,}84\ \mathrm{s}$ après l'émission. Célérité dans l'eau : $1{,}50 \times 10^3\ \mathrm{m\cdot s^{-1}}$. Quelle est la profondeur ?

**Solution.** Pendant $\Delta t = 0{,}84\ \mathrm{s}$, l'onde fait un **aller-retour** : distance parcourue $2h = c\,\Delta t$.

$$h = \frac{c\,\Delta t}{2} = \frac{1{,}50 \times 10^3 \times 0{,}84}{2} = 6{,}3 \times 10^2\ \mathrm{m}$$

!!! warning "Piège"
    Oublier le facteur $2$ donne $1{,}26\ \mathrm{km}$, résultat deux fois trop grand.

## Exemple 4 : la note la dans deux milieux

!!! example "Énoncé"
    Un diapason émet un la de fréquence $440\ \mathrm{Hz}$. Calculer la longueur d'onde dans l'air ($343\ \mathrm{m\cdot s^{-1}}$) puis dans l'eau ($1{,}48 \times 10^3\ \mathrm{m\cdot s^{-1}}$). Quelle grandeur est commune aux deux milieux ?

**Solution.**

$$\lambda_{\text{air}} = \frac{c_{\text{air}}}{f} = \frac{343}{440} = 0{,}780\ \mathrm{m} \qquad \lambda_{\text{eau}} = \frac{1480}{440} = 3{,}36\ \mathrm{m}$$

La **fréquence** (donc la période $T = 2{,}27\ \mathrm{ms}$) est commune : elle est fixée par la source.

## Exemple 5 : lecture d'un oscillogramme

!!! example "Énoncé"
    Sur un oscilloscope (base de temps $0{,}20\ \mathrm{ms/div}$, sensibilité verticale $0{,}50\ \mathrm{V/div}$), on voit $3$ périodes complètes sur $6{,}0$ divisions. Le signal oscille entre $-3{,}0$ et $+3{,}0$ divisions. Déterminer $T$, $f$, $S_m$ et $U_{pp}$.

**Solution.**

- $3$ périodes occupent $6{,}0 \times 0{,}20 = 1{,}2\ \mathrm{ms}$, donc $T = \dfrac{1{,}2}{3} = 0{,}40\ \mathrm{ms}$ et $f = \dfrac{1}{T} = 2{,}5 \times 10^3\ \mathrm{Hz}$.
- $S_m = 3{,}0 \times 0{,}50 = 1{,}5\ \mathrm{V}$ et $U_{pp} = 2S_m = 3{,}0\ \mathrm{V}$.

!!! warning "Piège"
    Ne pas prendre $6{,}0$ div pour **une** période : il y en a $3$.

## Exemple 6 : écrire le signal en un point

!!! example "Énoncé"
    Une source émet $s_S(t) = 3{,}0\cos\!\left(\dfrac{2\pi t}{T}\right)$ (en V) avec $f = 50\ \mathrm{Hz}$. La célérité vaut $340\ \mathrm{m\cdot s^{-1}}$. Écrire le signal reçu en $M$ à $d = 1{,}7\ \mathrm{m}$ de $S$. Que vaut $d/\lambda$ ?

**Solution.**

1. $T = 1/f = 0{,}020\ \mathrm{s}$ ; $\lambda = cT = 340 \times 0{,}020 = 6{,}8\ \mathrm{m}$.
2. $\tau = \dfrac{d}{c} = \dfrac{1{,}7}{340} = 5{,}0 \times 10^{-3}\ \mathrm{s} = \dfrac{T}{4}$ et $\dfrac{d}{\lambda} = \dfrac{1{,}7}{6{,}8} = 0{,}25$.
3. Pour $t \geq \tau$ :

$$s_M(t) = 3{,}0\cos\!\left(\frac{2\pi (t-\tau)}{T}\right) = 3{,}0\cos\!\left(\frac{2\pi t}{T} - \frac{\pi}{2}\right) = 3{,}0\sin\!\left(\frac{2\pi t}{T}\right)$$

Pour $t < \tau$, $s_M(t) = 0$ : l'onde n'est pas encore arrivée.

!!! warning "Piège"
    Le déphasage est $-2\pi d/\lambda = -\pi/2$ (retard), et le signal n'existe qu'à partir de $t = \tau$.
