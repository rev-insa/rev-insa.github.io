---
title: Formule du triangle de Pascal
key: 20182111
tags: démonstration algèbre
---

Démonstration de la formule du triangle de Pascal.  
<!--more-->

On veut montrer que
$$ C^{k}_{n}+C^{k+1}_{n}=C^{k+1}_{n+1} $$

Il faut tout d'abord savoir que
$$ \left( k+1\right) !=\left( k+1\right) k! $$

De la même façon, 
$$ \left( n-k\right) !=\left( n-k\right) \left( n-k-1\right) ! $$

La démonstration est un simple calcul une factorisation. Il faut just savoir que
$$ C^{k}_{n}=\dfrac {n!}{k!\left( n-k\right) !} $$

$$ C^{k}_{n}+C^{k+1}_{n}=\dfrac {n!}{k!\left( n-k\right) !}+\dfrac {n!}{\left( k+1\right) !\left( n-k-1\right) !} $$

$$ =\dfrac {n!}{k!\left( n-k-1\right) !}\left( \dfrac {1}{n-k}+\dfrac {1}{k+1}\right) $$

$$ =\dfrac {n!}{k!\left( n-k-1\right) !}\left( \dfrac {n-k+k+1}{\left( n-k\right) \left( k+1\right) }\right) $$

$$ =\dfrac {\left( n+1\right) !}{\left( k+1\right) !\left( \left( n+1\right) -\left( k+1\right) \right) !} $$

$$ =C^{k+1}_{n+1} $$