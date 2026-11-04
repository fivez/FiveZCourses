# Exercices : Mouvement actuel et absolu des plaques

!!! tip "Comment travailler"
    Cherche **sur papier** avant d'ouvrir un corrigé. Les exercices 1 à 7 sont **progressifs** ; les exercices 8 et 9 sont **de type contrôle** (analyse de documents, environ 25 minutes chacun). **Attention aux unités** dans tous les calculs.

---

## Partie I : Exercices progressifs

### Exercice 1 : Principe du GPS (niveau ★★)

Un récepteur reçoit les signaux de trois satellites avec les temps de propagation suivants : $0{,}0702\ \text{s}$, $0{,}0713\ \text{s}$ et $0{,}0691\ \text{s}$. On prend $c = 3{,}00\times10^{8}\ \text{m·s}^{-1}$.

1. Calculer les trois distances.
2. Une erreur d'horloge de $1\ \mu\text{s}$ sur le récepteur : quelle erreur de distance ?
3. Pourquoi faut-il au moins quatre satellites ?
4. Une plaque se déplace de $5\ \text{cm}$ en un an. Quelle variation du temps de propagation cela représente-t-il ? Que conclure ?

??? success "Corrigé"
    **1.** $d = c\,\Delta t$ :

    - $3{,}00\times10^{8}\times0{,}0702 = 2{,}106\times10^{7}\ \text{m} = 21\,060\ \text{km}$ ;
    - $3{,}00\times10^{8}\times0{,}0713 = 21\,390\ \text{km}$ ;
    - $3{,}00\times10^{8}\times0{,}0691 = 20\,730\ \text{km}$.

    **2.** $\delta d = 3{,}00\times10^{8}\times10^{-6} = 300\ \text{m}$.

    **3.** Il y a **quatre inconnues** : les trois coordonnées $x, y, z$ du récepteur et l'**erreur de son horloge**. Il faut donc **quatre équations**, donc quatre satellites.

    **4.** $\Delta t = \dfrac{0{,}05}{3{,}00\times10^{8}} \approx 1{,}7\times10^{-10}\ \text{s} = 0{,}17\ \text{ns}$. C'est **extrêmement petit** : on ne détecte pas un mouvement de plaque sur **une mesure** isolée, mais sur des **séries de plusieurs années**, avec des **traitements de précision** (phase du signal).

---

### Exercice 2 : Vitesse et direction de trois stations (niveau ★★★)

Déplacements horizontaux de trois stations en $10$ ans, **par rapport à un même repère** (valeurs simplifiées) :

| Station | Plaque | Vers l'est (m) | Vers le nord (m) |
|---|---|---|---|
| A | Pacifique | $-0{,}30$ | $+0{,}65$ |
| B | Amérique du Sud | $-0{,}10$ | $+0{,}14$ |
| C | Nazca | $+0{,}68$ | $+0{,}12$ |

1. Calculer la vitesse de chaque station en $\text{cm·an}^{-1}$.
2. Calculer la vitesse **relative** de Nazca par rapport à l'Amérique du Sud (composantes puis valeur).
3. Quel type de limite sépare ces deux plaques ? Justifier.

??? success "Corrigé"
    **1.**

    - A : $\sqrt{0{,}30^2+0{,}65^2} = 0{,}716\ \text{m}$ en $10$ ans soit $\approx 7{,}2\ \text{cm·an}^{-1}$.
    - B : $\sqrt{0{,}10^2+0{,}14^2} = \sqrt{0{,}0296} = 0{,}172\ \text{m}$ soit $\approx 1{,}7\ \text{cm·an}^{-1}$.
    - C : $\sqrt{0{,}68^2+0{,}12^2} = \sqrt{0{,}4768} = 0{,}690\ \text{m}$ soit $\approx 6{,}9\ \text{cm·an}^{-1}$.

    **2.** $\vec{v}_{C/B} = \vec{v}_C - \vec{v}_B$ : composante est $0{,}68 - (-0{,}10) = 0{,}78\ \text{m}$ ; composante nord $0{,}12 - 0{,}14 = -0{,}02\ \text{m}$. Norme : $\sqrt{0{,}78^2+0{,}02^2} \approx 0{,}78\ \text{m}$ en $10$ ans soit **$\approx 7{,}8\ \text{cm·an}^{-1}$**, dirigée **vers l'est**.

    **3.** Nazca se **rapproche** de l'Amérique du Sud : limite **convergente** (subduction de Nazca sous l'Amérique du Sud, avec fosse et arc des Andes).

    !!! warning "Piège"
        La vitesse **relative** s'obtient par **différence de vecteurs**, pas en comparant les **normes** ($6{,}9$ et $1{,}7$ donneraient à tort $5{,}2$).

---

### Exercice 3 : L'ouverture de l'Atlantique (niveau ★★★)

La distance entre deux stations GPS situées de part et d'autre de la dorsale médio-atlantique est : $6\,214\,118{,}45\ \text{m}$ en 2010 et $6\,214\,118{,}70\ \text{m}$ en 2020.

1. Calculer la vitesse d'ouverture en $\text{cm·an}^{-1}$.
2. En combien de temps l'océan s'élargirait-il de $1000\ \text{km}$ à cette vitesse ?
3. À vitesse constante, depuis quand les deux stations s'éloignent-elles à partir d'une distance nulle ? Comparer à l'âge de l'ouverture de l'Atlantique central ($\approx 180\ \text{Ma}$) et commenter.

??? success "Corrigé"
    **1.** $\Delta d = 6\,214\,118{,}70 - 6\,214\,118{,}45 = 0{,}25\ \text{m}$ en $10$ ans soit $2{,}5\ \text{cm·an}^{-1}$.

    **2.** $1000\ \text{km} = 10^{6}\ \text{m}$ ; durée $= \dfrac{10^{6}}{0{,}025} = 4\times10^{7}\ \text{ans} = 40\ \text{Ma}$.

    **3.** Durée $= \dfrac{6{,}214\times10^{6}}{0{,}025} \approx 2{,}5\times10^{8}\ \text{ans} \approx 250\ \text{Ma}$. C'est **plus** que $180\ \text{Ma}$ : l'**ordre de grandeur est correct**, mais la **vitesse n'a pas été constante** (elle a été **plus rapide** par le passé) et la **largeur actuelle** inclut aussi d'autres effets (élargissement de la marge, etc.).

---

### Exercice 4 : Composer des vitesses (niveau ★★★)

Selon un axe est-ouest (est positif), les vitesses **absolues** (par rapport aux points chauds) sont : Pacifique $-8{,}0$ ; Nazca $+6{,}0$ ; Amérique du Sud $-1{,}5\ \text{cm·an}^{-1}$.

1. Calculer la vitesse d'**écartement** à la dorsale est-Pacifique (Pacifique-Nazca).
2. Calculer la vitesse de **convergence** Nazca - Amérique du Sud.
3. On prend l'Amérique du Sud comme référence **fixe**. Calculer les vitesses du Pacifique et de Nazca dans ce référentiel. Que remarque-t-on pour la vitesse **relative** Nazca - Pacifique ?

??? success "Corrigé"
    **1.** $v_{\text{Nazca/Pacifique}} = +6{,}0 - (-8{,}0) = +14{,}0\ \text{cm·an}^{-1}$ : **écartement de $14\ \text{cm·an}^{-1}$**, de l'ordre de la valeur de la dorsale est-Pacifique.

    **2.** $v_{\text{Nazca/Amérique du Sud}} = +6{,}0 - (-1{,}5) = +7{,}5\ \text{cm·an}^{-1}$ : **convergence de $7{,}5\ \text{cm·an}^{-1}$**.

    **3.** Dans le référentiel de l'Amérique du Sud : Pacifique $= -8{,}0 - (-1{,}5) = -6{,}5$ ; Nazca $= +6{,}0 - (-1{,}5) = +7{,}5$. La **vitesse relative** Nazca - Pacifique vaut toujours $+7{,}5 - (-6{,}5) = +14{,}0\ \text{cm·an}^{-1}$ : elle est **indépendante du référentiel**.

    !!! abstract "À retenir"
        Les vitesses **individuelles** dépendent du **référentiel** ; les vitesses **relatives** entre deux plaques n'en dépendent **pas**.

---

### Exercice 5 : Rotation et vitesse (approfondissement, niveau ★★★★)

Une plaque tourne autour d'un pôle avec $\omega = 0{,}8^\circ\text{·Ma}^{-1}$. On rappelle $v = \omega\,R_T\sin\theta$ avec $R_T = 6371\ \text{km}$.

1. Calculer $v$ pour $\theta = 20^\circ$, $30^\circ$, $60^\circ$, $90^\circ$ et au pôle.
2. Expliquer pourquoi le taux d'ouverture d'une dorsale varie le long de celle-ci.

??? success "Corrigé"
    **1.** $\omega\,R_T = 8{,}9\ \text{cm·an}^{-1}$ (voir le calcul du cours).

    | $\theta$ | $0^\circ$ | $20^\circ$ | $30^\circ$ | $60^\circ$ | $90^\circ$ |
    |---|---|---|---|---|---|
    | $\sin\theta$ | $0$ | $0{,}342$ | $0{,}5$ | $0{,}866$ | $1$ |
    | $v$ ($\text{cm·an}^{-1}$) | $0$ | $3{,}0$ | $4{,}5$ | $7{,}7$ | $8{,}9$ |

    **2.** Les différents points d'une dorsale sont à des **distances angulaires** différentes du pôle : $v$ **augmente** avec $\sin\theta$. Le taux d'ouverture est **nul** au pôle et **maximal** à $90^\circ$.

---

### Exercice 6 : Bilan de surface (niveau ★★★)

Les dorsales créent $3\ \text{km}^2$ de lithosphère par an. Surface de la Terre : $5{,}1\times10^{8}\ \text{km}^2$ ; surface des océans : $3{,}6\times10^{8}\ \text{km}^2$.

1. Quelle surface est créée par Ma ? Quel pourcentage de la surface océanique cela représente-t-il ?
2. Quelle surface est créée en $180\ \text{Ma}$ ? Comparer à la surface océanique actuelle.
3. Conclure sur le devenir de cette lithosphère.

??? success "Corrigé"
    **1.** $3\ \text{km}^2\text{·an}^{-1}\times10^{6} = 3\times10^{6}\ \text{km}^2\text{·Ma}^{-1}$, soit $\dfrac{3\times10^{6}}{3{,}6\times10^{8}} \approx 0{,}83\ \%$ de la surface océanique **par Ma**.

    **2.** $3\times10^{6}\times180 = 5{,}4\times10^{8}\ \text{km}^2$ : **$1{,}5$ fois** la surface océanique actuelle.

    **3.** La lithosphère océanique **créée** est **détruite** ailleurs (subduction) : elle ne s'accumule pas. Sinon, la Terre grossirait. Ceci **explique** que la croûte océanique soit **jeune**.

---

### Exercice 7 : Vrai ou faux, avec justification (niveau ★★)

1. Une vitesse de plaque a un sens sans précision du référentiel.
2. Deux stations sur une même plaque, loin des limites, voient leur distance varier de plusieurs centimètres par an.
3. La vitesse relative de deux plaques ne dépend pas du référentiel.
4. Les points chauds sont absolument immobiles.
5. La dorsale est-Pacifique s'ouvre plus vite que la dorsale médio-atlantique.
6. Le GPS mesure directement la vitesse des plaques.
7. Les plaques rapides sont souvent bordées de zones de subduction.
8. La surface de la Terre augmente avec la création de lithosphère aux dorsales.

??? success "Corrigé"
    1. **Faux.** Il faut **toujours** préciser le référentiel.
    2. **Faux.** La distance est **constante** (plaque rigide).
    3. **Vrai.** C'est une **différence** de vecteurs.
    4. **Faux.** Ils sont **quasi fixes** (de l'ordre de $1\ \text{cm·an}^{-1}$ ou moins).
    5. **Vrai.** $\approx 10$ à $15$ contre $\approx 2$ à $3\ \text{cm·an}^{-1}$.
    6. **Faux.** Il mesure la vitesse de **stations**, attribuée aux plaques.
    7. **Vrai.** Exemple : Pacifique, Nazca.
    8. **Faux.** La création est **compensée** par la destruction en subduction.

---

## Partie II : Exercices type contrôle

### Exercice 8 : Analyse de documents (10 points)

!!! question "Question"
    **À l'aide des documents et de vos connaissances, montrer que les mesures GPS permettent de mettre en évidence le mouvement des plaques lithosphériques et leur rigidité, et de distinguer mouvement relatif et mouvement absolu.**

**Document 1 : distances entre stations GPS (en mètres)**

| Paire de stations | Plaques | 2012 | 2020 |
|---|---|---|---|
| Brasília - Dakar | Amérique du Sud - Afrique | $5\,134\,982{,}214$ | $5\,134\,982{,}454$ |
| Madrid - Paris | Eurasie - Eurasie | $1\,053\,218{,}102$ | $1\,053\,218{,}104$ |

**Document 2 : référentiel des points chauds**

Dans le référentiel des points chauds, supposés fixes, la vitesse (selon l'axe est-ouest, est positif) de l'Afrique est $+2{,}0\ \text{cm·an}^{-1}$ et celle de l'Amérique du Sud $-1{,}0\ \text{cm·an}^{-1}$.

**Document 3 : la plaque Pacifique**

La plaque Pacifique s'éloigne du point chaud d'Hawaï de $\approx 7\ \text{cm·an}^{-1}$ environ vers le nord-ouest.

**Barème indicatif :** doc 1, vitesses (3 pts) ; rigidité (2 pts) ; relatif/absolu (3 pts) ; conclusion et rédaction (2 pts).

??? success "Corrigé et réponse modèle"
    **Attendus**

    1. **Brasília - Dakar** : $\Delta d = 0{,}240\ \text{m}$ en $8$ ans soit $3{,}0\ \text{cm·an}^{-1}$ : les stations **s'éloignent** : les plaques **se déplacent** et l'Atlantique **s'ouvre**.
    2. **Madrid - Paris** : $\Delta d = 0{,}002\ \text{m}$ en $8$ ans soit $\approx 0{,}25\ \text{mm·an}^{-1}$ ($\approx 0$) : **pas de déformation** interne : la plaque est **rigide**.
    3. **Doc 2** : relatif $= +2{,}0 - (-1{,}0) = +3{,}0\ \text{cm·an}^{-1}$, **cohérent** avec le doc 1.
    4. **Distinction** : le **mouvement relatif** (Afrique/Amérique du Sud, $3{,}0$) est mesuré **entre deux plaques** ; le **mouvement absolu** (Afrique $+2{,}0$, Amérique du Sud $-1{,}0$ ; Pacifique $\approx 7$ cm·an⁻¹ à Hawaï) est défini **par rapport aux points chauds**.
    5. **Conclusion** : les plaques **bougent**, sont **rigides**, et leurs mouvements se décrivent dans **deux types de référentiels**.

    **Réponse modèle rédigée**

    > D'après le document 1, la distance entre Brasília et Dakar augmente de $0{,}240\ \text{m}$ en huit ans, soit $3{,}0\ \text{cm·an}^{-1}$ : l'Amérique du Sud et l'Afrique s'éloignent, ce qui montre un mouvement des plaques et l'ouverture de l'Atlantique. En revanche, la distance Madrid-Paris, deux stations d'une même plaque, ne varie que de $2\ \text{mm}$ en huit ans ($\approx 0{,}25\ \text{mm·an}^{-1}$), ce qui indique une plaque rigide. Le document 2 donne les vitesses par rapport aux points chauds : Afrique $+2{,}0$ et Amérique du Sud $-1{,}0\ \text{cm·an}^{-1}$. Leur différence, $3{,}0\ \text{cm·an}^{-1}$, correspond à la vitesse relative mesurée par GPS. Le mouvement relatif décrit le déplacement d'une plaque par rapport à une autre, tandis que le mouvement absolu se réfère aux points chauds, comme pour la plaque Pacifique qui s'éloigne d'Hawaï à $\approx 7\ \text{cm·an}^{-1}$ (document 3). Ainsi, les mesures GPS montrent que les plaques se déplacent, qu'elles sont rigides, et que leur mouvement se décrit soit en relatif, soit en absolu.

    !!! warning "Erreurs sanctionnées"
        - Oublier de **convertir** m en cm et de diviser par la durée.
        - Donner une vitesse **sans référentiel**.
        - Ne pas utiliser la paire **Madrid - Paris** pour justifier la rigidité.
        - Écrire que le GPS « mesure la vitesse de la plaque » sans nuance.

---

### Exercice 9 : Bilan de création et de destruction (10 points)

**Document 1 : dorsales**

| Dorsale | Longueur (km) | Taux d'ouverture ($\text{cm·an}^{-1}$) |
|---|---|---|
| Atlantique | $15\,000$ | $2{,}5$ |
| Pacifique | $20\,000$ | $8{,}0$ |
| Indien | $20\,000$ | $4{,}0$ |

**Document 2 : zones de subduction**

Longueur cumulée $\approx 45\,000\ \text{km}$ ; vitesse moyenne de convergence $\approx 6\ \text{cm·an}^{-1}$.

**Document 3 :** surface des fonds océaniques : $3{,}6\times10^{8}\ \text{km}^2$ ; âge maximal de la croûte océanique $\approx 180\ \text{Ma}$.

**Questions**

1. Calculer la surface créée chaque année aux dorsales. (3 pts)
2. Calculer la surface détruite chaque année en subduction. (2 pts)
3. Comparer et conclure sur le rayon de la Terre. (2 pts)
4. Calculer la durée de renouvellement des fonds océaniques et la comparer à l'âge maximal. (3 pts)

??? success "Corrigé"
    **1.** Surface $=$ longueur $\times$ taux (en km·an⁻¹) :

    - Atlantique : $15\,000\times2{,}5\times10^{-5} = 0{,}375\ \text{km}^2\text{·an}^{-1}$ ;
    - Pacifique : $20\,000\times8{,}0\times10^{-5} = 1{,}6$ ;
    - Indien : $20\,000\times4{,}0\times10^{-5} = 0{,}8$.

    Total : $0{,}375+1{,}6+0{,}8 \approx 2{,}8\ \text{km}^2\text{·an}^{-1}$.

    **2.** $45\,000\times6\times10^{-5} = 2{,}7\ \text{km}^2\text{·an}^{-1}$.

    **3.** Création ($2{,}8$) et destruction ($2{,}7$) sont **du même ordre** : la surface de la lithosphère se **conserve**, donc le **rayon** de la Terre est **constant** (**pas d'expansion**).

    **4.** $\dfrac{3{,}6\times10^{8}}{2{,}8} \approx 1{,}3\times10^{8}\ \text{ans} \approx 130\ \text{Ma}$, **inférieur** à $180\ \text{Ma}$ : **cohérent** avec l'âge maximal (une partie des fonds est plus ancienne que la moyenne).

    !!! warning "Piège"
        Il faut **convertir** les $\text{cm·an}^{-1}$ en $\text{km·an}^{-1}$ : $1\ \text{cm} = 10^{-5}\ \text{km}$. Oublier cette conversion fausse le résultat d'un facteur $10^5$.
