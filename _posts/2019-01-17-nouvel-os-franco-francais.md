---
layout: post
title: "L'ANSSI dévoile ses plans pour un OS souverain moderne"
author: "Victor Hayden-Cervix"
image: "/assets/paraos.jpg"
tags: ['HADOPI', 'ClippyReviens', 'FuckQubes']
category: souveraineté
twitter_text: "L'ANSSI dévoile ses plans pour un OS souverain moderne"
introduction: "Des cendres de ClipOS naît ParallélépipèdOS"
---

Stupeur et consternation, hier, chez les divers groupes APT adversaires de
l'Hexagone, alors que l'ANSSI dévoilait ses plans pour une nouvelle version
révolutionnaire d'un OS souverain et à la sécurité inégalée.

Répondant au doux nom de ParallélépipèdOS, cet OS révolutionnaire[^1] est basé
sur une distribution Linux utilisant la solution de paravirtualisation Xen.
Il permet d'isoler chaque application dans un conteneur dédié. Les développeurs
nomment ces conteneurs des Pavés. Les données
de l'OS de base sont installées dans un volume séparé, accessible uniquement
en lecture seule, et géré par LVM, tandis que les données de travail de chaque
conteneur résident dans un volume séparé. Ainsi, il est possible de mettre à
jour tous les pavés en une seule opération, sans gaspiller d'espace disque.
Le tout est piloté par une interface graphique et un ensemble de services
maison entièrement écrits en OCaml.

Sous les pavés, on trouve une plage[^2] d'adresses réseau internes,
utilisée par une série d'interfaces virtuelles, qui permettent
aux pavés de communiquer entre eux.
Pour servir de firewall et/ou de passerelle VPN entre les différents pavés,
on utilise un pavé dédié, contenant OpenOffice préinstallé.
Ceci permet de cacher au pavé l'utilisation d'un VPN de sortie, et
de lui interdire de modifier ses propres règles de filtrage.

L'installation par défaut de ParallélépipèdOS inclut évidemment un pavé
préconfiguré pour utiliser le [Routeur à Echalotes](/anonymat/2018/07/27/le-routeur-a-echalotes.html).

Pour l'utilisation de programmes historiques ne fonctionnant que sur des OS
inférieurs, ParallélépipèdeOS offre bien sur des conteneurs hôtes, utilisant
la virtualisation traditionnelle. Mais pour un certain OS obsolète
en particulier, l'installation par défaut inclura Coq au Vin, une
fourchette[^3] de WINE mais entièrement vérifiée par des méthodes formelles.

À noter encore : pour la construction automatique des images de pavés,
ParallélépipèdOS prévoit de bientôt supporter [Marcel](https://github.com/brouberol/marcel), le docker français. Pour l'instant, la gestion automatique
des configurations utilise un outil de gestion de configuration maison,
nommé Piment d'Espelette.

Devant une telle foison d'innovations technologiques, il est fort navrant
mais probablement inévitable que d'éternels insatisfaits se plaignent
du gaspillage des deniers publics. Des insatisfaits comme Jean-Michel,
le [cyber-survivaliste](/societe/2018/08/03/enquete-cyber-survivalistes.html)
que nous connaissons bien, et qui nous confie, rageur: *« C'est une véritable
honte. Ces solutions de sécurité sont une catastrophe politique; maintenant, 
n'importe quel pédophile pourra se mettre complètement hors de portée de la
justice. Ils ne s'en cachent même pas, c'est écrit dans le nom, là:
ParallélépiPEDOS. Ne venez pas me dire que c'est un accident. »*

Heureusement, il ne s'agit que d'une minorité, et ParallélépipèdOS est bien
parti pour rencontrer un bien meilleur succès que son prédécesseur, ClipOS,
qui avait laissé la communauté de marbre (en particulier de par l'implémentation
défaillante de sa fonctionnalité phare, un outil de clipping supposé faciliter
le [paint-testing](/professionalisme/2018/10/10/paint-testing-pratique.html)).

## Crédits

Sur une idée originale de Princ3ssYuna.

[^1]: Dont le concept a depuis été honteusement volé par certaines nations rivales, NDLR.
[^2]: Si tu as compris cette vanne, bienvenue au club des vieux débris.
[^3]: Traduction officielle de l'ANSSI de l'anglais *« fork »*.
