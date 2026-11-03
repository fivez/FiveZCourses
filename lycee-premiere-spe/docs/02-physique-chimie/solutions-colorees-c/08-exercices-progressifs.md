# 8. Exercices progressifs

!!! tip "Comment utiliser cette page"
    Les exercices sont classés par **difficulté croissante**. Pour chacun : cherchez **seul**, rédigez sur papier, **puis** dépliez le corrigé. Les **pièges** sont signalés dans les corrigés par des encadrés orange ou rouges : relisez-les, ce sont les erreurs qui coûtent des points en contrôle.

    Constantes : $h=6{,}63\times10^{-34}$ J·s ; $c=3{,}00\times10^{8}$ m·s⁻¹ ; $1\ \text{eV}=1{,}60\times10^{-19}$ J.

---

## Exercice 1 : couleurs perçues et radiations absorbées ★

Le spectre d'absorption d'une solution aqueuse de permanganate de potassium présente un maximum à $\lambda_{max}=525$ nm.

1. Quelle est la couleur de la radiation absorbée au maximum ? En déduire la couleur de la solution.
2. Calculer l'énergie, en joules puis en eV, d'un photon de longueur d'onde 525 nm.
3. Une solution de sulfate de cuivre(II) est bleue. Quelle couleur absorbe-t-elle ?
4. Un extrait de feuille d'épinard est vert. Son spectre présente deux bandes d'absorption. Lesquelles peut-on prévoir ?
5. « Une solution incolore n'absorbe aucune lumière. » Critiquer cette affirmation.

??? success "Corrigé"
    1. 525 nm correspond au **vert**. La solution transmet le reste (rouge et bleu-violet) : elle est **violette / pourpre** (complémentaire du vert).
    2. $E=\dfrac{hc}{\lambda}=\dfrac{6{,}63\times10^{-34}\times3{,}00\times10^{8}}{525\times10^{-9}}=3{,}79\times10^{-19}$ J, soit $\dfrac{3{,}79\times10^{-19}}{1{,}60\times10^{-19}}=2{,}37$ eV.

        !!! warning "Point d'attention"
            $\lambda$ doit être converti en **mètres** : $525\ \text{nm}=525\times10^{-9}$ m. Oublier cette conversion donne un résultat faux d'un facteur $10^9$.
    3. Le bleu a pour complémentaire l'orange-rouge : la solution absorbe dans l'**orange-rouge** (vers 800 nm).
    4. Le vert est perçu quand le **bleu-violet** (~430-450 nm) et le **rouge** (~660-680 nm) sont absorbés : on attend **deux bandes**, l'une dans le bleu-violet, l'autre dans le rouge.
    5. **Faux.** Une solution incolore n'absorbe aucune radiation **visible**, mais elle peut absorber dans l'**UV** ou l'**IR**.

---

## Exercice 2 : absorbance et transmittance ★

Le « blanc » donne $I_0=800$ (unités arbitraires).

1. Une solution donne $I=200$. Calculer $T$ et $A$.
2. Une solution a pour absorbance $A=1{,}30$. Calculer $T$ puis $I$.
3. Pour $A=0{,}30$, quel pourcentage de la lumière est absorbé ?
4. Une solution a $A=2{,}0$. Quelle remarque faire sur la fiabilité de la mesure ?
5. Deux cuves identiques contenant la même solution sont placées l'une derrière l'autre dans le faisceau. Exprimer l'absorbance et la transmittance de l'ensemble en fonction de $A$ et $T$ d'une seule cuve.

??? success "Corrigé"
    1. $T=\dfrac{200}{800}=0{,}25$ (25 %) ; $A=\log\dfrac{800}{200}=\log4=2\log2=0{,}60$.
    2. $T=10^{-1{,}30}=0{,}0501\approx5{,}0\,\%$ ; $I=T\times I_0=0{,}0501\times800=40$.
    3. $T=10^{-0{,}30}\approx0{,}50$ : **50 %** transmis, donc **50 % absorbés**.

        !!! failure "Erreur fréquente"
            Penser que $A=0{,}30$ correspond à 30 % de lumière absorbée. L'absorbance **n'est pas** un pourcentage.
    4. $T=10^{-2}=1\,\%$ : le détecteur ne reçoit que 1 % de la lumière incidente. Le **bruit relatif** est grand, la lumière parasite devient non négligeable et la loi de Beer-Lambert n'est plus fiable : on **dilue** la solution.
    5. Transmittances : $T_{tot}=T\times T=T^2$ ; absorbances : $A_{tot}=-\log T^2=2A$. Cela illustre l'**additivité** de $A$ (équivalente à doubler $\ell$).

---

## Exercice 3 : exploiter la loi de Beer-Lambert ★★

À $\lambda_{max}$, le coefficient d'absorption molaire d'un colorant est $\varepsilon=2{,}0\times10^{3}$ L·mol⁻¹·cm⁻¹. On utilise une cuve de largeur $\ell=1{,}0$ cm.

1. Une solution a pour absorbance $A=0{,}40$. Calculer sa concentration $c$.
2. Quelle est l'absorbance de cette même solution dans une cuve de 5,0 mm ?
3. On dilue la solution initiale par 4 et on la place dans une cuve de 2,0 cm. Que vaut $A$ ?
4. Quelle est la transmittance de la solution de la question 1 ?
5. Quelle est la concentration maximale pour laquelle $A\le1{,}5$ avec la cuve de 1,0 cm ?
6. Un élève trouve $c=2{,}0\times10^{-5}$ mol·L⁻¹ à la question 1 car il a pris $\ell=10$ mm. Où est son erreur ?

??? success "Corrigé"
    1. $c=\dfrac{A}{\varepsilon\ell}=\dfrac{0{,}40}{2{,}0\times10^{3}\times1{,}0}=2{,}0\times10^{-4}$ mol·L⁻¹.
    2. $\ell'=5{,}0$ mm $=0{,}50$ cm (**conversion en cm !**) : $A'=A\times\dfrac{0{,}50}{1{,}0}=0{,}20$.
    3. $A''=A\times\dfrac{1}{4}\times\dfrac{2{,}0}{1{,}0}=0{,}40\times0{,}25\times2{,}0=0{,}20$.
    4. $T=10^{-0{,}40}=0{,}40$ soit **40 %**.
    5. $c_{max}=\dfrac{1{,}5}{2{,}0\times10^{3}\times1{,}0}=7{,}5\times10^{-4}$ mol·L⁻¹.
    6. Il a injecté $\ell=10$ dans une formule où $\varepsilon$ est en L·mol⁻¹·**cm**⁻¹ : $\ell$ doit être en **cm** ($1{,}0$ cm) et non en mm. Le résultat est faux d'un facteur 10.

        !!! warning "Réflexe"
            Faites toujours un **contrôle dimensionnel** : l'unité de $\varepsilon\,\ell\,c$ doit se simplifier en « rien ».

---

## Exercice 4 : dilutions et gamme étalon ★★

On dispose d'une solution mère $S_0$ de concentration $c_0=1{,}0\times10^{-2}$ mol·L⁻¹.

1. On veut 50,0 mL de solution à $c_1=2{,}0\times10^{-3}$ mol·L⁻¹. Calculer le facteur de dilution et le volume à prélever. Décrire le matériel et le protocole.
2. On prépare une gamme de cinq solutions de 100,0 mL, de concentrations $1{,}0\ ;\ 2{,}0\ ;\ 3{,}0\ ;\ 4{,}0\ ;\ 5{,}0\ (\times10^{-3}$ mol·L⁻¹). Calculer les volumes de $S_0$ à prélever.
3. On veut maintenant $1{,}0\times10^{-4}$ mol·L⁻¹ à partir de la solution à $2{,}0\times10^{-3}$ mol·L⁻¹ ; on ne dispose pas d'une pipette de 2,5 mL. Proposer une **dilution en deux étapes** (pipettes disponibles : 5,0 ; 10,0 ; 25,0 mL ; fioles : 50,0 et 100,0 mL).
4. Un élève prélève 10,0 mL de $S_0$ mais complète la fiole de 100,0 mL au lieu de 50,0 mL. Quelle concentration obtient-il ? Quelle conséquence sur l'absorbance attendue ?

??? success "Corrigé"
    1. $F=\dfrac{c_0}{c_1}=\dfrac{1{,}0\times10^{-2}}{2{,}0\times10^{-3}}=5{,}0$ ; $V_0=\dfrac{V_1}{F}=\dfrac{50{,}0}{5{,}0}=10{,}0$ mL.
       Protocole : **pipette jaugée de 10,0 mL** (rincée à $S_0$) et **fiole jaugée de 50,0 mL** ; verser les 10,0 mL dans la fiole avec un peu d'eau distillée, compléter aux trois quarts, agiter, ajuster au trait de jauge, boucher, homogénéiser.
    2. $V_0=\dfrac{c_iV}{c_0}=\dfrac{c_i\times100{,}0}{1{,}0\times10^{-2}}$ : **10,0 ; 20,0 ; 30,0 ; 40,0 ; 50,0 mL** ; pour les volumes non disponibles en pipette jaugée (30,0 ; 40,0 ; 50,0 mL), on utilise une **burette graduée** ou on combine des pipettes.
    3. $F=\dfrac{2{,}0\times10^{-3}}{1{,}0\times10^{-4}}=20=4\times5$.
       *Étape 1 :* 25,0 mL → fiole de 100,0 mL ($F=4$) : $5{,}0\times10^{-4}$ mol·L⁻¹.
       *Étape 2 :* 10,0 mL de cette solution → fiole de 50,0 mL ($F=5$) : $1{,}0\times10^{-4}$ mol·L⁻¹.
    4. $c=\dfrac{c_0V_0}{V}=\dfrac{1{,}0\times10^{-2}\times10{,}0}{100{,}0}=1{,}0\times10^{-3}$ mol·L⁻¹ au lieu de $2{,}0\times10^{-3}$ : **deux fois trop diluée**. L'absorbance mesurée sera **deux fois plus faible** que prévu, et le point de l'étalonnage sera mal placé (décalé vers l'abscisse $c$ faussement annoncée).

        !!! failure "Erreur fréquente"
            Des erreurs de verrerie fausseront **toute** la droite d'étalonnage et donc toutes les concentrations déduites. D'où l'utilisation systématique de verrerie **jaugée**.

---

## Exercice 5 : un dosage complet ★★★

Un colorant alimentaire de masse molaire $M=2{,}5\times10^{2}$ g·mol⁻¹ est dosé par spectrophotométrie à $\lambda_{max}$, cuve de 1,0 cm. Des étalons donnent :

| $c$ (mmol·L⁻¹) | 0,10 | 0,20 | 0,30 | 0,40 | 0,50 |
|---|---|---|---|---|---|
| $A$ | 0,12 | 0,25 | 0,36 | 0,49 | 0,60 |

Une boisson est **diluée 5 fois** ; la solution diluée a pour absorbance $A_x=0{,}42$.

1. Vérifier que les mesures sont compatibles avec la loi de Beer-Lambert et déterminer $k$.
2. Déterminer la concentration molaire $c_x$ du colorant dans la boisson, **par le calcul** puis **graphiquement**.
3. En déduire sa concentration massique. Le fabricant annonce $0{,}45$ g·L⁻¹ : calculer l'écart relatif.
4. Que se passe-t-il si l'élève oublie le facteur de dilution ?
5. Pourquoi est-il légitime de dire que $A_x$ est « dans la gamme » ?

??? success "Corrigé"
    1. Les rapports $A/c$ valent $1{,}20\ ;\ 1{,}25\ ;\ 1{,}20\ ;\ 1{,}23\ ;\ 1{,}20$ L·mmol⁻¹ : ils sont **quasi constants**, donc $A\propto c$ (droite passant par l'origine). Modèle par l'origine :
       $k=\dfrac{\sum c_iA_i}{\sum c_i^2}=\dfrac{0{,}666}{0{,}55}=1{,}21\ \text{L·mmol}^{-1}=1{,}21\times10^{3}\ \text{L·mol}^{-1}$.
    2. *Calcul :* $c_{dil}=\dfrac{A_x}{k}=\dfrac{0{,}42}{1{,}21}=0{,}347$ mmol·L⁻¹ ; la boisson est 5 fois plus concentrée : $c_x=5\times0{,}347=1{,}73$ mmol·L⁻¹ $=1{,}7\times10^{-3}$ mol·L⁻¹.
       *Graphique :* horizontale à $A=0{,}42$ ; elle coupe la droite à $c\approx0{,}35$ mmol·L⁻¹ ; on multiplie par 5.
    3. $t=c_xM=1{,}73\times10^{-3}\times2{,}5\times10^{2}=0{,}43$ g·L⁻¹. Écart relatif : $\dfrac{|0{,}45-0{,}43|}{0{,}45}\approx4\,\%$ : cohérent avec les incertitudes du protocole.
    4. Il trouverait $c=0{,}35$ mmol·L⁻¹, soit 5 fois trop faible : écart relatif de 80 % avec la valeur annoncée.
    5. Les étalons vont de $A=0{,}12$ à $0{,}60$ ; $A_x=0{,}42$ est **entre** les points $c=0{,}30$ ($A=0{,}36$) et $c=0{,}40$ ($A=0{,}49$) : on **interpole**, ce qui est fiable. Une extrapolation ne le serait pas.

---

## Exercice 6 : choisir la longueur d'onde de travail ★★★

On enregistre le spectre d'absorption d'une solution d'un colorant ($c=2{,}0\times10^{-4}$ mol·L⁻¹, $\ell=1{,}0$ cm) :

| $\lambda$ (nm) | 400 | 430 | 460 | 480 | 500 | 530 | 560 | 600 | 650 |
|---|---|---|---|---|---|---|---|---|---|
| $A$ | 0,10 | 0,36 | 0,72 | 0,82 | 0,66 | 0,30 | 0,10 | 0,03 | 0,01 |

1. Déterminer $\lambda_{max}$. Quelle est la couleur de la solution ?
2. Calculer $\varepsilon_{max}$.
3. On envisage de doser à 430 nm plutôt qu'à $\lambda_{max}$. Comparer **la sensibilité** (pente de la droite d'étalonnage).
4. Une erreur de réglage de $\lambda$ de $\pm5$ nm est possible. Comparer l'effet sur $A$ à 430 nm et à 480 nm.
5. Conclure sur le choix de $\lambda_{max}$.

??? success "Corrigé"
    1. $\lambda_{max}\approx480$ nm (bleu). La solution absorbe le bleu et transmet surtout le jaune-orange : elle est **orange**.
    2. $\varepsilon_{max}=\dfrac{0{,}82}{1{,}0\times2{,}0\times10^{-4}}=4{,}1\times10^{3}$ L·mol⁻¹·cm⁻¹.
    3. À 430 nm : $\varepsilon=\dfrac{0{,}36}{2{,}0\times10^{-4}}=1{,}8\times10^{3}$ ; la pente $k$ est donc $\dfrac{0{,}36}{0{,}82}=0{,}44$ fois celle à 480 nm : la sensibilité est **2,3 fois plus faible**. Pour la même variation $\Delta c$, $\Delta A$ est 2,3 fois plus petit : la mesure est moins précise.
    4. Au voisinage de 430 nm, le spectre est **raide** : entre 430 et 460 nm, $A$ varie de $0{,}36$ à $0{,}72$, soit environ $0{,}012$ par nm : une erreur de 5 nm change $A$ d'environ **0,06** (jusqu'à 17 % de 0,36). Autour de 480 nm, le spectre est **plat** : $A$ ne varie que de quelques centièmes sur 20 nm (de 0,72 à 0,82 puis 0,66), l'effet d'un décalage de 5 nm est **inférieur à 0,02** (nul exactement au sommet).
    5. $\lambda_{max}$ combine **sensibilité maximale** et **robustesse** aux imprécisions de réglage (sommet du pic : dérivée quasi nulle). On ne choisit un autre $\lambda$ que pour éviter une espèce interférente.

---

## Exercice 7 : limites du modèle, décalage et blanc ★★★★

**Partie A : limites de la loi.** Pour un colorant, les mesures à $\lambda_{max}$ (cuve de 1,0 cm) donnent :

| $c$ (µmol·L⁻¹) | 20 | 40 | 60 | 80 | 100 | 150 | 200 |
|---|---|---|---|---|---|---|---|
| $A$ | 0,18 | 0,37 | 0,54 | 0,73 | 0,91 | 1,24 | 1,52 |

1. Calculer le rapport $A/c$ pour chaque point. Que constate-t-on ?
2. Jusqu'à quelle concentration la loi de Beer-Lambert est-elle respectée à 5 % près ? Proposer des causes.
3. Un élève trace la droite par l'origine sur **tous** les points. Quel défaut ?

**Partie B : blanc oublié.** On refait la gamme **sans** faire le blanc avec le solvant :

| $c$ (µmol·L⁻¹) | 20 | 40 | 60 | 80 | 100 |
|---|---|---|---|---|---|
| $A$ | 0,22 | 0,41 | 0,58 | 0,77 | 0,95 |

4. Calculer l'ordonnée à l'origine et la pente. Interpréter.
5. Un échantillon donne $A_x=0{,}30$ dans ces mêmes conditions. Calculer $c_x$ correctement, puis avec un modèle forcé par l'origine ($k=\dfrac{\sum c_iA_i}{\sum c_i^2}$). Comparer.
6. Quelle est la bonne conduite à tenir ?

??? success "Corrigé"
    1. $A/c$ (en $10^{-3}$ L·µmol⁻¹) : $9{,}0\ ;\ 9{,}25\ ;\ 9{,}0\ ;\ 9{,}1\ ;\ 9{,}1\ ;\ 8{,}3\ ;\ 7{,}6$. Constant (≈ 9,1) jusqu'à 100 µmol·L⁻¹, puis **décroissant** : la courbe s'infléchit.
    2. À 150 µmol·L⁻¹, le rapport est inférieur de 9 % à 9,1 ; à 100, l'écart est nul. La loi est valable jusqu'à $c\approx100$ µmol·L⁻¹ ($A\lesssim1$). Causes : lumière parasite, bande passante non nulle, interactions entre entités (agrégation) à forte concentration.
    3. La droite forcée par l'origine sur tous les points aurait une pente **sous-estimée** et passerait loin des étalons de faible $c$ ; l'estimation des petites concentrations serait **faussée**. On supprime les points hors domaine (ici 150 et 200) ou on dilue.
    4. Les absorbances sont exactement celles de la gamme précédente **+ 0,04**. Régression affine : pente $=\dfrac{36{,}4}{4000}=9{,}1\times10^{-3}$ L·µmol⁻¹, ordonnée à l'origine $=0{,}586-9{,}1\times10^{-3}\times60=0{,}040$. La pente est correcte ; l'ordonnée non nulle est un **décalage systématique** (absorption de la cuve, du solvant, blanc non fait) qui s'ajoute à toutes les mesures.
    5. Modèle affine : $c_x=\dfrac{0{,}30-0{,}040}{9{,}1\times10^{-3}}=28{,}6$ µmol·L⁻¹. Modèle par l'origine : $k=\dfrac{212{,}2}{22\,000}=9{,}65\times10^{-3}$ ; $c_x=\dfrac{0{,}30}{9{,}65\times10^{-3}}=31{,}1$ µmol·L⁻¹. Écart de **+9 %** par rapport à la bonne valeur. (Le biais est le plus fort **loin du centre** de la gamme ; au centre, l'erreur serait presque invisible : un point d'étalonnage « correct » ne prouve pas que le modèle l'est.)
    6. **Refaire le blanc** et reprendre toutes les mesures. À défaut, il faut utiliser un modèle **affine** $A=kc+b$ pour les étalons et l'échantillon, tous mesurés dans les mêmes conditions. Une ordonnée à l'origine non nulle est un **signal d'alerte**.

---

## Exercice 8 : mélange de deux colorants (défi, additivité) ★★★★★

!!! note "Hors programme strict"
    Cet exercice utilise la propriété d'**additivité** des absorbances, qui découle de la loi de Beer-Lambert. Il teste la compréhension profonde du modèle.

Deux colorants $X$ et $Y$ sont présents dans une même solution. Pour une cuve de 1,0 cm, on connaît leurs coefficients d'absorption molaire (L·mol⁻¹·cm⁻¹) :

| | $\lambda_1$ | $\lambda_2$ |
|---|---|---|
| $X$ | 8000 | 1000 |
| $Y$ | 500 | 6000 |

Le mélange a pour absorbances $A_1=0{,}540$ à $\lambda_1$ et $A_2=0{,}470$ à $\lambda_2$.

1. Écrire la loi d'additivité à chaque longueur d'onde.
2. Déterminer $c_X$ et $c_Y$.
3. Pourquoi une seule mesure ne suffirait-elle pas ?
4. Si $Y$ n'absorbait pas du tout à $\lambda_1$, le problème serait plus simple : pourquoi ?

??? success "Corrigé"
    1. À chaque $\lambda_i$ : $A_i=\ell\left(\varepsilon_X(\lambda_i)\,c_X+\varepsilon_Y(\lambda_i)\,c_Y\right)$, soit
       $$\begin{cases}8000\,c_X+500\,c_Y=0{,}540\\ 1000\,c_X+6000\,c_Y=0{,}470\end{cases}$$
    2. Dans la première équation : $c_X=\dfrac{0{,}540-500\,c_Y}{8000}$. En substituant dans la seconde : $0{,}0675-62{,}5\,c_Y+6000\,c_Y=0{,}470\Rightarrow5937{,}5\,c_Y=0{,}4025$, donc $c_Y=6{,}78\times10^{-5}$ mol·L⁻¹, puis $c_X=\dfrac{0{,}540-0{,}0339}{8000}=6{,}33\times10^{-5}$ mol·L⁻¹.
       Vérification dans la 2ᵉ équation : $1000\times6{,}33\times10^{-5}+6000\times6{,}78\times10^{-5}=0{,}0633+0{,}4067=0{,}470$ ✓.
    3. Il y a **deux inconnues** ($c_X$, $c_Y$) : il faut au moins **deux équations indépendantes**, donc deux longueurs d'onde où le rapport $\varepsilon_X/\varepsilon_Y$ diffère.
    4. Le système devient **triangulaire** : $A_1=\varepsilon_X(\lambda_1)c_X$ donne $c_X$ directement, sans résoudre de système : c'est le principe du choix d'une longueur d'onde où **seule** l'espèce dosée absorbe.
