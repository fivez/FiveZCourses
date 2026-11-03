# Exercices type contrôle

!!! warning "Conditions de contrôle"
    Chronomètre en main, sans le cours, calculatrice en radians. Durée indicative : 20 à 25 minutes par exercice. Les corrigés sont **masqués** : ouvre-les seulement après avoir rédigé.

## Exercice A : houle et bouées (≈ 25 min)

!!! question "Énoncé"
    Deux bouées $B_1$ et $B_2$, alignées avec la direction de propagation de la houle, sont distantes de $150\ \mathrm{m}$. Chacune enregistre la hauteur de l'eau (en m) par rapport au niveau moyen. Les enregistrements sont reproduits ci-dessous ($B_2$ est plus loin de la source que $B_1$).

    ```mermaid
    xychart-beta
        title "Hauteur de l'eau aux bouées B1 et B2"
        x-axis "temps t (s)" [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
        y-axis "hauteur (m)" -0.6 --> 0.6
        line [0.5, 0.35, 0, -0.35, -0.5, -0.35, 0, 0.35, 0.5, 0.35, 0, -0.35, -0.5, -0.35, 0, 0.35, 0.5, 0.35, 0, -0.35, -0.5, -0.35, 0, 0.35, 0.5]
        line [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0.5, 0.35, 0, -0.35, -0.5, -0.35, 0, 0.35, 0.5, 0.35, 0, -0.35, -0.5]
    ```

    La première courbe correspond à $B_1$, la seconde à $B_2$. On admet que, pour cette houle, la célérité ne dépend que du milieu, et que l'amortissement est négligeable.

    1. Justifier que la houle est une onde mécanique progressive.
    2. Déterminer graphiquement le retard $\tau$ de $B_2$ sur $B_1$, puis la célérité $c$.
    3. Déterminer la période $T$ et la fréquence $f$ de la houle, puis la longueur d'onde $\lambda$.
    4. $B_1$ et $B_2$ vibrent-elles en phase, en opposition de phase, ou ni l'un ni l'autre ? Justifier par deux méthodes, dont une graphique.
    5. Une bouée $B_3$ est placée entre $B_1$ et $B_2$, sur la même ligne. À quelle distance de $B_1$ doit-elle être pour vibrer en phase avec $B_1$ ? Et en opposition de phase ? (cas les plus proches de $B_1$)
    6. Écrire $s_{B_1}(t)$ et $s_{B_2}(t)$ en précisant le domaine de validité.
    7. Un élève affirme : « l'eau est transportée à $12{,}5\ \mathrm{m\cdot s^{-1}}$ vers la plage ». Critiquer.

??? info "Corrigé"
    1. Une perturbation (variation de hauteur) se propage de proche en proche dans un milieu matériel (l'eau) ; $B_2$ reproduit le mouvement de $B_1$ avec un retard : c'est une onde mécanique progressive, ici périodique.
    2. $B_2$ commence à osciller à $t = 12\ \mathrm{s}$ alors que $B_1$ est déjà en mouvement : $\tau = 12\ \mathrm{s}$ (le premier maximum de $B_2$ à $t = 12\ \mathrm{s}$ correspond à celui de $B_1$ à $t=0$). $c = \dfrac{d}{\tau} = \dfrac{150}{12} = 12{,}5\ \mathrm{m\cdot s^{-1}}$.
    3. Les maxima de $B_1$ sont à $0$, $8$, $16$, $24\ \mathrm{s}$ : $T = 8{,}0\ \mathrm{s}$, $f = \dfrac{1}{8{,}0} = 0{,}125\ \mathrm{Hz}$. $\lambda = cT = 12{,}5 \times 8{,}0 = 1{,}0 \times 10^2\ \mathrm{m}$.
    4. Méthode 1 : $\dfrac{d}{\lambda} = \dfrac{150}{100} = 1{,}5$ (demi-entier) ; méthode 2 : $\dfrac{\tau}{T} = \dfrac{12}{8{,}0} = 1{,}5$. Graphiquement : à $t = 16\ \mathrm{s}$, $B_1$ est à $+0{,}5\ \mathrm{m}$ et $B_2$ à $-0{,}5\ \mathrm{m}$ ; leurs élongations sont opposées à chaque instant (après $12\ \mathrm{s}$) : **opposition de phase**.
    5. En phase : $d = \lambda = 100\ \mathrm{m}$ (le plus proche, $B_1$ elle-même exclue). Opposition de phase : $d = \lambda/2 = 50\ \mathrm{m}$.
    6. $s_{B_1}(t) = 0{,}50\cos\!\left(\dfrac{2\pi t}{8{,}0}\right)$ ; $s_{B_2}(t) = s_{B_1}(t - 12) = 0{,}50\cos\!\left(\dfrac{2\pi t}{8{,}0} - 3\pi\right) = -0{,}50\cos\!\left(\dfrac{2\pi t}{8{,}0}\right)$ pour $t \geq 12\ \mathrm{s}$ ; $s_{B_2}(t) = 0$ avant (en unités SI).
    7. La célérité est celle de la **perturbation**, pas celle de l'eau. Les bouées oscillent verticalement sur place, preuve qu'il n'y a pas de transport de matière sur la distance de propagation.

    Remarque (hors programme) : en eau profonde, la célérité de la houle dépend de sa période ; la valeur $12{,}5\ \mathrm{m\cdot s^{-1}}$ est donc propre à cette houle de période $8{,}0\ \mathrm{s}$.

## Exercice B : mesure de la célérité du son (≈ 25 min)

!!! question "Énoncé"
    Un haut-parleur, alimenté par un GBF, émet un son sinusoïdal de fréquence $f = 1{,}000\ \mathrm{kHz}$. Deux microphones $M_1$ (fixe) et $M_2$ (mobile) sont alignés avec le haut-parleur, et leurs signaux sont visualisés sur un oscilloscope. Au départ, les deux signaux sont en phase. On éloigne $M_2$ : les signaux sont à nouveau en phase **cinq fois** successivement, après un déplacement total de $M_2$ égal à $1{,}720\ \mathrm{m}$.

    1. Quelle est la nature du son ? Justifier en précisant la direction du mouvement d'une molécule d'air.
    2. Montrer que, lorsque $M_2$ s'éloigne de $M_1$ de $d$, les signaux sont en phase si $d$ est un multiple entier de $\lambda$.
    3. Déterminer $\lambda$ puis $c$.
    4. Pourquoi mesurer la distance pour cinq coïncidences plutôt qu'une seule ? On admet une incertitude de $0{,}2\ \mathrm{cm}$ sur la distance dans les deux cas : comparer les incertitudes relatives.
    5. On admet $c \approx 331 + 0{,}6\,\theta$ ($\theta$ en $^\circ\mathrm{C}$). Estimer la température de la salle.
    6. On double la fréquence : $f' = 2{,}000\ \mathrm{kHz}$. Que deviennent $c$, $\lambda$ et le déplacement de $M_2$ pour cinq coïncidences ? Un élève affirme que « $c$ double aussi ». Répondre.
    7. $M_2$ est maintenant à $8{,}6\ \mathrm{cm}$ de $M_1$ (avec $f = 1{,}000\ \mathrm{kHz}$). Calculer le retard $\tau$ et le déphasage de $M_2$ par rapport à $M_1$.

??? info "Corrigé"
    1. Son = onde **longitudinale** : une molécule d'air oscille d'avant en arrière **dans la direction de propagation** (compressions et dilatations).
    2. $M_2$ reproduit le signal de $M_1$ avec le retard $\tau = d/c$. En phase si $\tau = kT$, soit $d = kcT = k\lambda$ avec $k$ entier.
    3. Cinq coïncidences successives correspondent à $5\lambda$ : $\lambda = \dfrac{1{,}720}{5} = 0{,}344\ \mathrm{m}$ ; $c = \lambda f = 0{,}344 \times 1000 = 344\ \mathrm{m\cdot s^{-1}}$.
    4. Pour une coïncidence : $\dfrac{0{,}2}{34{,}4} \approx 0{,}6\ \%$ ; pour cinq : $\dfrac{0{,}2}{172{,}0} \approx 0{,}12\ \%$. L'incertitude relative est divisée par $5$.
    5. $\theta = \dfrac{c - 331}{0{,}6} = \dfrac{344 - 331}{0{,}6} \approx 22\ ^\circ\mathrm{C}$.
    6. $c$ reste égale à $344\ \mathrm{m\cdot s^{-1}}$ (même milieu) ; $\lambda' = \dfrac{344}{2000} = 0{,}172\ \mathrm{m}$ ; déplacement $5\lambda' = 0{,}860\ \mathrm{m}$. L'élève se trompe : à milieu fixé, doubler $f$ divise $\lambda$ par deux ($\lambda = c/f$), et $c$ ne change pas.
    7. $T = 1{,}000\ \mathrm{ms}$ ; $\tau = \dfrac{0{,}086}{344} = 2{,}5 \times 10^{-4}\ \mathrm{s} = 0{,}25\ \mathrm{ms} = \dfrac{T}{4}$ ; $\dfrac{d}{\lambda} = \dfrac{0{,}086}{0{,}344} = 0{,}25$ ; déphasage $\Delta\varphi = -\dfrac{2\pi d}{\lambda} = -\dfrac{\pi}{2}$ : $M_2$ est en retard d'un quart de période.

## Exercice C : le tsunami (≈ 25 min)

!!! question "Énoncé"
    Un séisme sous-marin génère une onde à la surface de l'océan. Lorsque la longueur d'onde est très grande devant la profondeur $h$ de l'eau, la célérité est donnée par $c = \sqrt{g\,h}$ avec $g = 9{,}81\ \mathrm{m\cdot s^{-2}}$. La période de l'onde est $T = 20\ \mathrm{min}$.

    1. Calculer la célérité en eau profonde ($h = 4000\ \mathrm{m}$), en $\mathrm{m\cdot s^{-1}}$ et en $\mathrm{km\cdot h^{-1}}$.
    2. Calculer la longueur d'onde correspondante. Vérifier que $\lambda \gg h$.
    3. Près de la côte, la profondeur est $h' = 10\ \mathrm{m}$. Calculer $c'$ et $\lambda'$. Vérifier encore $\lambda' \gg h'$.
    4. Pourquoi $\lambda$ diminue-t-elle alors que la période ne change pas ?
    5. L'épicentre est à $1800\ \mathrm{km}$ d'une côte, profondeur supposée constante égale à $4000\ \mathrm{m}$. Estimer la durée de propagation.
    6. Un élève dit : « la masse d'eau se déplace à $198\ \mathrm{m\cdot s^{-1}}$ ». Répondre.

??? info "Corrigé"
    1. $c = \sqrt{9{,}81 \times 4000} = \sqrt{39\,240} = 198\ \mathrm{m\cdot s^{-1}}$, soit $198 \times 3{,}6 \approx 7{,}1 \times 10^2\ \mathrm{km\cdot h^{-1}}$.
    2. $T = 20 \times 60 = 1200\ \mathrm{s}$ ; $\lambda = cT = 198 \times 1200 \approx 2{,}4 \times 10^5\ \mathrm{m} = 2{,}4 \times 10^2\ \mathrm{km}$, très supérieure à $h = 4\ \mathrm{km}$ : l'hypothèse est vérifiée.
    3. $c' = \sqrt{9{,}81 \times 10} = 9{,}9\ \mathrm{m\cdot s^{-1}} \approx 36\ \mathrm{km\cdot h^{-1}}$ ; $\lambda' = c'T = 9{,}9 \times 1200 \approx 1{,}2 \times 10^4\ \mathrm{m} = 12\ \mathrm{km} \gg 10\ \mathrm{m}$ : hypothèse encore vérifiée.
    4. La période est imposée par la source et se conserve quand $h$ change ; $c$ diminue avec $h$, donc $\lambda = cT$ diminue : l'onde se « raccourcit ».
    5. $\Delta t = \dfrac{d}{c} = \dfrac{1{,}8 \times 10^6}{198} \approx 9{,}1 \times 10^3\ \mathrm{s} \approx 2{,}5\ \mathrm{h}$.
    6. Faux : $c$ est la célérité de la **perturbation**, pas la vitesse de l'eau. L'eau oscille localement ; il n'y a pas de transport de matière sur plusieurs milliers de kilomètres.
