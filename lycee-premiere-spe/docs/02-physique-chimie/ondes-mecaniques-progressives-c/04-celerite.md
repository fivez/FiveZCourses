# La célérité d'une onde

## 1. Définition et mesure

!!! note "Définition : célérité"
    La **célérité** $c$ d'une onde est la **vitesse de propagation de la perturbation** dans le milieu. Elle s'exprime en $\mathrm{m\cdot s^{-1}}$.

!!! tip "Propriété : calcul de la célérité"
    Si la perturbation met une durée $\Delta t$ pour parcourir une distance $d$ :

    $$c = \frac{d}{\Delta t}$$

    avec $d$ en m, $\Delta t$ en s, $c$ en $\mathrm{m\cdot s^{-1}}$.

!!! quote "Pourquoi la célérité est-elle constante ?"
    Dans un milieu homogène, chaque portion du milieu se comporte comme la précédente : la perturbation met la même durée pour franchir des distances égales. Le signal avance donc d'un mouvement uniforme, de vitesse $c$.

!!! success "Méthode : mesurer une célérité avec deux capteurs"
    1. Placer deux capteurs $A$ et $B$ sur la ligne de propagation, distants de $d$ (mesurée).
    2. Enregistrer les deux signaux sur le même graphe.
    3. Lire le retard $\Delta t$ entre un même repère des deux signaux (début de l'impulsion, même maximum…).
    4. Calculer $c = d/\Delta t$ en convertissant $\Delta t$ en secondes.

## 2. De quoi dépend la célérité ?

!!! tip "Propriété : $c$ dépend du milieu, pas de la source"
    La célérité est fixée par les **propriétés du milieu** : nature, état, température, tension d'une corde… Elle ne dépend **ni de l'amplitude** de la perturbation, **ni de la façon** dont la source l'a produite.

    - Corde : $c$ augmente avec la tension, diminue avec la masse par unité de longueur.
    - Air : $c$ augmente avec la température.

!!! warning "Attention : limite du modèle"
    Dans ce chapitre, on se limite aux milieux où $c$ ne dépend pas de la fréquence (milieux **non dispersifs**), ce qui est le cas du son dans l'air. Pour la houle en eau profonde, $c$ dépend de la période : ce cas dépasse le programme. Un énoncé le précisera.

!!! example "Argument de cohérence"
    Si la célérité du son dépendait de la fréquence, les notes graves et aiguës d'un orchestre, émises en même temps, n'arriveraient pas ensemble au fond de la salle : la mélodie serait déformée. Ce n'est pas le cas.

## 3. Ordres de grandeur

| Milieu | Onde | $c$ (ordre de grandeur) |
|---|---|---|
| Air, $20\ ^\circ\mathrm{C}$ | Son | $343\ \mathrm{m\cdot s^{-1}}$ |
| Eau liquide | Son | environ $1{,}5 \times 10^3\ \mathrm{m\cdot s^{-1}}$ |
| Acier | Son (longitudinale) | environ $5{,}9 \times 10^3\ \mathrm{m\cdot s^{-1}}$ |
| Croûte terrestre | Ondes P | environ $6\ \mathrm{km\cdot s^{-1}}$ |
| Croûte terrestre | Ondes S | environ $3{,}5\ \mathrm{km\cdot s^{-1}}$ |
| Corde de guitare | Onde transversale | quelques centaines de $\mathrm{m\cdot s^{-1}}$ |

Dans l'air, une loi empirique donne $c \approx 331 + 0{,}6\,\theta$ ($c$ en $\mathrm{m\cdot s^{-1}}$, $\theta$ en $^\circ\mathrm{C}$). Le son va **plus vite dans les solides et les liquides que dans les gaz**.

## 4. Célérité et vitesse des points du milieu

!!! failure "Erreur fréquente : confondre célérité et vitesse des éléments du milieu"
    La célérité est celle de la **perturbation**. Les éléments du milieu, eux, oscillent sur place avec une vitesse variable, très différente.

    Exemple : sur une corde, une bosse avance à $c = 150\ \mathrm{m\cdot s^{-1}}$ alors qu'un point de la corde se déplace de quelques centimètres en quelques dixièmes de seconde, soit à quelques $\mathrm{dm\cdot s^{-1}}$ au plus.

## 5. Retard, distance et célérité

!!! tip "Propriété"
    $$\tau = \frac{d}{c} \qquad\Longleftrightarrow\qquad c = \frac{d}{\tau} \qquad\Longleftrightarrow\qquad d = c\,\tau$$

!!! example "Exemple : retard entre éclair et tonnerre"
    On compte $6{,}0\ \mathrm{s}$ entre l'éclair et le tonnerre. La lumière arrive quasi instantanément (célérité $3 \times 10^8\ \mathrm{m\cdot s^{-1}}$) ; seul le son a un retard $\tau = 6{,}0\ \mathrm{s}$ : $d = c\,\tau = 343 \times 6{,}0 \approx 2{,}1 \times 10^3\ \mathrm{m}$.

## 6. Pour aller plus loin (hors programme)

!!! quote "Formules donnant la célérité"
    - Corde de masse linéique $\mu$ et de tension $F$ : $c = \sqrt{F/\mu}$. Vérification dimensionnelle : $[F/\mu] = \dfrac{\mathrm{kg\cdot m\cdot s^{-2}}}{\mathrm{kg\cdot m^{-1}}} = \mathrm{m^2\cdot s^{-2}}$, donc $c$ en $\mathrm{m\cdot s^{-1}}$ ✓.
    - Gaz parfait : $c = \sqrt{\dfrac{\gamma R T}{M}}$. Pour l'air ($\gamma = 1{,}4$, $R = 8{,}314\ \mathrm{J\cdot mol^{-1}\cdot K^{-1}}$, $T = 293\ \mathrm{K}$, $M = 0{,}029\ \mathrm{kg\cdot mol^{-1}}$) : $c = \sqrt{\dfrac{1{,}4 \times 8{,}314 \times 293}{0{,}029}} \approx 343\ \mathrm{m\cdot s^{-1}}$ ✓.
    - Vagues en eau peu profonde (profondeur $h \ll \lambda$) : $c = \sqrt{g\,h}$.

## 7. Vérifie-toi

!!! question "Énoncé"
    1. Un coup de pistolet d'un starter est entendu $0{,}50\ \mathrm{s}$ après qu'on a vu la fumée. À quelle distance est-il (air à $20\ ^\circ\mathrm{C}$) ?
    2. Si on frappe plus fort la corde, la célérité augmente-t-elle ?
    3. Pourquoi est-il faux de dire que « le son se propage à $343\ \mathrm{m\cdot s^{-1}}$ » sans autre précision ?

??? info "Corrigé"
    1. $d = c\,\tau = 343 \times 0{,}50 \approx 1{,}7 \times 10^2\ \mathrm{m}$.
    2. Non : $c$ ne dépend que du milieu. Frapper plus fort augmente l'amplitude, pas la célérité.
    3. Cette valeur n'est valable que pour l'air à $20\ ^\circ\mathrm{C}$. Dans l'eau ou l'acier, ou à une autre température, la célérité est différente.
