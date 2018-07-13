---
layout: post
title: "Infauxsec vous dit tout sur les nouvelles fonctionnalités de Python 4"
author: "Jean-Kévin Acoeur"
image: "/assets/python4.png"
tags: ['python', 'code']
category: code
twitter_text: "Les nouveautés dans python 4"
introduction: "Une refonte intégrale du langage."
---

Il y a 10 ans déjà sortait la 3<sup>ème</sup> version du langage Python. En
s'autorisant à rompre la compatibilité avec les versions précédentes, les
concepteurs du langage se donnaient l'occasion de corriger quelques vieilles
verrues comme par exemple la gestion de l'encodage du texte, et de simplifier
un peu le parser.

Nous sommes en 2018, et s'il s'avère que Python 3 a passé avec succès le test
du temps, ces années de feedback ont révélé de nouveaux problèmes récurrents.
L'équipe de développement de Python travaille déjà sur une version 4, qui
elle aussi apportera son lot d'incompatibilités. Jean-Guido, contributeur
clef du projet, a accepté de nous présenter les changements les plus
significatifs prévus pour la nouvelle version.

### L'indentation facultative

Python se démarque d'autres langages par son utilisation de l'indentation
pour marquer les blocs. Un choix universellement décrié, car il cause
d'innombrables problèmes de compatibilité entre éditeurs utilisant
des tabs ou des espaces. Il complique également l'utilisation du
copier-coller, une technique absolument essentielle pour le programmeur
moderne. En python 4, les accolades (`{` et `}`) seront désormais
utilisées pour délimiter les blocs.

### Nouvelles structures de contrôle

L'implémentation des boucles `for` via les itérateurs s'avère inefficace
pour 99% des boucles, dans lesquelles on se contente généralement
d'incrémenter un index. Un nouveau style de boucle, inspiré du C, viendra
combler ce manque. L'appel a un itérateur générique se fera désormais au moyen
du mot-clef `foreach`.

Python 4 introduira également l'instruction `switch`, comblant une très sérieuse
lacune des versions précédentes.

### Interpolation des strings

En Python 3, le formatage des strings était passablement inefficace, avec
la nécessité d'appeler sans arrêt la méthode `format`. Même avec la nouvelle
syntaxe `f""`, le marqueur d'interpolation `{}` fait deux caractères, soit un de
trop. Python 4 suivra les meilleures pratiques établies par les langages
concurrents en adoptant le `$` pour l'interpolation des variables.

### Meilleure intégration des librairies de base

Pip et setuptools sont de véritables cauchemars à utiliser. Virtualenv
est un mécanisme fragile (un simple changement du path de base suffit
à le casser). Télécharger des packages en vue d'une installation sur un
système non connecté à Internet relève de la gageure absolue. Ceci rend
le déploiement dans des environnements sécurisés très problématique.
Les librairies les plus utiles (comme le client MySQL) seront désormais
intégrées directement dans la librairie standard.

### Révision des mots-clés

Le mot-clé `def`, peu intuitif, sera remplacé par le plus explicite
`function`. Le mot-clé `print`, peu ergonomique, sera remplacé
par le plus sympathique `echo`. `import` sera remplacé par `include`
pour des raisons similaires.

### Meilleure ergonomie des variables

Les programmeurs python dépendent énormément de la coloration syntaxique
pour écrire du code correct, puisque rien ne distingue les mots-clef des
noms de variables. Ceci est discriminatoire envers les programmeurs
daltoniens, qui représentent tout de même 5% de la population. Ce problème
sera résolu par l'introduction d'un sigil obligatoire (`$`) devant chaque
utilisation du nom d'une variable.

### Meilleure intégration avec le Web

L'architecture des services distribués modernes n'a plus grand-chose à voir
avec celle d'il y a 10 ans. HTTP et JSON sont devenus omniprésents pour tous
types de RPC. L'écosystème Web de Python est fragmenté entre différents
frameworks incompatibles, et différentes implémentations de serveurs web.

Python 4 unifiera tout cela, et simplifiera le déploiement des applications Web,
en adoptant un système unique de service et de dispatch pour les pages Web.
Cet ingénieux mécanisme, qui fera automatiquement correspondre une URL
avec un script séparé, se nommera Python Hypertext Processor. Vous pourrez
simplement uploader vos scripts `.py` dans le répertoire idoine plutôt que
d'avoir à instancier votre application Web comme avec WSGI.


Nous remercions chaleureusement Jean-Guido pour ses explications fort
complètes, et nous réjouissons d'entrer dans le futur avec Python 4 !
