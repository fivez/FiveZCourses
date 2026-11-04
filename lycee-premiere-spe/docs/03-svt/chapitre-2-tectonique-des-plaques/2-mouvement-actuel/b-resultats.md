# B. Résultats : vitesses et mouvements des plaques

## 1. Résultat n° 1 : les plaques se déplacent, et elles sont rigides

!!! abstract "Résultats des mesures de géodésie"
    - Les stations GPS **se déplacent** de façon **régulière** dans le temps : la série temporelle est une **droite**.
    - Les stations situées **sur une même plaque**, **loin des limites**, ont des **vitesses quasi identiques** : la **distance** entre elles ne varie presque pas (au plus **quelques mm·an⁻¹**). La plaque est donc **rigide**.
    - Les stations situées **de part et d'autre d'une limite** ont des vitesses **différentes** : leur **distance varie**. La **déformation** se **concentre** à la limite.

!!! tip "Comment le montrer"
    Pour deux stations A et B :

    - **même plaque** : $\dfrac{\Delta d_{AB}}{\Delta t} \approx 0$ ;
    - **plaques différentes** : $\dfrac{\Delta d_{AB}}{\Delta t} = v_{\text{relative}} \neq 0$.

## 2. Résultat n° 2 : des vitesses de l'ordre du centimètre par an

!!! abstract "Ordres de grandeur à connaître"
    Les vitesses de plaques vont de **$\approx 1$ à $\approx 10\ \text{cm·an}^{-1}$** (quelques valeurs jusqu'à $15$ ou plus), c'est-à-dire **$10$ à $100\ \text{km·Ma}^{-1}$**, comparables à la **croissance des ongles** ($\approx 3\ \text{cm·an}^{-1}$).

### 2.1 Vitesses relatives (ouverture ou fermeture)

| Limite | Vitesse relative approximative |
|---|---|
| Dorsale **médio-atlantique** | $\approx 2$ à $3\ \text{cm·an}^{-1}$ |
| Dorsale **est-Pacifique** (Pacifique-Nazca) | **$\approx 10$ à $15\ \text{cm·an}^{-1}$** (la plus rapide) |
| Dorsale **indienne** | $\approx 3$ à $6\ \text{cm·an}^{-1}$ |
| **Inde - Eurasie** (collision) | $\approx 4$ à $5\ \text{cm·an}^{-1}$ |
| **Nazca - Amérique du Sud** (subduction) | $\approx 7$ à $8\ \text{cm·an}^{-1}$ |
| **Afrique - Eurasie** | $\approx 0{,}5$ à $1\ \text{cm·an}^{-1}$ |
| **Pacifique - Amérique du Nord** (San Andreas) | $\approx 4$ à $5\ \text{cm·an}^{-1}$ |

### 2.2 Vitesses absolues (référentiel des points chauds)

| Plaque | Vitesse absolue approximative | Direction approximative |
|---|---|---|
| **Pacifique** | $\approx 7$ à $10\ \text{cm·an}^{-1}$ | nord-ouest |
| **Nazca** | $\approx 4$ à $7\ \text{cm·an}^{-1}$ | est |
| **Inde-Australie** | $\approx 5$ à $6\ \text{cm·an}^{-1}$ | nord-est |
| **Afrique** | $\approx 2$ à $3\ \text{cm·an}^{-1}$ | nord-est |
| **Amérique du Nord** | $\approx 1$ à $2\ \text{cm·an}^{-1}$ | sud-ouest |
| **Eurasie** | $\approx 1\ \text{cm·an}^{-1}$ | est-sud-est |
| **Amérique du Sud** | $\approx 1$ à $2\ \text{cm·an}^{-1}$ | ouest-nord-ouest |
| **Antarctique** | $\approx 1\ \text{cm·an}^{-1}$ | faible |

!!! note "Précision"
    Ces valeurs sont des **ordres de grandeur** arrondis : elles varient d'un modèle à l'autre et selon l'endroit. En contrôle, les **valeurs sont fournies** ; ce qui est attendu, c'est de **savoir les lire**.

!!! info "Observation remarquable"
    Les plaques les **plus rapides** (Pacifique, Nazca, Inde) sont celles dont une **grande partie du bord** est une **zone de subduction** : la **plaque plongeante** y participe à l'**entraînement** de la plaque (lien avec la **convection** du chapitre 1).

## 3. Résultat n° 3 : un bilan de surface équilibré

!!! abstract "Création et destruction de lithosphère"
    - Aux **dorsales** (longueur cumulée $\approx 60\,000\ \text{km}$), de la lithosphère océanique **se crée** à raison d'environ **$3\ \text{km}^2\text{·an}^{-1}$**.
    - Aux **zones de subduction**, une **surface équivalente** est **détruite**.

    **La surface de la Terre reste constante** : la Terre **n'est pas en expansion**.

!!! example "Exemple corrigé : ordre de grandeur"
    Les dorsales ont une longueur de $60\,000\ \text{km}$ et un taux d'ouverture moyen de $5\ \text{cm·an}^{-1}$. Calculer la surface créée par an, puis la durée de renouvellement de l'ensemble des fonds océaniques ($3{,}6\times10^{8}\ \text{km}^2$).

??? success "Corrigé"
    $5\ \text{cm·an}^{-1} = 5\times10^{-5}\ \text{km·an}^{-1}$.

    Surface créée : $60\,000\times5\times10^{-5} = 3{,}0\ \text{km}^2\text{·an}^{-1}$.

    Durée de renouvellement : $\dfrac{3{,}6\times10^{8}}{3{,}0} = 1{,}2\times10^{8}\ \text{ans} = 120\ \text{Ma}$.

    **Cohérence** : cet ordre de grandeur est compatible avec l'**âge maximal** de la croûte océanique ($\approx 180\ \text{Ma}$) : les fonds océaniques sont **renouvelés** en **quelques dizaines à une centaine de Ma**.

## 4. Lecture d'une carte de vecteurs vitesse

!!! tip "Méthode : exploiter une carte de vecteurs GPS"
    1. Repérer l'**échelle** des flèches (par exemple $1\ \text{cm} = 5\ \text{cm·an}^{-1}$) et le **référentiel** utilisé.
    2. **Mesurer la longueur** des flèches pour en déduire la **vitesse**.
    3. Regarder la **direction** relativement à la **limite** :
        - flèches **divergentes** de part et d'autre : limite **divergente** ;
        - flèches **convergentes** : limite **convergente** ;
        - flèches **parallèles** de sens opposés : limite **coulissante**.
    4. Repérer les **flèches identiques** dans une même zone : **plaque rigide**.
    5. **Conclure**, en rappelant le **référentiel**.

## 5. Cohérence avec le passé

!!! abstract "Une vitesse stable sur des millions d'années ?"
    Les vitesses mesurées **aujourd'hui** par GPS (sur quelques années) sont **cohérentes** avec les vitesses **moyennes** déduites des **archives géologiques** (partie 3) sur **des millions d'années** : le **mouvement des plaques est donc un phénomène durable**, pas un épisode transitoire.

## 6. Points d'attention de cette section

!!! warning "Erreurs fréquentes"
    - Écrire « l'Atlantique s'ouvre de $2{,}5\ \text{cm}$ » **sans unité de temps** : **par an**.
    - Dire que les plaques « avancent » **toutes dans le même sens** : leurs directions **divergent**.
    - Confondre **vitesse relative** à une dorsale ($\approx 2$ à $3\ \text{cm·an}^{-1}$, **somme** des deux demi-vitesses) et **vitesse absolue** de chaque plaque.
    - Attribuer à **toute** la plaque **la vitesse d'une station proche d'une limite** (déformation locale).
    - Oublier que la **vitesse du Pacifique** est **plus élevée** que celle de l'Atlantique.
    - Dire que la Terre « grossit » ou « rétrécit » : l'**équilibre** création / destruction maintient sa surface.
