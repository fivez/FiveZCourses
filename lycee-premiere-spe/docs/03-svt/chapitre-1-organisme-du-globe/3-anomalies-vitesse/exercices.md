# Exercices : Apports des anomalies de vitesse des ondes sismiques

!!! tip "Comment travailler"
    Cherche **sur papier** avant d'ouvrir un corrigé. Les exercices 1 à 6 sont **progressifs** ; les exercices 7 et 8 sont **de type contrôle** (analyse de documents, environ 25 minutes chacun).

---

## Partie I : Exercices progressifs

### Exercice 1 : Lire un géotherme (niveau ★★)

On donne quelques points d'un géotherme continental.

| Profondeur $z$ (km) | $0$ | $10$ | $30$ | $100$ | $150$ | $400$ |
|---|---|---|---|---|---|---|
| Température $T$ ($^\circ\text{C}$) | $15$ | $315$ | $700$ | $1300$ | $1350$ | $1475$ |

1. Calculer le gradient géothermique sur chaque intervalle.
2. Entre quelles profondeurs le mode de transfert change-t-il ? Justifier.
3. Calculer le flux conductif dans les $10$ premiers kilomètres ($\lambda = 2{,}5\ \text{W·m}^{-1}\text{·K}^{-1}$).
4. Quelle température obtiendrait-on à $100\ \text{km}$ en conservant le gradient initial ? Conclure.

??? success "Corrigé"
    **1.** $\dfrac{\Delta T}{\Delta z}$ :

    | Intervalle (km) | Gradient ($^\circ\text{C·km}^{-1}$) |
    |---|---|
    | $0$ à $10$ | $\dfrac{300}{10} = 30$ |
    | $10$ à $30$ | $\dfrac{385}{20} \approx 19$ |
    | $30$ à $100$ | $\dfrac{600}{70} \approx 8{,}6$ |
    | $100$ à $150$ | $\dfrac{50}{50} = 1{,}0$ |
    | $150$ à $400$ | $\dfrac{125}{250} = 0{,}5$ |

    **2.** Le gradient **diminue fortement** vers $100$ à $150\ \text{km}$ : on passe de $\approx 30$ à $\approx 1\ ^\circ\text{C·km}^{-1}$ puis $0{,}5$. Cela correspond au passage de la **conduction** (lithosphère rigide, gradient fort) à la **convection** (manteau sous-jacent, gradient faible).

    **3.** $\varphi = 2{,}5 \times 0{,}030 = 0{,}075\ \text{W·m}^{-2} = 75\ \text{mW·m}^{-2}$.

    **4.** $15 + 30\times100 = 3015\ ^\circ\text{C}$ au lieu de $1300\ ^\circ\text{C}$ mesurés : le gradient **n'est pas constant**. Extrapoler une valeur locale à toute la profondeur est une **erreur de raisonnement**.

---

### Exercice 2 : Radioactivité et chaleur (niveau ★★★)

Demi-vies : $^{238}\text{U}$ : $4{,}47\ \text{Ga}$ ; $^{232}\text{Th}$ : $14\ \text{Ga}$ ; $^{40}\text{K}$ : $1{,}25\ \text{Ga}$. Âge de la Terre : $4{,}56\ \text{Ga}$.

1. Calculer la proportion de chaque isotope restant aujourd'hui par rapport à la formation de la Terre.
2. Par quel facteur la quantité initiale de $^{40}\text{K}$ dépasse-t-elle l'actuelle ?
3. En déduire l'évolution de la production radioactive de chaleur au cours du temps.

??? success "Corrigé"
    **1.** Proportion restante $= \left(\tfrac12\right)^{t/t_{1/2}}$ avec $t = 4{,}56\ \text{Ga}$.

    - $^{238}\text{U}$ : $2^{-4{,}56/4{,}47} = 2^{-1{,}020} \approx 0{,}49$, soit **$49\ \%$**.
    - $^{232}\text{Th}$ : $2^{-4{,}56/14} = 2^{-0{,}326} \approx 0{,}80$, soit **$80\ \%$**.
    - $^{40}\text{K}$ : $2^{-4{,}56/1{,}25} = 2^{-3{,}65} \approx 0{,}08$, soit **$8\ \%$**.

    **2.** $\dfrac{1}{0{,}08} \approx 12{,}5$ : il y avait environ **$12$ fois plus** de $^{40}\text{K}$ à la formation de la Terre.

    **3.** La production radioactive de chaleur était **beaucoup plus forte** dans le passé, surtout à cause du potassium 40 (demi-vie courte). Elle **diminue** au cours du temps : la Terre **se refroidit** progressivement.

---

### Exercice 3 : Flux et puissance (niveau ★★)

Le flux géothermique moyen est $87\ \text{mW·m}^{-2}$. Rayon de la Terre : $6371\ \text{km}$.

1. Calculer la surface du globe puis la puissance totale perdue.
2. Une couche de granite de $10\ \text{km}$ d'épaisseur produit $2{,}5\ \mu\text{W·m}^{-3}$ de chaleur radioactive. Quelle part du flux continental ($65\ \text{mW·m}^{-2}$) cette couche explique-t-elle ?

??? success "Corrigé"
    **1.** $S = 4\pi R_T^2 = 4\pi\,(6{,}371\times10^{6})^2 \approx 5{,}1\times10^{14}\ \text{m}^2$.

    $P = \varphi\,S = 0{,}087 \times 5{,}1\times10^{14} \approx 4{,}4\times10^{13}\ \text{W} = 44\ \text{TW}$.

    **2.** Flux produit par la couche : $A\,h = 2{,}5\times10^{-6} \times 10\,000 = 0{,}025\ \text{W·m}^{-2} = 25\ \text{mW·m}^{-2}$. Part du flux continental : $\dfrac{25}{65} \approx 38\ \%$, soit **plus d'un tiers**. La **croûte continentale** produit donc elle-même une part importante de sa chaleur.

    !!! warning "Piège"
        Convertir $\mu\text{W}$ en W ($10^{-6}$) et km en m ($10^3$). Un flux se calcule en **$\text{W·m}^{-2}$**.

---

### Exercice 4 : De l'écart de temps à l'anomalie (niveau ★★★)

Un rayon sismique traverse sur $500\ \text{km}$ une région du manteau où le modèle de référence donne $V_S = 6{,}0\ \text{km·s}^{-1}$.

1. Le rayon arrive avec $2{,}5\ \text{s}$ d'**avance** sur le temps prédit. Calculer la vitesse moyenne réelle et l'anomalie $\Delta V/V$.
2. Un autre rayon, de même longueur, arrive avec $2{,}0\ \text{s}$ de **retard**. Même calcul.
3. Sachant que $100\ ^\circ\text{C}$ correspondent à environ $1\ \%$ de variation de vitesse, estimer l'écart de température dans chaque cas. Conclure.

??? success "Corrigé"
    Temps de référence : $\dfrac{500}{6{,}0} = 83{,}3\ \text{s}$.

    **1.** Temps réel $= 83{,}3 - 2{,}5 = 80{,}8\ \text{s}$ donc $V = \dfrac{500}{80{,}83} \approx 6{,}19\ \text{km·s}^{-1}$. $\dfrac{\Delta V}{V} = \dfrac{6{,}19-6{,}0}{6{,}0} \approx +3{,}1\ \%$ (anomalie **positive**).

    **2.** Temps réel $= 83{,}3 + 2{,}0 = 85{,}3\ \text{s}$ donc $V \approx 5{,}86\ \text{km·s}^{-1}$. $\dfrac{\Delta V}{V} \approx -2{,}4\ \%$ (anomalie **négative**).

    **3.** Cas 1 : $\approx 300\ ^\circ\text{C}$ **plus froid** que le manteau environnant (matériau froid : plaque plongeante). Cas 2 : $\approx 240\ ^\circ\text{C}$ **plus chaud** (matériau chaud : remontée). Ces valeurs sont des **ordres de grandeur** : la composition peut aussi jouer.

---

### Exercice 5 : Durées et vitesses de la convection (niveau ★★)

1. Une plaque plonge à $5\ \text{cm·an}^{-1}$ et descend jusqu'à $2900\ \text{km}$. Calculer la durée de la descente.
2. Même question à $1\ \text{cm·an}^{-1}$.
3. L'âge maximal de la croûte océanique actuelle est d'environ $180\ \text{Ma}$. Ce résultat est-il compatible avec ces durées ?

??? success "Corrigé"
    **1.** $2900\ \text{km} = 2{,}9\times10^{6}\ \text{m}$ ; $5\ \text{cm·an}^{-1} = 0{,}05\ \text{m·an}^{-1}$. Durée $= \dfrac{2{,}9\times10^{6}}{0{,}05} = 5{,}8\times10^{7}\ \text{ans} = 58\ \text{Ma}$.

    **2.** À $0{,}01\ \text{m·an}^{-1}$ : $2{,}9\times10^{8}\ \text{ans} = 290\ \text{Ma}$.

    **3.** Oui : la croûte océanique est **renouvelée** par la subduction en moins de $200\ \text{Ma}$, durée du même ordre que celles calculées. Les mouvements du manteau, **très lents** à l'échelle humaine, sont **rapides** à l'échelle des temps géologiques.

---

### Exercice 6 : Vrai ou faux, avec justification (niveau ★★)

1. Le gradient géothermique est constant de la surface au centre de la Terre.
2. Un gradient fort traduit un transfert par conduction.
3. Une anomalie sismique positive indique un matériau plus chaud.
4. Le flux géothermique s'exprime en W.
5. La convection du manteau implique que le manteau est liquide.
6. Environ la moitié de la chaleur terrestre est d'origine radioactive.
7. Le flux est plus élevé aux dorsales qu'au centre d'un vieux continent.
8. La tomographie mesure directement la température.

??? success "Corrigé"
    1. **Faux.** Il vaut $\approx 30$ en surface puis $\approx 0{,}3$ à $0{,}5\ ^\circ\text{C·km}^{-1}$ dans le manteau.
    2. **Vrai.** Pour évacuer un flux avec un matériau peu conducteur, il faut un gradient fort ($\varphi = \lambda\,\Delta T/\Delta z$).
    3. **Faux.** Positive = **plus rapide** = **plus froid**.
    4. **Faux.** Le flux s'exprime en $\text{W·m}^{-2}$ ; la **puissance** s'exprime en W.
    5. **Faux.** Le manteau est **solide** (ondes S) mais **ductile** : il flue très lentement.
    6. **Vrai.** Environ **la moitié** (estimation).
    7. **Vrai.** Lithosphère mince, matière chaude proche de la surface.
    8. **Faux.** Elle mesure des **vitesses** dont on **interprète** les écarts.

---

## Partie II : Exercices type contrôle

### Exercice 7 : Analyse de documents (10 points)

!!! question "Question"
    **À l'aide des documents et de vos connaissances, montrer que la tomographie sismique met en évidence une convection du manteau.**

**Document 1 : coupe tomographique sous une zone de subduction**

Sous un arc insulaire, une zone d'**anomalie positive** de $+1{,}5$ à $+3\ \%$ de $V_S$ forme un **panneau incliné** à $\approx 45^\circ$, depuis la surface jusqu'à environ $1500\ \text{km}$ de profondeur, au sein d'un manteau moyen d'anomalie nulle.

**Document 2 : sous une dorsale et sous un point chaud**

- Sous la dorsale : **anomalie négative** de $-2\ \%$ jusqu'à environ $200\ \text{km}$.
- Sous un point chaud intraplaque : **colonne d'anomalie négative** de $-1{,}5\ \%$ qui descend beaucoup plus profondément.

**Document 3 : relation vitesse - température**

À composition constante, $\dfrac{\Delta V_S}{V_S} \approx -1\ \%$ pour une augmentation de température de $100\ ^\circ\text{C}$.

**Document 4 : mouvements**

Les plaques lithosphériques se déplacent à quelques cm·an⁻¹.

**Barème indicatif :** exploitation des anomalies (3 pts) ; passage à la température (3 pts) ; interprétation en termes de mouvement (2 pts) ; conclusion et rédaction (2 pts).

??? success "Corrigé et réponse modèle"
    **Attendus**

    1. **Doc 1** : anomalie positive ($+1{,}5$ à $+3\ \%$) en panneau incliné jusqu'à $1500\ \text{km}$.
    2. **Doc 3** : une anomalie de $+3\ \%$ correspond à un matériau environ $300\ ^\circ\text{C}$ **plus froid** ($+1{,}5\ \%$ : $150\ ^\circ\text{C}$ plus froid).
    3. **Doc 2** : anomalie négative : $-2\ \%$ soit environ $200\ ^\circ\text{C}$ **plus chaud** sous la dorsale ; colonne chaude profonde sous le point chaud.
    4. **Interprétation** : une plaque **froide** et dense **plonge** dans un manteau plus chaud ; du matériau **chaud** et peu dense **remonte**. Des matériaux de températures différentes **à des endroits différents**, avec des **mouvements verticaux** compatibles avec les vitesses du document 4.
    5. **Conclusion** : une **convection** (mouvement de matière) existe dans le manteau.

    **Réponse modèle**

    > Le document 1 montre, sous une zone de subduction, une anomalie positive de $+1{,}5$ à $+3\ \%$ de vitesse formant un panneau incliné jusqu'à $1500\ \text{km}$. D'après le document 3, une variation de $+1\ \%$ correspond à une température inférieure d'environ $100\ ^\circ\text{C}$ : le panneau est donc plus froid de $150$ à $300\ ^\circ\text{C}$ que le manteau environnant. Il s'agit de lithosphère océanique froide et dense qui plonge dans le manteau. À l'inverse, le document 2 montre des anomalies négatives sous la dorsale ($-2\ \%$, soit environ $200\ ^\circ\text{C}$ de plus) et sous un point chaud ($-1{,}5\ \%$, colonne profonde) : du matériau chaud et moins dense remonte. Des matériaux froids qui descendent et des matériaux chauds qui montent, à des vitesses de l'ordre de quelques cm·an⁻¹ (document 4), caractérisent une convection. La tomographie met donc en évidence une convection mantellique.

    !!! warning "Erreurs sanctionnées"
        - Confondre **anomalie positive** et **température élevée**.
        - Affirmer que la tomographie « **voit** » le mouvement : elle montre des **états**, d'où on **déduit** le mouvement.
        - Oublier de **citer des valeurs**.
        - Écrire « le manteau est liquide ».

---

### Exercice 8 : Gradient, flux et conduction (10 points)

**Document 1 : deux sites**

| | Site A (vieux craton) | Site B (dorsale) |
|---|---|---|
| Flux géothermique | $45\ \text{mW·m}^{-2}$ | $200\ \text{mW·m}^{-2}$ |

**Document 2 :** conductivité thermique de la croûte : $\lambda = 2{,}5\ \text{W·m}^{-1}\text{·K}^{-1}$.

**Document 3 :** la base de la lithosphère est repérée par l'isotherme $1300\ ^\circ\text{C}$ ; température de surface : $15\ ^\circ\text{C}$.

**Questions**

1. Calculer le gradient géothermique superficiel de chaque site. (3 pts)
2. En supposant ce gradient constant, calculer la profondeur de l'isotherme $1300\ ^\circ\text{C}$ pour chaque site. (3 pts)
3. Comparer et interpréter la différence. (2 pts)
4. Discuter la validité de l'hypothèse « gradient constant ». (2 pts)

??? success "Corrigé"
    **1.** $\dfrac{\Delta T}{\Delta z} = \dfrac{\varphi}{\lambda}$.

    - A : $\dfrac{0{,}045}{2{,}5} = 0{,}018\ \text{K·m}^{-1} = 18\ ^\circ\text{C·km}^{-1}$.
    - B : $\dfrac{0{,}200}{2{,}5} = 0{,}080\ \text{K·m}^{-1} = 80\ ^\circ\text{C·km}^{-1}$.

    **2.** $z = \dfrac{1300-15}{\text{gradient}}$.

    - A : $\dfrac{1285}{18} \approx 71\ \text{km}$.
    - B : $\dfrac{1285}{80} \approx 16\ \text{km}$.

    **3.** Sous la **dorsale**, l'isotherme $1300\ ^\circ\text{C}$ est **très proche de la surface** : la lithosphère y est **mince** et le **flux élevé**, car du matériau chaud **remonte**. Sous le **craton**, elle est profonde : lithosphère **épaisse**, flux **faible**.

    **4.** L'hypothèse est **fausse** : le gradient **diminue** avec la profondeur (en particulier avec la radioactivité de la croûte, puis le passage à la convection). Les valeurs obtenues sont donc des **estimations minimales** pour la profondeur de l'isotherme sous le craton (la lithosphère des cratons dépasse souvent $150\ \text{km}$) ; sous la dorsale, c'est un **ordre de grandeur** d'une lithosphère très mince.
