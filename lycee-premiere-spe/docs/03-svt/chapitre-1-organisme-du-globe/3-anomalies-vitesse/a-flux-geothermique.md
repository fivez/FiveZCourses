# A (suite). Le flux géothermique

## 1. Définition

!!! info "Définition : flux géothermique"
    Le **flux géothermique** (ou flux thermique, flux de chaleur) est la **quantité d'énergie thermique** qui traverse une **unité de surface** de la Terre **par unité de temps**. Il s'exprime en $\text{W·m}^{-2}$ (le plus souvent en $\text{mW·m}^{-2}$).

$$\varphi = \frac{P}{S} \qquad\text{avec } P \text{ la puissance thermique (W) et } S \text{ la surface (m}^2\text{)}$$

## 2. Relation avec le gradient

Dans la lithosphère, la chaleur est transportée par **conduction** : d'après la **loi de Fourier**, $\varphi = \lambda \dfrac{\Delta T}{\Delta z}$.

!!! example "Exemple corrigé"
    Dans une croûte continentale de conductivité $\lambda = 2{,}5\ \text{W·m}^{-1}\text{·K}^{-1}$, le gradient est de $30\ ^\circ\text{C·km}^{-1}$. Calculer le flux géothermique.

??? success "Corrigé"
    Conversion : $30\ ^\circ\text{C·km}^{-1} = 0{,}030\ \text{K·m}^{-1}$.

    $\varphi = 2{,}5 \times 0{,}030 = 0{,}075\ \text{W·m}^{-2} = 75\ \text{mW·m}^{-2}$.

    **Interprétation** : ce résultat est cohérent avec les mesures de flux sur les continents ($\approx 65\ \text{mW·m}^{-2}$). Un flux de $0{,}075\ \text{W·m}^{-2}$ signifie que chaque mètre carré dégage $0{,}075\ \text{J}$ par seconde.

    !!! warning "Piège évité"
        Il faut **convertir** les $^\circ\text{C·km}^{-1}$ en $\text{K·m}^{-1}$ : une variation de $1\ ^\circ\text{C}$ équivaut à $1\ \text{K}$, et $1\ \text{km} = 1000\ \text{m}$.

## 3. Valeurs de référence

| | Flux moyen |
|---|---|
| **Moyenne mondiale** | $\approx 87\ \text{mW·m}^{-2}$ |
| **Continents** | $\approx 65\ \text{mW·m}^{-2}$ |
| **Océans** | $\approx 100\ \text{mW·m}^{-2}$ |
| **Dorsales océaniques** | **jusqu'à plus de $200\ \text{mW·m}^{-2}$** (localement bien plus près des sources hydrothermales) |
| **Vieux boucliers continentaux** | $\approx 40$ à $50\ \text{mW·m}^{-2}$ |

!!! abstract "Puissance totale dissipée"
    En multipliant le flux moyen par la **surface du globe** ($S = 4\pi R_T^2 \approx 5{,}1\times10^{14}\ \text{m}^2$) :
    $$P \approx 0{,}087 \times 5{,}1\times10^{14} \approx 4{,}4\times10^{13}\ \text{W} \approx 44\ \text{TW}$$
    (les estimations les plus récentes avoisinent $47\ \text{TW}$.)

!!! info "Comparaison"
    Le flux géothermique moyen est **environ $4000$ fois plus faible** que l'énergie solaire moyenne reçue par la surface ($\approx 340\ \text{W·m}^{-2}$ à l'échelle du globe). Il est **négligeable** pour le climat, mais **déterminant** pour la **dynamique interne** de la planète.

## 4. Interprétation des variations de flux

!!! abstract "Pourquoi le flux est-il plus élevé aux dorsales ?"
    - Sous une **dorsale**, la **lithosphère est mince** et du **matériau chaud** du manteau **remonte** : l'isotherme $1300\ ^\circ\text{C}$ est **proche de la surface**, le gradient est **fort**, donc le **flux** aussi.
    - La **circulation d'eau** (hydrothermalisme) **évacue** en plus de la chaleur.

!!! abstract "Pourquoi le flux diminue-t-il en s'éloignant d'une dorsale ?"
    La lithosphère océanique **se refroidit** et **s'épaissit** avec l'**âge** : le gradient **diminue**, donc le flux aussi.

!!! abstract "Pourquoi le flux continental est-il plus faible que le flux océanique ?"
    - La **croûte continentale** est **épaisse** et **isolante**, mais elle **contient** beaucoup d'éléments radioactifs, qui produisent de la chaleur **dans la croûte** elle-même (environ **un tiers** du flux continental en vient).
    - Le **flux issu du manteau** est donc **plus faible** sous les continents anciens.

!!! warning "Points d'attention"
    - Le flux est **faible en valeur** ($\approx 0{,}087\ \text{W·m}^{-2}$) mais la **puissance totale** est **énorme** (**$\approx 44\ \text{TW}$**).
    - **Flux** (par m², en W·m⁻²) et **puissance** (totale, en W) sont **deux grandeurs distinctes**.
    - **Ne pas confondre** flux géothermique et **gradient** : le flux est $\lambda \times$ gradient.
    - **Lien avec la dynamique** : un flux **élevé** localisé indique une **remontée de matière chaude** ; il **signale** un **mouvement de convection**.

## 5. Bilan : la Terre perd de la chaleur

!!! abstract "Conclusion de la partie A"
    - La Terre **perd** en permanence de la chaleur ($\approx 44$ à $47\ \text{TW}$) : elle **se refroidit lentement**.
    - Cette chaleur vient de la **chaleur primordiale** et de la **radioactivité**.
    - Elle est évacuée par **conduction** dans la **lithosphère** et par **convection** dans le **manteau** et le noyau externe.
    - La **convection du manteau** doit être **vérifiée** : c'est le rôle de la **tomographie sismique** (partie B).
