# Inverse et quotient de fonctions

!!! info "Objectifs pédagogiques et compétences"
    - Définir $\dfrac1f$ et $\dfrac fg$ et **exclure** les valeurs qui annulent le dénominateur.
    - Déduire les variations de $\frac1f$ de celles de $f$ quand $f$ garde un signe constant.
    - Reconnaître les pièges : fonction de signe non constant, domaine, simplification abusive.

!!! note "Prérequis"
    Chapitre précédent ; variations ; inégalités et inverses de nombres de même signe ; parité.

## 1. Définitions

!!! definition "Définition : Inverse d'une fonction"
    Soit $f$ définie sur $D_f$. La fonction **inverse** de $f$, notée $\dfrac1f$, est définie sur
    $$D_{1/f}=\{x\in D_f\;:\;f(x)\neq0\},\qquad \frac1f(x)=\frac1{f(x)}.$$

!!! definition "Définition : Quotient de deux fonctions"
    Soient $f$ et $g$. Le **quotient** $\dfrac fg$ est défini sur
    $$D_{f/g}=\{x\in D_f\cap D_g\;:\;g(x)\neq0\},\qquad \Bigl(\frac fg\Bigr)(x)=\frac{f(x)}{g(x)}.$$

!!! attention "Attention : Le domaine ne se « simplifie » pas"
    $f(x)=x^2-1$, $g(x)=x-1$ : $\dfrac fg$ est définie sur $\mathbb{R}\setminus\{1\}$ et vaut $x+1$ **sur ce domaine**. La fonction $x\mapsto x+1$ est définie sur $\mathbb{R}$ : ce n'est pas la même fonction (sa courbe a un point en plus, celui d'abscisse $1$).

    De même, $\dfrac{x}{\sqrt x}$ est définie sur $]0;+\infty[$ et vaut $\sqrt x$, qui est définie en $0$.

## 2. Parité

!!! propriete "Propriété : Parité d'un inverse ou d'un quotient"
    - $f$ paire (impaire) $\Rightarrow$ $\frac1f$ paire (impaire).
    - Quotient : paire/paire et impaire/impaire donnent une fonction **paire** ; paire/impaire et impaire/paire donnent une fonction **impaire** (sur un domaine symétrique).

## 3. Variations

!!! propriete "Propriété : Variations de l'inverse"
    Soit $f$ **de signe constant strict** (toujours $>0$ ou toujours $<0$) sur un intervalle $I$. Alors $\dfrac1f$ a sur $I$ des variations **contraires** à celles de $f$.

??? abstract "Démonstration"
    Soit $a<b$ dans $I$ avec $f$ croissante.

    Si $f>0$ : $0<f(a)\le f(b)$ donc $\frac1{f(a)}\ge\frac1{f(b)}$ : $\frac1f$ décroissante.

    Si $f<0$ : $f(a)\le f(b)<0$ ; la fonction inverse est décroissante sur $]-\infty;0[$ donc $\frac1{f(a)}\ge\frac1{f(b)}$ : $\frac1f$ décroissante. Même raisonnement si $f$ est décroissante.

!!! attention "Attention : Il faut un signe constant, et un intervalle"
    La fonction inverse $x\mapsto\frac1x$ est décroissante sur $]-\infty;0[$ et sur $]0;+\infty[$, **mais pas** sur $\mathbb{R}^*$ : $-1<1$ et pourtant $\frac1{-1}=-1<1=\frac11$.

    De même, $f(x)=x-1$ est croissante sur $\mathbb{R}$, mais $\frac1f$ n'est monotone ni sur $\mathbb{R}\setminus\{1\}$ (signe de $f$ qui change) ; elle est décroissante sur chacun des intervalles $]-\infty;1[$ et $]1;+\infty[$.

!!! methode "Méthode : Variations d'un quotient"
    1. Domaine ($g\neq0$). 2. Signe du dénominateur sur chaque intervalle. 3. Écrire, si possible, $\dfrac fg=\text{constante}+\dfrac{k}{\text{expression affine}}$ (division). 4. Appliquer les théorèmes (inverse, multiplication par une constante, somme). 5. Sinon étudier $h(b)-h(a)$.

## 4. Exemples corrigés

!!! example "Exemple : $h(x)=\dfrac1{x^2+1}$"
    $x^2+1\ge1>0$ : $D=\mathbb{R}$. $x^2+1$ est décroissante sur $]-\infty;0]$ et croissante sur $[0;+\infty[$ ; donc $h$ est **croissante** sur $]-\infty;0]$ et **décroissante** sur $[0;+\infty[$, maximum $h(0)=1$, $0<h\le1$ ; $h$ est paire.

!!! example "Exemple : Quotient et valeur absolue"
    $q(x)=\dfrac{|x|}{x}$ est définie sur $\mathbb{R}^*$, $q(x)=1$ si $x>0$, $q(x)=-1$ si $x<0$. Impaire : c'est le quotient d'une fonction paire ($|x|$) par une fonction impaire ($x$). Ce n'est pas la fonction constante $1$.

## 5. Exercices progressifs

!!! question "Exercice 1 – Domaines"
    Donner le domaine de : a) $\dfrac{2x+1}{x^2-4x+3}$ ; b) $\dfrac{\sqrt{x}}{x^2-4x}$ ; c) $\dfrac1{\,|x|-2\,}$.

    ??? success "Corrigé"
        a) $x^2-4x+3=(x-1)(x-3)$ : $D=\mathbb{R}\setminus\{1,3\}$.

        b) $x\ge0$ et $x(x-4)\neq0$ : $D=]0;4[\,\cup\,]4;+\infty[$ (le $0$ est exclu par le dénominateur).

        c) $|x|\neq2$ : $D=\mathbb{R}\setminus\{-2,2\}$.

!!! question "Exercice 2 – $h(x)=\dfrac1{x^2-2x+5}$"
    Montrer que $h$ est définie sur $\mathbb{R}$, étudier ses variations, trouver son maximum et l'ensemble des valeurs prises.

    ??? success "Corrigé"
        $x^2-2x+5=(x-1)^2+4\ge4>0$. Le dénominateur décroît sur $]-\infty;1]$ puis croît : $h$ **croît** sur $]-\infty;1]$ et **décroît** sur $[1;+\infty[$. Maximum $h(1)=\frac14$. Donc $0<h(x)\le\frac14$.

!!! question "Exercice 3 – Parité d'un quotient"
    Étudier la parité de $q(x)=\dfrac{x^3-x}{x^2-1}$ et la comparer à $x\mapsto x$.

    ??? success "Corrigé"
        $D=\mathbb{R}\setminus\{-1,1\}$, symétrique. $q(x)=\dfrac{x(x^2-1)}{x^2-1}=x$ sur $D$ : $q$ est impaire (impaire/paire). Mais $q\neq(x\mapsto x)$ car son domaine est $\mathbb{R}\setminus\{\pm1\}$.

## 6. Exercices type contrôle

!!! question "Exercice C1 – Variations d'une fonction homographique (15 min)"
    Soit $f(x)=\dfrac{x-2}{x+1}$. a) Domaine. b) Montrer que $f(x)=1-\dfrac3{x+1}$. c) Variations sur chaque intervalle du domaine. d) $f$ est-elle croissante sur $D$ ?

    ??? success "Corrigé"
        a) $D=\mathbb{R}\setminus\{-1\}$.

        b) $1-\dfrac3{x+1}=\dfrac{x+1-3}{x+1}=\dfrac{x-2}{x+1}$ ✓.

        c) Sur $]-1;+\infty[$ : $x+1>0$ croissante donc $\frac1{x+1}$ décroissante, $-\frac3{x+1}$ croissante, $f$ croissante. Sur $]-\infty;-1[$ : $x+1<0$ croissante, $\frac1{x+1}$ décroissante, donc $f$ croissante.

        d) **Non** : $f(-2)=\frac{-4}{-1}=4$ et $f(0)=-2$. On a $-2<0$ et $f(-2)>f(0)$. *Croissante sur chaque intervalle, pas sur la réunion.*

!!! question "Exercice C2 – Une fonction bornée (20 min)"
    $f(x)=\dfrac{x}{x^2+1}$. a) Parité. b) Montrer $|f(x)|\le\frac12$. c) Variations sur $[0;+\infty[$ en écrivant $f(x)=\dfrac1{x+\frac1x}$ pour $x>0$. d) Tableau de variations sur $\mathbb{R}$ et extrema.

    ??? success "Corrigé"
        a) $D=\mathbb{R}$, $f$ impaire.

        b) $(|x|-1)^2\ge0\iff x^2+1\ge2|x|$, d'où $\dfrac{|x|}{x^2+1}\le\dfrac12$, égalité si $|x|=1$.

        c) Pour $x>0$ : $f(x)=\dfrac{1}{x+\frac1x}$. $x+\frac1x$ est décroissante sur $]0;1]$ et croissante sur $[1;+\infty[$ (chapitre précédent) et strictement positive, donc $f$ est croissante sur $]0;1]$ et décroissante sur $[1;+\infty[$ ; $f(0)=0$, donc croissante sur $[0;1]$.

        d) Par imparité : croissante sur $[-1;1]$, décroissante sur $]-\infty;-1]$ et sur $[1;+\infty[$. Maximum $\frac12$ en $1$, minimum $-\frac12$ en $-1$.

!!! question "Exercice C3 – Domaine du quotient (8 min)"
    $f(x)=\sqrt x$ et $g(x)=x^2-4x$. Donner $D_{f/g}$ et simplifier $\frac fg$ pour $x\in D_{f/g}$.

    ??? success "Corrigé"
        $x\ge0$ et $x(x-4)\neq0$ : $D=]0;4[\,\cup\,]4;+\infty[$. $\dfrac fg(x)=\dfrac{\sqrt x}{x(x-4)}=\dfrac1{\sqrt x\,(x-4)}$ sur $D$.

!!! tip "Fiche de révision"
    - $D_{1/f}=\{f\neq0\}$ ; $D_{f/g}=D_f\cap D_g\cap\{g\neq0\}$.
    - Signe constant sur $I$ $\Rightarrow$ $\frac1f$ a des variations contraires.
    - $\frac1x$ décroît sur chaque intervalle de $\mathbb{R}^*$ **séparément**.
    - Un quotient simplifié n'a pas toujours le même domaine que le quotient initial.
