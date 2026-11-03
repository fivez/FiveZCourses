# Comprendre pourquoi un résultat est vrai, quand l'utiliser, comment le démontrer

Pour chaque résultat du chapitre, trois questions : **pourquoi est-ce vrai ?** **quand puis-je l'utiliser ?** **comment le démontrer en trois lignes ?**

## 1. Le retard : $\tau = d/c$

!!! tip "Pourquoi est-ce vrai ?"
    La perturbation avance à vitesse constante $c$ : la durée pour parcourir $d$ est $d/c$ (définition de la vitesse).

!!! success "Quand l'utiliser ?"
    Quand l'onde se propage **sans déformation** à **célérité constante** (milieu homogène, non dispersif). Attention : $d$ est la distance **le long de la propagation**, et pour un écho, $2d$.

!!! quote "Démonstration en trois lignes"
    1. La perturbation quitte $S$ en $t_0$. 2. Elle parcourt $d$ à vitesse $c$ : durée $d/c$. 3. Elle arrive en $M$ en $t_0 + d/c$, donc $y_M(t) = y_S(t - d/c)$.

## 2. La double périodicité

!!! tip "Pourquoi est-ce vrai ?"
    La source répète le même mouvement toutes les $T$ ; chaque point répète ce mouvement avec son retard, donc périodique en temps. À un instant fixé, des points décalés d'une distance $cT$ « sont dans la même situation », donc périodique en espace.

!!! success "Quand l'utiliser ?"
    Quand la source est périodique et le milieu non dispersif. À utiliser pour **choisir** entre lire $T$ (graphe temporel) et $\lambda$ (graphe spatial).

!!! quote "Démonstration en trois lignes"
    $y(x,t) = y_S(t - x/c)$. À $x$ fixé : remplacer $t$ par $t+T$ ne change rien. À $t$ fixé : remplacer $x$ par $x + cT$ ne change rien.

## 3. $\lambda = cT$

!!! tip "Pourquoi est-ce vrai ?"
    En une période, l'onde avance de $cT$ ; entre deux points en phase consécutifs, il y a un retard d'exactement une période.

!!! success "Quand l'utiliser ?"
    Pour tout calcul reliant une grandeur spatiale ($\lambda$) à une grandeur temporelle ($T$ ou $f$), **dans un seul milieu à la fois**. Si l'onde change de milieu, on l'applique milieu par milieu avec la **même** $f$.

!!! quote "Démonstration en trois lignes"
    Point $M$ en phase avec $S$ le plus proche : retard $\tau = T$. Or $\tau = d/c$. Donc $d = cT$, et cette distance minimale est $\lambda$ par définition.

## 4. Points en phase : $d = k\lambda$

!!! tip "Pourquoi est-ce vrai ?"
    $d = k\lambda$ correspond à un retard $kT$ ; décaler un signal périodique d'un nombre entier de périodes ne le change pas.

!!! success "Quand l'utiliser ?"
    Pour comparer deux points d'une même ligne de propagation. L'opposition de phase ($d = (k+\frac12)\lambda$) n'a de sens que pour un signal **sinusoïdal**.

!!! quote "Démonstration en trois lignes"
    $\tau = d/c = k\lambda/c = kT$. $y_M(t) = y_S(t - kT) = y_S(t)$. Pour $d = (k+\tfrac12)\lambda$ et un signal sinusoïdal : $y_M(t) = y_S(t - T/2) = -y_S(t)$.

## 5. $f$ ne change pas en changeant de milieu

!!! tip "Pourquoi est-ce vrai ?"
    À l'interface, chaque point est entraîné à la fréquence de la source et la transmet : les perturbations ne peuvent ni s'accumuler ni disparaître.

!!! success "Quand l'utiliser ?"
    À chaque exercice avec changement de milieu : $f$ commune, puis $\lambda_i = c_i/f$.

## 6. Le signal sinusoïdal reçu

!!! tip "Pourquoi est-ce vrai ?"
    $s_M(t) = s_S(t-\tau)$ est la traduction mathématique de la propriété 3 ; $\tau/T = d/\lambda$ donne le déphasage.

!!! success "Quand l'utiliser ?"
    Quand on demande l'expression du signal en un point, ou un déphasage ; sans oublier $t \geq \tau$.

## 7. Cinq questions à se poser devant tout exercice d'ondes

!!! success "Mon réflexe"
    1. **Quel milieu ?** (donc quelle célérité).
    2. **Quelle grandeur impose la source ?** ($T$, $f$).
    3. **Que représente l'axe horizontal du graphique ?** (temps ou espace).
    4. **Suis-je en train de confondre une vitesse de propagation et une vitesse de matière ?**
    5. **Mes unités et mes chiffres significatifs sont-ils corrects ?**

## 8. Test final de compréhension

!!! question "Énoncé"
    Sans formule : expliquer à un camarade pourquoi, lorsque la fréquence d'une onde double dans un milieu inchangé, la distance entre deux crêtes est divisée par deux.

??? info "Corrigé"
    La fréquence double : la période est divisée par deux. L'onde avance toujours à la même vitesse $c$ (imposée par le milieu), donc pendant une période elle parcourt une distance deux fois plus courte. Or cette distance est précisément la distance entre deux crêtes : $\lambda = cT$ est divisée par deux.
