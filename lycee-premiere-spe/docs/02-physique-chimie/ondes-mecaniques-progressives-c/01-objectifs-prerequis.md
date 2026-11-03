# Objectifs pédagogiques et prérequis

## Objectifs pédagogiques

!!! abstract "À l'issue du chapitre, tu dois savoir…"
    **Connaissances**

    - définir une onde mécanique progressive et citer ses propriétés fondamentales ;
    - distinguer onde transversale et onde longitudinale, avec des exemples de chaque ;
    - définir la célérité $c$, donner des ordres de grandeur et dire de quoi elle dépend ;
    - définir une onde progressive périodique, sa période $T$, sa fréquence $f$ et sa longueur d'onde $\lambda$ ;
    - expliquer la double périodicité (dans le temps et dans l'espace) ;
    - établir et utiliser la relation $\lambda = c\,T = \dfrac{c}{f}$ ;
    - modéliser un signal périodique par une fonction sinusoïdale $s(t) = S_m\cos\!\left(\dfrac{2\pi}{T}\,t + \varphi\right)$.

    **Savoir-faire**

    - déterminer un retard, une célérité, une période, une fréquence, une longueur d'onde à partir d'un document (chronogramme, cliché, oscillogramme) ;
    - exploiter $\tau = d/c$ pour relier un signal reçu à un signal émis ;
    - décider si deux points du milieu vibrent en phase ou en opposition de phase ;
    - écrire l'expression d'un signal sinusoïdal à partir de son graphe.

## Compétences travaillées

| Compétence | Ce qu'on attend de toi dans ce chapitre |
|---|---|
| **S'approprier** | Extraire d'un énoncé ou d'un document les grandeurs utiles ($d$, $\Delta t$, $f$…) |
| **Analyser / Raisonner** | Choisir la bonne relation ($\tau = d/c$ ou $\lambda = cT$), justifier qu'une grandeur est constante |
| **Réaliser** | Lire un graphe, convertir les unités, faire un calcul avec le bon nombre de chiffres significatifs |
| **Valider** | Vérifier l'homogénéité, l'ordre de grandeur, la cohérence d'un résultat |
| **Communiquer** | Rédiger : relation littérale, application numérique, unité, conclusion |

## Prérequis

!!! note "Rappels indispensables"
    - **Vitesse d'un mouvement uniforme** : $v = \dfrac{d}{\Delta t}$, en $\mathrm{m\cdot s^{-1}}$ ; conversion $1\ \mathrm{km\cdot h^{-1}} = \dfrac{1}{3{,}6}\ \mathrm{m\cdot s^{-1}}$.
    - **Phénomène périodique** : il se reproduit identique à lui-même à intervalles de temps égaux ; la période $T$ (en s) et la fréquence $f$ (en Hz) sont liées par $f = \dfrac{1}{T}$.
    - **Préfixes** : $\mathrm{k} = 10^3$, $\mathrm{m} = 10^{-3}$, $\mu = 10^{-6}$, $\mathrm{M} = 10^6$.
    - **Trigonométrie** : $\cos$ et $\sin$ sont $2\pi$-périodiques ; $\cos 0 = 1$, $\cos\frac{\pi}{2} = 0$, $\cos\pi = -1$, $\cos(x - \frac{\pi}{2}) = \sin x$.
    - **Chiffres significatifs** : un résultat ne peut pas être plus précis que la donnée la moins précise.

!!! warning "Attention : calculatrice"
    Pour tout ce chapitre, la calculatrice doit être en **radians** (mode `RAD`). En mode degrés, $\cos(\pi/2)$ ne vaut pas $0$ mais $0{,}9996\ldots$

## Test de positionnement

!!! question "Énoncé : six questions de 30 secondes"
    1. Convertir $25\ \mathrm{kHz}$ en Hz et $12\ \mathrm{ms}$ en s.
    2. Le son se propage à $343\ \mathrm{m\cdot s^{-1}}$. Quelle distance parcourt-il en $2{,}0\ \mathrm{s}$ ?
    3. Un signal a pour période $T = 4{,}0\ \mathrm{ms}$. Quelle est sa fréquence ?
    4. Donner $\cos(0)$, $\cos\left(\frac{\pi}{2}\right)$, $\cos(\pi)$, $\cos(2\pi)$.
    5. Écrire $0{,}0850\ \mathrm{m}$ en millimètres et donner le nombre de chiffres significatifs.
    6. Un train roule à $72\ \mathrm{km\cdot h^{-1}}$. Convertir en $\mathrm{m\cdot s^{-1}}$.

??? info "Corrigé"
    1. $25\ \mathrm{kHz} = 25 \times 10^3\ \mathrm{Hz} = 2{,}5 \times 10^4\ \mathrm{Hz}$ ; $12\ \mathrm{ms} = 12 \times 10^{-3}\ \mathrm{s} = 1{,}2 \times 10^{-2}\ \mathrm{s}$.
    2. $d = v\,\Delta t = 343 \times 2{,}0 = 686\ \mathrm{m}$, soit $6{,}9 \times 10^2\ \mathrm{m}$ avec 2 chiffres significatifs.
    3. $f = \dfrac{1}{T} = \dfrac{1}{4{,}0 \times 10^{-3}} = 2{,}5 \times 10^{2}\ \mathrm{Hz}$.
    4. $1$ ; $0$ ; $-1$ ; $1$.
    5. $0{,}0850\ \mathrm{m} = 85{,}0\ \mathrm{mm}$ : **3** chiffres significatifs (les zéros de gauche ne comptent pas, le zéro de droite compte).
    6. $72 / 3{,}6 = 20\ \mathrm{m\cdot s^{-1}}$.

    Si plus de deux réponses sont fausses, revois d'abord les rappels ci-dessus avant d'aller plus loin.
