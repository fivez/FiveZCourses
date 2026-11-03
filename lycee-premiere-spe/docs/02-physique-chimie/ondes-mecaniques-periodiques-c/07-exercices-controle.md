# 7. Exercices type contrôle

!!! tip "Conditions de contrôle"
    **Durée : 1 h** pour l'ensemble. **Calculatrice autorisée (mode radians pour les cosinus).** Barème indicatif sur 20. Rédigez comme en contrôle : formule littérale, application numérique avec unité, chiffres significatifs cohérents, phrase de conclusion. Dépliez les corrigés **après** avoir terminé.

---

## Exercice A : mesure du niveau d'eau dans une cuve (8 points)

Un capteur à ultrasons est fixé au-dessus d'une cuve, à la hauteur $H=2{,}00$ m au-dessus du fond. Il émet des salves de fréquence $f=40$ kHz, répétées avec la période $T_{rep}=80$ ms, dirigées vers la surface de l'eau. La température de l'air est $\theta=20\ °\text{C}$ et la célérité du son vaut $v=343$ m·s⁻¹. Le capteur détecte l'écho de la surface $\Delta t=4{,}0$ ms après l'émission.

1. (1 pt) Calculer la période $T$ et la longueur d'onde $\lambda$ des ultrasons dans l'air.
2. (1,5 pt) Établir l'expression de la distance $d$ entre le capteur et la surface de l'eau en fonction de $v$ et $\Delta t$. Justifier.
3. (1,5 pt) En déduire la hauteur d'eau $h$ dans la cuve.
4. (1,5 pt) Déterminer la portée maximale du capteur. Quelle est sa signification physique ?
5. (2,5 pt) En été, la température de l'air au-dessus de la cuve atteint $35\ °\text{C}$. On utilise toujours $v=343$ m·s⁻¹ dans le calcul. (a) Calculer la vraie célérité à 35 °C avec $v(\theta)\approx331+0{,}60\,\theta$. (b) Pour la même durée $\Delta t=4{,}0$ ms, quelle serait la vraie distance ? Quelle erreur sur $h$ ?

??? success "Corrigé masqué"
    1. $T=\dfrac1f=\dfrac{1}{40\times10^3}=2{,}5\times10^{-5}$ s $=25\ \mu$s ; $\lambda=vT=343\times25\times10^{-6}=8{,}6\times10^{-3}$ m $=8{,}6$ mm.
    2. L'onde parcourt l'aller et le retour, soit $2d$, à la célérité constante $v$ pendant $\Delta t$ : $2d=v\Delta t$, donc $d=\dfrac{v\Delta t}{2}$.
    3. $d=\dfrac{343\times4{,}0\times10^{-3}}{2}=0{,}686$ m. $h=H-d=2{,}00-0{,}686=1{,}31$ m.
    4. $d_{max}=\dfrac{vT_{rep}}{2}=\dfrac{343\times80\times10^{-3}}{2}=13{,}7$ m. Au-delà, l'écho d'une salve arrive **après** l'émission de la suivante : on ne peut plus associer l'écho à sa salve (ambiguïté). Ici, $H=2{,}00\ \text{m}<d_{max}$ : le capteur est adapté.
    5. (a) $v(35)=331+0{,}60\times35=352$ m·s⁻¹. (b) $d_{vrai}=\dfrac{352\times4{,}0\times10^{-3}}{2}=0{,}704$ m, donc $h_{vrai}=2{,}00-0{,}704=1{,}30$ m. Avec $v=343$ on trouvait $1{,}31$ m : l'erreur est de $\approx1{,}8$ cm sur $d$ (soit **2,6 %** de $d$) et donc aussi de $1{,}8$ cm sur $h$ (environ 1,4 % de $h$), car $h=H-d$. Il faut compenser la température (sonde) pour une mesure précise.

---

## Exercice B : onde progressive sur une corde (6 points)

Un vibreur de fréquence $f=20$ Hz fait vibrer l'extrémité S d'une longue corde tendue. L'élongation de S est $y_S(t)=A\cos(2\pi ft)$ avec $A=5{,}0$ mm. L'onde se propage à $v=1{,}6$ m·s⁻¹ sans atténuation. On étudie le point M situé à $x=0{,}52$ m de S.

1. (1 pt) Calculer la période et la longueur d'onde.
2. (1 pt) Calculer le retard $\tau$ de M sur S.
3. (1,5 pt) M vibre-t-il en phase avec S, en opposition de phase ou autrement ? Justifier de deux façons.
4. (1,5 pt) Écrire l'expression de $y_M(t)$ pour $t\ge\tau$ et la simplifier.
5. (1 pt) Calculer l'élongation de M à $t=0{,}40$ s.

??? success "Corrigé masqué"
    1. $T=\dfrac1f=0{,}050$ s ; $\lambda=\dfrac vf=\dfrac{1{,}6}{20}=0{,}080$ m $=8{,}0$ cm.
    2. $\tau=\dfrac xv=\dfrac{0{,}52}{1{,}6}=0{,}325$ s.
    3. *Par la distance :* $\dfrac x\lambda=\dfrac{0{,}52}{0{,}080}=6{,}5$ : demi-entier. *Par le retard :* $\dfrac\tau T=\dfrac{0{,}325}{0{,}050}=6{,}5$ périodes. Dans les deux cas : **opposition de phase** (déphasage $13\pi\equiv\pi$ à $2\pi$ près).
    4. $y_M(t)=y_S(t-\tau)=A\cos\!\left(2\pi f(t-\tau)\right)=A\cos(2\pi ft-13\pi)=A\cos(2\pi ft-\pi)=-A\cos(2\pi ft)$ pour $t\ge0{,}325$ s, avec $A=5{,}0$ mm. (Avant $t=\tau$, M est au repos.)
    5. $t=0{,}40$ s $>\tau$ : $y_M=-5{,}0\cos(2\pi\times20\times0{,}40)=-5{,}0\cos(16\pi)=-5{,}0$ mm. (Contrôle : $y_S(t-\tau)=5{,}0\cos(2\pi\times20\times0{,}075)=5{,}0\cos(3\pi)=-5{,}0$ mm ✓.)

---

## Exercice C : localisation d'un séisme (6 points)

Trois stations sismiques ont pour coordonnées (en km) $A(0\,;0)$, $B(90\,;0)$ et $C(30\,;60)$. On suppose des célérités constantes $v_P=5{,}8$ km·s⁻¹ et $v_S=3{,}4$ km·s⁻¹. À la station A, les ondes P arrivent à 14 h 22 min 10,0 s et les ondes S à 14 h 22 min 16,1 s. Les décalages S−P valent $\Delta t_B=8{,}8$ s et $\Delta t_C=2{,}4$ s aux stations B et C.

1. (1 pt) Démontrer que la distance station–foyer s'écrit $d=\Delta t\,\dfrac{v_Pv_S}{v_P-v_S}$.
2. (1,5 pt) Calculer $d_A$, $d_B$, $d_C$.
3. (2 pt) Déterminer par le calcul les coordonnées de l'épicentre.
4. (0,5 pt) Déterminer l'heure du séisme.
5. (1 pt) Pourquoi faut-il au moins trois stations ? Citer deux hypothèses du modèle.

??? success "Corrigé masqué"
    1. $t_P=t_0+\dfrac d{v_P}$ et $t_S=t_0+\dfrac d{v_S}$, donc $\Delta t=t_S-t_P=d\left(\dfrac1{v_S}-\dfrac1{v_P}\right)=d\,\dfrac{v_P-v_S}{v_Pv_S}$ et $d=\Delta t\,\dfrac{v_Pv_S}{v_P-v_S}$. $\blacksquare$
    2. $K=\dfrac{5{,}8\times3{,}4}{5{,}8-3{,}4}=\dfrac{19{,}72}{2{,}4}=8{,}22$ km·s⁻¹. $\Delta t_A=16{,}1-10{,}0=6{,}1$ s. $d_A=8{,}22\times6{,}1=50{,}1$ km ; $d_B=8{,}22\times8{,}8=72{,}3$ km ; $d_C=8{,}22\times2{,}4=19{,}7$ km.
    3. $x=\dfrac{d_A^2-d_B^2+x_B^2}{2x_B}=\dfrac{2\,511-5\,227+8\,100}{180}=\dfrac{5\,384}{180}=29{,}9$ km. $y=\pm\sqrt{d_A^2-x^2}=\pm\sqrt{2\,511-894}=\pm40{,}2$ km. Distance à C(30 ; 60) : pour $y=+40{,}2$, $\sqrt{0{,}01+19{,}8^2}=19{,}8$ km $\approx d_C$ ✓ ; pour $y=-40{,}2$, on trouve $\approx100$ km ✗. **Épicentre $\approx(30\,;40)$ km.**
    4. $t_0=t_P-\dfrac{d_A}{v_P}=10{,}0-\dfrac{50{,}1}{5{,}8}=10{,}0-8{,}6=1{,}4$ s : séisme à **14 h 22 min 01,4 s**.
    5. Une station ne donne que la distance (cercle) ; deux stations donnent deux points d'intersection (ambiguïté) ; **la troisième, non alignée, lève l'ambiguïté**. Hypothèses : vitesses **constantes** (milieu homogène), trajet **rectiligne**, sol **plat**, profondeur du foyer négligée.

---

## Barème et auto-évaluation

| Exercice | Points | Compétences |
|---|---|---|
| A | 8 | S'approprier, réaliser, valider (télémètre, incertitudes) |
| B | 6 | Modéliser, déphasage, retard |
| C | 6 | Démontrer, analyser, triangulation |

!!! warning "Les points qui font perdre le plus de points"
    Facteur 2 oublié dans le télémètre ; unités (ms, µs, km, cm) non converties ; période mesurée max-min (demi-période) ; mode degrés de la calculatrice ; $y_M(t)=y_S(t+\tau)$ au lieu de $t-\tau$ ; $d=v\Delta t$ appliqué à l'écart S−P ; troisième station oubliée dans la triangulation ; conclusion absente.
