---
layout: post
title: "BlaguetteHat: une vulnérabilité dans le processeur des machines à café"
author: "Philomène Inneblaque"
image: "/assets/coffee.jpg"
tags: ['0xc0ffee', 'PVE']
category: 0-day
twitter_text: "Backdoor universelle dans les machines à café"
introduction: "La backdoor aurait été introduite délibérément par le constructeur"
---

Stupeur et consternation, ce week-end, pendant la conférence Blaguette Hat, à Cheppes-les-Prairies,
alors que Jean-Christopher[^1], un chercheur en sécurité hardware, présentait sa découverte,
fruit de plusieurs mois d'enquête: une backdoor matérielle, probablement mise en place
délibérément par le constructeur, dans les processeurs de contrôle des machines à café
Nespresso(tm).

*« Nous sommes bien loin des machines à café de nos ancêtres, qui se
contentaient d'un seul microprocesseur pour gérer l'obsolescence
programmée »*, nous explique Jean-Christopher. *« Aujourd'hui, le Caffeine
Management Engine présent sur toutes les machines à café modernes est un
véritable système autonome, invisible, qui à la main sur toutes les ressources
du système. A part une poignée d'ingénieurs, personne ne sait ce qui
tourne dessus. La seule chose dont nous sommes certains, c'est qu'il
se programme en Java. Mais j'ai découvert que certaines marques de machines
à café sont livrées avec la backdoor activée par défaut. Dans ce cas, il
suffit d'envoyer la séquence 0xd0c0ffee en morse sur le bouton d'alimentation
de la machine, pour débloquer le* God Mode *qui lève toutes les restrictions
imposées par le contsructeur. »*

Une découverte dangereuse: le mystérieux coprocesseur permettrait au code
non privilégié d'élever son niveau en contournant toutes les protections
que le système d'exploitation aurait déposées sur sa route. On pourrait
ainsi imaginer que les machines à café deviennent la cible de cyberattaques
par un état-nation, avec par exemple comme but d'abaisser subrepticement
le taux de caféine du breuvage, ce qui porterait un coup fatal à l'économie
numérique française.

D'un autre côté, de nombreux hackers se réjouissent des possibilités
offertes par un monde rempli de machines à café libérées du carcan
du logiciel propriétaire. Certains travaillent déja à reprogrammer
leurs machines à café pour servir du chocolat chaud, du thé glacé,
de l'absinthe, extruder du plastique ABS, voire même dans certains
cas extrêmes, se débarasser de l'intermédiaire inutile et produire
directement des théorèmes mathématiques. Une information qui donne
déja des sueurs froides autant à la Société Mathématique de France
qu'au Syndicat des Stagiaires de la Logistique Caféinée.


[^1]: Prénom d'emprunt
