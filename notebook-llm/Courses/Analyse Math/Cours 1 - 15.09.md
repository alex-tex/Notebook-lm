---
classe: Analyse Math
type:
profs:
date: 0026-09-15
tags:
  - Intro
---
# Notions de base
## 1.1 Logique

assertions logiques: énoncé

**exemples**:
- "pour tout entier n, si n > 3 alors n > 2" (=> vrai)
- "5 < 3" (=> faux)

**Remarque**: 
Pas tous les énoncés sont des assertions admissibles. 
Exemples: 
• “Lana Del Rey est mieux que Sibelius” (un énoncé faisant appel à des valeur subjectives) (=> faux)

### Négation

¬ (négation, “non”): 
![[Pasted image 20260915124743.png]]


Les autres opérations sont binaires: elles associent une assertion `a deux assertions données.

![[Pasted image 20260915124843.png]]


### L'implication

L'opération "=>" indique "implique". Exemple:

n > 3  => n > 2

![[Pasted image 20260915125340.png]]

### Equivalence

L'opération "<=>" indique "équivalence". Exemple:

On écrit l'assertion A => B de façon équivalente B <= A, ce qui se lit "B si A".

![[Pasted image 20260915125611.png]]


### Convention

l'ordre de opération; ¬, ∧ ∨, ⇒, ⇔ (décroissant)

Par exemple:  ¬A ∨ B ∧ C  veut dire  (¬A) ∨ (B ∧ C)

"," veut aussi dire "∧"

## 1.2 Lois de Morgan

¬(A∧B) <=> (¬A) ∨ (¬B)
¬(A∨B) <=> (¬A) ∧ (¬B)

vérification