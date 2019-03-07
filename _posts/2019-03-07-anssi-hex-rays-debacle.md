---
layout: post
title: "L'ANSSI prévoit de publier la source de son outil de rétro-ingénierie maison"
author: "Philomène Inneblaque"
image: "/assets/hexagone-rays.jpg"
tags: ['hexagone', 'mistral', 'gagnant']
category: souveraineté
twitter_text: ""
introduction: ""
---

Stupeur et consternation sur les réseaux sociaux ce mercredi suite à une
révélation inattendue de l'ANSSI.

Alors que la NSA publiait ce mardi les sources de GHIDRA, son outil de
rétroingénierie utilisé en interne pendant les 15 dernières années, l'équivalent
français de l'agence a décidé de contre-attaquer en annonçant la publication des
sources de son propre outil.

Et quelle surprise pour les rétroingénieurs du monde entier : il s'avèrerait en
fait que cet outil serait nommé IDA !

Selon nos informations, ce ne serait pas une coïncidence ; Hex-Rays, la
compagnie responsable du développement du fameux outil serait en fait une
couverture de l'ANSSI, et son nom serait un clin d'œil à la mère-patrie
française, signifiant en fait *« Hexagone-Rays »*.

L'ANSSI aurait ainsi profité d'un quasi-monopole pendant près de 10 ans sur
l'industrie des outils de rétro-ingénierie propriétaires, et aurait ainsi généré
près de 90% de son budget annuel via la vente du logiciel et de toutes ses
extensions aux 5 clients de l'entreprise.

Mais aujourd'hui, un concurrent de taille est mis sur le marché par le pendant
américain de l'ANSSI. Celle-ci a donc décidé d'abandonner ce budget conséquent
pour saisir également l'opportunité de distribuer une backdoor franco-française
à tous les rétro-ingénieurs du monde.

Mais cette publication est aussi l'occasion d'intégrer de tous nouveaux modules
jusqu'alors secrets à votre installation IDA.

IDA aura à présent un support intégré pour le SOP (Strike-Oriented Programming)
et les SoPchains, concept nommé par l'ANSSI et correspondant à une exploitation
basée sur la grève de l'unité de gestion mémoire *[NDLR : les non-initiés
appellent la vulnérabilité originelle « Spectre »]*.

Enfin, et c'est sans doute le plus important pour tout rétro-ingénieur qui se
respecte, IDA permettra de travailler aisément avec les FDO[^1], concept
similaire aux (et probablement à l'origine des) PDO[^2] en PHP : il y aura
un support total et inconditionnel des FDO, implémentation directe du FDP[^3].

Et vous, quelle est la fonctionnalité qui vous fera sauter le pas ? Dites-le
nous en commentaire !

[^1]: French Data Objects.
[^2]: PHP Data Objects.
[^3]: French Data Protocol.
