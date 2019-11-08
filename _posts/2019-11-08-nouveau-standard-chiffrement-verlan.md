---
layout: post
title: "L'ANSSI publie un nouveau standard de chiffrement basé sur le verlan"
author: "Jean-Kévin Acoeur"
image: "/assets/alice-bob.png"
tags: ['siann', 'tocryp']
category: crypto
twitter_text: ""
introduction: "En 2019, le base64 n'est plus vraiment à la hauteur"
---

Stupeur et consternation, hier, chez les services de renseignement d'un certain
nombre d'états rivaux, alors que l'ANSSI annonçait la mise en place d'un
nouveau standard de chiffrement, qui sera introduit progressivement pour
remplacer les technologies vieillissantes comme AES et RSA.

Le nouveau standard, fruit de nombreuses années de recherches intenses
auprès des meilleurs [cryptologues des cités](https://infauxsec.github.io/crypto/2018/08/01/crypter-chiffrer-il-se-fait-tabasser.html), sera basé sur le verlan.
De nombreuses marques de banc[^1] ont en effet montré que le verlan, qui opère
sur des groupes de syllabes plutôt que des octets individuels, offre une bien
meilleure performance comparé au ROT13, quand l'implémentation utilise les
extensions SIMD des processeurs modernes.

Pour les applications militaires les plus sensibles, il sera évidemment
possible d'utiliser le triple-verlan pour remplacer le triple-ROT13. Mais
attention, contrairement à ce que l'on pourrait penser, le triple-verlan n'est
pas simplement une application du verlan répétée 3 fois ; il s'agit en réalité
d'une inversion dans le champ lexical, entouré de deux applications du verlan.

Par exemple, le message `t'es sûr que c'est une bonne idée, Manu ?` sera d'abord
chiffré en `t'es russe que c'est une N.B dei manu ?`, puis en
`t'es soviet que c'est une P.S le bras de satan ?`, et finalement en
`té vietso que c'est une SP le sabre de temps ça ?`.

La technique est révolutionnaire, puisqu'elle est la première à proposer un
système de chiffrement sans clé qui soit militaire-pente[^2].


[^1]: Traduction officielle de l'ANSSI de l'anglais *« benchmark »*.
[^2]: Traduction officielle de l'ANSSI de l'anglais *« military-grade »*.
