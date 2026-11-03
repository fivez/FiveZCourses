# Exercices progressifs

!!! warning "Mode d'emploi"
    Huit exercices de difficulté croissante (★ à ★★★★). Cherche d'abord sur papier, rédige en suivant la méthode M7 (fichier 8), puis ouvre le corrigé.

## Exercice 1 ★ : vrai ou faux (avec justification)

!!! question "Énoncé"
    Dire si chaque affirmation est vraie ou fausse **et justifier**.

    - a) Une onde mécanique peut se propager dans le vide.
    - b) Au passage d'une onde, la matière est transportée avec l'onde.
    - c) Dans une onde transversale, la perturbation est perpendiculaire à la direction de propagation.
    - d) La célérité du son dans l'air dépend de la fréquence de la source.
    - e) À célérité fixée, si la fréquence augmente, la longueur d'onde diminue.
    - f) Quand une onde passe de l'air à l'eau, sa fréquence est modifiée.
    - g) Le son est une onde transversale.
    - h) Deux points distants de $3\lambda$ sur la ligne de propagation vibrent en phase.
    - i) Une onde progressive est forcément périodique.

??? info "Corrigé"
    - a) **Faux** : un milieu matériel est nécessaire.
    - b) **Faux** : transport d'énergie, pas de matière.
    - c) **Vrai** : c'est la définition.
    - d) **Faux** : dans l'air, $c$ dépend de la température (milieu), pas de $f$ (sinon un orchestre serait déformé à distance).
    - e) **Vrai** : $\lambda = c/f$ avec $c$ constante.
    - f) **Faux** : $f$ est imposée par la source ; seules $c$ et $\lambda$ changent.
    - g) **Faux** : longitudinale (compressions et dilatations dans la direction de propagation).
    - h) **Vrai** : $d = 3\lambda$ est un multiple entier de $\lambda$.
    - i) **Faux** : une impulsion unique est progressive et non périodique.

## Exercice 2 ★ : retard et célérité sur une corde

!!! question "Énoncé"
    Une impulsion se propage le long d'une corde tendue. Deux capteurs $A$ et $B$, distants de $4{,}50\ \mathrm{m}$, enregistrent l'impulsion. Le signal de $B$ est en retard de $30\ \mathrm{ms}$ sur celui de $A$.

    1. Calculer la célérité de l'onde.
    2. Un capteur $C$ est placé à $12{,}0\ \mathrm{m}$ de $A$, dans le même sens. Quel est le retard de $C$ par rapport à $A$ ?
    3. Un élève trouve $c = 4{,}50/30 = 0{,}15\ \mathrm{m\cdot s^{-1}}$. Quelle erreur a-t-il faite ?

??? info "Corrigé"
    1. $c = \dfrac{d}{\Delta t} = \dfrac{4{,}50}{30 \times 10^{-3}} = 1{,}5 \times 10^2\ \mathrm{m\cdot s^{-1}}$.
    2. $\tau_{AC} = \dfrac{12{,}0}{150} = 8{,}0 \times 10^{-2}\ \mathrm{s} = 80\ \mathrm{ms}$.
    3. Il n'a pas converti les ms en s. $\mathbf{30\ ms = 0{,}030\ s}$ ; le résultat $0{,}15\ \mathrm{m\cdot s^{-1}}$ est absurde pour une corde tendue.

## Exercice 3 ★★ : ultrasons dans deux milieux

!!! question "Énoncé"
    Un émetteur d'ultrasons de fréquence $f = 25\ \mathrm{kHz}$ fonctionne successivement dans l'air ($c_a = 343\ \mathrm{m\cdot s^{-1}}$) puis dans l'eau ($c_e = 1{,}48 \times 10^3\ \mathrm{m\cdot s^{-1}}$).

    1. Calculer la période $T$.
    2. Calculer $\lambda_a$ et $\lambda_e$.
    3. Quelles grandeurs sont communes aux deux milieux ? Expliquer physiquement.

??? info "Corrigé"
    1. $T = \dfrac{1}{f} = \dfrac{1}{25 \times 10^3} = 4{,}0 \times 10^{-5}\ \mathrm{s} = 40\ \mu\mathrm{s}$.
    2. $\lambda_a = \dfrac{c_a}{f} = \dfrac{343}{25 \times 10^3} = 1{,}37 \times 10^{-2}\ \mathrm{m} = 13{,}7\ \mathrm{mm}$ ; $\lambda_e = \dfrac{1480}{25 \times 10^3} = 5{,}92 \times 10^{-2}\ \mathrm{m} = 59{,}2\ \mathrm{mm}$.
    3. $f$ et $T$ sont communes : l'émetteur impose le rythme, et à l'interface le nombre de perturbations par seconde se conserve. $\lambda$ est proportionnelle à $c$ : $\lambda_e/\lambda_a = c_e/c_a \approx 4{,}3$.

    **Piège** : $25\ \mathrm{kHz}$ à convertir en Hz.

## Exercice 4 ★★ : lecture d'un oscillogramme

!!! question "Énoncé"
    Sur l'écran d'un oscilloscope (sensibilité horizontale $0{,}50\ \mathrm{ms/div}$, verticale $2{,}0\ \mathrm{V/div}$), on observe exactement **2 périodes** sur $6{,}0$ divisions. Le signal oscille entre $-2{,}5$ et $+2{,}5$ divisions. À $t = 0$, le signal est maximal.

    1. Déterminer $T$ et $f$.
    2. Déterminer l'amplitude $S_m$ et la tension crête à crête.
    3. Écrire $s(t)$.
    4. Il s'agit d'un son dans l'air ($c = 343\ \mathrm{m\cdot s^{-1}}$). Calculer $\lambda$.
    5. Un élève lit $T = 6{,}0 \times 0{,}50 = 3{,}0\ \mathrm{ms}$. Que lui répondre ?

??? info "Corrigé"
    1. $2T = 6{,}0 \times 0{,}50 = 3{,}0\ \mathrm{ms}$, donc $T = 1{,}5\ \mathrm{ms}$ et $f = \dfrac{1}{1{,}5 \times 10^{-3}} = 6{,}7 \times 10^2\ \mathrm{Hz}$.
    2. $S_m = 2{,}5 \times 2{,}0 = 5{,}0\ \mathrm{V}$ ; $U_{pp} = 10{,}0\ \mathrm{V}$.
    3. Maximum à $t=0$ : $\varphi = 0$, donc $s(t) = 5{,}0\cos\!\left(\dfrac{2\pi t}{1{,}5 \times 10^{-3}}\right)$ en V.
    4. $\lambda = cT = 343 \times 1{,}5 \times 10^{-3} = 0{,}51\ \mathrm{m}$.
    5. Il a pris $2$ périodes pour $1$ : $T = 3{,}0/2 = 1{,}5\ \mathrm{ms}$.

## Exercice 5 ★★★ : cliché d'une corde sinusoïdale

!!! question "Énoncé"
    Une corde est parcourue par une onde sinusoïdale de fréquence $f = 8{,}0\ \mathrm{Hz}$ émise par la source $S$. Sur un cliché pris à $t_0$, trois crêtes consécutives s'étendent sur $1{,}20\ \mathrm{m}$ (de la première à la troisième).

    1. Déterminer $\lambda$, puis $T$ et $c$.
    2. Un point $M$ est à $3{,}00\ \mathrm{m}$ de $S$ et un point $N$ à $2{,}70\ \mathrm{m}$. Calculer leurs retards.
    3. Comparer le mouvement de $M$ et de $S$, puis celui de $N$ et de $S$.
    4. À l'instant où $S$ est à son élongation maximale, que valent les élongations de $M$ et de $N$ (en fonction de l'amplitude $A$) ?

??? info "Corrigé"
    1. Trois crêtes consécutives délimitent **deux** longueurs d'onde : $2\lambda = 1{,}20$, donc $\lambda = 0{,}60\ \mathrm{m}$. $T = 1/f = 0{,}125\ \mathrm{s}$ et $c = \lambda f = 0{,}60 \times 8{,}0 = 4{,}8\ \mathrm{m\cdot s^{-1}}$.
    2. $\tau_M = \dfrac{3{,}00}{4{,}8} = 0{,}625\ \mathrm{s}$ ; $\tau_N = \dfrac{2{,}70}{4{,}8} = 0{,}5625\ \mathrm{s}$.
    3. $\dfrac{d_M}{\lambda} = \dfrac{3{,}00}{0{,}60} = 5$ : **en phase** avec $S$ ($\tau_M = 5T$). $\dfrac{d_N}{\lambda} = \dfrac{2{,}70}{0{,}60} = 4{,}5$ : **opposition de phase** ($\tau_N = 4{,}5T$).
    4. $y_M = +A$ et $y_N = -A$ (en régime établi, une fois l'onde arrivée).

    **Piège** : compter $3$ crêtes comme $3\lambda$ donnerait $\lambda = 0{,}40\ \mathrm{m}$ : faux.

## Exercice 6 ★★★ : séisme, ondes P et S

!!! question "Énoncé"
    Une station sismique enregistre l'arrivée des ondes P puis, $70\ \mathrm{s}$ plus tard, celle des ondes S. Célérités dans la croûte : $c_P = 6{,}0\ \mathrm{km\cdot s^{-1}}$ et $c_S = 3{,}5\ \mathrm{km\cdot s^{-1}}$.

    1. Donner la nature de chaque onde.
    2. Exprimer le décalage $\Delta t$ en fonction de la distance $d$ à l'épicentre, de $c_P$ et $c_S$.
    3. En déduire $d$.
    4. Pourquoi aucune onde S ne traverse-t-elle le noyau externe ?
    5. Un élève calcule $d = \Delta t\,(c_P - c_S)$. Où est l'erreur ?

??? info "Corrigé"
    1. P : longitudinale ; S : transversale.
    2. $t_P = d/c_P$ et $t_S = d/c_S$ donc $\Delta t = t_S - t_P = d\left(\dfrac{1}{c_S} - \dfrac{1}{c_P}\right) = d\,\dfrac{c_P - c_S}{c_P\,c_S}$.
    3. $d = \dfrac{\Delta t\; c_P\, c_S}{c_P - c_S} = \dfrac{70 \times 6{,}0 \times 3{,}5}{2{,}5} = 588\ \mathrm{km} \approx 5{,}9 \times 10^2\ \mathrm{km}$. Vérification : $t_P = 98\ \mathrm{s}$, $t_S = 168\ \mathrm{s}$, écart $70\ \mathrm{s}$ ✓.
    4. Le noyau externe est liquide, et un liquide ne transmet pas les ondes transversales.
    5. $\Delta t\,(c_P - c_S)$ n'est pas une distance : la relation correcte est $d = c_P t_P = c_S t_S$. Cette formule donnerait $175\ \mathrm{km}$, ce qui est faux.

## Exercice 7 ★★★★ : corde composite

!!! question "Énoncé"
    Une corde est formée de deux tronçons raccordés. Tronçon 1 : longueur $2{,}0\ \mathrm{m}$, célérité $c_1 = 80\ \mathrm{m\cdot s^{-1}}$. Tronçon 2 : longueur $6{,}0\ \mathrm{m}$, célérité $c_2 = 160\ \mathrm{m\cdot s^{-1}}$. Un vibreur impose à l'extrémité du tronçon 1 un mouvement sinusoïdal de fréquence $200\ \mathrm{Hz}$.

    1. Calculer $T$, $\lambda_1$ et $\lambda_2$.
    2. Calculer la durée totale de propagation d'une extrémité à l'autre.
    3. Calculer la célérité moyenne sur l'ensemble. Est-elle égale à la moyenne arithmétique de $c_1$ et $c_2$ ?
    4. Combien de longueurs d'onde y a-t-il dans chaque tronçon ? L'extrémité libre est-elle en phase avec le vibreur ?

??? info "Corrigé"
    1. $T = \dfrac{1}{200} = 5{,}0 \times 10^{-3}\ \mathrm{s}$ ; $\lambda_1 = \dfrac{c_1}{f} = 0{,}40\ \mathrm{m}$ ; $\lambda_2 = \dfrac{c_2}{f} = 0{,}80\ \mathrm{m}$ (même $f$, $\lambda$ proportionnelle à $c$).
    2. $t_1 = \dfrac{2{,}0}{80} = 25\ \mathrm{ms}$ ; $t_2 = \dfrac{6{,}0}{160} = 37{,}5\ \mathrm{ms}$ ; $\tau = 62{,}5\ \mathrm{ms}$.
    3. $c_{\text{moy}} = \dfrac{8{,}0}{62{,}5 \times 10^{-3}} = 128\ \mathrm{m\cdot s^{-1}}$, **différente** de $\dfrac{80+160}{2} = 120\ \mathrm{m\cdot s^{-1}}$ : la vitesse moyenne se calcule avec la distance totale et la durée totale.
    4. $N_1 = \dfrac{2{,}0}{0{,}40} = 5$ et $N_2 = \dfrac{6{,}0}{0{,}80} = 7{,}5$, soit $12{,}5$ au total ; de même $\dfrac{\tau}{T} = \dfrac{62{,}5}{5{,}0} = 12{,}5$. Le retard est un nombre demi-entier de périodes : **opposition de phase**.

    **Piège** : écrire $d_{\text{tot}}/\lambda$ avec une seule longueur d'onde est faux, car $\lambda$ change de tronçon.

## Exercice 8 ★★★★ : modéliser deux signaux

!!! question "Énoncé"
    Un capteur $A$ enregistre un signal sinusoïdal d'amplitude $4{,}0\ \mathrm{V}$ et de période $2{,}0\ \mathrm{ms}$. À $t = 0$, $s_A = 0$ et le signal est croissant. Un capteur $B$ est placé à $17{,}15\ \mathrm{cm}$ de $A$ sur la ligne de propagation (son dans l'air, $c = 343\ \mathrm{m\cdot s^{-1}}$).

    1. Déterminer $\varphi_A$ et écrire $s_A(t)$.
    2. Calculer $\lambda$, $\tau$ et $d/\lambda$.
    3. Écrire $s_B(t)$ et la simplifier. Pour quel domaine de $t$ est-elle valable ?
    4. Que vaut $s_B(0)$ ? Que donne la formule ? Commenter.
    5. Vérifier $s_B(\tau) = s_A(0)$.

??? info "Corrigé"
    1. Zéro croissant à $t = 0$ : $\varphi_A = -\dfrac{\pi}{2}$, donc $s_A(t) = 4{,}0\cos\!\left(\dfrac{2\pi t}{T} - \dfrac{\pi}{2}\right) = 4{,}0\sin\dfrac{2\pi t}{T}$.
    2. $\lambda = cT = 343 \times 2{,}0 \times 10^{-3} = 0{,}686\ \mathrm{m}$ ; $\tau = \dfrac{0{,}1715}{343} = 5{,}0 \times 10^{-4}\ \mathrm{s} = 0{,}50\ \mathrm{ms} = \dfrac{T}{4}$ ; $\dfrac{d}{\lambda} = 0{,}25$.
    3. $s_B(t) = s_A(t - \tau) = 4{,}0\cos\!\left(\dfrac{2\pi t}{T} - \dfrac{\pi}{2} - \dfrac{\pi}{2}\right) = 4{,}0\cos\!\left(\dfrac{2\pi t}{T} - \pi\right) = -4{,}0\cos\dfrac{2\pi t}{T}$, valable pour $t \geq \tau = 0{,}50\ \mathrm{ms}$.
    4. La formule donnerait $-4{,}0\ \mathrm{V}$ en $t=0$, mais l'onde n'est pas arrivée : $s_B(0) = 0$. Avant $\tau$, $B$ est au repos.
    5. $s_B(\tau) = -4{,}0\cos\!\left(\dfrac{2\pi}{T}\cdot\dfrac{T}{4}\right) = -4{,}0\cos\dfrac{\pi}{2} = 0 = s_A(0)$ ✓.
