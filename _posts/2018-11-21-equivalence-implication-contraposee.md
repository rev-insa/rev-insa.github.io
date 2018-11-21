---
title: Equivalence entre une implication et sa contraposée
key: 20182111
tags: démonstration algèbre
---

Démonstration de l'équivalence entre une implication et sa contraposée.  
<!--more-->

On cherche à montrer qu'une implication et la contraposée de la même implication sont équivalentes, c'est à dire que

$$ P\Rightarrow Q\Leftrightarrow non\left( P\right) \Rightarrow non\left( Q\right) $$

On appelle **A**
$$ P\Rightarrow Q\ $$
et **B**
$$ non\left( P\right) \Rightarrow non\left( Q\right) $$
.

Pour prouver l'équivalence, il faut montrer l'égalité dans les deux sens.

(=>) On Suppose que **A** est vraie et non(Q) vraie.
C'est à dire que
$$ P\Rightarrow Q\ $$
correspond à
$$ non\left( P\right) ou\: Q $$

Si P est vraie alors Q vraie car **A** vraie (P vraie implique que Q soit vraie)
Contradiction car Q est fausse.
Donc P est fausse, et non(P) est vraie.
Donc **B** vraie car non(P) vraie et non(Q) vraie.

On a alors

$$ A\Rightarrow B\$$

$$ P\Rightarrow Q\Rightarrow non\left( P\right) \Rightarrow non\left( Q\right) $$

(<=) Il faut maintenant prouver que
$$ A\Leftarrow B\$$

On sait que **B** : 

$$ non\left( P\right) \Rightarrow non\left( Q\right) $$

donc par contraposée 

$$ non\left(non\left( P\right)\right) \Rightarrow non\left(non\left( Q\right)\right) $$

ce qui correspond à
$$ P\Rightarrow Q\ $$

D'où
$$ A\Leftarrow B\$$
.
Comme
$$ A\Rightarrow B\$$
et
$$ A\Leftarrow B\$$
, on a
$$ A\Leftrightarrow B $$

$$ P\Rightarrow Q\Leftrightarrow non\left( P\right) \Rightarrow non\left( Q\right) $$