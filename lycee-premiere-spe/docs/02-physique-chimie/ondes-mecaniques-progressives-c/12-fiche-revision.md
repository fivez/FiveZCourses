# Synthèse et fiche de révision

!!! abstract "L'essentiel en dix points"
    1. Une **onde mécanique progressive** est la propagation d'une perturbation de proche en proche dans un **milieu matériel**, avec transport d'**énergie** mais **sans transport de matière**.
    2. Le point $M$ reproduit le mouvement de la source avec un **retard** $\tau = \dfrac{d}{c}$ : $y_M(t) = y_S(t - \tau)$ pour $t \geq \tau$.
    3. **Transversale** : perturbation $\perp$ propagation (corde, ondes S). **Longitudinale** : perturbation $\parallel$ propagation (ressort, son, ondes P).
    4. **Célérité** : $c = \dfrac{d}{\Delta t}$, fixée par le **milieu**, pas par la source.
    5. **Onde progressive périodique** : la source répète la même perturbation à intervalles de temps égaux ; $f = 1/T$.
    6. **Double périodicité** : $T$ dans le temps (en un point fixé), $\lambda$ dans l'espace (à un instant fixé).
    7. $\boxed{\lambda = cT = \dfrac{c}{f}}$ : la longueur d'onde est la distance parcourue pendant une période.
    8. Points en **phase** : $d = k\lambda$ ; en **opposition de phase** : $d = (k+\tfrac12)\lambda$.
    9. Signal sinusoïdal : $s(t) = S_m\cos\!\left(\dfrac{2\pi t}{T} + \varphi\right)$, et au point $M$ : $s_M(t) = s_S(t-\tau)$, déphasage $-\dfrac{2\pi d}{\lambda}$.
    10. En changeant de milieu : $f$ et $T$ **inchangées** ; $c$ et $\lambda$ changent.

## Formules

| Grandeur | Relation | Unité |
|---|---|---|
| Retard | $\tau = d/c$ | s |
| Célérité | $c = d/\Delta t$ | $\mathrm{m\cdot s^{-1}}$ |
| Fréquence | $f = 1/T$ | Hz |
| Longueur d'onde | $\lambda = cT = c/f$ | m |
| Signal sinusoïdal | $s(t) = S_m\cos\left(\frac{2\pi}{T}t + \varphi\right)$ | unité de $s$ |
| Déphasage dû au retard | $\Delta\varphi = -2\pi\tau/T = -2\pi d/\lambda$ | rad |

## Ordres de grandeur à connaître

| Milieu | $c$ |
|---|---|
| Air ($20\ ^\circ\mathrm{C}$) | $343\ \mathrm{m\cdot s^{-1}}$ |
| Eau | $\approx 1{,}5 \times 10^3\ \mathrm{m\cdot s^{-1}}$ |
| Acier | $\approx 5{,}9 \times 10^3\ \mathrm{m\cdot s^{-1}}$ |
| Ondes sismiques P / S (croûte) | $\approx 6\ /\ 3{,}5\ \mathrm{km\cdot s^{-1}}$ |

## Points d'attention à relire avant le contrôle

!!! failure "Les erreurs qui coûtent des points"
    - Lire $\lambda$ sur un graphe temporel (ou $T$ sur un graphe spatial).
    - Oublier de convertir ms, kHz, mm, km.
    - Compter $n$ crêtes comme $n$ longueurs d'onde (il y en a $n-1$).
    - Oublier le facteur 2 pour un écho (aller-retour).
    - Affirmer que $c$ dépend de la fréquence, ou que $f$ change quand on change de milieu.
    - Confondre célérité de l'onde et vitesse des points du milieu.
    - Calculatrice en degrés.
    - Écrire $t+\tau$ au lieu de $t-\tau$, ou oublier $t \geq \tau$.

## Liste de contrôle

- [ ] Je sais définir : perturbation, onde mécanique progressive, onde transversale, longitudinale, célérité, période, fréquence, longueur d'onde.
- [ ] Je sais démontrer $\tau = d/c$, la double périodicité, $\lambda = cT$.
- [ ] Je sais lire $T$, $f$, $\lambda$, $S_m$, $\varphi$ sur un graphe.
- [ ] Je sais écrire le signal reçu en un point.
- [ ] Je sais décider si deux points sont en phase ou en opposition.

## Cartes flash

??? question "Une onde mécanique transporte-t-elle de la matière ?"
    Non : elle transporte de l'énergie et de l'information.

??? question "Que fixe la source ? Que fixe le milieu ?"
    La source fixe $T$ et $f$ ; le milieu fixe $c$ ; ensemble ils fixent $\lambda = cT$.

??? question "Comment définir $\lambda$ sans formule ?"
    Plus petite distance entre deux points du milieu qui vibrent en phase ; distance parcourue par l'onde pendant une période.

??? question "Un son change de milieu. Que devient $f$ ?"
    Elle ne change pas.

??? question "Retard et déphasage : lien ?"
    $\Delta\varphi = -2\pi\tau/T = -2\pi d/\lambda$.

??? question "Pourquoi le son est-il longitudinal dans l'air ?"
    Un fluide ne transmet pas le cisaillement : seules les compressions-dilatations se propagent, dans la direction de propagation.
