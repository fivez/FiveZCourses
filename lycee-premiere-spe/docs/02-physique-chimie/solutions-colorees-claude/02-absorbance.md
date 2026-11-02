# 2. Qu'est-ce que l'absorbance $A(\lambda)$ et comment la mesure-t-on ?

!!! abstract "Objectifs de cette section"
    - Définir l'intensité lumineuse transmise, la **transmittance** $T$ et l'**absorbance** $A$.
    - Passer **dans les deux sens** de $A$ à $T$ (calculs avec $\log$ et $10^x$).
    - Comprendre **pourquoi** on introduit un logarithme et pourquoi on mesure un **rapport** d'intensités.

## 2.1 Intensité transmise et transmittance

On envoie sur une cuve une radiation **monochromatique** de longueur d'onde $\lambda$. On note :

- $I_0(\lambda)$ : intensité lumineuse **transmise par la cuve contenant uniquement le solvant** (le « blanc ») ;
- $I(\lambda)$ : intensité lumineuse **transmise par la cuve contenant la solution**.

!!! info "Définition : transmittance"
    La **transmittance** de la solution à la longueur d'onde $\lambda$ est
    $$T(\lambda) = \frac{I(\lambda)}{I_0(\lambda)}, \qquad 0 \le T \le 1 \ (\text{ou } 0\,\% \text{ à } 100\,\%).$$
    Elle représente la **fraction de lumière qui traverse** la solution.

## 2.2 Absorbance

!!! info "Définition : absorbance"
    L'**absorbance** de la solution à la longueur d'onde $\lambda$ est
    $$A(\lambda) = \log\!\left(\frac{I_0(\lambda)}{I(\lambda)}\right) = -\log T(\lambda)$$
    où $\log$ désigne le **logarithme décimal**. L'absorbance est une grandeur **sans unité** et **positive**.

!!! success "Propriété : relation réciproque"
    $$T = \frac{I}{I_0} = 10^{-A} \qquad\Longleftrightarrow\qquad A = -\log T.$$
    Plus la solution absorbe, plus $A$ est grand et plus $T$ est petit.

### Valeurs de référence à connaître

| Absorbance $A$ | Transmittance $T=10^{-A}$ | Lumière absorbée |
|---|---|---|
| 0 | 100 % | 0 % |
| 0,10 | 79 % | 21 % |
| 0,30 | 50 % | 50 % |
| 0,50 | 32 % | 68 % |
| 0,70 | 20 % | 80 % |
| 1,00 | 10 % | 90 % |
| 2,00 | 1 % | 99 % |
| 3,00 | 0,1 % | 99,9 % |

!!! tip "Méthode : les trois logarithmes à connaître"
    $\log 2 \approx 0{,}30$, $\log 3 \approx 0{,}48$, $\log 5 \approx 0{,}70$ (car $\log 5 = \log 10 - \log 2$).
    Exemples : $T = 25\,\% = \tfrac14 \Rightarrow A = \log 4 = 2\log 2 \approx 0{,}60$ ; $T = 50\,\% \Rightarrow A = \log 2 \approx 0{,}30$.

## 2.3 Pourquoi un rapport ? Pourquoi un logarithme ?

!!! note "Pourquoi un rapport $I_0/I$ ?"
    L'intensité brute dépend de la lampe, du détecteur, des réflexions sur la cuve, de l'absorption du solvant. En faisant le **rapport** avec le blanc (même cuve, même solvant), on **élimine** toutes ces contributions : il ne reste que l'effet de l'**espèce dissoute**.

!!! note "Pourquoi un logarithme ?"
    Quand la lumière traverse deux couches successives, les **transmittances se multiplient** ($T = T_1\times T_2$). Le logarithme transforme un produit en **somme** : $A = A_1 + A_2$. Les absorbances sont **additives** (épaisseurs, mélanges). C'est cette propriété qui rendra $A$ **proportionnelle** à $\ell$ et $c$ (section 5).

??? abstract "Démonstration : additivité des absorbances de deux couches successives"
    Soit $I_0$ l'intensité incidente, $I_1$ l'intensité après la première couche, $I$ après la seconde.
    $$A_1 = \log\frac{I_0}{I_1},\qquad A_2 = \log\frac{I_1}{I}.$$
    $$A_1 + A_2 = \log\frac{I_0}{I_1} + \log\frac{I_1}{I} = \log\!\left(\frac{I_0}{I_1}\times\frac{I_1}{I}\right) = \log\frac{I_0}{I} = A_{\text{totale}}.\ \blacksquare$$

## 2.4 Domaine de mesure utile

!!! warning "Point d'attention : éviter les absorbances trop fortes ou trop faibles"
    - Si $A \gtrsim 2$, il ne passe que 1 % de la lumière : le détecteur mesure un signal très faible, **fortement bruité**. De plus, la loi de Beer-Lambert cesse d'être valable (section 5).
    - Si $A \lesssim 0{,}05$, le signal est du même ordre que le bruit : l'incertitude **relative** sur $A$ est très grande.
    - Zone idéale de travail : environ **$0{,}1 \le A \le 1{,}5$**.

## 2.5 Exemples corrigés

!!! example "Exemple 1 : de $I$ à $A$"
    Le blanc donne $I_0 = 800$ (unités arbitraires). La solution donne $I = 200$. Calculer $T$ et $A$.

    ??? success "Corrigé"
        $T = \dfrac{200}{800} = 0{,}25 = 25\,\%$ et $A = \log\dfrac{800}{200} = \log 4 = 0{,}60$.

!!! example "Exemple 2 : de $A$ à $I$"
    Avec le même $I_0 = 800$, une autre solution a $A = 1{,}30$. Quelle intensité est transmise ?

    ??? success "Corrigé"
        $I = I_0\times10^{-A} = 800\times10^{-1{,}30} = 800\times 0{,}0501 = 40{,}1 \approx 40$ (soit 5,0 % de $I_0$).

!!! failure "Erreur fréquente"
    - Utiliser $\ln$ au lieu de $\log$ : $\ln 4 = 1{,}39 \neq \log 4 = 0{,}60$. En physique-chimie de Première, l'absorbance utilise le **logarithme décimal**.
    - Confondre $A$ et le pourcentage absorbé : $A = 0{,}30$ ne signifie **pas** « 30 % absorbés » mais **50 %** absorbés.
    - Prendre pour $I_0$ l'intensité de la lampe : $I_0$ est mesurée **avec la cuve de solvant** (le « blanc »).
    - Écrire une unité à $A$ : l'absorbance **n'a pas d'unité**.
