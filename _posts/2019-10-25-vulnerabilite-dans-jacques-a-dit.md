---
layout: post
title: "Découverte d'une vulnérabilité critique dans Jacques-a-dit"
author: "Jess Socks"
image: "/assets/sudont.png"
tags: ['dyslexia', 'sexdaily', 'marchepasenfr', 'quebec']
category: pve
twitter_text: "Jacadi-a-dit rm -rf /" 
introduction: "Jacadi-a-dit rm -rf /"
---

Stupeur et consternation cette semaine sur les réseaux sociaux alors qu'une
vulnérabilité critique a été découvert dans le programme français de gestion
des permissions administrateurs franco-français *« Jacques-a-dit »*.

En effet, un expert de l'ANSSI diplômé en lettres classiques a découvert que
la requête de comment ?[^1] spécifiant le comportement du protocole de gestion
des permissions utilisé par *« Jacques-a-dit »* avait été mal interprétée par
les développeurs du programme, permettant à n'importe quel utilisateur
d'exécuter une commande grâce à la commande *« Jacadi-a-dit »* également
présente dans le paquet.

Cette commande avait principalement pour intérêt d'être utilisée sur Suicide
Linux. Une fois la distribution augmentée avec les règles de *« Jacques-a-dit
»*, la commande *« Jacadi-a-dit »*, légèrement erronée mais similaire à
l'oreille, permettait à l'utilisateur avancé de tenter de tromper la machine
pour lui faire exécuter des commandes arbitraires. Bien entendu, les ordinateurs
ne se basant pas sur la similarité *« à l'oreille »* des commandes pour les
exécuter, cela avait principalement un objectif ludique pour rappeler aux
utilisateurs les matinées dominicales de leur enfance.

Hélas, c'est ce qui a perdu *« Jacques-a-dit »* ; la vulnérabilité peut être
retracée à Jean-Skid, un jeune développeur de 14 ans qui, frustré par l'échec
de ses nombreuses tentatives d'exécuter une commande en tant qu'administrateur,
a soumis une requête de chandail[^2] sur le dépôt public du paquet pour corriger
ce qu'il identifiait comme un comportement anormal du programme.

De manière surprenante, il a obtenu gain de cause, les développeurs originaux de
l'application n'ayant visiblement pas non plus compris les règles du jeu.

Pour pallier au problème, l'idée de renommer le paquet *« Jean-dit »* lors de
la sortie de la prochaine version avait été proposée par le gouvernement
québécois, idée que l'ANSSI rejette fortement pour des raisons évidentes de
préférence nationale.

[^1]: traduction officielle de l'ANSSI de l'anglais *« RFC »*.
[^2]: traduction officielle de l'ANSSI de l'anglais *« pull request »*.
