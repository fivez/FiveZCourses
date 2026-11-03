# Solutions colorées et dosage par étalonnage

!!! abstract "En une phrase"
    Une solution colorée **absorbe** certaines radiations de la lumière blanche ; la quantité de lumière absorbée, mesurée par l'**absorbance** $A$, est **proportionnelle à la concentration** de l'espèce colorée (loi de Beer-Lambert). On exploite cette proportionnalité pour **doser** une espèce par étalonnage.

## Objectifs pédagogiques et compétences

À l'issue de ce chapitre, vous devez être capable de :

- **Expliquer** l'origine de la couleur d'une solution à partir de son spectre d'absorption et du cercle chromatique ;
- **Définir** et **calculer** l'absorbance $A(\lambda)$ et la transmittance $T(\lambda)$ ;
- **Décrire** le principe et le protocole d'utilisation d'un spectrophotomètre ;
- **Identifier** les facteurs qui influencent l'absorbance et raisonner « toutes choses égales par ailleurs » ;
- **Énoncer**, **justifier** et **utiliser** la loi de Beer-Lambert, en connaissant précisément son domaine de validité ;
- **Distinguer** un spectre d'absorption $A=f(\lambda)$ d'une courbe d'étalonnage $A=f(c)$ ;
- **Réaliser** un dosage par étalonnage : choix de $\lambda_{max}$, préparation d'une gamme par dilution, tracé de la droite d'étalonnage, détermination d'une concentration inconnue (par le calcul **et** par lecture graphique) ;
- **Porter un regard critique** sur un protocole et sur un résultat (domaine de validité, erreurs systématiques).

Compétences de la démarche scientifique mobilisées : *s'approprier*, *analyser*, *réaliser*, *valider*, *communiquer*.

## Prérequis

!!! info "À maîtriser avant de commencer"
    - **Lumière** : spectre de la lumière blanche, longueur d'onde $\lambda$ (en nm), domaine visible approximativement de 400 à 800 nm.
    - **Quantité de matière et concentration** : $n = c \times V$, concentration molaire $c$ (mol·L⁻¹) et massique $t$ (g·L⁻¹), $t = c \times M$.
    - **Dilution** : conservation de la quantité de matière de soluté, verrerie jaugée.
    - **Fonction logarithme décimal** : $\log(10^x)=x$, $\log(ab)=\log a+\log b$, $\log\frac1x=-\log x$.
    - **Proportionnalité et fonctions linéaires** : droite passant par l'origine, coefficient directeur.
    - **Énergie d'un photon** : $E = h\nu = \dfrac{hc}{\lambda}$.

## Plan du chapitre

| Fichier | Contenu |
|---|---|
| [1. D'où vient la couleur d'une solution ?](01-solution-coloree.md) | Lumière blanche, absorption, couleurs complémentaires |
| [2. L'absorbance](02-absorbance.md) | Définition de $A(\lambda)$, transmittance, calculs |
| [3. Le spectrophotomètre](03-spectrophotometre.md) | Principe, schéma, protocole de mesure |
| [4. Facteurs influençant l'absorbance](04-facteurs-absorbance.md) | $\lambda$, $c$, $\ell$, nature, solvant, pH… |
| [5. Loi de Beer-Lambert](05-loi-beer-lambert.md) | Énoncé, démonstration, limites |
| [6. Spectre d'absorption et courbe d'étalonnage](06-spectre-et-etalonnage.md) | Les deux courbes, ce qu'elles disent |
| [7. Réaliser un dosage par spectrophotométrie](07-dosage-spectrophotometrie.md) | $\lambda_{max}$, gamme, droite, $c_x$ |
| [8. Exercices progressifs](08-exercices-progressifs.md) | 8 exercices corrigés (repliables) |
| [9. Exercices type contrôle](09-exercices-controle.md) | 3 exercices, corrigés masqués |
| [10. Synthèse et fiche de révision](10-synthese-fiche-revision.md) | À savoir par cœur |
| [11. Comprendre, savoir quand l'utiliser, savoir démontrer](11-comprendre-pourquoi.md) | Le « pourquoi » de chaque résultat |

## Conventions des encadrés

!!! info "Définition"
    Encadré bleu : ce qu'il faut connaître **mot pour mot**.

!!! success "Propriété"
    Encadré vert : résultat à savoir **utiliser** (et souvent **démontrer**).

!!! tip "Méthode"
    Encadré turquoise : marche à suivre à appliquer **systématiquement**.

!!! warning "Point d'attention"
    Encadré orange : subtilité, cas particulier, condition de validité.

!!! failure "Erreur fréquente"
    Encadré rouge : faute classique, à éviter à tout prix.

!!! example "Exemple"
    Encadré violet : application directe et corrigée.

??? question "Exercice ou question (repliable)"
    Les **corrigés** sont toujours repliés : cherchez d'abord, **puis** déroulez.

!!! note "Comment travailler ce chapitre"
    1. Lisez le cours section par section, **crayon en main** : refaites chaque exemple sans regarder la solution.
    2. Traitez les exercices progressifs dans l'ordre. Ne consultez le corrigé qu'après une vraie tentative.
    3. Chronométrez-vous sur les exercices type contrôle (environ 1 h pour l'ensemble).
    4. Terminez par la fiche de révision, puis réécrivez de mémoire les démonstrations de la section 11.
