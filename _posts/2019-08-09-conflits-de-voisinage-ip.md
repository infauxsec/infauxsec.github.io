---
layout: post
title: "Ces conflits de voisinage qui vous empoisonnent la vie"
author: "Jess Socks"
image: "/assets/conflit-ip.jpg"
tags: ['voisinage']
category: Société
twitter_text: "Les conflits de voisinage d'IP échauffent les esprits cet été"
introduction: "Le propriétaire de 8.8.8.7 témoigne a visage découvert"
---


Août, le mois préféré des campeurs et fêtards de tout bord, ne fait pas toujours
que des heureux. L'exubérance des uns fait le malheur des autres, et ce dans le
cyber-espace également. Notre équipe est partie à la rencontre de Jean-Cyprien,
0x10 ans, assistant du responsable IT du marchand de glaces du campus Google à
Mountain View. Là-bas, nous avons pu recueillir son son émouvant témoignage.


Jean-Cyprien pensait faire une bonne affaire lorsqu'il s'est vu attribuer
l'addresse 8.8.8.7 pour son serveur dédié personnel, une charmante petite box
au sein d'un bloc tranquille, avec une adresse conviviale et mémorable ; le rêve
pour un informaticien amoureux des belles choses. C'était en 2007.


Les ennuis de Jean-Cyprien commencent 2 ans plus tard, lorsqu'emménage une
famille nombreuse à l'adresse voisine, au 8.8.8.8. Depuis, les visites s'y
succèdent à un rythme effréné et délirant. Jean-Cyprien est rapidement incommodé
par le bruit et l'odeur du trafic ARP incessant, qui avoisine un trillion de
requêtes au quotidien, dont certaines sont fréquemment dirigées vers sa propre
adresse pour cause de fautes de frappe. Il s'en plaint plusieurs fois aux
autorités compétentes mais ses appels au calme restent sans effet.


*« C'est absolument intolérable »*, nous raconte Jean-Cyprien. *« Au début, il
s'agissait seulement de quelques requêtes par minute, mais on dirait que tous
les jeunes se sont donnés le mot. En plus, leur téléphone sonne sans arrêt.
Ping ! Ping ! Ping ! Ping ! ça va me rendre fou. Et ils font la fête 24h/24.
C'est comme s'ils s'étaient donné le mot sur les réseaux sociaux. En plus,
ils n'utilisent même pas DNSSEC, ils se fichent de la confidentialité de leur
trafic DNS, ils se fichent de l'efficacité des caches ! Bortzmeyer, au
secours ! »*

Nous avons contacté l'autre voisin de 8.8.8.8, à l'adresse IP 8.8.8.9, qui
n'a pas souhaité commenter.

Pour sensibiliser la jeunesse au problème, l'ANSSI a immédiatement lancé sur
Twitter une opération de mercatique virale, encourageant les membres de la
communauté à faire connaissance avec leurs voisins d'adresse IP. Si vous
utilisez un système d'exploitation professionnel, tels ceux de la société
américaine MiniDoux, vous pouvez utiliser la commande `net send` pour
faire connaissance avec vos sympathiques voisins. Pour les autres, nous
recommandons l'utilisation de `nmap`.
