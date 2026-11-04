# Exercices : Organisation de la Terre en surface

!!! tip "Comment travailler"
    Cherche **sur papier** avant d'ouvrir un corrigé. Les exercices 1 à 4 sont **progressifs** ; les exercices 5 et 6 sont **de type contrôle** (analyse de documents, à faire en temps limité : environ 25 minutes chacun).

---

## Partie I : Exercices progressifs

### Exercice 1 : Histogramme à classes inégales (niveau ★★)

On donne la répartition de la surface du globe (valeurs **simplifiées**) selon des classes d'altitude **de largeurs différentes**.

| Classe d'altitude (m) | $\geq +3000$ | $[+1000 ; +3000[$ | $[+500 ; +1000[$ | $[0 ; +500[$ | $[-2000 ; 0[$ | $[-4000 ; -2000[$ | $[-5000 ; -4000[$ | $[-6000 ; -5000[$ | $< -6000$ |
|---|---|---|---|---|---|---|---|---|---|
| % de la surface | 1 | 6 | 8 | 14 | 8 | 20 | 23 | 18 | 2 |

1. Vérifier que le total est cohérent.
2. Pour chaque classe **fermée**, calculer le pourcentage de surface **par tranche de $1000\ \text{m}$**.
3. Identifier les deux modes. Conclure.
4. Un élève affirme : « la classe $[-4000 ; -2000[$ avec $20\ \%$ est un mode ». Réfuter.

??? success "Corrigé"
    **1.** $1+6+8+14+8+20+23+18+2 = 100\ \%$. Les données sont cohérentes.

    **2.** On divise le pourcentage par la largeur de la classe exprimée en milliers de mètres :

    | Classe | Largeur (km) | % de la surface | % par $1000\ \text{m}$ |
    |---|---|---|---|
    | $[+1000 ; +3000[$ | 2 | 6 | 3 |
    | $[+500 ; +1000[$ | 0,5 | 8 | 16 |
    | $[0 ; +500[$ | 0,5 | 14 | **28** |
    | $[-2000 ; 0[$ | 2 | 8 | 4 |
    | $[-4000 ; -2000[$ | 2 | 20 | 10 |
    | $[-5000 ; -4000[$ | 1 | 23 | **23** |
    | $[-6000 ; -5000[$ | 1 | 18 | 18 |

    Les classes ouvertes ($\geq +3000$ et $< -6000$) ne se comparent pas.

    **3.** Les deux valeurs les plus élevées sont $28\ \%$ par $1000\ \text{m}$ pour $[0 ; +500[$ (**mode continental**) et $23\ \%$ par $1000\ \text{m}$ pour $[-5000 ; -4000[$ (**mode océanique**). Elles sont séparées par un creux ($3$ à $4\ \%$ par $1000\ \text{m}$). La distribution est **bimodale**.

    **4.** La classe $[-4000 ; -2000[$ est **deux fois plus large** que les autres : son pourcentage brut est « gonflé » par sa largeur. Rapporté à $1000\ \text{m}$, elle vaut seulement $10\ \%$, bien en dessous de $23\ \%$. Ce n'est **pas** un mode.

    !!! warning "Piège"
        Comparer des **hauteurs de barres** n'a de sens que pour des classes de **même largeur**. Sinon on compare des **densités** (pourcentage par unité d'altitude).

---

### Exercice 2 : Identifier des roches (niveau ★★)

On décrit cinq échantillons.

- **A** : roche claire, grains visibles à l'œil nu et jointifs, sans orientation : grains gris translucides sans clivage, grains blancs et roses à clivages, paillettes noires brillantes.
- **B** : roche **rubanée** avec alternance de lits clairs (quartz, feldspaths) et de lits sombres de biotite, minéraux alignés ; mêmes minéraux que A.
- **C** : roche sombre, pâte noire très fine contenant quelques cristaux vert olive ; en lame mince : petits cristaux de plagioclase allongés (microlites) et un peu de verre.
- **D** : roche sombre, tous les cristaux visibles à l'œil nu, plagioclase et pyroxène, **sans quartz**.
- **E** : roche disposée en couches, effervescence à l'acide, contient des coquilles fossiles.

1. Nommer chaque roche et donner sa famille.
2. Pour chaque roche magmatique, indiquer les conditions de refroidissement.
3. Comparer A et B, puis C et D.

??? success "Corrigé"
    **1.**

    | Échantillon | Roche | Famille |
    |---|---|---|
    | A | **granite** | magmatique plutonique |
    | B | **gneiss** | métamorphique |
    | C | **basalte** (phénocristaux d'olivine) | magmatique volcanique |
    | D | **gabbro** | magmatique plutonique |
    | E | **calcaire** (bioclastique) | sédimentaire |

    **2.** A et D : refroidissement **lent en profondeur** donc texture **grenue**. C : refroidissement **rapide en surface** donc texture **microlitique** avec verre.

    **3.** *A et B* : **même composition minéralogique** (quartz, feldspaths, micas) mais **organisation différente** : A est grenu sans orientation, B est foliée. B peut être un **orthogneiss** dérivé d'un granite par métamorphisme. *C et D* : **même composition chimique** (basalte et gabbro), **textures différentes** (vitesse de refroidissement).

    !!! warning "Piège"
        Un élève qui répond « B est un granite » ignore la **texture** : c'est l'organisation en lits qui fait le gneiss. La composition seule ne suffit pas à nommer une roche.

---

### Exercice 3 : Altitude et épaisseur de la croûte (niveau ★★★)

On utilise le modèle de la partie C avec : $\rho_c = 2{,}8$, $\rho_o = 2{,}9$, $\rho_e = 1{,}03$, $\rho_m = 3{,}3\ \text{g·cm}^{-3}$ ; $h_o = 7\ \text{km}$ ; $w = 3{,}8\ \text{km}$.

$$
e \;=\; \frac{h_c\,(\rho_m-\rho_c)\;-\;h_o\,(\rho_m-\rho_o)\;-\;w\,(\rho_m-\rho_e)}{\rho_m}
$$

1. Calculer l'épaisseur $h_c$ pour laquelle une croûte continentale affleure exactement au niveau de la mer ($e = 0$).
2. Calculer l'altitude $e$ d'une croûte continentale de $60\ \text{km}$ d'épaisseur (chaîne type Himalaya). Calculer la profondeur de sa base sous le niveau de la mer.
3. Que se passe-t-il si l'on prend $\rho_c = 3{,}0\ \text{g·cm}^{-3}$ et $h_c = 30\ \text{km}$ ? Conclure sur le rôle de la masse volumique.

??? success "Corrigé"
    On calcule d'abord la quantité constante : $h_o(\rho_m-\rho_o) + w(\rho_m-\rho_e) = 7\times0{,}4 + 3{,}8\times 2{,}27 = 2{,}8 + 8{,}626 = 11{,}426$.

    **1.** $e=0 \Rightarrow h_c \times 0{,}5 = 11{,}426 \Rightarrow h_c \approx 22{,}9\ \text{km}$. Une croûte continentale de **moins de $23\ \text{km}$** serait **sous** le niveau de la mer (cas des marges amincies, des bassins d'effondrement).

    **2.** $e = \dfrac{60\times0{,}5 - 11{,}426}{3{,}3} = \dfrac{18{,}574}{3{,}3} \approx 5{,}6\ \text{km}$. La base de la croûte est à $60 - 5{,}6 \approx 54{,}4\ \text{km}$ sous le niveau de la mer, contre environ $28{,}9\ \text{km}$ pour la croûte de $30\ \text{km}$ ($30 - 1{,}08$). La montagne a donc une **racine crustale profonde**.

    **3.** $e = \dfrac{30\times0{,}3 - 11{,}426}{3{,}3} = \dfrac{9 - 11{,}426}{3{,}3} \approx -0{,}7\ \text{km}$. La croûte serait **sous** le niveau de la mer, malgré ses $30\ \text{km}$ d'épaisseur. **À épaisseur égale**, une croûte plus dense flotte **moins haut** : l'altitude dépend de l'**épaisseur et de la masse volumique** conjointement.

---

### Exercice 4 : Vrai ou faux, avec justification (niveau ★★)

Pour chaque affirmation, répondre **vrai** ou **faux** et **justifier en une phrase**.

1. Le basalte est une roche plutonique.
2. Le gneiss est une roche magmatique.
3. L'altitude moyenne du globe correspond à l'un des deux modes de l'histogramme.
4. La croûte océanique actuelle la plus ancienne a environ $4\ \text{Ga}$.
5. Le plateau continental est constitué de croûte continentale.
6. Gabbro et basalte ont la même composition chimique.
7. La croûte océanique est plus épaisse que la croûte continentale mais moins dense.
8. Le granite contient de l'olivine en grande quantité.
9. La péridotite appartient à la croûte océanique.
10. À même densité, une croûte plus épaisse flotte plus haut.

??? success "Corrigé"
    1. **Faux.** Le basalte est **volcanique** (refroidissement rapide) ; le gabbro est son équivalent plutonique.
    2. **Faux.** Le gneiss est **métamorphique** (transformation à l'état solide).
    3. **Faux.** La moyenne tombe dans le **creux** entre les deux modes, là où il y a peu de surface.
    4. **Faux.** Environ $180$ à $200\ \text{Ma}$ ; c'est la croûte **continentale** qui atteint $4\ \text{Ga}$.
    5. **Vrai.** Il est **immergé** mais **continental**.
    6. **Vrai.** Seule la **texture** diffère.
    7. **Faux.** Elle est **plus mince** ($\approx 7\ \text{km}$) et **plus dense**.
    8. **Faux.** L'olivine est **absente** d'un granite ; elle caractérise les roches ferromagnésiennes (basalte, péridotite).
    9. **Faux.** La péridotite constitue le **manteau**.
    10. **Vrai.** D'après la formule, $e$ augmente avec $h_c$ quand $\rho_c < \rho_m$.

---

## Partie II : Exercices type contrôle

### Exercice 5 : Analyse de documents (10 points)

!!! question "Question"
    **À l'aide des documents et de vos connaissances, montrer que la bimodalité des altitudes à la surface de la Terre traduit l'existence de deux types de croûte.**

**Document 1 : répartition des altitudes (valeurs simplifiées)**

| Classe d'altitude (m) | $>+2000$ | $+1000$ à $+2000$ | $0$ à $+1000$ | $0$ à $-1000$ | $-1000$ à $-2000$ | $-2000$ à $-3000$ | $-3000$ à $-4000$ | $-4000$ à $-5000$ | $-5000$ à $-6000$ | $<-6000$ |
|---|---|---|---|---|---|---|---|---|---|---|
| % de la surface | 3 | 4 | 22 | 5 | 3 | 6 | 14 | 23 | 18 | 2 |

**Document 2 : caractéristiques moyennes des deux croûtes**

| | Croûte A | Croûte B |
|---|---|---|
| Épaisseur moyenne | $7\ \text{km}$ | $30$ à $35\ \text{km}$ |
| Masse volumique | $2{,}9\ \text{g·cm}^{-3}$ | $2{,}7\ \text{g·cm}^{-3}$ |
| Âge maximal | $\approx 180\ \text{Ma}$ | $\approx 4\ \text{Ga}$ |

**Document 3 : échantillons**

- Un forage continental de plus de $12\ \text{km}$ de profondeur (péninsule de Kola) a rencontré surtout des **gneiss** et des **roches granitiques**.
- Un dragage sur le flanc d'une dorsale océanique a remonté des **basaltes** et des **gabbros**.

**Document 4 : donnée complémentaire**

La masse volumique moyenne du manteau supérieur, sous les croûtes, est d'environ $3{,}3\ \text{g·cm}^{-3}$.

**Barème indicatif :** Doc 1 (2 pts) ; identification des croûtes (3 pts) ; explication (3 pts) ; conclusion et rédaction (2 pts).

??? success "Corrigé et réponse modèle"
    **Attendus**

    1. **Constat** : l'histogramme présente **deux modes** : $0$ à $+1000\ \text{m}$ ($22\ \%$ de la surface) et $-4000$ à $-5000\ \text{m}$ ($23\ \%$), séparés par un creux ($3\ \%$ et $6\ \%$ de la surface entre $-1000$ et $-3000\ \text{m}$). Les altitudes sont donc réparties en **deux populations**.
    2. **Identification** : la croûte A (mince, dense, jeune) correspond à la **croûte océanique** ; elle est composée de **basaltes et de gabbros** (document 3). La croûte B (épaisse, moins dense, ancienne) correspond à la **croûte continentale**, composée de **granitoïdes et de gneiss**.
    3. **Explication** : les deux croûtes sont **moins denses** que le manteau ($3{,}3$) et « flottent » sur lui. La croûte B, plus **épaisse** et plus **légère**, s'élève plus haut ; la croûte A, plus **mince** et plus **dense**, se trouve plus bas, d'où la différence d'altitude de plusieurs kilomètres.
    4. **Conclusion** : la bimodalité des altitudes **reflète** la présence de **deux types de croûte** de natures différentes.

    **Réponse modèle rédigée**

    > Le document 1 montre une distribution bimodale : $22\ \%$ de la surface du globe se situe entre $0$ et $+1000\ \text{m}$ et $23\ \%$ entre $-4000$ et $-5000\ \text{m}$, avec peu de surface entre les deux. Cela indique deux populations d'altitudes. D'après les documents 2 et 3, la croûte A, mince ($7\ \text{km}$), dense ($2{,}9$) et jeune, constituée de basaltes et de gabbros, est la croûte océanique ; la croûte B, épaisse ($30$ à $35\ \text{km}$), moins dense ($2{,}7$), ancienne et constituée de granitoïdes et de gneiss, est la croûte continentale. Ces deux croûtes sont moins denses que le manteau ($3{,}3$, document 4) et flottent sur lui. La croûte continentale, plus épaisse et plus légère, s'élève plus haut que la croûte océanique, plus mince et plus dense. La bimodalité des altitudes traduit donc l'existence de deux types de croûte.

    !!! warning "Erreurs sanctionnées"
        - Décrire le document 1 **sans citer de valeurs**.
        - Écrire que la croûte océanique est plus basse « parce qu'elle est plus mince » **seulement** : il faut **épaisseur et densité**.
        - Ne pas **croiser** les documents (le sujet demande explicitement de relier).
        - Confondre croûte et manteau (la péridotite n'est pas dans la croûte).

---

### Exercice 6 : Roches, croûtes et calcul (10 points)

**Document 1 : compositions minéralogiques (en % du volume)**

| Minéral | Échantillon X | Échantillon Z |
|---|---|---|
| Quartz | 30 | 0 |
| Feldspaths potassiques | 30 | 0 |
| Plagioclases | 25 | 50 |
| Biotite et muscovite | 15 | 0 |
| Pyroxènes | 0 | 35 |
| Olivine | 0 | 10 |
| Oxydes | 0 | 5 |

- X : texture **grenue**. Z : texture **microlitique** avec un peu de verre.

**Document 2 :** modèle d'équilibre : $e = \dfrac{h_c(\rho_m-\rho_c)-h_o(\rho_m-\rho_o)-w(\rho_m-\rho_e)}{\rho_m}$ avec $\rho_c = 2{,}8$, $\rho_o = 2{,}9$, $\rho_e = 1{,}03$, $\rho_m = 3{,}3\ \text{g·cm}^{-3}$, $h_o = 7\ \text{km}$, $w = 3{,}8\ \text{km}$.

**Questions**

1. Nommer les roches X et Z et justifier. (2 pts)
2. Dire laquelle est la plus dense et pourquoi. (2 pts)
3. Indiquer le type de croûte caractérisé par chacune. (1 pt)
4. Une étude sismique indique une épaisseur crustale de $45\ \text{km}$ sous une chaîne. Calculer l'altitude prévue par le modèle. (3 pts)
5. L'altitude moyenne observée est de $2{,}5\ \text{km}$. Proposer deux raisons possibles de l'écart. (2 pts)

??? success "Corrigé"
    **1.** X : **granite** (quartz, feldspaths potassiques, plagioclases et micas ; texture grenue donc refroidissement lent en profondeur). Z : **basalte** (plagioclases, pyroxènes, olivine, oxydes ; texture microlitique donc refroidissement rapide).

    **2.** **Z (basalte)**, plus dense : riche en minéraux **ferromagnésiens** (pyroxènes, olivine, oxydes), qui sont plus denses que le quartz et les feldspaths.

    **3.** X : **croûte continentale** (granitoïdes). Z : **croûte océanique** (basaltes).

    **4.** On a vu $h_o(\rho_m-\rho_o)+w(\rho_m-\rho_e) = 11{,}426$. Alors
    $$e = \frac{45\times0{,}5 - 11{,}426}{3{,}3} = \frac{22{,}5-11{,}426}{3{,}3} = \frac{11{,}074}{3{,}3} \approx 3{,}4\ \text{km}.$$

    **5.** Deux raisons possibles : (i) le modèle est **simplifié** (croûte et manteau supposés homogènes) ; (ii) l'**érosion** abaisse les reliefs ; (iii) les masses volumiques réelles varient localement ; (iv) l'altitude moyenne d'une chaîne n'est pas l'altitude de ses sommets. Toute raison **justifiée** est acceptée (deux demandées).

    !!! warning "Piège"
        La question 5 teste l'**esprit critique** : un modèle donne un **ordre de grandeur**, pas une valeur exacte. Ne dis pas « le modèle est faux » ; dis « il est approché et donne un bon ordre de grandeur ».
