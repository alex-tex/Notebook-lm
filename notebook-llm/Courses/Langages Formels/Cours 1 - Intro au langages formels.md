---
classe: Langages Formels
type: cours
profs:
tags:
date:
---
### Alphabet 

##### Définition:
alphabet noté Σ: ensemble fini de symbols

### Σ∗ : tous les mots possibles sur l’alphabet Σ

supposons que Σ={a,b} on écrit Σ∗ pour désigner tous les mots possibles construits avec a et b, y compris le mot vide.

Σ∗={∅, a, b, aa, ab, ba, aaa, aab, ... }

### Langage: ensemble de mots

**L ⊂ Σ∗**

ex: L1 = {aab, aba, abb, baa, bab, bba, bbb}
sur  = {a,b}
"Mots de longueur 3 utilisant a et b"
L1 est un langage fini

L2 = {acbb, accbb, acccbb, ...}
"Mots qui commencent par a, suivi d'un nom b arbitraire de c, suivi de b"

**L2 est un log infini**

taille d'un langage | L |: nombre de mot qu'il contient

| L1 | = 8 | L2 | = inf

Langage vide noté ∅ = {} 

>**Attention:**
>Langage vide n'est pas un mot vide

ex: 
L = {ensemble} 
| L | = 1

ex:
Σ = {a,b}
Σ* = {E, a ,b , aa, ab, bb} 


Soit Σ (ensemble), on note Σ* le langage de tous les mots 

Σ+: idem mais mots de longueur au moins 1 

Σ+ = Σ+ \ {ensemble}

il faut distinguer $Σ^∗$ et $Σ^n$  : car $Σ^n$ représente les mots de **longueur exactement $n$** (pas infini)

**Exemple:**
si  Σ={0,1}   alors:
$Σ^0$={ε}
$Σ^1$ = {0,1}
$Σ^2$ = {00,01,10,11}
$Σ^3$ = {000,001,010,011,100,101,110,111}


>ATTENTION: **il faut pas non plus confondre avec Σ+**

Σ+=Σ∗−{ε}​

donc:
Σ∗={**ε**,a,b,aa,ab,…}    et    Σ+={a,b,aa,ab,…}

(ε désigne le mot vide)
## Opérations

- Union: L1 u L2
- Intersection: L1 n L2
- Complément: L = Σ* / L
- Concatération: L1 o L2
L1 o L2 = {w1 . w2 | w1 appartient à L1, w2 appartient à L2}


![[cours1_lf_Drawing 2026-09-16 10.44.41.excalidraw|100%]]