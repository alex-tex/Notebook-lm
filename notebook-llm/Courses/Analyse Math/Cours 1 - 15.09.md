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

vérification:
![[Pasted image 20260915132619.png]]

![[Pasted image 20260915133154.png]]

![[Pasted image 20260915133048.png]]


- Dans le principe de raisonnement mathématique, aussi appelé modus ponens,
afin de montrer B (la proposition) on montre A (l'hypothèse) et l'implication A => B. 
**Formellement: (A ∧ (A ⇒ B)) ⇒ B .**

- Dans le raisonnement par double implication, pour montrer l’équivalence
A ⇔ B (“A ssi B”) on montre A ⇒ B (“A seulement si B”) et B ⇒ A (“A si
B”). 
**Formellement: (A ⇔ B) ⇔ (A ⇒ B) ∧ (B ⇒ A)**

- Dans le raisonnement par la contraposée, pour montrer l’implication A ⇒ B
on montre l’implication ¬B ⇒ ¬A. En effet, par Remarque 1.5 on a
(A ⇒ B) ⇔ (¬A ∨ B) ⇔ (¬B ⇒ ¬A).
On appelle l’implication ¬B ⇒ ¬A la contraposée de l’implication A ⇒ B.
Toute implication est donc équivalente `a sa contraposée.
Par exemple: “tous les corbeaux sont noirs” est équivalent `a “si un objet
n’est pas noir alors il n’est pas un corbeau” (mais pas `a “si un objet n’est pas
un corbeau alors il n’est pas noir”).

- Dans le raisonnement par l’absurde, pour montrer que A ⇒ B, on suppose la
négation de la conclusion B et on dérive une contradiction `a l’hypothèse A.
On déduit que ¬B ⇒ ¬A et donc, par contraposée, A ⇒ B.