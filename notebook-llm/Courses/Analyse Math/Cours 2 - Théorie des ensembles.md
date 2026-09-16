---
classe: Analyse Math
type: cours
profs:
tags:
  - semestre1
date: 2026-09-15
---
Un ensemble est une collection non-ordonnée d’élements.

**Notation:**

- x ∈ X “x est un ´el´ement de X”
- x  /∈ X “x n’est pas un ´el´ement de X”
- {a,b,...,c } l'ensemble courrant des éléments a,b,...,c

> **Exemple**:
· {1,2,3} = {2,1,3} = {1,2,3,2,2, 1}
· N = {0,1,2,3, ... }
· N* = {1,2,3, ... }



![[Pasted image 20260915135854.png]]



• {n ∈ N∗ : n divise 15} = {1, 3, 5, 15}
• P({1, 2}) = {∅, {1}, {2}, {1, 2}}

### Distributivité

X n (Y u Z) = (X n Y) u (X n Z)

représentation diagramme de Venn:
![[diagram]]
X u (Y n Z) = (X u Y) n (X u Z)
## Quantificateurs

- Quantifiacteur universel ∀ (“pour tout”). L’assertion ∀x ∈ X, A(x) est
vraie ssi l’assertion A(x) est vraie pour chaque x ∈ X.
- **Quantificateur existentiel ∃** (“il existe”). L’assertion ∃x ∈ X, A(x) est
vraie ssi il existe un x ∈ X pour lequel l’assertion A(x) est vraie.
- **On écrit aussi ∃!x ∈ X, A(x)** quand il existe un unique x ∈ X pour lequel
l’assertion A(x) est vraie.

Exemple 1.12:
(i) ∀n ∈ N, n2 ⩾ n
(ii) “∃n ∈ N, ∀k ∈ N, k ⩽ n” est fausse (“il existe un plus grand nombre naturel” est fausse; cf. Exemple 1.6)
(iii) ∀n ∈ N, ∃k ∈ N, k > n (négation de (ii))

![[Pasted image 20260916125608.png]]


On appelle (i) preuve par contre-exemple.
Exemple 1.14. L’assertion ∀x ∈ R, x 2 + 3x + 1 ⩾ 0 est fausse parce pour x = −1 on a (−1)2 + 3(−1) + 1 = −1 < 0.

![[Pasted image 20260916130143.png]]