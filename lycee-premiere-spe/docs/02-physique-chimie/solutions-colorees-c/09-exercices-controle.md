# 9. Exercices type contrôle

!!! tip "Conditions de contrôle"
    **Durée : 1 h** pour l'ensemble. **Calculatrice autorisée.** Barème indicatif sur 20. Rédigez **comme en contrôle** : formule littérale, application numérique avec unité, chiffres significatifs cohérents, phrase de conclusion. Dépliez les corrigés **après** avoir terminé.

---

## Exercice A : dosage des ions cuivre(II) (8 points)

Une solution aqueuse de sulfate de cuivre(II) est **bleue**. On souhaite déterminer la concentration d'une solution $S_x$ en ions $\text{Cu}^{2+}$ par spectrophotométrie. On dispose d'une solution mère $S_0$ de concentration $c_0=0{,}100$ mol·L⁻¹, de fioles jaugées de 50,0 mL et de cuves de largeur 1,0 cm.

**Document : mesures à $\lambda=800$ nm** (blanc réalisé avec de l'eau distillée)

| Solution | $S_1$ | $S_2$ | $S_3$ | $S_4$ | $S_0$ |
|---|---|---|---|---|---|
| $c$ (mol·L⁻¹) | 0,020 | 0,040 | 0,060 | 0,080 | 0,100 |
| $A$ | 0,25 | 0,48 | 0,73 | 0,96 | 1,21 |

La solution $S_x$ est obtenue en diluant **2 fois** la solution commerciale $S_{com}$ (étiquette : $0{,}140$ mol·L⁻¹) ; on mesure $A_x=0{,}84$.

1. (1 pt) Quelle couleur la solution absorbe-t-elle principalement ? Justifier le choix de $\lambda=800$ nm.
2. (1,5 pt) Calculer les volumes de $S_0$ à prélever pour préparer 50,0 mL de $S_1$, $S_2$, $S_3$, $S_4$. Nommer la verrerie.
3. (2 pt) Montrer que la loi de Beer-Lambert est vérifiée et déterminer $k$. En déduire la valeur de $\varepsilon$ à 800 nm.
4. (2 pt) Déterminer la concentration de $S_x$ **par le calcul**, puis **par lecture graphique** (décrire la méthode).
5. (1 pt) En déduire la concentration de $S_{com}$. Calculer l'écart relatif avec l'étiquette.
6. (0,5 pt) Quelle masse de sulfate de cuivre pentahydraté ($M=249{,}7$ g·mol⁻¹) faut-il dissoudre pour préparer 250 mL de $S_0$ ?

??? success "Corrigé masqué"
    1. La solution est **bleue** : elle absorbe l'**orange-rouge** (complémentaire du bleu). On travaille à $\lambda_{max}\approx800$ nm (limite rouge/proche IR) car l'absorbance y est **maximale** : sensibilité et précision maximales, et erreurs de réglage de $\lambda$ sans effet notable.
    2. $V_0=\dfrac{c_iV}{c_0}$ avec $V=50{,}0$ mL : $S_1$ : $\dfrac{0{,}020\times50{,}0}{0{,}100}=10{,}0$ mL ; $S_2$ : **20,0 mL** ; $S_3$ : **30,0 mL** ; $S_4$ : **40,0 mL**. Verrerie : **pipette jaugée** (ou burette) pour prélever $V_0$, **fiole jaugée** de 50,0 mL.
    3. Rapports $A/c$ : $12{,}5\ ;\ 12{,}0\ ;\ 12{,}2\ ;\ 12{,}0\ ;\ 12{,}1$ L·mol⁻¹ : quasi constants. Les points sont alignés sur une droite passant par l'origine : **$A=kc$, la loi est vérifiée**. Modèle par l'origine : $k=\dfrac{\sum c_iA_i}{\sum c_i^2}=\dfrac{0{,}2658}{0{,}0220}=12{,}1$ L·mol⁻¹. Avec $\ell=1{,}0$ cm : $\varepsilon=\dfrac{k}{\ell}=12\ \text{L·mol}^{-1}\text{·cm}^{-1}$.
    4. *Calcul :* $c_x=\dfrac{A_x}{k}=\dfrac{0{,}84}{12{,}1}=6{,}9\times10^{-2}$ mol·L⁻¹ (valeur non arrondie : $0{,}0695$). *Graphique :* on repère $A_x=0{,}84$ en ordonnée, on trace l'horizontale jusqu'à la droite d'étalonnage, puis la verticale jusqu'à l'axe des abscisses : on lit $c_x\approx0{,}069$ mol·L⁻¹ (on laisse les traits de construction). $A_x$ est entre 0,73 et 0,96 : interpolation.
    5. $c_{com}=2\times c_x=2\times0{,}0695=0{,}139\approx0{,}14$ mol·L⁻¹. Écart relatif : $\dfrac{|0{,}140-0{,}139|}{0{,}140}\approx0{,}7\,\%$ : valeur **cohérente** avec l'étiquette.
    6. $n=c_0V=0{,}100\times0{,}250=2{,}50\times10^{-2}$ mol ; $m=nM=2{,}50\times10^{-2}\times249{,}7=6{,}24$ g.

---

## Exercice B : analyse critique d'un protocole (6 points)

Un élève doit doser le colorant bleu d'un sirop. Voici son compte rendu :

> *« Je prépare cinq solutions étalons de 0,50 à 2,00 mmol·L⁻¹ en prélevant la solution mère avec une éprouvette graduée. Je règle le spectrophotomètre sur 400 nm, car c'est le début du visible. Je ne fais pas le blanc (l'appareil affiche déjà 0,02 quand la cuve est vide). Je trace A en fonction de c en reliant les points par des segments. Je mesure le sirop **sans le diluer** : A = 2,35. Je lis sur ma courbe que c est très grand. »*

Mesures de l'élève : $c$ (mmol·L⁻¹) $=0{,}50\ ;\ 1{,}00\ ;\ 1{,}50\ ;\ 2{,}00$ ; $A=0{,}14\ ;\ 0{,}29\ ;\ 0{,}43\ ;\ 0{,}57$.

1. (2,5 pt) Relever **au moins cinq erreurs** de méthode et proposer pour chacune la correction.
2. (1 pt) Montrer que, pour ces étalons, $A$ est proportionnelle à $c$ et calculer $k$ (en L·mmol⁻¹).
3. (1,5 pt) Le professeur dilue le sirop **10 fois** : $A=0{,}26$. Déterminer la concentration du sirop. Comparer à la valeur obtenue par l'élève en prolongeant la droite ($c=A/k$ avec $A=2{,}35$).
4. (1 pt) Que révèle cette comparaison sur la validité de la loi pour la solution non diluée ?

??? success "Corrigé masqué"
    1. Erreurs et corrections :
        - **Éprouvette** pour prélever → utiliser **pipette jaugée** et **fiole jaugée** (précision).
        - **400 nm** choisi arbitrairement → tracer le **spectre** et travailler à **$\lambda_{max}$** (pour un colorant bleu, vers 600-640 nm).
        - **Blanc non fait** (affichage 0,02) → faire le blanc avec le solvant à la longueur d'onde utilisée.
        - Points **reliés par des segments** → **modéliser** par une droite (passant par l'origine) au plus près de tous les points.
        - Sirop **non dilué**, $A=2{,}35$ hors gamme (étalons : jusqu'à 0,57) → **diluer** pour que $A$ soit dans l'intervalle des étalons, et noter $F$.
        - (Bonus) Lecture sur le graphique par **extrapolation** : non fiable.
    2. $A/c$ : $0{,}28\ ;\ 0{,}29\ ;\ 0{,}287\ ;\ 0{,}285$ L·mmol⁻¹ : constant. $k=\dfrac{\sum c_iA_i}{\sum c_i^2}=\dfrac{2{,}145}{7{,}50}=0{,}286$ L·mmol⁻¹.
    3. Solution diluée : $c_{dil}=\dfrac{0{,}26}{0{,}286}=0{,}91$ mmol·L⁻¹ ; sirop : $c=10\times0{,}91=9{,}1$ mmol·L⁻¹. Valeur de l'élève : $\dfrac{2{,}35}{0{,}286}=8{,}2$ mmol·L⁻¹, soit **10 % de moins**.
    4. Si la loi était valable à $A=2{,}35$, on aurait trouvé la même valeur. Le désaccord montre que, pour la solution **concentrée**, $A$ est **inférieure** à la valeur linéaire : la loi n'est plus respectée (lumière parasite, fort $A$). D'où la nécessité de **diluer** pour rester dans le domaine de validité.

---

## Exercice C : transmittance, épaisseur et démonstration (6 points)

Une solution d'un colorant, placée dans une cuve de largeur $\ell=1{,}0$ cm, a une absorbance $A=0{,}70$ à la longueur d'onde de travail.

1. (1 pt) Calculer la transmittance $T$. Un élève affirme que « 70 % de la lumière est absorbée » : a-t-il raison ?
2. (1,5 pt) On remplace la cuve par une cuve de largeur 2,9 cm. Quelle est la nouvelle absorbance et la transmittance (à la même $c$) ?
3. (2 pt) **Démontrer** que lorsqu'on double la concentration, la transmittance est élevée **au carré**. Application numérique.
4. (1,5 pt) On ajoute dans la solution (concentration initiale inchangée) une seconde espèce, qui, **seule**, aurait une absorbance de 0,25 à la même longueur d'onde. Quelle est l'absorbance de la solution ? Quelle est $T$ ?

??? success "Corrigé masqué"
    1. $T=10^{-0{,}70}=0{,}20$ soit **20 %** transmis ; donc **80 %** absorbés. L'élève a tort : $A$ n'est pas un pourcentage.
    2. $A\propto\ell$ : $A'=0{,}70\times\dfrac{2{,}9}{1{,}0}=2{,}0$ ; $T'=10^{-2{,}0}=1{,}0\,\%$ (c'est l'épaisseur qui ne laisse passer que 1 % de la lumière).
    3. *Démonstration.* D'après Beer-Lambert, $A=\varepsilon\ell c$ et $T=10^{-A}=10^{-\varepsilon\ell c}$. Pour une concentration $2c$ : $T_2=10^{-\varepsilon\ell(2c)}=\left(10^{-\varepsilon\ell c}\right)^2=T^2$. $\blacksquare$
       Application : $T_2=(0{,}20)^2=0{,}040$ soit **4,0 %**. Vérification : $A_2=2\times0{,}70=1{,}40$ et $10^{-1{,}40}=0{,}040$ ✓.
    4. Les absorbances **s'ajoutent** : $A_{tot}=0{,}70+0{,}25=0{,}95$ ; $T=10^{-0{,}95}=0{,}11$, soit **11 %**. (À noter : $T_{tot}=T_1\times T_2=0{,}20\times0{,}56=0{,}11$.)

---

## Barème et auto-évaluation

| Exercice | Points | Compétences |
|---|---|---|
| A | 8 | Réaliser, analyser, valider (dosage complet) |
| B | 6 | Esprit critique, protocole, domaine de validité |
| C | 6 | Modèle, démonstration, additivité |

!!! warning "Les points qui font perdre le plus de points"
    Unités oubliées ($\ell$ en cm, $\lambda$ en m) ; facteur de dilution oublié ; absorbance confondue avec un pourcentage ; lecture graphique sans traits de construction ; extrapolation hors gamme sans commentaire ; conclusion absente.
