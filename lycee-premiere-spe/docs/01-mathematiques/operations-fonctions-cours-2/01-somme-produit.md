# Somme et produit de fonctions

!!! info "Objectifs pédagogiques et compétences"
    - Définir $f+g$, $\lambda f$ et $fg$ et **déterminer leur ensemble de définition**.
    - Étudier la parité et les variations d'une somme et d'un produit.
    - Connaître les cas où l'on **ne peut pas conclure** et savoir fournir un contre-exemple.

!!! note "Prérequis"
    Notion de fonction, domaine de définition, variations (définition avec $a<b\Rightarrow f(a)\le f(b)$), parité, racine carrée.

## 1. Définitions

!!! definition "Définition : Somme et produit de deux fonctions"
    Soient $f$ et $g$ définies respectivement sur $D_f$ et $D_g$. Sur $D_f\cap D_g$ on définit :
    $$(f+g)(x)=f(x)+g(x),\qquad (fg)(x)=f(x)\times g(x),\qquad (\lambda f)(x)=\lambda f(x)\ (\lambda\in\mathbb{R}).$$

!!! attention "Attention : Le domaine est une intersection"
    $f+g$ et $fg$ ne sont définies que là où **les deux** fonctions le sont.

    Exemple : $f(x)=\sqrt{x}$ et $g(x)=\sqrt{-x}$. Alors $D_{f+g}=[0\,;+\infty[\,\cap\,]-\infty\,;0]=\{0\}$.

!!! attention "Attention : $\sqrt{u}\sqrt{v}$ n'est pas toujours $\sqrt{uv}$"
    Soit $f(x)=\sqrt{x-1}$ et $g(x)=\sqrt{x-4}$. Alors $D_{fg}=[4\,;+\infty[$, alors que la fonction $x\mapsto\sqrt{(x-1)(x-4)}$ est définie sur $]-\infty\,;1]\cup[4\,;+\infty[$. Les deux fonctions **ne sont pas les mêmes** : elles coïncident seulement sur $[4\,;+\infty[$.

## 2. Parité

!!! propriete "Propriété : Parité d'une somme et d'un produit"
    Si $f$ et $g$ sont définies sur un même domaine symétrique par rapport à $0$ : voir le tableau du chapitre *Parité*. En particulier $fg$ est impaire si l'une est paire et l'autre impaire, et **$f^2$ est toujours paire** (que $f$ soit paire ou impaire).

??? abstract "Démonstration"
    $f^2(-x)=f(-x)^2$ ; si $f(-x)=\pm f(x)$ alors $f(-x)^2=f(x)^2$.

## 3. Variations

!!! propriete "Propriété : Somme"
    Si $f$ et $g$ sont croissantes (resp. décroissantes) sur un intervalle $I$, alors $f+g$ est croissante (resp. décroissante) sur $I$.

??? abstract "Démonstration"
    Soit $a<b$ dans $I$. $f(a)\le f(b)$ et $g(a)\le g(b)$ donnent, en additionnant, $f(a)+g(a)\le f(b)+g(b)$. Même raisonnement pour la décroissance.

!!! attention "Attention : Variations contraires : aucune conclusion générale"
    Si $f$ est croissante et $g$ décroissante, $f+g$ peut être n'importe quoi : avec $f(x)=x$ :
    - $g(x)=-x$ : $f+g=0$ constante ;
    - $g(x)=-\frac x2$ : $f+g=\frac x2$ croissante ;
    - $g(x)=-2x$ : $f+g=-x$ décroissante.

    Il faut alors **étudier directement** $f+g$ (par exemple $f(b)-f(a)$).

!!! propriete "Propriété : Produit"
    Si $f$ et $g$ sont croissantes et **positives** sur $I$, alors $fg$ est croissante sur $I$. Si $\lambda>0$, $\lambda f$ a les variations de $f$ ; si $\lambda<0$, $\lambda f$ a les variations contraires.

??? abstract "Démonstration"
    Soit $a<b$ dans $I$ : $0\le f(a)\le f(b)$ et $0\le g(a)\le g(b)$. Alors $f(a)g(a)\le f(b)g(a)\le f(b)g(b)$ : on multiplie la première inégalité par $g(a)\ge0$, puis la seconde par $f(b)\ge0$.

!!! attention "Attention : Produit de deux fonctions croissantes"
    **Faux en général** : $f(x)=g(x)=x$ sont croissantes sur $\mathbb{R}$ mais $fg=x^2$ ne l'est pas (décroissante sur $]-\infty;0]$). L'hypothèse « positives » est essentielle.

## 4. Méthode

!!! methode "Méthode : Étudier les variations d'une somme ou d'un produit"
    1. Donner le domaine : intersection des domaines.
    2. Chercher un intervalle où les deux fonctions ont **les mêmes variations** (somme) et **sont positives** (produit).
    3. Sinon, **étudier directement** le signe de $h(b)-h(a)$ pour $a<b$ (factoriser !).
    4. Vérifier avec deux valeurs numériques.

## 5. Exemples corrigés

!!! example "Exemple : Domaine d'un produit"
    $f(x)=\sqrt{x-1}$ et $g(x)=\sqrt{4-x}$ : $D_f=[1;+\infty[$, $D_g=]-\infty;4]$ ; $D_{fg}=[1\,;4]$ et $(fg)(x)=\sqrt{(x-1)(4-x)}=\sqrt{-x^2+5x-4}$ ; sur $[1;4]$ les deux écritures sont définies.

!!! example "Exemple : Somme de fonctions de même sens"
    $h(x)=x^3+\sqrt{x+3}$ sur $[-3;+\infty[$ : $x^3$ et $\sqrt{x+3}$ sont croissantes, donc $h$ aussi.

## 6. Exercices progressifs

!!! question "Exercice 1 – Valeurs et domaine"
    Soit $f(x)=2x+1$ et $g(x)=\sqrt{x+3}$. Donner $D_{f+g}$, $(f+g)(1)$, $(fg)(-3)$, et les variations de $f+g$.

    ??? success "Corrigé"
        $D_f=\mathbb{R}$, $D_g=[-3;+\infty[$, donc $D_{f+g}=[-3;+\infty[$. $(f+g)(1)=3+2=5$. $(fg)(-3)=(-5)\times0=0$. $f$ et $g$ sont croissantes, donc $f+g$ est croissante sur $[-3\,;+\infty[$.

!!! question "Exercice 2 – $x\mapsto x+\dfrac1x$ (niveau soutenu)"
    Étudier les variations de $h(x)=x+\dfrac1x$ sur $]0;+\infty[$ **à partir de la définition**. Donner son minimum.

    ??? success "Corrigé"
        Pour $0<a<b$ : $h(b)-h(a)=(b-a)+\dfrac{a-b}{ab}=(b-a)\Bigl(1-\dfrac1{ab}\Bigr)=\dfrac{(b-a)(ab-1)}{ab}$.

        Le signe est celui de $ab-1$ (car $b-a>0$ et $ab>0$).

        - Si $0<a<b\le1$ : $ab<1$, donc $h(b)<h(a)$ : $h$ est **décroissante** sur $]0;1]$.
        - Si $1\le a<b$ : $ab>1$, donc $h(b)>h(a)$ : $h$ est **croissante** sur $[1;+\infty[$.

        Minimum $h(1)=2$. On retrouve $x+\frac1x\ge2$ pour $x>0$.

        *Piège : $x$ croissante et $\frac1x$ décroissante : le théorème sur les sommes ne permet aucune conclusion.*

!!! question "Exercice 3 – Parité et sommes"
    Montrer que si $f$ est paire, $g$ impaire et $f+g$ paire, alors $g=0$.

    ??? success "Corrigé"
        $(f+g)(-x)=f(x)-g(x)$ et $(f+g)(x)=f(x)+g(x)$. Paire : égalité, donc $g(x)=-g(x)$ et $g(x)=0$.

## 7. Exercices type contrôle

!!! question "Exercice C1 – Vrai ou faux (10 min)"
    $f$ et $g$ sont définies sur $I$. a) $f,g$ croissantes $\Rightarrow f+g$ croissante. b) $f,g$ croissantes $\Rightarrow fg$ croissante. c) $f,g$ croissantes $\Rightarrow f-g$ croissante. d) $f,g$ croissantes et positives $\Rightarrow fg$ croissante. e) $f$ croissante $\Rightarrow f^2$ croissante.

    ??? success "Corrigé"
        a) Vrai. b) **Faux** ($x\cdot x$ sur $\mathbb{R}$). c) **Faux** ($f=x$, $g=2x$, $f-g=-x$). d) Vrai. e) **Faux** ($f(x)=x$).

!!! question "Exercice C2 – Domaine et parité d'un produit (12 min)"
    $f(x)=\sqrt{1+x}\,\sqrt{1-x}$. a) Domaine. b) Simplifier. c) Parité. d) Montrer que $0\le f\le1$ et que le maximum est atteint en $0$.

    ??? success "Corrigé"
        a) $D=[-1;+\infty[\cap]-\infty;1]=[-1\,;1]$.

        b) Sur $[-1;1]$, $f(x)=\sqrt{(1+x)(1-x)}=\sqrt{1-x^2}$.

        c) $D$ symétrique et $f(-x)=\sqrt{1-x^2}=f(x)$ : **paire**.

        d) Sur $[-1;1]$, $0\le x^2\le1$ donc $0\le1-x^2\le1$ et $0\le f\le1$ ; $f(0)=1$ ; $f(\pm1)=0$.

!!! question "Exercice C3 – Somme sans théorème (15 min)"
    Étudier les variations de $h(x)=x^2+\dfrac{1}{x^2}$ sur $]0;+\infty[$. *Indication : poser $u=x^2$.*

    ??? success "Corrigé"
        Pour $0<a<b$ : $h(b)-h(a)=(b^2-a^2)\Bigl(1-\dfrac{1}{a^2b^2}\Bigr)=\dfrac{(b^2-a^2)(a^2b^2-1)}{a^2b^2}$.

        $b^2-a^2>0$. Le signe est celui de $a^2b^2-1=(ab-1)(ab+1)$, soit celui de $ab-1$. Donc $h$ est décroissante sur $]0;1]$ et croissante sur $[1;+\infty[$. Minimum $h(1)=2$ (c'est $u+\frac1u$ avec $u=x^2$, composée avec la croissante $x\mapsto x^2$ sur $]0;+\infty[$).

!!! tip "Fiche de révision"
    - $D_{f+g}=D_{fg}=D_f\cap D_g$.
    - Somme : mêmes variations $\Rightarrow$ mêmes variations ; sinon étudier $h(b)-h(a)$.
    - Produit : croissantes **et positives** $\Rightarrow$ croissant.
    - $f^2$ toujours paire si $f$ paire ou impaire ; $\sqrt u\sqrt v=\sqrt{uv}$ si $u,v\ge0$ seulement.
