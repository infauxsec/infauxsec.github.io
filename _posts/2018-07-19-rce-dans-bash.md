---
layout: post
title: "RCE critique dans Bash"
author: "Xi Prau"
image: "/assets/shellfish.png"
tags: ['exploit', 'remote', '0-day']
category: 0-day
twitter_text: "Remote code execution dans Bash"
introduction: "La vulnérabilité daterait de juin 1989"
---

Après Heartbleed, Shellshock, ou Meltdown, c'est le tour d'une nouvelle
vulnérabilité de faire le tour d'Internet, avec un nom et un logo sexy[^2].
Une preuve incontestable de son importance, s'il en est.

L'identifiant officiel de cette vulnérabilité est PVE-2018-1337[^1], 
mais on la surnomme affectueusement « Shellfish ». Elle est,
presque comme Shellshock,
présente dans Bash depuis presque 30 ans. Elle a été publiée hier par
une équipe de deux chercheurs de Polytech Clermont-Ferrand, mais il se
murmure dans le milieu de l'infosec que la vulnérabilité était déjà
connue depuis des mois, et qu'elle aurait été acquise puis revendue
par Zerodium début 2017, pour un montant indéterminé mais certainement
à six ou sept chiffres.

Pour nos lecteurs les plus techniques, nous nous sommes procurés le détail
de l'exploit. Après une longue concertation avec nos avocats et notre
conseiller en éthique numérique, qui nous ont tous fortement déconseillé
de le publier, nous avons décidé de jeter leur avis à la poubelle et de n'en
faire qu'à notre tête. 

Le vecteur est d'une simplicité déroutante. Il suffit d'envoyer la séquence
suivante sur l'entrée standard d'un shell bash :

```
    \x0a\x65\x78\x65\x63\x20\x2f\x62\x69\x6e\x2f\x62\x61\x73\x68\x0a
```

Si le shell est vulnérable, l'attaquant se retrouvera au contrôle d'une
session ayant les privilèges de l'utilisateur.

Les maintainers de bash travaillent déja à un patch, mais il se murmure
en coulisses que ce problème découlerait d'une erreur fondamentale de
design et qu'il serait extrêmement difficile de le corriger correctement.

Ce n'est pas sans rappeler la PVE-2016-0042, qui dénonçait une vulnérabilité
dans PGP permettant de signer les clés publiques d'autres utilisateurs.

[^1]: De la liste publique PVE, abréviation pour « Pas une Vulnérabilité, ça, Enculé »
[^2]: Image de [http://getdrawings.com/shellfish-drawing](http://getdrawings.com/shellfish-drawing)
