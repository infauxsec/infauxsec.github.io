---
layout: post
title: "Le groupe de hackers « TubeSec » sème la terreur sur Internet"
author: "Victor Hayden-Cervix"
image: "/assets/tubesec.jpg"
tags: ['youtube', 'hacking']
category: skidz
twitter_text: "Un dangereux groupe de hackers entraîné à coups de vidéos YouTube"
introduction: "Ces dangereux pirates se sont formés uniquement en regardant des vidéos de hacking sur YouTube"
---

Stupeur et consternation, hier, sur les Internets mondiaux, alors qu'un
nouveau groupe de hackers sème le chaos en travers des autoroutes de
l'information.

Le groupe, qui s'est choisi le nom de *« TubeSec »*, se compose d'une nouvelle
génération de jeunes prodiges qui, contrairement à leurs ainés, se sont
formés uniquement en regardant des vidéos de hacking sur Youtube.

La rédaction d'Infauxsec est entrée en contact avec Jean-Tube Macaron,
leader autoproclamé du groupe, plus connu sous le pseudonyme de 
*« TubBoy »*. TubBoy est le chercheur principal du groupe, et a déjà
à son actif un nombre impressionnant de 0-days. Il est entre autres
le découvreur de la vulnérabilité `tracert`, qui permet d'identifier
à distance les endpoints d'un serveur tcp, comme expliqué dans cette
célèbre vidéo :

<iframe height="400" src="https://www.youtube.com/embed/SXmv8quf_xM"></iframe>

En exclusivité, TubBoy a accepté de nous parler de son projet actuel,
une vulnérabilité exploitable à distance dans la plupart des serveurs
http. Il procède à une démonstration devant nous, dans les locaux
de la rédaction. Il tape la commande suivante:

```bash
curl -s -D - www.google.com | grep Set-Cookie
```

Devant nos yeux ébahis, TubBoy nous explique la portée de sa découverte.
*« Voyez, avec cette commande, j'ai réussi à voler un cookie au serveur.
Et tout le monde sait que se faire voler un cookie est très dangereux
pour la sécurité. J'ai lu ça sur le blog de Korben. Mais ne vous
inquiétez pas, il faut une certaine expertise dans le domaine du
hacking digital pour arriver à utiliser un truc comme ça. Tout le monde
ne peut pas être aussi doué que l'élite. »*

Pourtant, si ses découvertes ont le potentiel pour déstabiliser Internet,
TubBoy n'est animé d'aucune malveillance. *« Si j'ai commencé à faire
ce genre de choses, c'était surtout pour être cool, vous comprenez.
La vie de geek célibataire n'est pas toujours facile. J'espère un jour
trouver une TubGirl avec qui je m'entendrai bien. Peut-être qu'avec
une bonne réputation dans la communauté, j'augmenterai mes chances. »*

### Crédits

Article inspiré d'une idée originale de 950c91ed4c6dd9b4b5ba28f0696e94f5ec9db1e3d7a87427f3f7cd95f541530c.
