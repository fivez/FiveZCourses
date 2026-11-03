# 6. Exercices progressifs

!!! tip "Comment utiliser cette page"
    Les exercices sont classés par **difficulté croissante**. Cherchez **seul**, rédigez, **puis** dépliez le corrigé. Relisez les encadrés orange et rouges des corrigés : ce sont les pièges qui coûtent des points en contrôle.

    Sauf indication contraire : célérité du son dans l'air $v=340$ m·s⁻¹ ; $v_{air}(\theta)\approx331+0{,}60\,\theta$ (m·s⁻¹, $\theta$ en °C).

---

## Exercice 1 : le télémètre ultrasonore ★

Un télémètre ultrasonore émet des salves de fréquence $f=40$ kHz, avec une période de répétition $T_{rep}=60$ ms.

1. L'écho d'un obstacle revient $\Delta t=5{,}8$ ms après l'émission. Calculer la distance à l'obstacle.
2. Calculer la portée maximale du télémètre.
3. La durée $\Delta t$ est mesurée à $\pm10\ \mu$s. Quelle est l'incertitude sur $d$ ?
4. Calculer la période $T$ et la longueur d'onde $\lambda$ des ultrasons.
5. Il fait 30 °C au lieu de 20 °C, mais l'opérateur utilise $v=343$ m·s⁻¹. Quelle est l'erreur relative sur $d$ ?

??? success "Corrigé"
    1. $d=\dfrac{v\Delta t}{2}=\dfrac{340\times5{,}8\times10^{-3}}{2}=0{,}99$ m.

        !!! failure "Piège : facteur 2"
            $\Delta t$ est la durée d'un **aller-retour** : la distance parcourue est $2d$.
    2. $d_{max}=\dfrac{vT_{rep}}{2}=\dfrac{340\times60\times10^{-3}}{2}=10$ m (10,2 m).
    3. $\delta d=\dfrac{v\,\delta(\Delta t)}{2}=\dfrac{340\times10\times10^{-6}}{2}=1{,}7\times10^{-3}$ m $=1{,}7$ mm.
    4. $T=\dfrac1f=\dfrac{1}{40\times10^3}=25\ \mu$s ; $\lambda=vT=340\times25\times10^{-6}=8{,}5\times10^{-3}$ m $=8{,}5$ mm.
    5. À 30 °C : $v=331+0{,}60\times30=349$ m·s⁻¹. La distance calculée avec 343 est trop faible dans le rapport $\dfrac{343}{349}$ : erreur relative $=\dfrac{349-343}{349}=1{,}7\,\%$ (distance **sous-estimée**).

---

## Exercice 2 : lecture d'un oscillogramme ★

Le signal d'un vibreur est observé à l'oscilloscope avec la base de temps $0{,}50$ ms/div et la sensibilité verticale $2{,}0$ V/div.

1. Cinq périodes occupent $8{,}0$ divisions horizontales. Calculer $T$ et $f$.
2. Le signal oscille entre $-3{,}0$ divisions et $+3{,}0$ divisions. Calculer l'amplitude.
3. Quel est le domaine concerné (infrasons, audible, ultrasons) ?
4. Un élève mesure l'écart entre un maximum et le minimum suivant : $0{,}80$ div. Quelle fréquence trouverait-il en prenant cette valeur pour $T$ ? Quelle erreur commet-il ?
5. Pourquoi mesurer cinq périodes plutôt qu'une seule ?

??? success "Corrigé"
    1. Durée de 5 périodes : $8{,}0\times0{,}50=4{,}0$ ms ; $T=\dfrac{4{,}0}{5}=0{,}80$ ms ; $f=\dfrac1T=\dfrac{1}{0{,}80\times10^{-3}}=1{,}25\times10^{3}$ Hz $=1{,}3$ kHz.
    2. Tension crête à crête : $6{,}0\times2{,}0=12$ V ; amplitude $=\dfrac{12}{2}=6{,}0$ V.
    3. $20\ \text{Hz}<1{,}25$ kHz $<20$ kHz : **domaine audible**.
    4. Entre un maximum et le minimum suivant : **demi-période**. Il trouverait $T'=0{,}80\times0{,}50=0{,}40$ ms, soit $f'=2{,}5$ kHz au lieu de $1{,}25$ kHz : fréquence **doublée**.

        !!! failure "Erreur fréquente"
            Ne jamais mesurer maximum → minimum : c'est $T/2$.
    5. L'incertitude de lecture (≈ $\pm0{,}5$ div) est répartie sur 5 périodes : l'incertitude **relative** sur $T$ est environ 5 fois plus faible.

---

## Exercice 3 : $\lambda$, $T$, $v$ et phase ★★

Un vibreur de fréquence $f=25$ Hz crée une onde sinusoïdale sur une corde. La longueur d'onde est $\lambda=4{,}0$ cm.

1. Calculer la période et la célérité de l'onde.
2. Deux points M et N de la corde sont distants de $10$ cm. Calculer le retard de N sur M. Sont-ils en phase ou en opposition de phase ?
3. On double la fréquence du vibreur sans modifier la corde ni sa tension. Que deviennent $v$, $T$, $\lambda$ ?
4. Dans quel sens (augmente/diminue) évolue $\lambda$ si on tend plus fortement la corde (ce qui augmente $v$), à $f$ fixée ?

??? success "Corrigé"
    1. $T=\dfrac{1}{25}=0{,}040$ s ; $v=\lambda f=4{,}0\times10^{-2}\times25=1{,}0$ m·s⁻¹.
    2. $\tau=\dfrac{d}{v}=\dfrac{0{,}10}{1{,}0}=0{,}10$ s ; $\dfrac{d}{\lambda}=\dfrac{10}{4{,}0}=2{,}5$ : demi-entier, donc **opposition de phase** (vérification : $\dfrac\tau T=\dfrac{0{,}10}{0{,}040}=2{,}5$).
    3. $v$ : **inchangée** (propriété du milieu) ; $f'=50$ Hz donc $T'=\dfrac T2=0{,}020$ s ; $\lambda'=\dfrac{v}{f'}=\dfrac{\lambda}{2}=2{,}0$ cm.
    4. $\lambda=\dfrac{v}{f}$ : $f$ fixée, $v$ augmente, donc $\lambda$ **augmente**.

        !!! warning "Piège"
            La fréquence est imposée par la **source** ; la célérité par le **milieu** ; la longueur d'onde en découle. Ne jamais écrire « $v$ augmente quand $f$ augmente ».

---

## Exercice 4 : mesurer $\lambda$ avec des ultrasons ★★

Un émetteur d'ultrasons de fréquence $f=40{,}0$ kHz est relié à la voie 1 d'un oscilloscope, un récepteur mobile à la voie 2. On éloigne le récepteur de l'émetteur le long de l'axe ; les deux signaux sont en phase pour la première fois à la position $x_0$. À partir de $x_0$, on déplace le récepteur jusqu'à observer 10 nouvelles coïncidences : le déplacement total est $8{,}5$ cm.

1. Calculer $\lambda$ puis la célérité du son $v$.
2. Pourquoi mesurer sur 10 longueurs d'onde ?
3. On estime l'incertitude de lecture de position à $\pm1$ mm. Calculer l'incertitude sur $\lambda$ si on mesure sur 1 puis sur 10 longueurs d'onde.
4. Un élève conclut $\lambda=\dfrac{8{,}5}{11}$ cm car il a « compté 11 positions ». Où est l'erreur ?

??? success "Corrigé"
    1. $10\lambda=8{,}5$ cm donc $\lambda=0{,}85$ cm $=8{,}5\times10^{-3}$ m ; $v=\lambda f=8{,}5\times10^{-3}\times40{,}0\times10^{3}=3{,}4\times10^{2}$ m·s⁻¹ $=340$ m·s⁻¹.
    2. L'erreur de lecture est **divisée par 10** sur $\lambda$ : mesure plus précise.
    3. Sur 1 longueur d'onde : $\pm1$ mm sur 8,5 mm, soit $\pm12\,\%$. Sur 10 : $\delta\lambda=\dfrac{1}{10}=0{,}1$ mm, soit $\pm1{,}2\,\%$.
    4. Il y a **10 intervalles** entre 11 positions successives en phase (la position de départ comprise) : il faut diviser par **10**, pas par 11.

---

## Exercice 5 : modélisation d'une onde progressive ★★★

Une source S vibre selon $y_S(t)=2{,}0\cos\!\left(\dfrac{2\pi t}{T}\right)$ (en mm), avec $T=20$ ms. L'onde se propage à $v=2{,}0$ m·s⁻¹ sans atténuation.

1. Calculer $\lambda$.
2. Écrire $y_M(t)$ pour M à $x_M=0{,}60$ m de S. M est-il en phase avec S ?
3. Écrire $y_N(t)$ pour N à $x_N=0{,}605$ m.
4. Calculer $y_N$ à $t=0{,}35$ s.
5. Le même point M est-il en mouvement avant $t=0{,}30$ s ? Justifier.

??? success "Corrigé"
    1. $\lambda=vT=2{,}0\times20\times10^{-3}=0{,}040$ m $=4{,}0$ cm.
    2. $\tau_M=\dfrac{0{,}60}{2{,}0}=0{,}30$ s ; $\dfrac{x_M}{\lambda}=\dfrac{0{,}60}{0{,}040}=15$ : entier, donc **en phase**. $y_M(t)=2{,}0\cos\!\left(\dfrac{2\pi(t-0{,}30)}{T}\right)=2{,}0\cos\!\left(\dfrac{2\pi t}{T}-30\pi\right)=2{,}0\cos\!\left(\dfrac{2\pi t}{T}\right)$.
    3. $\dfrac{x_N}{\lambda}=15{,}125$ ; déphasage $=30{,}25\pi\equiv\dfrac\pi4$ (à $2\pi$ près). $y_N(t)=2{,}0\cos\!\left(\dfrac{2\pi t}{T}-\dfrac\pi4\right)$.
    4. $\tau_N=0{,}3025$ s ; $t-\tau_N=0{,}0475$ s ; $\dfrac{2\pi\times0{,}0475}{0{,}020}=4{,}75\pi\equiv0{,}75\pi$. $y_N=2{,}0\cos(0{,}75\pi)=-1{,}4$ mm. (Calculatrice en **radians**.)
    5. **Non** : l'onde n'atteint M qu'à $t=\tau_M=0{,}30$ s. Avant, $y_M=0$ (milieu au repos). La loi $y_M(t)=y_S(t-\tau)$ n'est valable que pour $t\ge\tau$.

        !!! warning "Piège"
            La formule sinusoïdale décrit M **après** l'arrivée de l'onde. Avant : repos.

---

## Exercice 6 : deux graphes, deux périodicités ★★★

On dispose de deux enregistrements d'une même onde sinusoïdale progressive.
- **Graphe A** : élongation d'un point fixe M en fonction du **temps**. Deux maxima consécutifs aux dates $0{,}10$ s et $0{,}50$ s.
- **Graphe B** : profil de la corde à l'instant $t_1=0$, en fonction de la **position** $x$. Deux maxima consécutifs aux abscisses $0{,}30$ m et $1{,}50$ m.

1. Déterminer $T$, $f$ et $\lambda$.
2. En déduire la célérité $v$.
3. Sachant que le maximum situé en $x=0{,}30$ m à $t_1=0$ se déplace dans le sens des $x$ croissants, où se trouve ce maximum à $t=0{,}10$ s ?
4. Combien de temps faut-il à une perturbation pour parcourir $2{,}4$ m ?
5. Un élève affirme que « $\lambda=1{,}50$ m car le deuxième maximum est à 1,50 m ». Corriger.

??? success "Corrigé"
    1. $T=0{,}50-0{,}10=0{,}40$ s ; $f=\dfrac1T=2{,}5$ Hz ; $\lambda=1{,}50-0{,}30=1{,}20$ m.
    2. $v=\dfrac\lambda T=\dfrac{1{,}20}{0{,}40}=3{,}0$ m·s⁻¹.
    3. Déplacement $=vt=3{,}0\times0{,}10=0{,}30$ m : le maximum est à $x=0{,}30+0{,}30=0{,}60$ m.
    4. $\tau=\dfrac{d}{v}=\dfrac{2{,}4}{3{,}0}=0{,}80$ s (soit exactement $2T$ : $2\lambda=2{,}4$ m).
    5. $\lambda$ est l'**écart** entre deux maxima consécutifs, pas l'abscisse d'un maximum : $\lambda=1{,}50-0{,}30=1{,}20$ m. De même, $T=0{,}50-0{,}10=0{,}40$ s et non $0{,}50$ s.

        !!! failure "Erreur fréquente"
            Mélanger les axes ou lire une position au lieu d'un écart : $\lambda$ se lit sur un profil spatial, $T$ sur un graphe temporel, toujours par **différence** entre deux points homologues.

---

## Exercice 7 : distance d'un séisme ★★★

Les célérités des ondes sismiques dans la croûte sont $v_P=6{,}0$ km·s⁻¹ et $v_S=3{,}5$ km·s⁻¹. Une station enregistre l'arrivée des ondes P à 08 h 15 min 20,0 s et celle des ondes S à 08 h 15 min 44,0 s.

1. Montrer que $d=\Delta t\,\dfrac{v_Pv_S}{v_P-v_S}$ et calculer $d$.
2. Déterminer l'heure du séisme.
3. Quelle durée met une onde P pour parcourir 50 km ? Une onde S ?
4. Pourquoi une station située de l'autre côté du globe n'enregistre-t-elle pas d'ondes S directes ?
5. Le foyer est à une profondeur $h=15$ km. Calculer la distance épicentrale. Conclure.

??? success "Corrigé"
    1. Démonstration : $\Delta t=d\left(\dfrac1{v_S}-\dfrac1{v_P}\right)=d\,\dfrac{v_P-v_S}{v_Pv_S}$. Donc $d=\Delta t\,\dfrac{v_Pv_S}{v_P-v_S}$. $\Delta t=44{,}0-20{,}0=24{,}0$ s ; $K=8{,}4$ km·s⁻¹ ; $d=8{,}4\times24{,}0=2{,}0\times10^{2}$ km (201,6 km).
    2. $t_0=t_P-\dfrac{d}{v_P}=20{,}0-\dfrac{201{,}6}{6{,}0}=20{,}0-33{,}6=-13{,}6$ s, soit **08 h 15 min (20,0 − 33,6) s = 08 h 14 min 46,4 s**.
    3. Onde P : $\dfrac{50}{6{,}0}=8{,}3$ s ; onde S : $\dfrac{50}{3{,}5}=14{,}3$ s.
    4. Les ondes S sont des ondes **transversales** qui ne se propagent pas dans les **liquides** : elles sont arrêtées par le noyau externe liquide.
    5. $d_{ep}=\sqrt{201{,}6^2-15^2}=\sqrt{40\,643-225}=201{,}0$ km : écart de 0,3 % seulement, négligeable car $h\ll d$.

---

## Exercice 8 : triangulation complète ★★★★

Trois stations sont placées aux points $A(0\,;0)$, $B(120\,;0)$, $C(60\,;90)$ (coordonnées en km). Les vitesses sont $v_P=6{,}2$ km·s⁻¹ et $v_S=3{,}6$ km·s⁻¹. Les retards S−P mesurés valent $\Delta t_A=9{,}4$ s, $\Delta t_B=7{,}5$ s, $\Delta t_C=5{,}9$ s.

1. Calculer $K$ puis les distances $d_A,d_B,d_C$.
2. Déterminer par le calcul l'abscisse $x$ de l'épicentre à partir des stations A et B.
3. Calculer les deux valeurs possibles de $y$. Quelle station permet de choisir et quelle valeur retient-on ?
4. Décrire la construction graphique équivalente (échelle 1 cm pour 10 km).
5. Que se passe-t-il si les trois stations sont alignées ?

??? success "Corrigé"
    1. $K=\dfrac{6{,}2\times3{,}6}{6{,}2-3{,}6}=\dfrac{22{,}32}{2{,}6}=8{,}58$ km·s⁻¹. $d_A=8{,}58\times9{,}4=80{,}7$ km ; $d_B=8{,}58\times7{,}5=64{,}4$ km ; $d_C=8{,}58\times5{,}9=50{,}6$ km.
    2. $x=\dfrac{d_A^2-d_B^2+x_B^2}{2x_B}=\dfrac{6\,512-4\,147+14\,400}{240}=\dfrac{16\,765}{240}=69{,}9$ km.
    3. $y=\pm\sqrt{d_A^2-x^2}=\pm\sqrt{6\,512-4\,886}=\pm\sqrt{1\,626}=\pm40{,}3$ km. Distance à C($60$ ; $90$) :
        - pour $y=+40{,}3$ : $\sqrt{(69{,}9-60)^2+(40{,}3-90)^2}=\sqrt{98+2\,470}=50{,}7$ km $\approx d_C$ ✓ ;
        - pour $y=-40{,}3$ : $\sqrt{98+16\,900}=130$ km ✗.
        La **station C** lève l'ambiguïté : épicentre $\approx(70\,;40)$ km.
    4. Sur la carte (1 cm = 10 km) : cercles de rayons $8{,}1$ cm centré en A, $6{,}4$ cm centré en B, $5{,}1$ cm centré en C. Leur intersection commune est l'épicentre, avec un petit triangle d'incertitude lié aux erreurs de pointé.
    5. Si les stations sont **alignées**, les cercles centrés sur la droite des centres sont **symétriques** par rapport à cette droite : deux points d'intersection symétriques, la troisième station ne lève pas l'ambiguïté. Il faut des stations **non alignées**.
