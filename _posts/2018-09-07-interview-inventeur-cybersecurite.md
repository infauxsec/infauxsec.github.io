---
layout: post
title: "Interview exclusive avec John McAfee, inventeur de la cybersécurité"
author: Ella Prono
image: "/assets/mcafee/mcafee.png"
tags: ['cybersécurité', 'mcafee', 'interview']
category: histoire
twitter_text: "L'inventeur de la cybersécurité vous dit tout"
introduction: "L'inventeur de la cybersécurité vous dit tout sur ses dernières trouvailles"
---

Dans les années 80, John McAfee créait le premier antivirus à voir le jour et
lui donnait son nom. En 2018, celui-ci promeut le premier porte-monnaie matériel
impossible à pirater, Bitfi. Ces deux accomplissements suffiraient à combler
la vie de n'importe quel homme, mais pas celle de celui-ci. Intriguée par le
fabuleux destin de John McAfee, Infauxsec News a réussi à décrocher une
entrevue avec l'homme responsable de l'invention de la cybersécurité.

Nous arrivons à la demeure de John McAfee en fin d'après-midi. Pour préserver
l'anonymat de nos rédacteurs en chef, nous portons tous des cagoules. Nous
sommes
surpris par les fouilles que nous devons subir, qui sont au nombre de quatre. Le
soleil commence à se coucher quand nous rejoignons finalement notre hôte, qui
nous invite à partager les civilités d'usage en la forme de quelques rails de
sels de bain, que nous acceptons dans le respect de la tradition locale.

Une fois bien ~~défoncés~~ détendus, notre curiosité est sans borne et nous
n'attendons plus pour questionner notre homme :

**Infauxsec News : Bonjour John ! Tout d'abord, merci pour ce chaleureux
accueil. Avant d'entrer dans le vif du sujet, une question nous brûle les
lèvres : vous avez 72 ans, par quelle prouesse supportez-vous encore une telle
consommation de drogue quotidienne ?**

McAfee : « Eh bien, tout d'abord, j'aimerais vous corriger sur un point : selon
la définition de mon dictionnaire personnel, *« Le petit McAfee »*™, je n'ai
jamais consommé de drogue, étant donné que je n'ai jamais rien introduit
d'illicite dans mon corps. Cela répond aussi à votre question : je traite mon
corps comme un temple, c'est pourquoi je fais très attention à ce que j'ingère
en ayant toujours un coup d'avance sur la législation. Je me souviens encore
de l'époque où je commençais. Je venais d'inventer la cybersécurité, et les
lois étaient encore très laxistes, alors on se faisait des injections de SQL
avec les copains dans des squats. On s'amusait bien. Maintenant, la jeune
génération a peur de ça… »

**IN : Puisque vous avez abordé le sujet, et comme c'est un peu pour ça que
nous sommes là, parlez-nous de votre invention de la cybersécurité !**

M : « C'est un sujet que je suis toujours gêné d'aborder pour plusieurs
raisons : d'une part, d'autres précurseurs se sont penchés sur ce que j'avais
découvert quelques années après moi, et je n'aimerais pas les vexer en
m'attribuant tous les mérites de mon travail tout de même bien mieux que le
leur, et d'autre part je suis maladivement humble. Je vais toutefois tâcher de
vous répondre, car Infauxsec News a prouvé maintes fois être une source
d'information fiable et honnête. Tout commence en 1987, quand j'ai formé ma
boîte d'antivirus avec des acolytes aujourd'hui tombés dans l'oubli. Bien
entendu, virus et antivirus n'existaient pas cette époque ; j'avais anticipé
la création de ce marché, c'est pourquoi tous les experts s'accordent à dire
que cet événement marque l'invention de la cybersécurité. »

**IN : Parlons de ce premier antivirus ! La twittosphère est en émoi depuis que
vous avez annoncé être le papa de la cybersécurité, mais tout le monde s'accorde
à dire que votre antivirus original est encore aujourd'hui l'état de l'art en
matière de détection de code malveillant. Qu'en pensez-vous ?**

M : « Sur ce point, je ne peux vous donner tort. Mon premier antivirus était
tellement parfait qu'aujourd'hui, les entreprises peinent encore à rivaliser.
Certaines essaient même d'incorporer du machine learning à leur solution
pour profiter du mot bourdonnement[^1] *[Rires]*. Ma solution était élégante et
efficace : `cat <filename> | head -n 1 | grep -i "virus"`. Malgré sa simplicité
apparente, on voit que j'avais déjà déduit des informations importantes *[NDLR :
c'est-à-dire que le terme « virus » se trouve toujours sur la première ligne
d'un fichier contenant un virus]* et simplifié mon code au maximum pour tenir
compte de ça. J'ai même obtenu [un prix pour ce
code](http://porkmail.org/era/unix/award.html#cat). Bien sûr, quand on a des
idées si révolutionnaires, on fait peur aux gens, c'est pourquoi j'ai été écarté
de ma propre compagnie. Mon seul regret est que la documentation ne soit pas
assez complète. »

**IN : Impressionnant, il est vrai que peu d'entreprises sont capables de
produire un code d'une telle élégance aujourd'hui. Pourtant, vous avez réussi à
en trouver une à votre goût en Bitfi. Pourtant, malgré votre parole d'or
concernant la sécurité incassable du porte-monnaie, certains utilisateurs de
Twitter continuent de prétendre avoir piraté le matériel. Quel message
aimeriez-vous leur faire passer ?**

M : « Tout d'abord, j'aimerais leur dire que ce n'est pas gentil de passer son
temps à critiquer. Ensuite, j'ai offert un prix de 100,000$, 250,000$, puis même
20,000,000$ pour que quelqu'un me prouve qu'il avait piraté le porte-monnaie, et
rien ! Certains chercheurs débutants en sécurité, comme
[Cyber-hylobatidés](https://twitter.com/cybergibbons)[^2] ont prétendu avoir
réussi, et je ne leur en veux pas : c'est tout simplement leur inexpérience qui
a parlé. En effet, ils ont réussi à obtenir des RCE sur le porte-monnaie, mais
tout le monde sait qu'en 2018, [on ne considère plus celles-ci comme des
vulnérabilités](https://infauxsec.github.io/bounties/2018/07/30/starbucks-bounty.html).
Étant donné que les menaces de mort à l'égard de ma famille n'ont pas augmenté
en volume, je considère qu'il n'y a pas eu piratage. »

*[À ce moment-là, John McAfee part se repoudrer le nez pour nous donner son
meilleur profil]*

**IN : Avant de conclure notre article, souhaitez-vous faire passer un dernier
message à nos lecteurs ?**

M : « Oui, j'aimerais faire passer un message d'espoir : dans la vie, vous
rencontrerez toujours des gens qui ne veulent pas que vous réussissiez ; le
secret, c'est de ne JAMAIS abandonner, et de bien diversifier temporellement ses
investissements. Par exemple, en allant me repoudrer le nez, j'ai reçu un appel
m'invitant à être le conseiller d'une boîte pour leur nouvelle cryptomonnaie :
le cinq-H-un-T coin *[NDLR : 5H1Tcoin]*. J'ai d'ores et déjà transféré tous
mes fonds dans cette devise, car j'y crois à 100%, elle est basée sur des
concepts révolutionnaires comme les miens. Si elle n'atteint pas 1,000,000$ en
2018, je mangerai mon pénis durant ma prochaine interview avec Infauxsec News. »

**IN : Merci John pour ces derniers conseils**

Après nous être quittés en suivant encore une fois les civilités d'usage, nos
journalistes s'empressent de transférer toutes leurs économies dans le 5H1Tcoin,
sur les bons conseils de leur nouvel ami. C'est inspirés par la grandeur d'âme,
la modestie et le talent de notre interlocuteur que nous rentrons à la
rédaction.

*EDIT :* Après avoir lu le brouillon de notre article et consulté son conseiller
en parler élite[^3], John McAfee a souhaité que nous supprimions de celui-ci les
informations concernant son soutien au 5H1Tcoin. Par éthique journalistique,
nous avons refusé, c'est pourquoi notre tête est à présent mise à prix :

![Têtes mises à prix](/assets/mcafee/mise-a-prix.png)


[^1]: traduction officielle de l'ANSSI de l'anglais *« buzzword »*
[^2]: traduction officielle de l'ANSSI de l'anglais *« Cybergibbons »*
[^3]: traduction officielle de l'ANSSI de l'anglais *« leetspeak »*
