---
layout: post
title: "Un jeune homme entre dans la légende du bug bounty"
author: "Derek Toritra-Vershal"
image: "/assets/starbugs.png"
tags: ['barres chocolatées', 'exploitation']
category: bounties
twitter_text: "un jeune homme aurait réussi à obtenir un bounty de la part de Starbucks"
introduction: "Il aurait obtenu un bounty de la part de Starbucks"
---

Réjouissances et excitation ce matin alors que Jean-Boon Ty annonce avoir
accompli un exploit que toute la communauté des bounty hunters jugeait
impossible ; en effet, le jeune chasseur de primes aurait réussi à décrocher
le Graal dans le milieu, c'est-à-dire un bug bounty de la part de Starbucks.

Une rapide visite sur HackerOne semble corroborer les dires de Jean-Boon : on
y découvre un rapport, qui, s'il n'est pas exposé publiquement, indique que la
récompense *« 1 T-shirt "I love Starbugs" »* a été remise au chasseur l'ayant
rédigé.

Du côté de Twitter, l'heure est à la spéculation : quelle vulnérabilité
pourrait avoir donné lieu à une telle récompense de la part de Starbucks ?
La rédaction d'Infauxsec News, toujours fidèle au poste, a contacté
Jean-Boon Ty afin d'obtenir des éclaircissements sur cette affaire.

*« Ça n'a pas été facile »* confirme-t-il. *« Il faut bien comprendre que le
contexte est assez défavorable aux experts en sécurité aujourd'hui. Après plus
de 30 ans de code de merde dans les entreprises, tout est troué ; on est même
obligés de payer pour que les entreprises prennent nos RCE pour pouvoir faire
de la place sur nos disques. »*

Il nous indique que le rapport a mis 2 ans et demi à être marqué comme résolu,
un délai relativement court dans le domaine des bug bounties ; pourtant,
Jean-Boon aura dû approfondir sa vulnérabilité à plusieurs reprises pour
mériter sa récompense :

*« Je suis tout d'abord parvenu à contrôler toute l'infrastructure interne de
Starbucks en exploitant une SSRF dans le CSS de la page d'accueil de
*[https://www.starbucks.com](https://www.starbucks.com) *et j'ai fait tomber la
base de données de production. Malheureusement, cette vulnérabilité était
hors scope. Après ça, j'ai utilisé mon accès à leur système pour deface les
fiches de paye des employés en y écrivant "Hacked by Jean-Boon" à la place
du salaire, mais ça n'a pas suffi à les faire changer d'avis. Heureusement, Starbucks est
une entreprise honnête qui sait récompenser les bounty hunters lorsqu'ils
trouvent des vulnérabilités hors scope, pour peu que l'impact sur leurs services
soit démontré ; il m'a suffi de kidnapper les enfants du CEO en me servant de
son calendrier présent sur les services internes pour que Starbucks reconnaisse
l'impact de ma découverte. »*

Une récompense qui fait chaud au cœur, et démontre qu'en comptant sur des
acteurs de bonne foi, le bug bounty aura encore de beaux jours devant lui.

### Crédits

Article inspiré d'une idée originale de
ee9a25c95b7fe661a2401c32bd8bd4efb08ce6323d4a461cb7ee818a57c5f57f et des rapports
[https://hackerone.com/reports/316789](https://hackerone.com/reports/316789) et
[https://hackerone.com/reports/153026](https://hackerone.com/reports/153026). 
