---
layout: post
title: "Un rançongiciel provoque un Cyber 11 septembre"
author: "Philomène Inneblaque"
image: "/assets/grubcker.jpg"
tags: ['RetardedRollercoaster', 'exim']
category: malware
twitter_text: "Un rançongiciel Linux provoque un cyber-11 septembre"
introduction: "Il exploite une incohérence dans le format des dates d'Exim"
---

Stupeur et consternation, avant-hier, au SOC de l'Agence Cyber-Spatiale
Européenne, alors que l'infrastructure informatique cédait aux assauts d'un
redoutable rançongiciel, causant la paralysie de toutes les opérations en
cours.


Le maliciel, qui répond au doux nom de Grubcker, se propage via une
[zérodée](https://infauxsec.github.io/professionalisme/2018/10/10/paint-testing-pratique.html)
dans le logiciel de messagerie Exim, et cible les applications web écrites
avec les langages les plus populaires de l'industrie (comme
[Python 4](https://infauxsec.github.io/code/2018/07/13/python4-features.html)).


La charge utile embarquée est d'une redoutable efficacité ; elle consiste a
identifier, dans divers documents ou programmes, toutes les dates au format
Jour-Mois-Année (un standard hautement rationnel et efficace, en vigueur
dans les régions les plus civilisées du globe), pour les remplacer par
le très inférieur format Mois-Jour-Année, produit ridicule de la décadente
et impérialiste société anglo-saxonne.


Les conséquences seront coûteuses pour l'ACSE, le bug de conversion du
format de date ayant déja causé l'explosion au lancement d'une centaine de
sondes cyber-spatiales, plus communément appelées *« paquets SYN »* avant que
l'agence ne réussisse à couper `nmap`.


Par miracle, la France n'a, elle, pas été touchée par la vague d'infections ;
le déploiement initial ayant eu lieu le 09.09.2019, le maliciel a pu être
détecté _in extremis_ par un stagiaire de l'ANSSI (major de sa promotion à
l'ENS) chargé d'implémenter une fonction `estUnPalindrome` en OCaml.

Devant la découverte d'un palliatif à l'infection, les autres pays européens,
qui ne bénéficient pas de l'excellence française en matière de technologie, ont
demandé à Xavier Leroy de mener la défense cyber-spatiale européenne. Celui-ci
est déjà en train d'assembler sa ligue des cyber-justiciers pour lutter plus
efficacement contre la cyber-criminalité grandissante et les nouvelles menaces
d'invasions depuis le cyber-espace.
