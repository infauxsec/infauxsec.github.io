---
layout: post
title: "Dans les bas-fonds des réseaux de trolls sur Twitter"
author: "Xi Prau"
image: "/assets/trolls-francais/cocorico.png"
tags: ['osint', 'troll', 'fromage']
category: osint
twitter_text: "dans les bas-fonds des réseaux de trolls sur Twitter"
introduction: "L'envers du décor du marketing de masse"
---

## Où tout a commencé : le premier lien

Le 12 juillet paraissait
[un nouvel article de x0rz](https://blog.0day.rocks/uncovering-foreign-trolls-trying-to-influence-french-elections-on-twitter-a78a8c12953)
analysant les actions suspectes de deux comptes Twitter ayant probablement visé
la manipulation des dernières élections présidentielles françaises. Inspirée
par le courage et la volonté de l'auteur à démasquer ceux et celles qui osent
perturber le processus démocratique de notre belle startup nation, notre
rédaction a voulu contribuer à l'effort en s'infiltrant dans un milieu dont on
ne parle que trop peu : celui des trolls français.

Le même jour, le compte Twitter peu actif **@fromagedenosmontagnes**
a envoyé un message de menace à **@snyderjulie** (animatrice et productrice de
télévision connue pour être amatrice de vin italien d'après sa
[récente vidéo](https://www.youtube.com/watch?v=fZWaFIVpNYc)). Le tweet, à
présent effacé, disait en québécois : *« Va falloir t'calmer au plus crisse. On
sait c'que tu fais tabarnak, tsé veut dire. »*, ce qui se traduit à peu près
par *« Il va falloir te calmer au plus vite, on sait ce que tu fais. »* en bon
français.

![Julie](/assets/trolls-francais/snyderjulie.png)
![Et Jean Lassalle](/assets/trolls-francais/lassalle.png)

Un mélange presque esotérique de français et de québecois.

## Quand un pro fromage suisse rencontre un pro vin italien

**@fromagedenosmontagnes** retweete et mentionne beaucoup un certain
**@vinussconi**, compte pourtant aux antipodes de ce qu'il représente ; en
effet, **@vinussconi** mène une campagne de promotion du fromage français et
du vin de nos régions.

![VIVE LE VIN](/assets/trolls-francais/vinussconi.png)

## Attribution

Le fait que ces deux comptes parlent de la production alimentaire française est
un point commun troublant. Il apparaît évident que ce sont des trolls et qu'ils
sont contrôlés par la même personne ou le même groupe.

Néanmoins, chez Infauxsec news, nous travaillons sur la base de faits, et la
chance nous a souri à cet égard, car il nous aura fallu trouver un OPSEC fail
providentiel du propriétaire des comptes pour nous convaincre :

![BONJOUR CHOCOLAT](/assets/trolls-francais/chocolat.png)
![ALLO GOOGLE CER CHIEN](/assets/trolls-francais/google.png)

Vous ne rêvez pas, ce premier tweet du Ministère des Armées s'attaque cette
fois au chocolat belge, ce qui démontre que le réseau de trolls est au moins
150% plus large que ce que nous anticipions.

L'utilisation du compte du Ministère des Armées suggère la responsabilité d'une
entité comme la DGSE. Mais quel pourrait être leur objectif ? Nous allons donc
vous présenter notre théorie, étayée par des exemples.

## Objectif de l'opération

La DGSE conduit cette *PSYOP*[^1] dans un contexte de guerre économique. Alors
que le succès des produits du terroir français est en plein déclin, cette
tentative a pour but de nuire au succès de produits allant contre les
intérêts de nos entreprises locales.

Dans cette optique, un réseau d'au moins 5 comptes sabote la réputation de
divers produits : le chocolat belge (*@Defense_gouv*), le fromage
suisse (*@fromagedenosmontagnes*), le vin italien (*@vinussconi*), le hentai
japonais (*@castermanbd*) et même la démocratie française (*@EmmanuelMacron*).

Comme nous pouvons le remarquer, ce dernier compte utilise même des chaînes de
Markov afin de générer ses tweets :

![Democratie](/assets/trolls-francais/macron.png)

## Analyse de l'impact

Les trolls repérés ont pour certains quelques millions de followers. Une
métrique pertinente pour mesurer l'impact de ces trolls est d'utiliser le
dernier de notre liste comme étalon : d'après
[http://www.legorafi.fr/2018/07/16/le-gouvernement-profite-de-la-victoire-des-bleus-pour-faire-voter-la-retraite-a-85-ans-une-hausse-de-la-tva-de-50-et-labolition-de-la-securite-sociale/](un
récent article du Gorafi), fer de lance des journaux d'analyse politique, les
acquis sociaux seraient en nette baisse, et ce principalement grâce à cette
PSYOP.

À l'heure où nous écrivons ces lignes, la plupart des tweets que nous avons
mentionnés ont été supprimés et leurs auteurs reconvertis dans la propagande
pour Justin Bieber, s'étant sans doute rendus compte de l'OPSEC fail de
**@Defense_gouv**.

Nous avons déjà repéré un autre réseau similaire de trolls visant cette fois-ci
la communauté de sécurité informatique francophone. Peut-être nous y
attaquerons-nous dans un prochain article !

[^1]: Opération Psychologique
