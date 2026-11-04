# Exercices : Détermination des grandes enveloppes de la Terre

!!! tip "Comment travailler"
    Cherche **sur papier** avant d'ouvrir un corrigé. Les exercices 1 à 6 sont **progressifs** ; les exercices 7 et 8 sont **de type contrôle** (analyse de documents, environ 25 minutes chacun).

---

## Partie I : Exercices progressifs

### Exercice 1 : Magnitude et énergie (niveau ★★)

1. Un séisme de magnitude $6{,}0$ est suivi, dans la même région, d'un séisme de magnitude $8{,}0$. Par quel facteur l'**amplitude** et l'**énergie** sont-elles multipliées ?
2. Comparer l'énergie d'un séisme de magnitude $6{,}5$ à celle d'un séisme de magnitude $5{,}0$.
3. Un journal écrit : « le séisme d'hier était d'intensité 7 et de magnitude VIII ». Relever **deux erreurs**.

??? success "Corrigé"
    **1.** Écart de $2$ unités : amplitude $\times\,10^{2} = 100$ ; énergie $\times\,10^{1{,}5\times 2} = 10^{3} = 1000$.

    **2.** Écart de $1{,}5$ : $\dfrac{E_2}{E_1} = 10^{1{,}5\times1{,}5} = 10^{2{,}25} \approx 178$.

    **3.** Deux erreurs : (i) la **magnitude** est exprimée par un **nombre décimal** (échelle ouverte) et l'**intensité** par un **chiffre romain** (EMS-98) ; les deux ont été **inversées** ; (ii) un séisme a **une seule magnitude** mais **plusieurs intensités** selon le lieu.

    !!! warning "Piège"
        Le facteur $32$ s'applique à **chaque unité** de magnitude. Pour un écart de $2$, on **ne dit pas** « $64$ » ($2\times32$) mais $32^2 \approx 1000$.

---

### Exercice 2 : Retrouver les vitesses et l'heure origine (niveau ★★★)

Deux stations, situées à $210\ \text{km}$ et $336\ \text{km}$ de l'épicentre, enregistrent les arrivées suivantes (l'heure origine est **inconnue**).

| Station | Distance | Arrivée P | Arrivée S |
|---|---|---|---|
| 1 | $210\ \text{km}$ | 12 h 04 min 30 s | 12 h 04 min 55 s |
| 2 | $336\ \text{km}$ | 12 h 04 min 51 s | 12 h 05 min 31 s |

1. Calculer $V_P$ et $V_S$ à partir des **différences** entre les deux stations.
2. En déduire l'**heure origine**, puis la vérifier avec les ondes S.
3. Calculer le rapport $V_P/V_S$. Que vaut $K/\mu$ si ce rapport est exactement $\sqrt{3}$ ?

??? success "Corrigé"
    **1.** Entre les deux stations, la différence de distance est $336 - 210 = 126\ \text{km}$.

    - Ondes P : écart de temps $= 51 - 30 = 21\ \text{s}$ donc $V_P = \dfrac{126}{21} = 6{,}0\ \text{km·s}^{-1}$.
    - Ondes S : écart de temps $= (5\ \text{min}\ 31\ \text{s}) - (4\ \text{min}\ 55\ \text{s}) = 36\ \text{s}$ donc $V_S = \dfrac{126}{36} = 3{,}5\ \text{km·s}^{-1}$.

    **2.** Temps de trajet des P jusqu'à la station 1 : $\dfrac{210}{6{,}0} = 35\ \text{s}$. Heure origine : $12\ \text{h}\ 04\ \text{min}\ 30\ \text{s} - 35\ \text{s} = 12\ \text{h}\ 03\ \text{min}\ 55\ \text{s}$.

    Vérification avec les S : $\dfrac{210}{3{,}5} = 60\ \text{s}$ ; $12\ \text{h}\ 03\ \text{min}\ 55\ \text{s} + 60\ \text{s} = 12\ \text{h}\ 04\ \text{min}\ 55\ \text{s}$ ✓.

    **3.** $\dfrac{V_P}{V_S} = \dfrac{6{,}0}{3{,}5} \approx 1{,}71$, proche de $\sqrt{3} \approx 1{,}73$. Si $\dfrac{V_P^2}{V_S^2} = \dfrac{K + \frac43\mu}{\mu} = 3$, alors $\dfrac{K}{\mu} + \dfrac43 = 3$ donc $\dfrac{K}{\mu} = \dfrac53$. C'est le cas d'un **solide de Poisson**, bon modèle de la croûte.

    !!! warning "Piège"
        Utiliser les **différences** entre stations permet de **ne pas connaître l'heure origine** : c'est la méthode à retenir quand une donnée manque.

---

### Exercice 3 : Régimes et failles (niveau ★★)

Trois observations de terrain :

- **(a)** dans un fossé d'effondrement, des couches sont coupées par des failles inclinées ; le compartiment **supérieur** s'est **abaissé** ;
- **(b)** dans une chaîne de montagnes, des couches sont **plissées** et on observe un **empilement** d'unités le long d'un plan peu incliné ;
- **(c)** une rivière est **décalée horizontalement** de $5\ \text{m}$ après un séisme, le long d'un plan **vertical**.

1. Pour chaque cas, donner le **type de faille**, le **régime** et un **contexte géodynamique**.
2. Dans le cas (a), une faille de **pendage $60^\circ$** a un **rejet vertical** de $2\ \text{m}$. Calculer l'**extension horizontale** (rejet horizontal). Pour $10$ failles identiques, quelle est l'extension totale ?

??? success "Corrigé"
    **1.**

    | Cas | Faille | Régime | Contexte |
    |---|---|---|---|
    | (a) | **normale** | **extensif** | rift continental, dorsale |
    | (b) | **inverse** (chevauchement) et plis | **compressif** | collision ou subduction |
    | (c) | **décrochante** | **coulissant** | faille transformante |

    **2.** L'extension horizontale vaut $\dfrac{\text{rejet vertical}}{\tan(\text{pendage})} = \dfrac{2}{\tan 60^\circ} = \dfrac{2}{1{,}732} \approx 1{,}15\ \text{m}$. Pour $10$ failles : $\approx 11{,}5\ \text{m}$.

    !!! warning "Piège"
        Dans (c), le **déplacement est horizontal** : on ne parle ni de « compartiment qui monte » ni de « compartiment qui descend ».

---

### Exercice 4 : Où enregistre-t-on quoi ? (niveau ★★★)

Trois stations sont à des distances angulaires $\Delta_A = 80^\circ$, $\Delta_B = 120^\circ$ et $\Delta_C = 160^\circ$ de l'épicentre. Pour chacune, dire si elle enregistre des **ondes P directes** et des **ondes S**, et justifier. Pour B, expliquer pourquoi de **faibles ondes P** y sont néanmoins observées.

??? success "Corrigé"
    | Station | Ondes P | Ondes S | Justification |
    |---|---|---|---|
    | A ($80^\circ$) | oui | oui | avant $103^\circ$, les ondes ont traversé **uniquement le manteau** |
    | B ($120^\circ$) | **non** (zone d'ombre) | **non** | entre $103^\circ$ et $142^\circ$, les P sont **déviées** par le noyau ; les S ne traversent pas le noyau liquide |
    | C ($160^\circ$) | oui (retardées) | **non** | les P ont **traversé le noyau** et en ressortent ; les S sont arrêtées par le noyau externe liquide |

    De faibles ondes P sont observées en B : elles sont **réfléchies sur le noyau interne** (discontinuité de Lehmann), ce qui prouve l'existence d'une **graine solide** et plus rapide.

---

### Exercice 5 : Réfraction et profondeur du Moho (niveau ★★★)

1. À une interface, $V_1 = 6{,}0\ \text{km·s}^{-1}$ et $V_2 = 8{,}0\ \text{km·s}^{-1}$. Un rayon arrive avec $i_1 = 30^\circ$. Calculer $i_2$ puis l'angle critique $i_c$.
2. Au passage de la **limite manteau/noyau** ($V_1 = 13{,}7$, $V_2 = 8{,}0\ \text{km·s}^{-1}$), $i_1 = 30^\circ$. Calculer $i_2$. Le rayon s'écarte-t-il ou se rapproche-t-il de la normale ?
3. Sous un océan, on mesure $V_1 = 6{,}5$, $V_2 = 8{,}0\ \text{km·s}^{-1}$ et une distance critique $x_c = 45\ \text{km}$. Calculer l'épaisseur de la croûte océanique.

??? success "Corrigé"
    **1.** $\sin i_2 = \dfrac{V_2}{V_1}\sin i_1 = \dfrac{8{,}0}{6{,}0}\times0{,}5 = 0{,}667$ donc $i_2 \approx 41{,}8^\circ$. Angle critique : $\sin i_c = \dfrac{V_1}{V_2} = 0{,}75$ donc $i_c \approx 48{,}6^\circ$.

    **2.** $\sin i_2 = \dfrac{8{,}0}{13{,}7}\times0{,}5 = 0{,}292$ donc $i_2 \approx 17{,}0^\circ$. Comme $V_2 < V_1$, le rayon **se rapproche de la normale**. Les rayons sont **fortement déviés** vers l'axe, d'où la **zone d'ombre**.

    **3.** $h = \dfrac{x_c}{2}\sqrt{\dfrac{V_2-V_1}{V_2+V_1}} = 22{,}5\times\sqrt{\dfrac{1{,}5}{14{,}5}} = 22{,}5 \times 0{,}3216 \approx 7{,}2\ \text{km}$, valeur cohérente avec la croûte océanique.

---

### Exercice 6 : Vrai ou faux, avec justification (niveau ★★)

1. Les ondes P sont plus rapides parce qu'elles sont longitudinales.
2. La zone d'ombre des ondes P est due à leur absorption par le noyau.
3. Le Moho marque la limite entre lithosphère et asthénosphère.
4. L'absence d'ondes S dans le noyau externe prouve qu'il est liquide.
5. Le noyau interne est solide parce qu'il est plus froid que le noyau externe.
6. Le modèle PREM donne la composition chimique des enveloppes.
7. Un séisme de magnitude 7 libère environ 32 fois plus d'énergie qu'un séisme de magnitude 6.
8. Les foyers sismiques profonds ($500\ \text{km}$) se rencontrent aux dorsales.

??? success "Corrigé"
    1. **Faux.** La raison est $V_P = \sqrt{(K+\frac43\mu)/\rho} > V_S = \sqrt{\mu/\rho}$.
    2. **Faux.** Elle est due à la **réfraction** des ondes au passage du noyau.
    3. **Faux.** Le Moho sépare la **croûte** du **manteau** ; la limite lithosphère-asthénosphère est **mécanique** (vers $100\ \text{km}$).
    4. **Vrai.** Un milieu qui ne transmet pas les ondes S a $\mu = 0$, donc c'est un liquide.
    5. **Faux.** Il est **solide** à cause de la **pression**, qui élève la température de fusion.
    6. **Faux.** Il donne **vitesses et densités**, pas la composition.
    7. **Vrai.** Environ $10^{1{,}5} \approx 32$.
    8. **Faux.** Les foyers profonds sont en **subduction** ; les dorsales ont des foyers superficiels.

---

## Partie II : Exercices type contrôle

### Exercice 7 : Analyse de documents (10 points)

!!! question "Question"
    **À partir des documents et de vos connaissances, montrer que le noyau de la Terre comprend une partie externe liquide et une graine interne solide.**

**Document 1 : ondes enregistrées selon la distance angulaire à l'épicentre**

| Distance angulaire $\Delta$ | $60^\circ$ | $100^\circ$ | $110^\circ$ | $130^\circ$ | $150^\circ$ | $170^\circ$ |
|---|---|---|---|---|---|---|
| Ondes P directes | oui | oui | non | non | oui | oui |
| Ondes S | oui | oui | non | non | non | non |

**Document 2 : observation de Lehmann (1936)**

Dans la zone où aucune onde P directe n'est attendue (entre $103^\circ$ et $142^\circ$), on enregistre pourtant de **faibles ondes P**, dont l'arrivée est nette et ne correspond à aucun trajet traversant uniquement le noyau externe. Ces ondes sont compatibles avec une **réflexion** sur une surface située à $\approx 5150\ \text{km}$ de profondeur.

**Document 3 : vitesses des ondes de volume**

$$V_P = \sqrt{\dfrac{K + \frac43\mu}{\rho}} \qquad V_S = \sqrt{\dfrac{\mu}{\rho}}$$

où $\mu$ est la rigidité du milieu. Un liquide a $\mu = 0$.

**Barème indicatif :** exploitation du document 1 (3 pts) ; exploitation du document 3 (2 pts) ; exploitation du document 2 (3 pts) ; structure et conclusion (2 pts).

??? success "Corrigé et réponse modèle"
    **Attendus**

    1. **Doc 1** : les ondes S sont enregistrées jusqu'à $100^\circ$ mais **jamais** à partir de $110^\circ$ ; les ondes P sont absentes entre $110^\circ$ et $130^\circ$ puis réapparaissent à $150^\circ$ et $170^\circ$. La zone d'ombre des P est liée à la **déviation** des ondes qui traversent une enveloppe à vitesse différente.
    2. **Doc 3** : si $\mu = 0$, $V_S = 0$ : une enveloppe qui n'est pas traversée par les ondes S est **liquide**.
    3. **Doc 2** : des ondes P sont **réfléchies** à $5150\ \text{km}$ : il existe une surface où la vitesse **augmente brusquement**, donc un **changement d'état** : la graine **solide**.
    4. **Conclusion** : le noyau est composé d'une **partie externe liquide** (à partir de $\approx 2900\ \text{km}$) et d'une **graine solide** (à partir de $\approx 5150\ \text{km}$).

    **Réponse modèle rédigée**

    > Le document 1 montre que les ondes S sont enregistrées jusqu'à $100^\circ$ de distance angulaire mais jamais au-delà, alors que les ondes P disparaissent entre $110^\circ$ et $130^\circ$ puis réapparaissent à partir de $150^\circ$. D'après le document 3, les ondes S ne se propagent pas dans un milieu de rigidité nulle ($V_S = 0$ si $\mu = 0$), c'est-à-dire un liquide. L'absence d'ondes S au-delà de $103^\circ$ indique donc que les ondes ont rencontré une enveloppe liquide, le noyau externe, dont la limite se situe à environ $2900\ \text{km}$. La déviation des ondes P à son entrée explique leur zone d'ombre. D'autre part, le document 2 révèle de faibles ondes P dans cette zone d'ombre, compatibles avec une réflexion à $5150\ \text{km}$ : une augmentation brusque de vitesse signe un changement d'état, vers une graine solide. Le noyau est donc composé d'un noyau externe liquide et d'un noyau interne solide.

    !!! warning "Erreurs sanctionnées"
        - Écrire que les S sont « absorbées » ou « bloquées ».
        - Attribuer la zone d'ombre à l'**absorption** au lieu de la **réfraction**.
        - Ne pas citer de **valeurs** des documents ($100^\circ$, $110^\circ$, $5150\ \text{km}$…).
        - Oublier de conclure sur **les deux** points demandés (liquide **et** solide).

---

### Exercice 8 : Exploiter le modèle PREM (10 points)

**Document : extraits du modèle PREM**

| Profondeur $z$ (km) | $V_P$ (km·s⁻¹) | $V_S$ (km·s⁻¹) | $\rho$ (g·cm⁻³) |
|---|---|---|---|
| $15$ | $6{,}8$ | $3{,}9$ | $2{,}9$ |
| $100$ | $8{,}1$ | $4{,}5$ | $3{,}38$ |
| $2800$ | $13{,}7$ | $7{,}3$ | $5{,}5$ |
| $3000$ | $8{,}1$ | $0$ | $10{,}0$ |
| $5500$ | $11{,}1$ | $3{,}5$ | $12{,}9$ |

**Formules :** $\mu = \rho V_S^2$ et $K = \rho\left(V_P^2 - \frac43 V_S^2\right)$ (unités SI).

**Questions**

1. Identifier, entre quelles lignes se trouvent **deux discontinuités majeures**, et les nommer. (2 pts)
2. Calculer $\mu$ à $2800\ \text{km}$ et à $3000\ \text{km}$ ; interpréter. (3 pts)
3. Calculer $K$ à $2800$ et à $3000\ \text{km}$. (2 pts)
4. Le $V_P$ **chute** à $2900\ \text{km}$ alors que $\rho$ **augmente** : expliquer à l'aide des résultats. (2 pts)
5. Citer **une limite** du modèle PREM. (1 pt)

??? success "Corrigé"
    **1.** Entre $2800$ et $3000\ \text{km}$ : **discontinuité de Gutenberg** ($\approx 2900\ \text{km}$), où $V_S$ tombe à $0$ et $V_P$ chute. Entre $3000$ et $5500\ \text{km}$ : **discontinuité de Lehmann** ($\approx 5150\ \text{km}$), où $V_S$ redevient non nul et $V_P$ augmente. (La limite croûte/manteau, le **Moho**, se trouve entre $15$ et $100\ \text{km}$.)

    **2.**

    - À $2800\ \text{km}$ : $\mu = 5500 \times (7300)^2 = 5500\times5{,}329\times10^{7} \approx 2{,}9\times10^{11}\ \text{Pa} \approx 293\ \text{GPa}$.
    - À $3000\ \text{km}$ : $\mu = 10000 \times 0^2 = 0$.

    La rigidité devient **nulle** : le milieu à $3000\ \text{km}$ est un **liquide**.

    **3.**

    - À $2800\ \text{km}$ : $K = 5500\,(13700^2 - \tfrac43\times7300^2) = 5500\,(1{,}877\times10^{8} - 7{,}105\times10^{7}) \approx 5500\times1{,}166\times10^{8} \approx 6{,}4\times10^{11}\ \text{Pa} \approx 641\ \text{GPa}$.
    - À $3000\ \text{km}$ : $K = 10000\times 8100^2 = 10000\times6{,}561\times10^{7} \approx 6{,}6\times10^{11}\ \text{Pa} \approx 656\ \text{GPa}$.

    **4.** $K$ varie très peu ($\approx 641$ puis $\approx 656\ \text{GPa}$). Mais le terme $\frac43\mu$ ($\approx 391\ \text{GPa}$) **disparaît** et $\rho$ presque **double** ($5{,}5$ puis $10{,}0$). Comme $V_P = \sqrt{(K+\frac43\mu)/\rho}$, le numérateur chute de $\approx 1032$ à $\approx 656\ \text{GPa}$ alors que le dénominateur augmente : $V_P$ **diminue**. La vitesse dépend de **trois grandeurs** à la fois.

    **5.** Le PREM est un **modèle 1D** : il **ne montre pas les variations latérales** (hétérogénéités, convection) ; il ne donne pas la **composition**.

    !!! warning "Piège"
        Convertir les **unités** : $3{,}38\ \text{g·cm}^{-3} = 3380\ \text{kg·m}^{-3}$ et $8{,}1\ \text{km·s}^{-1} = 8100\ \text{m·s}^{-1}$. Oublier ces conversions donne des résultats faux d'un facteur $10^3$ ou $10^6$.
