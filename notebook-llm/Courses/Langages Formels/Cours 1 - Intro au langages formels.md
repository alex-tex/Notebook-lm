---
classe: Langages Formels
type: cours
profs:
tags:
date:
---
Langage: ensemble de mots

ex: L1 = {aab, aba, abb, baa, bab, bba, bbb}
sur ensemb = {a,b}
"Mots de longueur 3 utilisant a et b"
L1 est un langage fini

L2 = {acbb, accbb, acccbb, ...}
"Mots qui commoncent par a, suivi d'un nom b arbitraire de c, suivi de b"

**L2 est un log infini**

taille d'un langage | L |:
nombre de mot qu'il contient

|L1| = 8 | L2 | = inf

Langage vide noté ∅ = {} 

>**Attention:**
>Langage vide n'est pas un mot vide

ex: 
L = {ensemble} 
| L | = 1

ex:
E = {a,b}
 E* = {E, a ,b , aa, ab, bb}
-- 
Soit E (ensemble), on note E* le langage de tous les mots 

E+: idem mais mots de longueur au moins 1 

E+ = E+ \ {ensemble}

### Σ∗ : tous les mots possibles sur l’alphabet Σ

supposons que Σ={a,b} on écrit Σ∗ pour désigner tous les mots possibles construits avec a et b, y compris le mot vide.

Σ∗={ε, a, b, aa, ab, ba, aaa, aab, ... }


## Opérations

- Union: L1 u L2
- Intersection: L1 n L2
- Complément: L = E* / L
- Concatération: L1 o L2
L1 o L2 = {w1 . w2 | w1 appartient à L1, w2 appartient à L2}


![[cours1_lf_Drawing 2026-09-16 10.44.41.excalidraw]]