# Valeur absolue : définition et propriétés

!!! info "Objectifs pédagogiques et compétences"
    - Définir la valeur absolue et l'interpréter comme une **distance**.
    - Connaître et **démontrer** les propriétés algébriques (produit, inverse, quotient, puissance) et l'inégalité triangulaire.
    - Résoudre équations et inéquations contenant des valeurs absolues, avec disjonction de cas ou interprétation en distance.
    - Repérer les erreurs classiques ($|x+y|$, signe du second membre, « et » / « ou »).

!!! note "Prérequis"
    Ordre sur $\mathbb{R}$, carrés et racines carrées ($\sqrt{a^2}$), identités remarquables, inéquations du premier degré, intervalles.

## 1. Définition

!!! definition "Définition : Valeur absolue d'un réel"
    Pour tout réel $x$ :
    $$|x|=\begin{cases} x & \text{si } x\ge 0\\ -x & \text{si } x\le 0\end{cases}$$

!!! definition "Définition : Distance sur la droite réelle"
    Si $A$ et $B$ ont pour abscisses $a$ et $b$, la distance $AB$ vaut $|a-b|=|b-a|$. Ainsi $|x|$ est la distance de $x$ à $0$ et $|x-c|$ la distance de $x$ à $c$.

!!! attention "Attention : Le cas $x=0$ et le signe de $-x$"
    Les deux lignes se recoupent en $0$ (car $0=-0$) : pas de contradiction. Et $-x$ **n'est pas** « un nombre négatif » : si $x=-3$, alors $-x=3$ et $|x|=-x=3$.

!!! propriete "Propriété : Lien avec la racine carrée"
    Pour tout réel $x$, $\;|x|=\sqrt{x^2}$ ; en particulier $|x|^2=x^2$ et $|x|\ge 0$.

??? abstract "Démonstration"
    Si $x\ge0$ : $\sqrt{x^2}=x=|x|$ car $x\ge0$. Si $x<0$ : $x^2=(-x)^2$ avec $-x>0$, donc $\sqrt{x^2}=-x=|x|$.

## 2. Propriétés algébriques

!!! propriete "Propriété : Propriétés de la valeur absolue"
    Pour tous réels $x$ et $y$ :

    1. $|x|\ge0$ et $|x|=0\iff x=0$.
    2. $|x|=|y|\iff x=y$ ou $x=-y$.
    3. $|-x|=|x|$.
    4. $|xy|=|x|\,|y|$.
    5. Si $y\neq0$ : $\left|\dfrac1y\right|=\dfrac1{|y|}$ et $\left|\dfrac xy\right|=\dfrac{|x|}{|y|}$.
    6. Pour $n\in\mathbb{N}$ : $|x^n|=|x|^n$ (et pour $n\in\mathbb{Z}$ si $x\neq0$).
    7. **Inégalité triangulaire** : $|x+y|\le|x|+|y|$, avec égalité si et seulement si $xy\ge0$.
    8. $\bigl||x|-|y|\bigr|\le|x-y|$.

!!! attention "Attention : Ce qui est faux"
    - $|x+y|\neq|x|+|y|$ en général : $|1+(-1)|=0\neq2$.
    - $|x|$ n'est pas « $x$ sans son signe » dans $|x-3|$ : $|x-3|=x-3$ **seulement si** $x\ge3$.
    - Il n'y a **pas** de formule pour $|x|+|y|$ sous une seule valeur absolue.

??? abstract "Démonstration : Propriétés 1 à 6"
    1. Si $x\ge0$, $|x|=x\ge0$ ; si $x\le0$, $|x|=-x\ge0$. Si $|x|=0$, alors $x=0$ ou $-x=0$.
    2. $|x|=|y|\iff|x|^2=|y|^2$ (deux nombres positifs) $\iff x^2=y^2\iff(x-y)(x+y)=0$.
    3. $|-x|=\sqrt{(-x)^2}=\sqrt{x^2}=|x|$.
    4. $|xy|=\sqrt{x^2y^2}=\sqrt{x^2}\sqrt{y^2}=|x||y|$ (les deux carrés sont positifs).
    5. $\left|\frac1y\right||y|=\left|\frac1y\cdot y\right|=|1|=1$, d'où $\left|\frac1y\right|=\frac1{|y|}$ ; puis $\left|\frac xy\right|=\left|x\cdot\frac1y\right|=|x|\cdot\frac1{|y|}$.
    6. Récurrence : $|x^0|=1=|x|^0$ ; si $|x^n|=|x|^n$ alors $|x^{n+1}|=|x^n||x|=|x|^{n+1}$.

??? abstract "Démonstration : Inégalité triangulaire (propriétés 7 et 8)"
    $$(|x|+|y|)^2-(x+y)^2=x^2+2|xy|+y^2-x^2-2xy-y^2=2\bigl(|xy|-xy\bigr)\ge0 .$$
    Les deux nombres $|x|+|y|$ et $|x+y|$ étant positifs, comparer leurs carrés revient à les comparer : $|x+y|\le|x|+|y|$. Il y a égalité $\iff|xy|=xy\iff xy\ge0$.

    Pour 8 : $|x|=|(x-y)+y|\le|x-y|+|y|$ donc $|x|-|y|\le|x-y|$. En échangeant les rôles, $|y|-|x|\le|y-x|=|x-y|$. Ainsi $-|x-y|\le|x|-|y|\le|x-y|$, c'est exactement $\bigl||x|-|y|\bigr|\le|x-y|$ (voir la propriété ci-dessous).

!!! propriete "Propriété : Valeur absolue et intervalles"
    Soit $a\ge 0$, $c\in\mathbb{R}$ et $r\ge0$.

    - $|x|\le a\iff -a\le x\le a$ ; $\;|x|<a\iff -a<x<a$.
    - $|x|\ge a\iff x\le -a$ **ou** $x\ge a$ ; $\;|x|>a\iff x<-a$ ou $x>a$.
    - $|x-c|\le r\iff c-r\le x\le c+r$ (intervalle centré en $c$ de rayon $r$).

!!! attention "Attention : Le signe du second membre"
    Si $a<0$ : $|x|=a$ et $|x|\le a$ n'ont **aucune** solution ; $|x|\ge a$ est vraie pour **tout** réel. Et « $|x|>a\Rightarrow$ ou » : la réunion de deux intervalles, **jamais** leur intersection (elle serait vide).

## 3. Méthodes

!!! methode "Méthode : Résoudre une équation ou inéquation avec valeurs absolues"
    ```mermaid
    flowchart TD
      A["Équation ou inéquation"] --> B{"Une seule valeur absolue isolée ?"}
      B -- "Oui, du type |u| = a ou |u| < a" --> C["Utiliser la propriété sur les intervalles ou u = ± a, après avoir vérifié le signe de a"]
      B -- "Oui, du type |u| = |v|" --> D["u = v ou u = -v"]
      B -- "Plusieurs valeurs absolues" --> E["Tableau de signes : disjonction de cas sur les intervalles délimités par les zéros"]
      E --> F["Résoudre dans chaque intervalle, puis ne garder que les solutions appartenant à l'intervalle"]
      C --> G["Conclure et vérifier"]
      D --> G
      F --> G
    ```

## 4. Exemples corrigés

!!! example "Exemple : Simplifier"
    $|\pi-4|=4-\pi$ (car $\pi<4$) ; $|\sqrt2-\sqrt3|=\sqrt3-\sqrt2$ ; $|x^2-4x+4|=(x-2)^2$ car un carré est positif.

!!! example "Exemple : Équation $|2x-1|=|x+4|$"
    $2x-1=x+4\iff x=5$ ou $2x-1=-x-4\iff x=-1$. Vérification : $|9|=|9|$ et $|-3|=|3|$ ✓. $S=\{-1\,;5\}$.

!!! example "Exemple : Inéquations"
    $|2x-1|\le3\iff-3\le2x-1\le3\iff-1\le x\le2$, soit $S=[-1\,;2]$.

    $|x+2|>4\iff x+2<-4$ ou $x+2>4\iff x<-6$ ou $x>2$, soit $S=]-\infty\,;-6[\,\cup\,]2\,;+\infty[$.

!!! example "Exemple : Deux valeurs absolues : $|x-1|+|x-4|=7$"
    Zéros : $1$ et $4$.

    - $x<1$ : $-(x-1)-(x-4)=-2x+5=7\iff x=-1$ ; $-1<1$ ✓.
    - $1\le x\le4$ : $(x-1)-(x-4)=3\neq7$ : aucune solution.
    - $x>4$ : $2x-5=7\iff x=6$ ; $6>4$ ✓.

    $S=\{-1\,;6\}$. *Lecture géométrique : somme des distances à $1$ et à $4$ égale à $7$ ; le segment $[1,4]$ mesure $3$, on recule de $2$ à gauche et on avance de $2$ à droite.*

## 5. Exercices progressifs

!!! question "Exercice 1 – Sans valeur absolue"
    Écrire sans valeur absolue : $|1-\sqrt2|$ ; $|\sqrt5-2|$ ; $|x^2+1|$ ; $|x-3|$ pour $x\le3$ ; $|3-x|$ pour $x\le3$.

    ??? success "Corrigé"
        $|1-\sqrt2|=\sqrt2-1$ ; $|\sqrt5-2|=\sqrt5-2$ ($\sqrt5>2$) ; $|x^2+1|=x^2+1$ ; pour $x\le3$ : $|x-3|=3-x$ et $|3-x|=3-x$.

!!! question "Exercice 2 – Équations"
    Résoudre : a) $|3x-2|=5$ ; b) $|x+1|=|2x-3|$ ; c) $|x-1|=-3$ ; d) $|x|=x-2$.

    ??? success "Corrigé"
        a) $3x-2=5\iff x=\frac73$ ou $3x-2=-5\iff x=-1$ ; $S=\{-1\,;\frac73\}$.

        b) $x+1=2x-3\iff x=4$ ou $x+1=-2x+3\iff x=\frac23$ ; $S=\{\frac23\,;4\}$.

        c) Une valeur absolue est positive : $S=\varnothing$.

        d) Il faut $x-2\ge0$, donc $x\ge2$, et alors $|x|=x\neq x-2$. $S=\varnothing$.

!!! question "Exercice 3 – Inéquations"
    Résoudre : a) $|x-3|<2$ ; b) $|2x+1|\ge5$ ; c) $|x|\le-1$ ; d) $|x-1|\ge-2$.

    ??? success "Corrigé"
        a) $]1\,;5[$. b) $2x+1\le-5$ ou $2x+1\ge5$ : $]-\infty\,;-3]\cup[2\,;+\infty[$. c) $\varnothing$. d) $\mathbb{R}$ (une valeur absolue est toujours $\ge0>-2$).

!!! question "Exercice 4 – Encadrements et triangulaire"
    On suppose $|x-2|\le0{,}5$ et $|y+1|\le0{,}25$. Encadrer $x+y$ puis majorer $|x+y-1|$ avec l'inégalité triangulaire. Comparer avec l'encadrement direct.

    ??? success "Corrigé"
        $x\in[1{,}5\,;2{,}5]$, $y\in[-1{,}25\,;-0{,}75]$, donc $x+y\in[0{,}25\,;1{,}75]$ et $x+y-1\in[-0{,}75\,;0{,}75]$ : $|x+y-1|\le0{,}75$.

        Triangulaire : $|x+y-1|=|(x-2)+(y+1)|\le|x-2|+|y+1|\le0{,}5+0{,}25=0{,}75$. Même majorant, obtenu **sans** passer par les intervalles. Il est atteint (par exemple $x=2{,}5$ et $y=-0{,}75$).

## 6. Exercices type contrôle

!!! question "Exercice C1 – Inéquation à deux valeurs absolues (12 min)"
    Résoudre $|x-1|+|x+2|\le5$ par disjonction de cas, puis par une interprétation géométrique.

    ??? success "Corrigé"
        Zéros : $-2$ et $1$.

        - $x<-2$ : $-(x-1)-(x+2)=-2x-1\le5\iff x\ge-3$. Solutions : $[-3\,;-2[$.
        - $-2\le x\le1$ : $-(x-1)+(x+2)=3\le5$ : toujours vrai. Solutions : $[-2\,;1]$.
        - $x>1$ : $2x+1\le5\iff x\le2$. Solutions : $]1\,;2]$.

        $S=[-3\,;2]$. *Géométrie :* la somme des distances à $-2$ et à $1$ vaut au minimum $3$ (entre eux) ; on peut dépasser de $\frac{5-3}{2}=1$ de chaque côté : $[-2-1\,;1+1]$.

!!! question "Exercice C2 – Inégalité triangulaire inverse (10 min)"
    Démontrer que pour tous réels $x,y$ : $\bigl||x|-|y|\bigr|\le|x-y|$. En déduire que si $|x-2|\le0{,}1$ alors $|x|\ge1{,}9$.

    ??? success "Corrigé"
        Voir la démonstration du cours (propriété 8). Avec $y=2$ : $\bigl||x|-2\bigr|\le|x-2|\le0{,}1$, donc $|x|\ge2-0{,}1=1{,}9$.

!!! question "Exercice C3 – Maximum et minimum (12 min)"
    Montrer que pour tous réels $a,b$ : $\max(a,b)=\dfrac{a+b+|a-b|}{2}$ et $\min(a,b)=\dfrac{a+b-|a-b|}{2}$. En déduire $\max(\sqrt2,\frac{3}{2})$.

    ??? success "Corrigé"
        Si $a\ge b$ : $|a-b|=a-b$ et $\frac{a+b+a-b}{2}=a=\max$ ; $\frac{a+b-a+b}{2}=b=\min$. Si $a<b$ : $|a-b|=b-a$ et on obtient $b$ puis $a$.

        Numériquement $\sqrt2\approx1{,}414<1{,}5$ (car $2<2{,}25$), donc $\max=\frac32$.

!!! question "Exercice C4 – Valeur absolue d'une expression du second degré (15 min)"
    Résoudre dans $\mathbb{R}$ : $|x^2-1|=x+1$.

    ??? success "Corrigé"
        Condition nécessaire : $x+1\ge0$, soit $x\ge-1$. Ensuite $|x^2-1|=x+1\iff x^2-1=x+1$ ou $x^2-1=-(x+1)$.

        - $x^2-x-2=0\iff(x-2)(x+1)=0\iff x=2$ ou $x=-1$.
        - $x^2+x=0\iff x(x+1)=0\iff x=0$ ou $x=-1$.

        Toutes ces valeurs vérifient $x\ge-1$. Vérification : $|3|=3$ ✓ ; $|0|=0$ ✓ ; $|-1|=1$, $x+1=1$ ✓ (pour $x=0$). $S=\{-1\,;0\,;2\}$.

        *Point d'attention : la condition « second membre $\ge0$ » est indispensable ; ici elle n'élimine aucune solution, mais sur $|x^2-1|=x-1$ par exemple elle en éliminerait. Vérifiez toujours.*

!!! question "Exercice C5 – Vrai ou faux ? Justifier"
    a) $\forall x$, $|x^2|=x^2$. b) $\forall x$, $|x-3|=x-3$. c) $\forall x,y$, $|x-y|=|x|-|y|$. d) $|x|<2\Rightarrow|x^2-1|<3$. e) $|x+y|=|x|+|y|\iff xy\ge0$.

    ??? success "Corrigé"
        a) **Vrai** ($x^2\ge0$). b) **Faux** : $x=0$ donne $3\neq-3$. c) **Faux** : $x=1,y=2$ donne $1\neq-1$. d) **Vrai** : $0\le x^2<4$ donc $-1\le x^2-1<3$, d'où $|x^2-1|<3$ (le minorant $-1$ est $>-3$). e) **Vrai** : cas d'égalité de l'inégalité triangulaire.

!!! tip "Fiche de révision"
    - $|x|=x$ si $x\ge0$, $-x$ si $x\le0$ ; $|x|=\sqrt{x^2}$ ; $|x-c|$ = distance de $x$ à $c$.
    - $|x|=0\iff x=0$ ; $|x|=|y|\iff x=\pm y$ ; $|-x|=|x|$ ; $|xy|=|x||y|$ ; $\left|\frac xy\right|=\frac{|x|}{|y|}$ ; $|x^n|=|x|^n$.
    - $|x+y|\le|x|+|y|$ (égalité $\iff xy\ge0$) ; $\bigl||x|-|y|\bigr|\le|x-y|$.
    - $|x|\le a\iff-a\le x\le a$ ; $|x|\ge a\iff x\le-a$ ou $x\ge a$ ($a\ge0$).
    - Plusieurs valeurs absolues : tableau de signes, cas par cas, vérifier l'appartenance à l'intervalle.
