---
layout: post
title: "Linus Torvalds rejoint Infauxsec News"
author: "Jean-Kévin Acoeur"
image: "/assets/winux.jpg"
tags: ['innovation', 'linux', 'realnews']
category: meta
twitter_text: "Les nouveaux projets de Linux Torvalds"
introduction: "Linus Torvalds vous dit tout sur ses nouveaux projets"
---

Ce dimanche, Linus Torvalds a publié, avec beaucoup d'humilité, un [email
d'excuses](https://lkml.org/lkml/2018/9/16/167) concernant son comportement
passé sur LKML. À la fin de ce courriel qui a fait trembler les internets
mondiaux, le créateur de Linux annonce vouloir faire une pause dans la
maintenance du noyau afin de pouvoir *« corriger son comportement »*.  Si ce
dernier souhaitait de prime abord développer un nouvel outil durant cet
interlude de maintenance du noyau, Infauxsec news a su voir une opportunité et
la saisir en engageant une personnalité reconnue par la communauté dans son
équipe.

Après trois journées de tractations intensives, nos arguments ont fini par
convaincre Linus de délaisser le vieux monde représenté par Linux pour
s'engager à nos côtés, à la fois dans l'écriture d'articles toujours plus
passionnants techniquement et dans le développement d'un nouveau kernel et
système d'exploitation associé, sur lesquels
il aura un pouvoir de décision total. Pour sa première journée dans
nos locaux, Linus a tenu à présenter les innovations en préparation ; en
voici donc les grandes lignes, présentées par Linus lui-même !

## Nouveau langage de programmation

*« Après avoir travaillé sur Linux pendant presque 30 ans, je me suis rendu
compte que le C n'était clairement pas le bon choix, puisque presque personne
n'est capable de développer correctement en utilisant ce langage. C'est
pourquoi, pour éviter de m'énerver lorsque les membres de l'équipe feront
des PR, j'ai décidé de passer au Rust. »*

## Nouveau système de fichiers

*« Après 11 ans de développement, Btrfs est stable, mais a déjà montré ses
limites (la plus grande étant que le projet a été initié par Oracle). Il me
fallait un nouveau système de fichiers, plus en accord avec mes aspirations,
c'est pourquoi j'ai opté pour l'utilisation de NTFS. »*

## Normalisation des noms des utilitaires

*« Les utilitaires d'administration système n'ont pas toujours eu des noms
aisés à retenir dans les distributions Linux. C'est pourquoi je vais faire
primer la cohérence cette fois-ci en renommant les outils maladroitement
nommés. Par exemple,* `ifconfig` *deviendra* `ipconfig`*. »*

## Fermeture du code source

*« Il s'agit d'un des points sur lesquels j'ai le plus longuement réfléchi.
Lors du développement du kernel Linux, les contributeurs ont subi mon
comportement inacceptable durant des années. J'ai enfin pris conscience que
le problème venait de moi, car j'ai un gros problème pour gérer ma colère,
étant très perfectionniste. Je vais travailler là-dessus, mais le chemin est
long. C'est pourquoi, pour préserver ma santé mentale dans un premier temps,
le code ne sera pas ouvert durant une période encore indéterminée. »*

## Remaniement du logo

*« Si je dois travailler sur ma personnalité, j'ai tout de même fait
beaucoup de mal à la communauté durant toutes ces années, agissant comme un
portier*[^1] *plutôt exclusif. Afin de promouvoir l'inclusivité dans mon
nouveau projet, j'ai souhaité remanier Tux en le stylisant cette fois-ci avec
quatre couleurs supplémentaires faisant référence à la communauté
LGBTIQ+* [NDLR : voir illustration de l'article]*. »*

## Intégration de support multiplateforme

*« J'ai trouvé que le WSL (Windows Subsystem for Linux) sur Windows 10 était
une innovation très intelligente, puisqu'elle permet enfin aux utilisateurs de
Windows de profiter des atouts des deux systèmes. Dans l'optique de suivre
cette belle initiative et même de l'emmener un cran plus loin, j'ai décidé de
reprendre le code de Wine et de l'intégrer directement au kernel afin de
fournir à l'utilisateur un support natif de l'API Windows. »*

## Harmonisation de l'API du kernel

*« Ceci suit directement le dernier point. Avec la débâcle systemd, j'ai pu
constater que personne n'en avait rien à faire de la supervision correcte et
que les utilisateurs préfèrent nettement écrire des scripts à usage unique.
Dans cette optique, je propose d'harmoniser l'API du kernel en ce sens en
dépréciant* `fork()` *au profit de* `CreateProcess()`*. »*

## ASLR configurable

*« Pour rendre le déboguage plus facile, j'aimerais que les utilisateurs
puissent compiler chaque binaire avec l'ASLR activé ou non, quelque chose qui
n'est pas faisable sur Linux. En échange de ceci, l'ASLR ne sera initialisé
qu'au démarrage, signifiant que l'adresse de base d'un programme ne changera pas
entre deux exécutions successives. »*

## Changement de système de partage de fichiers

*« Avec Linux, on a clairement pu toucher aux limites de NFS en tant que système
de partage de fichiers. Je souhaite simplement le déprécier pour passer à SMB,
un système bien plus sécurisé et qui a fait ses preuves. »*

## Changement de nom

*« Le changement de nom est primordial ; ce système est une version bien trop
améliorée de Linux pour qu'il puisse conserver ce nom. En plus, j'y ai
longuement réfléchi, il est temps de faire peau neuve. "Linux" était le produit
de ma personnalité négative "Linus", un truc de "Loser". Mon nouveau projet
sera toujours éponyme, car je vais changer mon nom en "Winus", ma nouvelle
personnalité positive et "Winner". Mon produit s'appellera donc "Winux". D'un
point de vue plus personnel, je réfléchis également à me faire un tatouage de
papillon en bas du dos pour symboliser ma métamorphose. »*

Toute la rédaction d'Infauxsec News est honorée de pouvoir accompagner Winus
dans cette nouvelle aventure, qui devrait marquer une nouvelle ère dans le monde
de l'informatique.

[^1]: traduction officielle de l'ANSSI de l'anglais *« gatekeeper »*
