---
title: Calcul de la somme des entiers
key: 20182111
tags: démonstration algèbre
---

Démonstration des formules sur la somme des entiers
<!--more-->

On veut montrer que
$$ S^{1}_{n}=\sum ^{n}_{k=1}k=\dfrac {n\left( n+1\right) }{2} $$
et
$$ S^{2}_{n}=\sum ^{n}_{k=1}k^{2}=\dfrac {n\left( n+1\right) \left( 2n+1\right) }{6} $$  

**Calcul de**
$$ S^{1}_{n} $$

On utilise cette expression:

$$ \left( k+1\right) ^{2}-k^{2}=k^{2}+2k+1-k^{2}=2k+1 $$

On fait ensuite la somme

$$ \sum ^{n}_{k=1}\left( k+1\right) ^{2}-k^{2}=2^{2}-1^{2}+3^{2}-2^{2}+4^{2}-3^{2}\ldots $$

On remarque que les carrés s'annulent ce qui donne

$$ \sum ^{n}_{k=1}\left( k+1\right) ^{2}-k^{2}=\left( n+1\right) ^{2}-1 $$

Mais on sait aussi que

$$ \sum ^{n}_{k=1}\left( k-1\right) ^{2}-k^{2}=\sum ^{n}_{k=1}2k+1 $$

$$ =2\sum ^{n}_{k=1}k+\sum ^{n}_{k=1}1 $$

$$ =2S^{1}_{n}+n $$

D'où

$$ 2S^{1}_{n}+n=\left( n+1\right) ^{2}-1 $$

$$ S^{1}_{n}=\dfrac {\left( n+1\right) ^{2}-1-n}{2}=\dfrac {n^{2}+n}{2}=\dfrac {n\left( n+1\right) }{2} $$

**Calcul de**
$$ S^{2}_{n} $$

de la même façon,

$$ \left( k+1\right) ^{3}-k^{3}=k^{3}+3k+1-k^{3}=3k^{2}+3k+1 $$

$$ \sum ^{n}_{k=1}\left( k+1\right) ^{3}-k^{3}=\left( n+1\right) ^{3}-1 $$

et

$$ \sum ^{n}_{k=1}\left( k+1\right) ^{3}-k^{3}=\sum ^{n}_{k=1}3k^{2}+3k+1 $$

D'où

$$ \left( n+1\right) ^{3}-1=3S^{2}_{n}+3S^{1}_{n}+n $$

$$ 3S^{2}_{n}=\left( n+1\right) ^{3}-1-\dfrac {3n\left( n+1\right) }{2}-n $$

$$ =n^{3}+3n^{2}+3n+1-1-\dfrac {3n^{2}}{2}-\dfrac {3n}{2}-n $$

$$ =n^{2}+\dfrac {3}{2}n^{2}+\dfrac {1}{2}n $$

$$ =\dfrac {n}{2}\left( 2n^{2}+3n+1\right) $$

$$ =\dfrac {2n^{2}+3n+1}{2} $$

Finalement
$$ S^{2}_{n}=\dfrac {n\left( n+1\right) \left( 2n+1\right) }{6} $$
.

