---
layout: post
title: "Les langages post-pandémie : COVID++19 ou Gorona ?"
author: "Jess Socks"
image: "/assets/gorona-vs-cpp.png"
tags: ['COVID++19', 'Gorona']
category: fourchelangue
twitter_text: ""
introduction: "Notre analyse comparative détaillée des deux langages"
---

Stupeur et consternation constante, ces deux derniers mois, alors que les
autorités des divers pays européens bataillent vainement pour empêcher la
pandémie COVID-19 de gagner du terrain. Depuis l'instauration du confinement en
France, le temps n'est plus seulement à la prise de mesures répondant au danger,
mais également à la préparation de futures mesures préventives pour éviter à une
telle situation de se reproduire.

Évidemment, cela impacte également le domaine numérique : entre deux injections
de billions[^1] de dollars, la FDIC a consenti à subventionner la recherche
internationale en informatique pour le montant exorbitant de 200 000$ sur 5 ans
afin de concevoir un langage de programmation résilient et respectueux des
normes sanitaires mises en place en temps de pandémie. Grâce aux fonds débloqués
par le gouvernement, ce ne sont pas un mais deux groupes de recherche qui ont pu
arrêter de cueillir des fraises et se mettre au travail.

Infauxsec News a pu interviewer un des meneurs de chaque groupe, Jean-Bjarne
Stroustrup, architecte principal du langage COVID++, et Jean-Ken Thompson,
auteur de Gorona, afin d'en savoir plus.

*« COVID++ est le plus sérieux candidat comme langage industriel du futur »*,
avance Jean-Bjarne. *« Nous ne partons pas de zéro ; c'est une évolution
des standards précédents. La dernière itération, COVID++19, corrige et
améliore tout ce que ses détracteurs pouvaient reprocher à une première version
du langage, comme ANSI COVID. Nous disposons de fonctionnalités uniques
pour l'isolation sociale des programmes ; par exemple, nous avons un allocateur
dédié qui impose 2 mots d'éloignement minimum entre les variables locales. »*

*« L'approche de Jean-Bjarne est vouée à l'échec »*, commente pour sa part
Jean-Ken. *« L'expérience montre que les programmeurs sont incapables de
comprendre des consignes complexes. C'est pourquoi Gorona inclut des
concepts radicaux, comme un ramasse-miettes sans contact, et une passe
de compilation dédiée au nettoyage des mains. Nous proposons aussi un
changement de paradigme, avec le concept de guarantaine : la communication
entre plateaux[^2] se fait uniquement en déposant des messages dans des
boîtes aux lettres, messages qui sont ensuite isolés pendant 40 jours
puis soigneusement désinfectés. »*

Jean-Ken ne se prive pas non plus de critiquer les innovations du langage
concurrent, et continue :

*« Ils me font bien rigoler, avec leur allocateur. C'est une approche digne
du siècle passé. Nous, nous avons mis au point un système révolutionnaire :
qui reste compatible avec l'arithmétique des pointeurs : nous inversons
le boutisme[^3] de tous les pointeurs en mémoire. Ainsi, nous gardons une
indexation efficace des tableaux, et vous pouvez continuer a écrire `tab[1]`
comme d'habitude, mais notre système garantit que `tab[0]` et `tab[1]` ne seront
jamais dans la même ligne de cache. »*

Mais si les deux équipes ont des solutions concurrentes d'adressage au niveau
logiciel, elles ne se privent pas d'exploiter les solutions matérielles dernier
cri pour faire respecter les normes sanitaires.

*« Pour nous assurer que le port de masque est bien respecté pour tous les
pointeurs, Gorona propose l'utilisation de la Mémoire Graffiti Extension[^4]
développée par ARM »* explique Jean-Ken. *« Si un pointeur sort sans le bon
masque, le programme s'interrompt automatiquement et un courriel de dénonciation
est envoyé à la préfecture. Les pirates ne feront pas leurs rigolos longtemps
avec Gorona. »*

Son de cloche similaire mais moqueur chez Jean-Bjarne, qui raconte :

*« Jean-Ken devrait arrêter de programmer, la Mémoire Graffiti Extension c'est
tellement 2018 et ce n'est même pas encore réellement utilisable. Pour COVID++,
nous avons décidé de rester ancrés dans le réel tout en fournissant une vraie
solution à nos utilisateurs : grâce au Pointeur Authentification Code[^5], nous
pouvons signer des autorisations de sortie officielles pour tous nos pointeurs,
afin d'être sûrs à 100% qu'ils respectent le confinement dans le bac à sable.
Et puis, tout à fait entre nous : changement de paradigme, mes fesses !
ça fait des siècles qu'on connaît le principe de la quarantaine, et ils croient
révolutionner l'informatique en changeant une lettre ? »*

Les deux groupes de recherche s'accordent toutefois à dire que leur projet rame
à cause de la fondation LLVM, qui apparemment mettrait trop de temps à
développer sa nouvelle option de compilation HSAN[^6].

[^1]: traduction officielle de Larousse de l'anglais *« trillions »*.
[^2]: traduction officielle de l'ANSSI de l'anglais *« threads »*
[^3]: traduction officielle de l'ANSSI de l'anglais *« endianness »*.
[^4]: traduction officielle de l'ANSSI de l'anglais *« Memory Tagging Extension »*.
[^5]: traduction officielle de l'ANSSI de l'anglais *« Pointer Authentication Code »*.
[^6]: Hand Sanitizer.
