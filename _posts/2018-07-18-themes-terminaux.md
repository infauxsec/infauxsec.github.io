---
layout: post
title: "Les couleurs les plus tendances pour vos terminaux cet automne"
author: "Hans Gruber"
image: "/assets/terminal.jpg"
tags: ['terminal', 'mode']
category: mode
twitter_text: "Les #couleurs les plus #tendances pour vos #terminaux cet automne"
introduction: "Adoptez le style de vos hackers préférés"
style: "/assets/terminal.css"
---

L'automne approche, et avec lui, le retour de vacances, la rentrée au travail,
et bien entendu, les jugements superficiels sur l'apparence de votre desktop.
Pour éviter les mauvaises surprises, il vous faut dès maintenant
commencer à affiner le thème de couleurs de votre éditeur de texte,
et y assortir votre terminal si nécessaire, pour épater tous vos collègues dans le
bureau !

Toujours au top des dernières tendances mode, Infauxsec a sélectionné pour
vous les colorschemes des hackers les plus *trendy*, dont nous vous conseillons
de vous inspirer pour créer votre propre style.

### Le style RMS

{:.stallman}
```elisp
(while linux-exists
  (if (string-match-p "GNU" (nameOf distribution))
    (progn
      (rant-about distribution)
      (say (how_much ubuntu sucks))
      (blame_for vi everything
      )
    )
  )
)

```

Vous avez une barbe et des cheveux longs ? Vous aimez tout créer vous-même,
des langages de programmation aux OS en passant par les éditeurs de texte, parce
que tout ce que font les autres n'est pas assez bien pour vous ? Adoptez
le style Richard Stallman ! Les couleurs terreuses évoquent le gnou gambadant
gaiement dans la savane, et se marieront à merveille avec le teint cireux
typique des hackers Lisp enfermés dans leurs caves.

### Le style Linus

{:.linus}
```c
void broadcast_rage_rant(targets_t *target)
{
    message_t msg;

    for (; target; target = target->next) {
        message_init(&msg);
        msg.target = target;

        if (FECAL_MATTER == target->brain) {
            while (rand() < RANT_STOP_PARAM) {
                message_add_insult(&msg, target, random_insult(GLOBAL_INSULTS));
            }
        }

        post_to(LKLM, &msg);
        message_cleanup(&msg)
    }

}
```

Vous n'avez pas votre langue dans votre poche, vous ne supportez pas
l'incompétence, et vous aimez vous défouler sur les incapables ?
Toute votre équipe tremble à l'idée de déclencher une de vos
mémorables explosions de rage ? Les couleurs sanguines du thème Linus 
sauront instiller la crainte dans le coeur de tous vos ennemis au
sein de l'open space.

### Le style Mitnick

{:.mitnick}
```shell
#!/bin/sh

echo -en "\033[1;31m[*] Starting SUPER S33KR3T EXPLOITZZZ !"
sleep 1
echo -n "."
sleep 1
echo -n "."
sleep 1
echo -n "."
echo -e "\033[1;32mOK !!!\033[0m"
export PS1="# "

```

Vous cherchez l'approbation de vos managers qui n'y connaissent rien mais
sont très impressionnables par l'apparence ? Vous aimez ~~bullshitter~~parler
technique avec ceux qui n'y connaissent rien, porter des lunettes de soleil,
et vous reposer sur vos lauriers pendant très, très longtemps ? Le style
Mitnick est fait pour vous ! Sobre mais underground, il fera de vous la
coqueluche de vos supérieurs.

### Le style Poettering

{:.poettering}
```c
/* systemd-ebgp-router.c */

#include "alloc-util.h"
#include "udev.h"
#include "http.h"
#include "crypt.h"
#include "vty.h"
#include "rfkill.h"
#include "pulseaudio.h"
#include "hypervisor.h"
#include "fuzzing.h"
#include "bootloader.h"
#include "sat-solver.h"
#include "quantum-computing-utils.h"
#include "tensorflow.h"

```

Vous êtes un visionnaire, un esthète, un architecte des systèmes complexes ?
Vous aimez avoir un plan basé sur une vision globale, sans trop vous préoccuper
des détails, que vous confiez sans hésiter à vos subordonnés moins doués
que vous ? Vous vous tamponnez pas mal de la fonction, tant que la forme y est ?
Le style Poettering vous ira comme un gant (ou plutôt
comme une moufle, beaucoup plus élégante avec son compartiment unique).

### Le style ESR

{:.esraymond}
```c
int main() {
    int c;
    void *tinfoil_hat;

    tinfoil_hat = malloc(1000000);
    write_crappy_pop3_program();
   
    for (c=0; c <= BUG_COUNT; c++) {
        fix_bug_in_program();
        update_jargon_file();
    }

    sleep(911);

    if (crazy = true) 
        wear(tinfoil_hat);
        send_death_threats_to_bruce();

}
```

Vous aimez l'odeur du napalm au petit matin ? Vous êtes fan des belles
mécaniques, en particulier celles comportant une culasse et un magasin ?
Vous en avez marre de tous ces SJW qui prétendent que le QI des noirs
est comparable à celui des blancs ? Adoptez le style Eric S. Raymond,
qui aura l'énorme avantage de stimuler la fibre nationaliste des français
aussi bien que celle des américains.

### Le style Bluetouff

{:.bluetouff}
```shell
#!/bin/sh

for SITE in $(cat sites-gouv-fr.txt)
do
    for p in $(wget -O "$SITE/robots.txt |grep 'Disallow:' |cut -f2)
    do
        wget -r "$SITE/$p"
    done
done
```

Vous aimez les protocoles de communication *vintage*, les jeux de mots un peu lourds,
et servir de martyr à l'incompétence technique du gouvernement ? Tournez-vous
sans hésiter vers le style Bluetouff, qui ravira vos mirettes avec ses délicates
nuances d'azur.

Et vous, quel est votre thème préféré ? Dites-le nous en commentaire !
