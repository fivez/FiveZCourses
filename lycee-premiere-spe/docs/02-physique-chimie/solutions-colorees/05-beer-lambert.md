# 5. Loi de Beer-Lambert

## Objectifs

Énoncer la loi, identifier ses paramètres, exploiter une relation de proportionnalité et discuter ses limites.

## Prérequis

Proportionnalité, concentration molaire, unités et lecture d'une droite.

## Propriété

!!! propriete "Loi de Beer-Lambert"
    Pour une espèce absorbante, à une longueur d'onde fixée et dans les conditions où la loi est vérifiée :
    $$
    A(\\lambda)=\\varepsilon(\\lambda)\\,\\ell\\,C
    $$
    À espèce, longueur d'onde et longueur de cuve fixées, on écrit :
    $$
    \\boxed{A=aC}
    $$
    L'absorbance est alors proportionnelle à la concentration.

- $A$ : absorbance, sans unité ;
- $\\varepsilon(\\lambda)$ : coefficient d'absorption molaire ;
- $\\ell$ : longueur du trajet optique ;
- $C$ : concentration en quantité de matière.

Les unités doivent être cohérentes. Par exemple, si $C$ est en $\\text{mol}\\,\\text{L}^{-1}$ et $\\ell$ en cm, $\\varepsilon$ peut être exprimé en $\\text{L}\\,\\text{mol}^{-1}\\,\\text{cm}^{-1}$.

## Démonstration et interprétation

Dans un domaine expérimental adapté, chaque couche traversée absorbe une fraction de la lumière. L'atténuation globale dépend de la quantité d'espèce absorbante rencontrée sur le trajet optique. La loi de Beer-Lambert traduit le fait que l'absorbance est proportionnelle à la concentration et à la longueur traversée.

Pour un protocole donné, le produit $\\varepsilon\\ell$ est constant. On pose donc $a=\\varepsilon\\ell$, d'où $A=aC$.

La représentation de $A$ en fonction de $C$ est une droite passant idéalement par l'origine.

## Exemple corrigé

Une solution de concentration $C_1=2{,}0\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}$ présente une absorbance $A_1=0{,}36$.

Déterminer la concentration d'une solution de même espèce mesurée dans les mêmes conditions et présentant $A_2=0{,}63$.

Par proportionnalité :
$$
\\frac{A_1}{C_1}=\\frac{A_2}{C_2}
$$
$$
C_2=C_1\\frac{A_2}{A_1}
=2{,}0\\times10^{-5}\\times\\frac{0{,}63}{0{,}36}
$$
$$
\\boxed{C_2=3{,}5\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}}
$$

## Limites et précautions

La loi n'est exploitable que dans un domaine de concentration adapté et pour des conditions chimiques et instrumentales maîtrisées. Des concentrations trop élevées, des interactions entre espèces, une modification de l'équilibre chimique ou des limites instrumentales peuvent provoquer des écarts à la linéarité.

!!! attention "Une droite n'est pas une vérité universelle"
    Ne prolonge pas automatiquement une droite d'étalonnage au-delà de la gamme mesurée. Une solution inconnue trop concentrée doit généralement être diluée pour que son absorbance se situe dans la gamme des étalons.

## Méthodes à maîtriser

- Si $A=aC$, alors $C=A/a$.
- Si la droite est $A=aC+b$, alors $C=(A-b)/a$.
- Vérifier que l'inconnue est dans la gamme d'étalonnage.
- Contrôler les unités de la pente et de la concentration.

## Exercice progressif

Une droite d'étalonnage a pour équation $A=1{,}80\\times10^4 C+0{,}015$, avec $C$ en $\\text{mol}\\,\\text{L}^{-1}$. Une solution donne $A=0{,}555$. Calculer $C$.

??? success "Correction"
    $$
    C=\\frac{A-0{,}015}{1{,}80\\times10^4}
    =\\frac{0{,}540}{1{,}80\\times10^4}
    $$
    $$
    \\boxed{C=3{,}00\\times10^{-5}\\,\\text{mol}\\,\\text{L}^{-1}}
    $$
