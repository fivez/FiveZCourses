# 2. Absorbance : définition et mesure

## Objectifs

Définir l'absorbance, la transmittance et interpréter leur relation.

## Prérequis

Savoir comparer deux intensités lumineuses et utiliser le logarithme décimal.

## Définitions et propriétés

!!! definition "Transmittance"
    La transmittance $T$ est le rapport entre l'intensité lumineuse transmise $I$ et l'intensité incidente $I_0$ :
    $$
    T=\frac{I}{I_0}
    $$
    Elle est sans unité et comprise entre 0 et 1 dans le modèle usuel.

!!! definition "Absorbance"
    L'absorbance $A(\lambda)$ caractérise l'atténuation d'une radiation de longueur d'onde $\lambda$ par un échantillon. Elle est sans unité :
    $$
    A(\lambda)=-\log(T)=\log\left(\frac{I_0}{I}\right)
    $$
    Le logarithme est décimal.

!!! propriete "Interprétation"
    À conditions identiques, plus l'absorbance est grande, plus la proportion de lumière transmise est faible.

## Cours détaillé

- $I_0$ désigne l'intensité incidente de la radiation choisie.
- $I$ désigne l'intensité transmise après traversée de l'échantillon.
- $T$ est la fraction de lumière transmise.
- $A$ est une grandeur sans dimension.

Si $I=I_0$, alors $T=1$ et $A=0$. Si $I<I_0$, alors $T<1$ et $A>0$.

### Exemple numérique

Si $I_0=100$ unités et $I=10$ unités :
$$
T=\frac{10}{100}=0{,}10
$$
$$
A=-\log(0{,}10)=1{,}00
$$

Si seulement 1 % de la lumière est transmise, $T=0{,}01$ et $A=2$.

## Méthode à maîtriser

Pour calculer l'absorbance :

1. identifier $I_0$ et $I$ ;
2. calculer $T=I/I_0$ ;
3. calculer $A=-\log(T)$ ;
4. vérifier que l'absorbance est sans unité.

!!! attention "Ne pas confondre absorbance et pourcentage de transmission"
    Une transmittance de 10 % signifie $T=0{,}10$, et non $T=10$. Il faut convertir le pourcentage en fraction avant de calculer le logarithme.

## Exercices progressifs

**Exercice 1.** Une cuve reçoit une intensité $I_0=250$ unités et transmet $I=50$ unités. Calculer $T$ puis $A$.

??? success "Correction"
    $T=50/250=0{,}20$.

    $A=-\log(0{,}20)\approx0{,}699$.

**Exercice 2.** Une solution présente une absorbance $A=1{,}30$. Déterminer la transmittance, puis le pourcentage de lumière transmis.

??? success "Correction"
    $A=-\log(T)$ donc $T=10^{-A}=10^{-1{,}30}\approx0{,}0501$.

    Le pourcentage transmis vaut environ $5{,}01\,\%$.

## Synthèse

$A$ augmente lorsque $I/I_0$ diminue. L'absorbance est une grandeur sans unité et dépend de la longueur d'onde utilisée.
