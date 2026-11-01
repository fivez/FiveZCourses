# 8. Exercices de synthèse — Solutions colorées

Les exercices ci-dessous sont conçus pour un entraînement exigeant. Les corrections sont repliables : traite chaque problème intégralement avant de les ouvrir.

## Exercice 1 — Dosage avec droite affine et dilution

Une espèce colorée est dosée par spectrophotométrie. Les mesures des étalons, réalisées à la longueur d'onde de travail, conduisent à la droite :
$$
A=(2{,}15\\times10^4)C+0{,}008
$$
où $C$ est exprimée en $\\text{mol}\\,\\text{L}^{-1}$.

Une solution commerciale est diluée en prélevant $10{,}0\\,\\text{mL}$ puis en complétant à $100{,}0\\,\\text{mL}$. L'absorbance de la solution diluée est $0{,}438$.

1. Déterminer la concentration de la solution diluée.
2. Déterminer la concentration de la solution commerciale.
3. La gamme étalon couvre les concentrations de $5{,}0\\times10^{-6}$ à $2{,}0\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$. Le dosage est-il réalisé dans la gamme ? Justifier.
4. Expliquer pourquoi il serait incorrect de comparer directement $0{,}438$ à la droite si la solution avait été mesurée à une autre longueur d'onde.

??? success "Correction détaillée"
    **1. Concentration diluée**

    $$
    C_d=\\frac{A-b}{a}
    =\\frac{0{,}438-0{,}008}{2{,}15\\times10^4}
    $$
    $$
    \\boxed{C_d=2{,}00\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}}
    $$

    **2. Concentration initiale**

    $$
    F=\\frac{V_f}{V_m}=\\frac{100{,}0}{10{,}0}=10{,}0
    $$
    $$
    C_i=FC_d=2{,}00\\times10^{-4}\\,\\text{mol}\\,\\text{L}^{-1}
    $$

    **3. Validité de la gamme**

    $C_d=2{,}00\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$ est exactement à la limite supérieure de la gamme. Le résultat est exploitable à cette limite, mais il est préférable, si l'incertitude ou la dispersion des mesures est importante, de refaire une dilution un peu plus forte afin de placer la mesure à l'intérieur de la gamme.

    **4. Longueur d'onde**

    La pente dépend de la longueur d'onde, car le coefficient d'absorption molaire dépend de $\\lambda$. Une droite établie à une longueur d'onde ne peut pas être utilisée telle quelle à une autre longueur d'onde.

## Exercice 2 — Exploitation critique d'une gamme étalon

On mesure les absorbances suivantes :

| $C$ ($10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$) | 0,00 | 0,50 | 1,00 | 1,50 | 2,00 | 2,50 |
|---:|---:|---:|---:|---:|---:|---:|
| $A$ | 0,010 | 0,112 | 0,211 | 0,313 | 0,411 | 0,620 |

Une solution inconnue présente $A=0{,}365$.

1. Les cinq premiers points sont-ils compatibles avec une relation affine ?
2. Le dernier point semble-t-il compatible avec la tendance des cinq premiers ? Justifier quantitativement.
3. Estimer l'équation de la droite à partir des cinq premiers points, en utilisant les deux points extrêmes de cette sous-série.
4. En déduire la concentration de la solution inconnue.
5. Citer deux causes expérimentales possibles d'un point aberrant.

??? success "Correction détaillée"
    **1. Analyse de la linéarité**

    Pour les cinq premiers points, l'absorbance augmente d'environ $0{,}10$ lorsque la concentration augmente de $0{,}50\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$. Les accroissements sont proches : les points sont compatibles avec une relation affine.

    **2. Contrôle du dernier point**

    À $C=2{,}50\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$, la tendance des premiers points prévoit environ $A=0{,}51$. La mesure $0{,}620$ s'en écarte nettement. Elle doit être vérifiée et ne doit pas être intégrée sans analyse à l'ajustement.

    **3. Droite estimée**

    Avec les points $(0;0{,}010)$ et $(2{,}00\\times10^{-5};0{,}411)$ :
    $$
    a=\\frac{0{,}411-0{,}010}{2{,}00\\times10^{-5}}
    =2{,}005\\times10^4\\,\\text{L}\\,\\text{mol}^{-1}
    $$
    On retient $A\\approx2{,}01\\times10^4 C+0{,}010$.

    **4. Concentration inconnue**
    $$
    C=\\frac{0{,}365-0{,}010}{2{,}005\\times10^4}
    \\approx1{,}77\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}
    $$

    **5. Causes possibles**

    Cuve sale ou mal orientée, bulle, erreur de préparation, erreur de pipetage, mauvais blanc, longueur d'onde incorrecte ou mesure faite hors du domaine de linéarité.

## Exercice 3 — Problème de synthèse : choisir la stratégie de dilution

Une solution inconnue est susceptible d'avoir une concentration comprise entre $10^{-4}$ et $10^{-3}\\,\\text{mol}\\,\\text{L}^{-1}$. La droite d'étalonnage est valide entre $2{,}0\\times10^{-6}$ et $2{,}0\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$.

On souhaite obtenir une absorbance comprise dans la gamme étalon. On peut effectuer une dilution au dixième ou au cinquantième.

1. Montrer qu'une dilution au dixième ne garantit pas que la solution soit dans la gamme.
2. Déterminer si une dilution au cinquantième garantit la gamme pour toute concentration initiale de l'intervalle.
3. Proposer une stratégie expérimentale prudente.

??? success "Correction détaillée"
    **1. Dilution au dixième**

    La concentration diluée serait comprise entre $10^{-5}$ et $10^{-4}\\,\\text{mol}\\,\\text{L}^{-1}$. La borne supérieure dépasse $2{,}0\\times10^{-5}$ : la gamme n'est pas garantie.

    **2. Dilution au cinquantième**

    La concentration diluée serait comprise entre :
    $$
    \\frac{10^{-4}}{50}=2{,}0\\times10^{-6}
    $$
    et
    $$
    \\frac{10^{-3}}{50}=2{,}0\\times10^{-5}
    $$
    Elle se trouve exactement dans la gamme, bornes comprises.

    **3. Stratégie**

    Une dilution au cinquantième est théoriquement adaptée à l'intervalle annoncé. En pratique, on peut réaliser une première mesure de reconnaissance, vérifier que l'absorbance est dans la gamme, puis refaire la mesure avec une dilution ajustée et des répétitions si nécessaire. Il faut documenter précisément les volumes utilisés.
