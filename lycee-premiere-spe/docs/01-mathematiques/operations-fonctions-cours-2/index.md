# Opérations sur les fonctions

```mermaid
flowchart TD
  F["Deux fonctions f et g"] --> S["Somme f + g"]
  F --> P["Produit f g"]
  F --> I["Inverse 1/f et quotient f/g"]
  F --> C["Composée g ∘ f"]
  F --> T["Translation : x ↦ f(x - a)"]
  S --> V["Domaine, parité, variations"]
  P --> V
  I --> V
  C --> V
  T --> G["Courbe : translation de vecteur (a ; 0)"]
```

| Chapitre | Contenu |
|---|---|
| [01 – Somme et produit](01-somme-produit.md) | Définitions, domaine, parité, variations |
| [02 – Inverse et quotient](02-inverse-quotient.md) | Domaine, variations, parité |
| [03 – Composée](03-composee.md) | $g\circ f$, domaine, parité, variations |
| [04 – Translation](04-translation.md) | $x\mapsto f(x-a)$, axes et centres de symétrie |
| [05 – Comprendre et démontrer](05-comprendre-et-demontrer.md) | Synthèse du thème |
