# Rappel : parité d'une fonction

!!! info "Objectifs pédagogiques et compétences"
    - Reconnaître un ensemble de définition **symétrique par rapport à 0**.
    - Définir, puis **démontrer** qu'une fonction est paire, impaire, ou ni l'un ni l'autre.
    - Interpréter la parité sur la courbe et l'utiliser pour réduire une étude.
    - Éviter les pièges de domaine, de $f(0)$ et de la « parité des sommes ».

!!! note "Prérequis"
    Notion de fonction et d'ensemble de définition ; repère orthogonal ; symétries axiale et centrale ; développements de $(a\pm b)^2$ et $(a\pm b)^3$.

## 1. Définitions

!!! definition "Définition : Ensemble symétrique par rapport à 0"
    Un ensemble $D\subset\mathbb{R}$ est **symétrique par rapport à 0** si
    $$\forall x\in D,\quad -x\in D .$$

Sont symétriques : $\mathbb{R}$, $\mathbb{R}^*$, $[-3\,;3]$, $]-\infty\,;-1]\cup[1\,;+\infty[$.
Ne sont pas symétriques : $[-1\,;2]$, $[0\,;+\infty[$, $\mathbb{R}\setminus\{1\}$.

!!! definition "Définition : Fonction paire, fonction impaire"
    Soit $f$ une fonction dont l'ensemble de définition $D_f$ est **symétrique par rapport à 0**.

    - $f$ est **paire** si, pour tout $x\in D_f$, $\;f(-x)=f(x)$ ;
    - $f$ est **impaire** si, pour tout $x\in D_f$, $\;f(-x)=-f(x)$.

!!! attention "Attention : La symétrie du domaine fait partie de la définition"
    Pour parler de $f(-x)$, il faut que $-x\in D_f$. Si $D_f$ n'est pas symétrique, $f$ **n'est ni paire ni impaire**, même si une formule « a l'air paire ».

    Exemple : $f(x)=x^2$ définie sur $[-1\,;2]$ n'est pas paire, car $2\in D_f$ mais $-2\notin D_f$.

## 2. Interprétation graphique

!!! propriete "Propriété : Parité et courbe"
    Le plan est muni d'un repère **orthogonal**. Soit $f$ de domaine $D_f$ symétrique par rapport à 0.

    - $f$ est paire $\iff$ $\mathcal{C}_f$ est symétrique par rapport à l'**axe des ordonnées**.
    - $f$ est impaire $\iff$ $\mathcal{C}_f$ est symétrique par rapport à l'**origine** $O$.

??? abstract "Démonstration"
    Soit $x\in D_f$, $M(x\,;f(x))\in\mathcal{C}_f$ et $M'(-x\,;f(-x))\in\mathcal{C}_f$.

    *Cas pair.* Si $f(-x)=f(x)$ alors $M'(-x\,;f(x))$ : c'est le symétrique de $M$ par rapport à $(Oy)$. Réciproquement, si $\mathcal{C}_f$ est symétrique par rapport à $(Oy)$, le point $(-x\,;f(x))$ appartient à $\mathcal{C}_f$ ; or l'unique point de $\mathcal{C}_f$ d'abscisse $-x$ est $M'$, donc $f(-x)=f(x)$.

    *Cas impair.* Si $f(-x)=-f(x)$ alors $M'(-x\,;-f(x))$ : c'est le symétrique de $M$ par rapport à $O$. La réciproque se traite de la même façon : l'unicité de l'image d'un réel est l'argument clé.

## 3. Parité et opérations

!!! propriete "Propriété : Somme et produit"
    | $f$ | $g$ | $f+g$ | $f\times g$ |
    |:---:|:---:|:---:|:---:|
    | paire | paire | paire | paire |
    | impaire | impaire | impaire | **paire** |
    | paire | impaire | en général ni l'une ni l'autre | impaire |

??? abstract "Démonstration : Produit de deux fonctions impaires"
    $(fg)(-x)=f(-x)\,g(-x)=\bigl(-f(x)\bigr)\bigl(-g(x)\bigr)=f(x)g(x)=(fg)(x)$. Les autres cases se démontrent de la même façon.

## 4. Méthode

!!! methode "Méthode : Étudier la parité d'une fonction"
    ```mermaid
    flowchart TD
      A["f définie sur D"] --> B{"D symétrique par rapport à 0 ?"}
      B -- "Non" --> C["f n'est ni paire ni impaire"]
      B -- "Oui" --> D["Calculer f de -x et simplifier"]
      D --> E{"f(-x) = f(x) pour tout x ?"}
      E -- "Oui" --> F["f est paire"]
      E -- "Non" --> G{"f(-x) = -f(x) pour tout x ?"}
      G -- "Oui" --> H["f est impaire"]
      G -- "Non" --> I["Ni paire ni impaire : donner un contre-exemple chiffré"]
    ```
    Rédaction : « $D_f$ est symétrique par rapport à 0. Pour tout $x\in D_f$, $f(-x)=\dots=\dots$ ». Pour **réfuter**, il suffit d'**un** contre-exemple numérique.

## 5. Exemples corrigés

!!! example "Exemple : Fonction paire"
    $f(x)=x^4-3x^2+1$ sur $\mathbb{R}$. $D_f=\mathbb{R}$ est symétrique et $f(-x)=(-x)^4-3(-x)^2+1=f(x)$ : $f$ est **paire**.

!!! example "Exemple : Fonction impaire"
    $g(x)=\dfrac{x}{x^2+1}$. Le dénominateur ne s'annule jamais, $D_g=\mathbb{R}$. $g(-x)=\dfrac{-x}{x^2+1}=-g(x)$ : $g$ est **impaire**.

!!! example "Exemple : Domaine non symétrique"
    $h(x)=\dfrac{1}{x-1}$ : $D_h=\mathbb{R}\setminus\{1\}$. On a $-1\in D_h$ mais $1\notin D_h$ : le domaine n'est pas symétrique, $h$ n'est ni paire ni impaire. On n'a même pas besoin de calculer $h(-x)$.

!!! example "Exemple : Ni paire ni impaire, avec contre-exemple"
    $k(x)=x^3+x^2$ : $k(1)=2$ et $k(-1)=0$. Comme $k(-1)\neq k(1)$, $k$ n'est pas paire ; comme $k(-1)\neq -k(1)$, elle n'est pas impaire.

## 6. Exercices progressifs

!!! question "Exercice 1 – Reconnaître la parité"
    Étudier la parité de :
    a) $f(x)=3x^5-2x$ ; b) $g(x)=\dfrac{x^2-1}{x^2+4}$ ; c) $h(x)=\sqrt{x^2-4}$ ; d) $k(x)=\dfrac{1}{x^2-x}$.

    ??? success "Corrigé"
        a) $D=\mathbb{R}$ ; $f(-x)=-3x^5+2x=-f(x)$ : **impaire**.

        b) $D=\mathbb{R}$ (car $x^2+4>0$) ; $g(-x)=g(x)$ : **paire**.

        c) $x^2-4\ge 0\iff x\le-2$ ou $x\ge 2$ : $D=]-\infty\,;-2]\cup[2\,;+\infty[$, symétrique. $h(-x)=\sqrt{(-x)^2-4}=h(x)$ : **paire**.

        d) $x^2-x=x(x-1)=0\iff x\in\{0,1\}$ : $D=\mathbb{R}\setminus\{0,1\}$. Or $-1\in D$ mais $1\notin D$ : **ni paire ni impaire**. *Piège : $k(-x)=\frac{1}{x^2+x}$ ressemble à $k(x)$ sans lui être égale, et le domaine n'est de toute façon pas symétrique.*

!!! question "Exercice 2 – Prolonger une fonction"
    Soit $f$ **impaire** sur $\mathbb{R}$ avec $f(x)=x^2-2x$ pour $x\ge0$, et $g$ **paire** sur $\mathbb{R}$ avec $g(x)=x^2-2x$ pour $x\ge0$. Donner $f(x)$ et $g(x)$ pour $x<0$, puis $f(-3)$ et $g(-3)$.

    ??? success "Corrigé"
        Pour $x<0$, on a $-x>0$.

        $f(x)=-f(-x)=-\bigl((-x)^2-2(-x)\bigr)=-(x^2+2x)=-x^2-2x$.

        $g(x)=g(-x)=(-x)^2-2(-x)=x^2+2x$.

        $f(-3)=-f(3)=-(9-6)=-3$ ; $g(-3)=g(3)=3$. Vérification : $-(-3)^2-2(-3)=-9+6=-3$ ✓ et $(-3)^2+2(-3)=3$ ✓.

!!! question "Exercice 3 – Le cas de $f(0)$"
    a) Montrer que si $f$ est impaire et définie en $0$, alors $f(0)=0$.
    b) La réciproque est-elle vraie ? c) Une fonction impaire peut-elle avoir une courbe qui ne passe pas par l'origine ?

    ??? success "Corrigé"
        a) $f(-0)=-f(0)$ donne $f(0)=-f(0)$, donc $2f(0)=0$.

        b) **Non.** $f(x)=x^2$ vérifie $f(0)=0$ mais est paire, non impaire ($f(-1)=1\neq-f(1)$).

        c) Oui, si $f$ **n'est pas définie en 0** : $x\mapsto\frac1x$ est impaire et sa courbe (une hyperbole) ne contient pas $O$.

!!! question "Exercice 4 – La seule fonction à la fois paire et impaire"
    Déterminer les fonctions à la fois paires et impaires.

    ??? success "Corrigé"
        Soit $f$ paire et impaire, $D_f$ symétrique. Pour $x\in D_f$ : $f(x)=f(-x)=-f(x)$, donc $f(x)=0$. Réciproquement la fonction nulle (sur un domaine symétrique) est paire et impaire. Ce sont donc exactement les **fonctions nulles sur un domaine symétrique**.

!!! question "Exercice 5 – Décomposition (niveau supérieur)"
    Soit $f$ définie sur un domaine $D$ symétrique par rapport à 0. On pose $p(x)=\dfrac{f(x)+f(-x)}{2}$ et $i(x)=\dfrac{f(x)-f(-x)}{2}$.
    a) Montrer que $p$ est paire, $i$ impaire et $f=p+i$.
    b) Appliquer à $f(x)=(x+1)^3$.
    c) Montrer que cette décomposition est **unique**.

    ??? success "Corrigé"
        a) $p(-x)=\frac{f(-x)+f(x)}{2}=p(x)$ ; $i(-x)=\frac{f(-x)-f(x)}{2}=-i(x)$ ; $p+i=f$.

        b) $(x+1)^3=x^3+3x^2+3x+1$ et $(1-x)^3=1-3x+3x^2-x^3$. Donc $p(x)=\dfrac{2+6x^2}{2}=1+3x^2$ et $i(x)=\dfrac{2x^3+6x}{2}=x^3+3x$. Vérif. : $1+3x^2+x^3+3x=(x+1)^3$ ✓.

        c) Si $f=p'+i'$ avec $p'$ paire, $i'$ impaire, alors $f(-x)=p'(x)-i'(x)$. En additionnant et soustrayant avec $f(x)=p'(x)+i'(x)$ : $p'=p$ et $i'=i$.

## 7. Exercices type contrôle

!!! question "Exercice C1 – Parité et domaines (10 min)"
    Étudier la parité de :
    a) $f(x)=\dfrac{x^3-x}{x^2+3}$ ; b) $g(x)=\sqrt{x+2}-\sqrt{2-x}$ ; c) $h(x)=\sqrt{x-1}+\sqrt{1-x}$ ; d) $k(x)=x+\dfrac{1}{x^2}$.

    ??? success "Corrigé"
        a) $D=\mathbb{R}$ ; $f(-x)=\dfrac{-x^3+x}{x^2+3}=-f(x)$ : **impaire**.

        b) $x+2\ge0$ et $2-x\ge0$ : $D=[-2\,;2]$, symétrique. $g(-x)=\sqrt{2-x}-\sqrt{2+x}=-g(x)$ : **impaire**.

        c) $x-1\ge0$ et $1-x\ge0$ : $D=\{1\}$. Alors $1\in D$ et $-1\notin D$ : **ni paire ni impaire** (malgré $h(1)=0$). *Piège classique : $\{1\}$ n'est pas symétrique.*

        d) $D=\mathbb{R}^*$ ; $k(1)=2$, $k(-1)=-1+1=0$. $k(-1)\neq k(1)$ et $k(-1)\neq-k(1)$ : **ni paire ni impaire**. *Une somme d'une fonction impaire ($x$) et d'une paire ($1/x^2$) n'est en général ni l'une ni l'autre.*

!!! question "Exercice C2 – Unicité de la décomposition (10 min)"
    Soit $h(x)=x^3+2x^2-x+4$. Déterminer l'unique couple $(f,g)$, $f$ paire et $g$ impaire sur $\mathbb{R}$, tel que $h=f+g$.

    ??? success "Corrigé"
        $h(-x)=f(-x)+g(-x)=f(x)-g(x)$. Donc $f(x)=\frac{h(x)+h(-x)}{2}$ et $g(x)=\frac{h(x)-h(-x)}{2}$. Ici $h(-x)=-x^3+2x^2+x+4$.

        $f(x)=\dfrac{4x^2+8}{2}=2x^2+4$ ; $g(x)=\dfrac{2x^3-2x}{2}=x^3-x$.

        Vérification : $f+g=x^3+2x^2-x+4=h$ ✓. *Astuce : $f$ regroupe les monômes de degré pair, $g$ ceux de degré impair.*

!!! question "Exercice C3 – Lecture graphique"
    Une fonction $f$ est définie sur $[-5\,;5]$ et $\mathcal{C}_f$ passe par $A(2\,;-3)$ et $B(-1\,;5)$.
    a) Si $f$ est impaire, que peut-on affirmer sur $f(-2)$, $f(1)$, $f(0)$ ?
    b) Si $f$ est paire ? c) $f$ peut-elle être à la fois paire et ayant $f(2)=-3$ et $f(-2)=3$ ?

    ??? success "Corrigé"
        a) $f(-2)=3$, $f(1)=-5$, $f(0)=0$ (cf. exercice 3).

        b) $f(-2)=-3$, $f(1)=5$ ; **rien** sur $f(0)$.

        c) Non : paire impose $f(-2)=f(2)=-3\neq3$.

!!! tip "Fiche de révision"
    - $D$ symétrique par rapport à 0 **d'abord**, calcul de $f(-x)$ ensuite.
    - Paire : $f(-x)=f(x)$, courbe symétrique par rapport à $(Oy)$. Impaire : $f(-x)=-f(x)$, courbe symétrique par rapport à $O$.
    - Impaire et définie en 0 $\Rightarrow f(0)=0$ ; la réciproque est fausse.
    - Paire × impaire = impaire ; impaire × impaire = paire ; paire + impaire : ni l'une ni l'autre en général.
    - Réfuter = un contre-exemple chiffré ; ou domaine non symétrique.
