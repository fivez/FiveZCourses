# Correspondance entre la droite des réels et le cercle trigonométrique

!!! info "Objectifs pédagogiques et compétences"
    - Comprendre l'**enroulement** de la droite réelle sur le cercle.
    - Associer à tout réel $t$ un point $M(t)$ du cercle, et comprendre pourquoi **plusieurs** réels ont le même point.
    - Définir la **mesure en radians d'un angle orienté**, la **mesure principale**, et manipuler les congruences modulo $2\pi$.
    - Utiliser les symétries du cercle.

!!! note "Prérequis"
    Chapitre 01 ; périmètre du cercle ; division euclidienne et multiples ; intervalles.

## 1. Enroulement de la droite réelle

!!! definition "Définition : La droite $\Delta$"
    Soit $\Delta$ la **tangente en $I$** au cercle trigonométrique $\mathcal{C}$, c'est-à-dire la droite d'équation $x=1$. On la munit du repère $(I\,;\vec\jmath)$ : le point de coordonnées $(1\,;t)$ a pour abscisse $t$ sur $\Delta$. Ainsi $\Delta$ est une représentation de l'**ensemble $\mathbb{R}$ des réels** : $I$ représente $0$, le point de coordonnées $(1;1)$ représente $1$, etc.

!!! definition "Définition : Point image d'un réel"
    On enroule $\Delta$ autour de $\mathcal{C}$ : la partie de $\Delta$ située au-dessus de $I$ ($t>0$) s'enroule dans le **sens direct**, la partie située au-dessous ($t<0$) dans le **sens indirect**. Au réel $t$ correspond ainsi un point $M(t)$ du cercle, tel que l'arc $\widehat{IM}$ parcouru dans ce sens a pour longueur $|t|$.

<svg viewBox="0 0 300 300" width="280" role="img" aria-label="Enroulement de la droite tangente en I sur le cercle : le point N d'abscisse 1 sur la tangente correspond au point M tel que l'arc IM mesure 1" style="max-width:100%;color:inherit">
<g fill="none" stroke="currentColor" stroke-width="1.5">
<circle cx="150" cy="150" r="100"/>
<line x1="20" y1="150" x2="280" y2="150"/>
<line x1="150" y1="280" x2="150" y2="20"/>
<line x1="250" y1="290" x2="250" y2="10" stroke="#2979ff" stroke-width="2"/>
<path d="M 250 150 A 100 100 0 0 0 204 65.9" stroke="#e53935" stroke-width="3"/>
<line x1="250" y1="50" x2="204" y2="65.9" stroke-dasharray="4 3"/>
</g>
<g fill="currentColor" font-size="14" font-family="sans-serif">
<text x="256" y="168">I</text>
<text x="256" y="46">N (t = 1)</text>
<text x="186" y="60">M(1)</text>
<text x="262" y="290" fill="#2979ff">Δ</text>
<text x="136" y="168">O</text>
</g>
</svg>

*Figure : la droite $\Delta$ (en bleu) enroulée sur $\mathcal{C}$ ; l'arc $\widehat{IM(1)}$ (en rouge) a pour longueur $1$.*

```mermaid
flowchart LR
  R["Réel t sur la droite Δ, tangente en I"] -- "enroulement : longueur d'arc |t|" --> M["Point M(t) du cercle"]
  M -- "plusieurs antécédents : t + 2kπ" --> R
```

!!! propriete "Propriété : Correspondance entre $\mathbb{R}$ et $\mathcal{C}$"
    1. À tout réel $t$ correspond **un unique** point $M(t)$ du cercle.
    2. À tout point $M$ du cercle correspondent **une infinité** de réels, deux d'entre eux différant d'un **multiple entier de $2\pi$** :
    $$M(t)=M(t')\iff t'=t+2k\pi,\ k\in\mathbb{Z}.$$
    On écrit $t'\equiv t\ [2\pi]$ (« $t'$ congru à $t$ modulo $2\pi$ »).

??? abstract "Démonstration"
    Un tour complet du cercle mesure $2\pi$. Après avoir parcouru l'arc de longueur $|t|$ à partir de $I$, parcourir encore $2k\pi$ dans le même sens ramène au même point : $M(t+2k\pi)=M(t)$. Réciproquement, deux parcours partant de $I$ aboutissent au même point si et seulement si leurs longueurs signées diffèrent d'un nombre entier de tours, c'est-à-dire de $2k\pi$.

## 2. Mesure d'un angle orienté, en radians

!!! definition "Définition : Mesure en radians d'un angle orienté"
    Soit $M$ un point du cercle trigonométrique. Tout réel $t$ tel que $M=M(t)$ est **une mesure en radians** de l'angle orienté $(\overrightarrow{OI},\overrightarrow{OM})$. Les mesures de cet angle sont donc les réels $t+2k\pi$, $k\in\mathbb{Z}$ : l'angle est défini **à $2\pi$ près**.

!!! definition "Définition : Mesure principale"
    La **mesure principale** d'un angle orienté est son unique mesure appartenant à l'intervalle $]-\pi\,;\pi]$.

!!! propriete "Propriété : Valeurs remarquables"
    | $t$ | $0$ | $\frac\pi2$ | $\pi$ | $-\frac\pi2$ (ou $\frac{3\pi}2$) | $2\pi$ |
    |:---:|:---:|:---:|:---:|:---:|:---:|
    | $M(t)$ | $I$ | $J$ | $I'$ | $J'$ | $I$ |

!!! propriete "Propriété : Relation de Chasles (admise)"
    Pour trois vecteurs non nuls : $(\vec u,\vec v)+(\vec v,\vec w)\equiv(\vec u,\vec w)\ [2\pi]$.

!!! attention "Attention : Pièges sur la mesure principale"
    - L'intervalle est $]-\pi;\pi]$ : $\pi$ est **inclus**, $-\pi$ est **exclu**. La mesure principale d'un angle plat est $\pi$, jamais $-\pi$.
    - Un angle a une infinité de mesures : écrire « l'angle vaut $\frac{\pi}{3}$ » est faux ; on dit « a pour mesure $\frac\pi3$ » ou « est congru à $\frac\pi3$ modulo $2\pi$ ».
    - Ne pas confondre le **réel** $t$ (une longueur signée) et le **point** $M(t)$.

!!! methode "Méthode : Trouver la mesure principale de $t$"
    Chercher l'entier $k$ tel que $t-2k\pi\in\,]-\pi;\pi]$. Pour $t=\alpha\pi$ avec $\alpha$ rationnel : réduire $\alpha$ modulo $2$ dans $]-1;1]$.

    ```mermaid
    flowchart TD
      A["t donné"] --> B["Écrire t = alpha × pi"]
      B --> C["Ajouter ou retrancher des multiples de 2 à alpha"]
      C --> D{"alpha dans ]-1 ; 1] ?"}
      D -- "Non" --> C
      D -- "Oui" --> E["Mesure principale = alpha × pi"]
    ```

## 3. Symétries du cercle

!!! propriete "Propriété : Images de $M(t)$ par des symétries"
    | Transformation | Image de $M(t)$ |
    |---|---|
    | symétrie par rapport à $(OI)$ | $M(-t)$ |
    | symétrie par rapport à $(OJ)$ | $M(\pi-t)$ |
    | symétrie centrale de centre $O$ | $M(t+\pi)$ |
    | symétrie par rapport à la droite $y=x$ | $M\bigl(\frac\pi2-t\bigr)$ |

??? abstract "Démonstration"
    La symétrie par rapport à $(OI)$ fixe $I$, conserve les longueurs et change le sens de parcours : l'arc de longueur signée $t$ issu de $I$ est envoyé sur l'arc de longueur signée $-t$ : $M(t)\mapsto M(-t)$. La symétrie centrale de centre $O$ est le demi-tour : elle fait avancer d'un demi-cercle, soit $\pi$. La symétrie par rapport à $(OJ)$ est la composée de la symétrie par rapport à $(OI)$ puis du demi-tour : $M(t)\mapsto M(-t)\mapsto M(-t+\pi)$. Enfin la symétrie par rapport à $y=x$ est la composée de la symétrie par rapport à $(OI)$ puis du quart de tour direct (qui envoie $M(u)$ sur $M(u+\frac\pi2)$) : $M(t)\mapsto M(-t)\mapsto M(\frac\pi2-t)$.

## 4. Exemples corrigés

!!! example "Exemple : Mesures principales"
    $\dfrac{47\pi}6-8\pi=-\dfrac\pi6\in\,]-\pi;\pi]$ ; $-\dfrac{25\pi}4+6\pi=-\dfrac\pi4$ ; $7\pi\equiv\pi$ ; $-\pi\equiv\pi$ ; $100-32\pi\approx-0{,}53$ (car $32\pi\approx100{,}53$).

!!! example "Exemple : Même point ?"
    $M\bigl(\frac{13\pi}3\bigr)=M\bigl(\frac\pi3\bigr)$ car $\frac{13\pi}3-\frac\pi3=4\pi=2\times2\pi$ ; mais $M\bigl(\frac{5\pi}3\bigr)\neq M\bigl(\frac\pi3\bigr)$ car $\frac{4\pi}3$ n'est pas un multiple de $2\pi$ (en revanche $M(\frac{5\pi}3)=M(-\frac\pi3)$).

## 5. Exercices progressifs

!!! question "Exercice 1 – Mesures principales"
    Donner la mesure principale de : $\dfrac{17\pi}3$ ; $-\dfrac{11\pi}2$ ; $\dfrac{31\pi}6$ ; $-2025\pi$ ; $2\pi\times1013$.

    ??? success "Corrigé"
        $\frac{17\pi}3-6\pi=-\frac\pi3$. $-\frac{11\pi}2+6\pi=\frac\pi2$. $\frac{31\pi}6-6\pi=-\frac{5\pi}6$. $-2025\pi+2026\pi=\pi$ ($2026=2\times1013$) : **$\pi$** et non $-\pi$. $2026\pi\equiv0$.

!!! question "Exercice 2 – Équations d'égalité de points"
    Résoudre dans $]-\pi;\pi]$ : a) $M(3t)=M(t)$ ; b) $M(2t)=M(-t)$.

    ??? success "Corrigé"
        a) $3t\equiv t\iff2t=2k\pi\iff t=k\pi$ : dans $]-\pi;\pi]$, $t\in\{0;\pi\}$ ($t=-\pi$ exclu). Les points sont $I$ et $I'$.

        b) $2t\equiv-t\iff3t=2k\pi\iff t=\frac{2k\pi}3$ : $t\in\bigl\{-\frac{2\pi}3\,;0\,;\frac{2\pi}3\bigr\}$. *Piège : $k=3$ donne $2\pi\notin]-\pi;\pi]$.*

!!! question "Exercice 3 – Les trois sommets"
    Montrer que les points $M\bigl(\frac\pi6+\frac{2k\pi}3\bigr)$, $k\in\mathbb{Z}$, sont exactement trois points distincts formant un triangle équilatéral.

    ??? success "Corrigé"
        $k$ et $k'$ donnent le même point si et seulement si $\frac{2(k-k')\pi}3\in2\pi\mathbb{Z}\iff k-k'\in3\mathbb{Z}$. Il suffit donc de prendre $k\in\{0,1,2\}$ : $\frac\pi6$, $\frac{5\pi}6$, $\frac{3\pi}2$. Les angles $(\overrightarrow{OM_k},\overrightarrow{OM_{k+1}})$ valent tous $\frac{2\pi}3$ : triangle équilatéral inscrit dans le cercle.

## 6. Exercices type contrôle

!!! question "Exercice C1 – Symétries (15 min)"
    Soit $t\in\mathbb{R}$. a) Déterminer un réel associé au symétrique de $M(t)$ par rapport à $(OJ)$. b) Pour $t=\frac\pi5$, trouver les mesures principales des symétriques par rapport à $(OI)$, $(OJ)$, $O$. c) Démontrer que $M(t)$ et $M(t')$ sont symétriques par rapport à $(OJ)$ si et seulement si $t+t'\equiv\pi\ [2\pi]$.

    ??? success "Corrigé"
        a) $\pi-t$.

        b) $(OI)$ : $-\frac\pi5$ ; $(OJ)$ : $\pi-\frac\pi5=\frac{4\pi}5$ ; $O$ : $\frac\pi5+\pi=\frac{6\pi}5\equiv-\frac{4\pi}5$.

        c) $M(t')$ symétrique de $M(t)$ par rapport à $(OJ)$ $\iff M(t')=M(\pi-t)\iff t'\equiv\pi-t\iff t+t'\equiv\pi\ [2\pi]$.

!!! question "Exercice C2 – Équation (15 min)"
    Résoudre dans $]-\pi;\pi]$ : $M(2t)=M\bigl(\frac\pi2-t\bigr)$. Interpréter.

    ??? success "Corrigé"
        $2t\equiv\frac\pi2-t\iff3t=\frac\pi2+2k\pi\iff t=\frac\pi6+\frac{2k\pi}3$. Dans $]-\pi;\pi]$ : $k=0$ : $\frac\pi6$ ; $k=1$ : $\frac{5\pi}6$ ; $k=-1$ : $-\frac\pi2$ ; $k=2$ : $\frac{3\pi}2>\pi$ ✗ ; $k=-2$ : $-\frac{7\pi}6<-\pi$ ✗. $S=\bigl\{-\frac\pi2;\frac\pi6;\frac{5\pi}6\bigr\}$.

        Interprétation : $M(\frac\pi2-t)$ est le symétrique de $M(t)$ par rapport à $y=x$ ; on cherche les $t$ tels que $M(2t)$ soit ce symétrique.

!!! question "Exercice C3 – Combien de points ? (20 min)"
    a) Combien de points distincts $M\bigl(\frac{k\pi}6\bigr)$, $k\in\mathbb{Z}$ ? b) Les points $M(k)$, $k\in\mathbb{Z}$ (entiers, sans $\pi$) sont-ils distincts ? *On admet que $\pi$ est irrationnel.*

    ??? success "Corrigé"
        a) $M(\frac{k\pi}6)=M(\frac{k'\pi}6)\iff\frac{(k-k')\pi}6=2m\pi\iff k-k'=12m$. Il y a donc **12** points distincts (ceux de $k=0,\dots,11$) : un point tous les $30^\circ$.

        b) $M(k)=M(k')$ avec $k\neq k'$ imposerait $k-k'=2m\pi$, soit $\pi=\frac{k-k'}{2m}\in\mathbb{Q}$ ($m\neq0$ car $k\neq k'$), ce qui contredit l'irrationalité de $\pi$. Les points $M(k)$ sont donc **tous distincts** : il y en a une infinité sur le cercle.

!!! tip "Fiche de révision"
    - $\Delta$ : tangente en $I$, repère $(I;\vec\jmath)$ ; l'enroulement associe à $t$ le point $M(t)$ avec arc $\widehat{IM}=|t|$.
    - $M(t)=M(t')\iff t'=t+2k\pi$.
    - Mesure d'un angle orienté $(\overrightarrow{OI},\overrightarrow{OM})$ : tout $t$ avec $M=M(t)$ ; principale dans $]-\pi;\pi]$.
    - Symétries : $(OI)$ : $-t$ ; $(OJ)$ : $\pi-t$ ; $O$ : $t+\pi$ ; $y=x$ : $\frac\pi2-t$.
