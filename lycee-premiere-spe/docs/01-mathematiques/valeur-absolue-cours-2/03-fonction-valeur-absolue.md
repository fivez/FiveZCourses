# Étude de la fonction valeur absolue

!!! info "Objectifs pédagogiques et compétences"
    - Étudier la **parité**, les **variations** et tracer la courbe de $x\mapsto|x|$.
    - Obtenir l'expression par morceaux de $|f|$ et de $x\mapsto|x-a|+b$.
    - Déduire la courbe de $|f|$ de celle de $f$ et ses variations de celles de $f$.
    - Repérer le point anguleux en $0$.

!!! note "Prérequis"
    Chapitres 01 et 02 ; variations d'une fonction ; fonctions affines et carré ; signe d'une expression ; lecture graphique.

## 1. La fonction valeur absolue

!!! definition "Définition : Fonction valeur absolue"
    C'est la fonction $\operatorname{abs}:\mathbb{R}\to\mathbb{R}$, $x\mapsto|x|$. Son ensemble de définition est $\mathbb{R}$ et
    $$|x|=\begin{cases}-x&\text{si }x\le0\\ x&\text{si }x\ge0.\end{cases}$$

!!! propriete "Propriété : Parité, variations, extremum"
    1. La fonction valeur absolue est **paire**.
    2. Elle est **strictement décroissante** sur $]-\infty\,;0]$ et **strictement croissante** sur $[0\,;+\infty[$.
    3. Elle admet un **minimum** égal à $0$, atteint **uniquement** en $0$.

??? abstract "Démonstration"
    1. $D=\mathbb{R}$ est symétrique et $|-x|=|x|$.
    2. Sur $[0\,;+\infty[$, $|x|=x$ : strictement croissante. Sur $]-\infty\,;0]$, $|x|=-x$ : fonction affine de coefficient $-1<0$, strictement décroissante.
    3. $|x|\ge0=|0|$ et $|x|=0\iff x=0$.

| $x$ | $-\infty$ | | $0$ | | $+\infty$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| $\lvert x\rvert$ | $+\infty$ | $\searrow$ | $0$ | $\nearrow$ | $+\infty$ |

!!! propriete "Propriété : Courbe représentative"
    Dans un repère orthonormé, la courbe de $x\mapsto|x|$ est la réunion de deux demi-droites d'origine $O$ : la demi-droite $y=-x$ ($x\le0$) et la demi-droite $y=x$ ($x\ge0$). C'est une courbe en forme de « V » dont le sommet est $O$, symétrique par rapport à l'axe des ordonnées. Elle est tracée avec les deux bissectrices des axes.

!!! attention "Attention : Pas de tangente en $0$"
    Le taux d'accroissement en $0$ est $\dfrac{|h|}{h}$ : il vaut $+1$ pour $h>0$ et $-1$ pour $h<0$. Il n'a donc pas de limite quand $h\to0$ : **la fonction valeur absolue n'est pas dérivable en $0$** (point anguleux), alors qu'elle l'est partout ailleurs (dérivée $-1$ sur $]-\infty;0[$, $1$ sur $]0;+\infty[$).

## 2. La fonction $|f|$

!!! propriete "Propriété : Courbe et variations de $|f|$"
    Soit $f$ une fonction, $\mathcal{C}_f$ sa courbe.

    - Là où $f\ge0$ : $|f|=f$ ; là où $f\le0$ : $|f|=-f$.
    - $\mathcal{C}_{|f|}$ s'obtient en **conservant** la partie de $\mathcal{C}_f$ située au-dessus de l'axe des abscisses et en **symétrisant par rapport à cet axe** la partie située au-dessous.
    - Sur un intervalle où $f\ge0$, $|f|$ a les mêmes variations que $f$ ; sur un intervalle où $f\le0$, $|f|$ a les variations **contraires**.

!!! methode "Méthode : Étudier $|f|$"
    ```mermaid
    flowchart TD
      A["Fonction f"] --> B["Étudier le signe de f : tableau de signes"]
      B --> C["Écrire |f| par morceaux : f là où f ≥ 0, -f là où f ≤ 0"]
      C --> D["Déduire les variations sur chaque morceau"]
      D --> E["Recoller : valeurs aux bornes, extrema, points anguleux"]
      E --> F["Tracer : garder le haut, symétriser le bas par rapport à l'axe des abscisses"]
    ```

!!! attention "Attention : Les points de recollement"
    Aux zéros de $f$ (où le signe change), $|f|$ présente en général un **point anguleux**. Une étude de variations qui oublie de comparer les valeurs aux bornes des morceaux est incomplète.

## 3. Exemples corrigés

!!! example "Exemple : $f(x)=|x-2|+1$"
    $f(x)=x-1$ pour $x\ge2$ et $f(x)=3-x$ pour $x\le2$. Décroissante sur $]-\infty\,;2]$, croissante sur $[2\,;+\infty[$, minimum $1$ en $x=2$ : la courbe est celle de $|x|$ translatée du vecteur $\binom{2}{1}$ (voir le chapitre *Opérations sur les fonctions*). Axe de symétrie : $x=2$, car $f(2+h)=|h|+1=f(2-h)$.

!!! example "Exemple : $g(x)=|x^2-4|$"
    $x^2-4\ge0\iff|x|\ge2$. Donc $g(x)=x^2-4$ si $|x|\ge2$ et $g(x)=4-x^2$ si $|x|<2$. $g$ est paire. Sur $[0\,;2]$, $4-x^2$ décroît de $4$ à $0$ ; sur $[2\,;+\infty[$, $x^2-4$ croît. Par parité :

    | $x$ | $-\infty$ | | $-2$ | | $0$ | | $2$ | | $+\infty$ |
    |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
    | $g(x)$ | $+\infty$ | $\searrow$ | $0$ | $\nearrow$ | $4$ | $\searrow$ | $0$ | $\nearrow$ | $+\infty$ |

    La courbe a la forme d'un « W » : les minima $0$ en $\pm2$ sont des points anguleux ; le maximum **local** $4$ en $0$ est lisse (sommet d'une parabole).

## 4. Exercices progressifs

!!! question "Exercice 1 – Courbe de $x\mapsto|x+1|-2$"
    Écrire la fonction par morceaux, dresser le tableau de variations, trouver les zéros et l'axe de symétrie.

    ??? success "Corrigé"
        $f(x)=x-1$ si $x\ge-1$ ; $f(x)=-x-3$ si $x\le-1$. Décroissante sur $]-\infty\,;-1]$, croissante sur $[-1\,;+\infty[$, minimum $-2$ en $-1$. $f(x)=0\iff|x+1|=2\iff x=1$ ou $x=-3$. Axe de symétrie : $x=-1$ car $f(-1+h)=|h|-2=f(-1-h)$.

!!! question "Exercice 2 – La fonction $x\mapsto|2x-3|$"
    Écrire par morceaux, donner les variations, le minimum, et les pentes des deux demi-droites.

    ??? success "Corrigé"
        $|2x-3|=2x-3$ si $x\ge\frac32$ et $3-2x$ si $x\le\frac32$. Décroissante sur $]-\infty\,;\frac32]$, croissante sur $[\frac32\,;+\infty[$, minimum $0$ en $\frac32$. Pentes $-2$ et $2$ : le « V » est plus fermé que celui de $|x|$.

!!! question "Exercice 3 – $h(x)=|x^2-2x|$"
    a) Écrire $h$ par morceaux. b) Dresser le tableau de variations. c) Résoudre $h(x)=1$ puis $h(x)\le1$.

    ??? success "Corrigé"
        a) $x^2-2x=x(x-2)\ge0\iff x\le0$ ou $x\ge2$. Donc $h(x)=x^2-2x$ sur $]-\infty\,;0]\cup[2\,;+\infty[$ et $h(x)=-x^2+2x$ sur $[0\,;2]$.

        b) $x\mapsto x^2-2x$ est décroissante sur $]-\infty\,;1]$ et croissante sur $[1\,;+\infty[$. Donc $h$ est décroissante sur $]-\infty\,;0]$, croissante sur $[0\,;1]$ (car $-x^2+2x$ a pour sommet $(1\,;1)$), décroissante sur $[1\,;2]$, croissante sur $[2\,;+\infty[$. Valeurs : $h(0)=0$, $h(1)=1$, $h(2)=0$.

        c) Sur les zones extérieures : $x^2-2x=1\iff x=1\pm\sqrt2$, soit $1+\sqrt2\approx2{,}41\ge2$ ✓ et $1-\sqrt2\approx-0{,}41\le0$ ✓. Sur $[0;2]$ : $-x^2+2x=1\iff(x-1)^2=0\iff x=1$ ✓. $S=\{1-\sqrt2\,;1\,;1+\sqrt2\}$.

        Pour $h(x)\le1$ : sur $[0;2]$, $-x^2+2x\le1\iff-(x-1)^2\le0$ : toujours vrai ; sur les zones extérieures, $x^2-2x\le1\iff x\in[1-\sqrt2\,;1+\sqrt2]$. Donc $S=[1-\sqrt2\,;1+\sqrt2]$.

## 5. Exercices type contrôle

!!! question "Exercice C1 – $f(x)=|x-1|+|x+2|$ (15 min)"
    a) Écrire $f$ par morceaux. b) Variations et minimum. c) $f$ est-elle paire ? d) Montrer que $\mathcal{C}_f$ admet pour axe de symétrie la droite $x=-\frac12$. e) Résoudre $f(x)=5$.

    ??? success "Corrigé"
        a) $f(x)=-2x-1$ si $x<-2$ ; $f(x)=3$ si $-2\le x\le1$ ; $f(x)=2x+1$ si $x>1$.

        b) Décroissante sur $]-\infty\,;-2]$, **constante** sur $[-2\,;1]$, croissante sur $[1\,;+\infty[$. Minimum $3$, atteint **sur tout** $[-2\,;1]$ (pas en un seul point).

        c) Non : $f(2)=1+4=5$ et $f(-2)=3+0=3$.

        d) $f\bigl(-\tfrac12+h\bigr)=\bigl|h-\tfrac32\bigr|+\bigl|h+\tfrac32\bigr|$ est paire en $h$ : $f(-\frac12+h)=f(-\frac12-h)$. *Piège : une fonction non paire peut avoir un axe de symétrie $\neq(Oy)$.*

        e) $-2x-1=5\iff x=-3$ ✓ ; $2x+1=5\iff x=2$ ✓ ; palier à $3\neq5$. $S=\{-3\,;2\}$.

!!! question "Exercice C2 – $f(x)=\dfrac{|x|}{1+|x|}$ (15 min)"
    a) Domaine et parité. b) Montrer que $0\le f(x)<1$. c) Montrer que $f$ est strictement croissante sur $[0;+\infty[$ **à partir de la définition**. d) En déduire le tableau de variations sur $\mathbb{R}$. e) Résoudre $f(x)=\frac12$.

    ??? success "Corrigé"
        a) $1+|x|\ge1>0$ : $D=\mathbb{R}$, $f$ paire.

        b) $|x|\ge0$ et $1+|x|>0$ donne $f\ge0$ ; $f(x)=1-\dfrac1{1+|x|}<1$.

        c) Pour $0\le a<b$ : $f(b)-f(a)=\dfrac{b}{1+b}-\dfrac a{1+a}=\dfrac{b(1+a)-a(1+b)}{(1+a)(1+b)}=\dfrac{b-a}{(1+a)(1+b)}>0$.

        d) Croissante sur $[0;+\infty[$, donc (parité) décroissante sur $]-\infty;0]$. Minimum $0$ en $0$.

        e) $\dfrac{|x|}{1+|x|}=\dfrac12\iff2|x|=1+|x|\iff|x|=1\iff x=\pm1$.

!!! question "Exercice C3 – $f(x)=x|x|$ : le piège du recollement (15 min)"
    a) Parité. b) Écrire par morceaux. c) Montrer que $f$ est strictement croissante sur $\mathbb{R}$. d) Résoudre $f(x)=4$ et $f(x)=-9$.

    ??? success "Corrigé"
        a) $f(-x)=-x|-x|=-x|x|=-f(x)$ : impaire.

        b) $f(x)=x^2$ si $x\ge0$ ; $f(x)=-x^2$ si $x<0$.

        c) Sur $[0;+\infty[$, $x^2$ est croissante. Sur $]-\infty;0]$, $x^2$ est décroissante donc $-x^2$ **croissante**. Recollement : si $a\le0\le b$ alors $f(a)\le0\le f(b)$. Donc $f$ est croissante sur $\mathbb{R}$ (strictement : sinon deux valeurs égales forceraient $a=b=0$).

        *Piège : « croissante sur chaque morceau » ne suffit pas à conclure sur la réunion ; ici c'est vrai grâce au recollement en 0, ce serait faux avec $f(x)=x^2$ sur $\mathbb{R}$.*

        d) $f(x)=4$ : $x\ge0$ et $x^2=4$, donc $x=2$. $f(x)=-9$ : $x<0$ et $-x^2=-9$, donc $x=-3$.

!!! tip "Fiche de révision"
    - $|x|$ : paire, décroissante sur $]-\infty;0]$, croissante sur $[0;+\infty[$, minimum $0$ en $0$ ; courbe en « V » (bissectrices) ; non dérivable en $0$.
    - $|f|$ : garder le haut, symétriser le bas ; mêmes variations où $f\ge0$, variations contraires où $f\le0$.
    - $x\mapsto|x-a|+b$ : sommet $(a;b)$, axe $x=a$.
    - Étude par morceaux : signe $\to$ expression $\to$ variations $\to$ comparer les valeurs de recollement.
