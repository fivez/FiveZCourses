# 4. Exercices de synthèse — Ondes mécaniques

Les corrections sont masquées. Les exercices exigent de choisir le modèle pertinent, de justifier les hypothèses et de contrôler les unités.

## Exercice 1 — Télémètre : temps de vol, température et portée

Un télémètre ultrasonore mesure la distance à un mur. À la température de fonctionnement, la célérité du son dans l'air est prise égale à $346\\,\\text{m}\\,\\text{s}^{-1}$. Le délai entre émission et réception est $18{,}6\\,\\text{ms}$.

1. Déterminer la distance au mur.
2. Le constructeur impose une durée maximale d'écoute de $42{,}0\\,\\text{ms}$. Déterminer la portée maximale théorique.
3. Un obstacle est placé à $7{,}50\\,\\text{m}$. L'écho peut-il être reçu dans la fenêtre temporelle ? Justifier.
4. Citer deux raisons pour lesquelles la portée réelle peut être inférieure à la valeur théorique.

??? success "Correction détaillée"
    **1. Distance**

    $$
    \\Delta t=18{,}6\\times10^{-3}\\,\\text{s}
    $$
    $$
    d=\\frac{346\\times18{,}6\\times10^{-3}}{2}
    =3{,}2178\\,\\text{m}
    $$
    $$
    \\boxed{d\\approx3{,}22\\,\\text{m}}
    $$

    **2. Portée maximale**

    $$
    d_{\\max}=\\frac{346\\times42{,}0\\times10^{-3}}{2}
    =7{,}266\\,\\text{m}
    $$
    $$
    \\boxed{d_{\\max}\\approx7{,}27\\,\\text{m}}
    $$

    **3. Obstacle à 7,50 m**

    Le temps aller-retour nécessaire est :
    $$
    \\Delta t=\\frac{2d}{v}
    =\\frac{2\\times7{,}50}{346}
    \\approx0{,}0434\\,\\text{s}=43{,}4\\,\\text{ms}
    $$
    Ce délai dépasse $42{,}0\\,\\text{ms}$. L'écho arrive trop tard : il ne peut pas être reçu dans la fenêtre prévue.

    **4. Limites réelles**

    Atténuation de l'onde, obstacle trop petit ou incliné, faible réflexion, bruit ambiant, sensibilité limitée du récepteur.

## Exercice 2 — Double périodicité et signal

Une onde progressive périodique se propage le long d'une corde. Sur un enregistrement temporel en un point fixe, on mesure $T=16{,}0\\,\\text{ms}$. Sur une photographie prise à un instant donné, la distance entre deux crêtes consécutives est $\\lambda=0{,}48\\,\\text{m}$.

1. Calculer la fréquence.
2. Calculer la célérité de l'onde.
3. Écrire une expression possible du signal au point étudié si l'amplitude est $3{,}0\\,\\text{mm}$, la valeur moyenne nulle et la phase initiale nulle.
4. Déterminer le premier instant strictement positif où le signal retrouve son maximum.

??? success "Correction détaillée"
    **1. Fréquence**

    $$
    T=16{,}0\\times10^{-3}=0{,}0160\\,\\text{s}
    $$
    $$
    f=\\frac{1}{T}=62{,}5\\,\\text{Hz}
    $$

    **2. Célérité**

    $$
    v=\\frac{\\lambda}{T}
    =\\frac{0{,}48}{0{,}0160}
    =30{,}0\\,\\text{m}\\,\\text{s}^{-1}
    $$

    **3. Signal**

    $$
    s(t)=3{,}0\\cos\\left(\\frac{2\\pi}{0{,}0160}t\\right)
    $$
    si $s$ est exprimé en mm et $t$ en secondes. On peut aussi écrire $s(t)=3{,}0\\cos(125\\pi t)$.

    **4. Retour au maximum**

    Le cosinus vaut 1 à $t=0$, puis de nouveau après une période. Le premier instant strictement positif est :
    $$
    \\boxed{t=T=16{,}0\\,\\text{ms}}
    $$

## Exercice 3 — Retrouver un modèle à partir d'un signal

Un capteur enregistre un signal modélisé par :
$$
s(t)=1{,}8+0{,}60\\sin(120\\pi t-\\pi/4)
$$
avec $t$ en secondes et $s$ en unités arbitraires.

1. Donner la valeur moyenne et l'amplitude.
2. Déterminer la fréquence et la période.
3. Déterminer les valeurs maximale et minimale du signal.
4. Expliquer pourquoi la phase initiale ne modifie ni la période ni la fréquence.

??? success "Correction détaillée"
    **1. Valeur moyenne et amplitude**

    $s_0=1{,}8$ et $A=0{,}60$.

    **2. Fréquence et période**

    On identifie $2\\pi f=120\\pi$, donc $f=60\\,\\text{Hz}$.
    $$
    T=\\frac{1}{60}=1{,}67\\times10^{-2}\\,\\text{s}
    $$

    **3. Extrema**

    Le sinus varie entre $-1$ et $+1$.
    $$
    s_{\\max}=1{,}8+0{,}60=2{,}4
    $$
    $$
    s_{\\min}=1{,}8-0{,}60=1{,}2
    $$

    **4. Phase**

    La phase décale le signal horizontalement dans le temps. Elle modifie l'état initial, mais pas l'intervalle de répétition : la période reste déterminée par le coefficient de $t$.

## Exercice 4 — Séisme : distance et triangulation

Trois stations enregistrent un même séisme. Pour cet exercice, on suppose que les célérités sont constantes : $v_P=6{,}0\\,\\text{km}\\,\\text{s}^{-1}$ et $v_S=3{,}5\\,\\text{km}\\,\\text{s}^{-1}$.

Les décalages mesurés sont :
- station A : $\\Delta t_A=24{,}0\\,\\text{s}$ ;
- station B : $\\Delta t_B=40{,}0\\,\\text{s}$ ;
- station C : $\\Delta t_C=32{,}0\\,\\text{s}$.

1. Établir la relation permettant de calculer la distance à partir de $\\Delta t$.
2. Calculer les trois distances.
3. Expliquer comment ces trois résultats permettent de localiser l'épicentre sur une carte.
4. Pourquoi une seule station ne suffit-elle pas ?
5. Pourquoi les distances calculées sont-elles des estimations dans la Terre réelle ?

??? success "Correction détaillée"
    **1. Établissement**

    $$
    \\Delta t=t_S-t_P=\\frac{d}{v_S}-\\frac{d}{v_P}
    $$
    $$
    \\Delta t=d\\left(\\frac{1}{v_S}-\\frac{1}{v_P}\\right)
    $$
    donc :
    $$
    d=\\frac{\\Delta t}{1/v_S-1/v_P}
    $$

    **2. Distances**

    Le dénominateur vaut :
    $$
    \\frac{1}{3{,}5}-\\frac{1}{6{,}0}
    =0{,}11905\\,\\text{s}\\,\\text{km}^{-1}
    $$

    Station A :
    $$
    d_A=\\frac{24{,}0}{0{,}11905}\\approx202\\,\\text{km}
    $$

    Station B :
    $$
    d_B\\approx336\\,\\text{km}
    $$

    Station C :
    $$
    d_C\\approx269\\,\\text{km}
    $$

    **3. Triangulation**

    Tracer sur la carte un cercle centré sur chaque station, avec le rayon correspondant. L'intersection des trois cercles localise l'épicentre.

    **4. Une station**

    Une seule distance définit un cercle de positions possibles, pas un point unique.

    **5. Limites**

    Les vitesses dépendent de la nature des roches, de la profondeur et du trajet. Les incertitudes de lecture des arrivées P et S influencent aussi les distances.
