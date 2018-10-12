---
layout: post
title: "Cybercriminalité : la France dort sur ses deux oreilles"
author: "Jean-Kévin Acoeur"
image: "/assets/triskel.png"
tags: ['police']
category: société
twitter_text: "Cybercriminalité : la France dort sur ses deux oreilles"
introduction: "Les forces de l'ordre au taquet pour arrêter les pires criminels"
---

C'est par une froide matinée d'octobre que nous nous rendons chez
Jean-Maurice, 53 ans, chef de la cellule de lutte anti-cybercriminalité des
Auvergne. Jean-Maurice nous a invités pour assister, en exclusivité,
à sa dernière opération coup-de-poing contre un dangereux cyberterroriste
qui menace la sécurité nationale.

## L'histoire d'un succès à la française

Il faut dire que Jean-Maurice n'en est pas à son coup d'essai ; c'est à lui
que revient, entre autres, l'honneur d'avoir organisé
[l'arrestation d'un dangereux cyberterroriste][http://infonie.org/DCRI.OneYearLater.html] en janvier 2012. Ce sinistre individu aurait ainsi permis a un groupe
de dangereux hackers en cagoules de discuter en toute impunité.

C'est Jean-Maurice également qui, toujours en 2012, met le grappin sur
le sinistre [Olivier Laurelli][https://bluetouff.com]. Ce dangereux pirate,
maître dans l'art de la militarisation des moteurs de recherche, aurait ainsi
volé plusieurs gigaoctets de données à une agence gouvernementale. A notre
connaissance, il n'aurait d'ailleurs jamais rendu ces données volées.

## Un travail d'orfèvre pour identifier le coupable

Dans les locaux de la DGSI, la pendule murale affiche 9h02, et les premiers
collègues de Jean-Maurice arrivent pour prendre leur service dans la salle
de briefing. Leur cible, aujourd'hui : un élusif escroc, l'auteur d'une Avancée
Persistante de Menace[^1] nommé `chmod`. Jean-Maurice nous résume la situation
en quelques mots:

*« Chmod est un maliciel extrêmement pernicieux. Il est capable de modifier
les autorisations d'accès dans un système unix, et donc de répandre le chaos.
Une brève analyse montre qu'il a infecté près de 95% des sites que nous
avons inspectés. Il est donc vital d'endiguer cette infection le plus
vite possible. »*

Pour identifier l'auteur, Jean-Maurice va avoir recours à une source anonyme,
dont il tient absolument à préserver l'identité. Nous ne la mentionnerons que
par son nom de code : le Moyeu des Cons.

D'une manière ou d'une autre, cette source réussira a obtenir le [code source du
malware Chmod][https://github.com/coreutils/coreutils/blob/master/src/chmod.c].
Les collaborateurs de Jean-Maurice se mettent alors au travail ; et deux heures
plus tard, juste avant la pause déjeuner (11h30), le verdict tombe : l'identité
de l'auteur est connue. Comme la plupart des hackers, dont l'égo est
surdimensionné, il n'a pu résister à l'envie de signer son forfait ; il a
laissé son nom dans un commentaire, bien caché au milieu du code source. Le
coupable répond au doux nom de David J. MacKenzie.

Jean-Maurice doit maintenant prendre une décision difficile : continuer
l'enquête et renforcer son dossier, ou passer immédiatement la main à ses
collègues de la BAC pour interpeller le malfaiteur avant qu'il ne commette
son prochain forfait. Mais devant l'ampleur de la dissémination de l'infection
par `chmod`, il finit par se prononcer en faveur de la seconde alternative.

Une fois l'équipe rentrée de la pause déjeuner (autour de 14h30), elle
joue contre la montre ; l'objectif est d'identifier le lieu de résidence de
l'individu avant la fin de la journée (15h45) pour passer la main à l'équipe
d'intervention de choc. Heureusement, Jean-Cyprien, l'expert en OSINT
du groupe, en a vu d'autres : quelques clics sur Wikipédia, et il identifie
la couverture de MacKenzie: celui-ci se cache en Écosse, où il se fait passer
pour un honnête réalisateur de films.

Au bureau, la consternation règne : le criminel est hors de la juridiction de
l'équipe. Jean-Maurice décide finalement de contacter son homologue
britannique au MI5 pour lui transmettre l'information. Ce soir, l'odieux
génie du mal dormira en cellule.

Ainsi, nous nous rassurons : les français peuvent dormir tranquille, car tant
que de braves éléments comme Jean-Maurice veilleront au grain, nous n'aurons
rien à craindre de ces criminels sans foi ni loi. Et dormez bien, braves gens !

## Crédits

Lointainement inspiré d'une idée de
e85d9a791dd3223a69925f0e4e40a7097f5bdc2743f6150c636fa1c4009b0c3c.

[^1]: Traduction officielle de l'ANSSI de l'anglais *« Advanced Persistent Threat »*
