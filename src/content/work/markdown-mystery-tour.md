---
title: Minivilles (Non-officiel)
publishDate: 2019-04-12
img: /assets/stock-1.jpg
img_alt: Image du jeu éponyme
description: |
  Adaptation du jeu Miniville en format virtuel sous JAVA.
tags:
  - Jeu
  - Dev
  - Simulation
---

## Minivilles

> Première adaptation d'un jeu de société

Dans le cadre de mes études, nous avons choisi le sujet trivial, mais pourtant non sans intérêt des jeux de sociétés. Recréer en JAVA des jeux de sociétés sous format virtuel était
un exercice parfait pour mettre à l'épreuve ce que nous avions appris. C'est ainsi que, une fois un groupe formé, je me suis mis au travail moi et mes camarades pour imaginer
comment réadapter le jeu de société Minivilles pour le rendre jouable sur un ordinateur. Je précise que, bien évidemment, nous n'avons pas les droits sur le jeu ou la marque, et
que le projet est purement amateur et est resté dans le domaine privé, à usage purement instructif. Les projets ont été repris et supprimés par l'école une fois évalués.

### Le jeu

Minivilles est un jeu de société qui fonctionne avec des cartes. Le prince est simple : chaque joueur commence son tour en lançant des dés. Chaque carte à un chiffre, que le joueur doit réaliser aux dés s'il souhaite pouvoir utiliser l'effet de la carte. En fonction des cartes qu'il possède et que les dés ont activés, il perd ou reçoit des pièces, qui lui servent ensuite à acheter des nouvelles cartes pour l'aider à gagner. Le but du jeu est d'acheter au moins 5 cartes de type "Monument", qui sont des cartes spéciales que chaque joueur peut acheter, mais qui coûtent énormément de pièces.

### Le projet

Naturellement, il fallait trouver comment non seulement adapter ça en jeu vidéo, mais aussi prendre en compte les règles, le principe du tour de table ainsi que plusieurs autres facteurs qui paraissent évidents lorsque l'on joue au vrai jeu autour d'une table, mais qu'il nous fallait penser à émuler ici aussi.

Après plusieurs semaines de travail, et un réel exercice d'organisation de groupe : nous avons fini par obtenir ce que nous voulions. Une version jeu vidéo de Minivilles, qui prend en compte à la fois les règles du jeu, mais aussi le nombre de joueurs. 

Le jeu commence en demandant combien de personnes jouent, puis désigne un joueur aléatoire commence premier joueur. Au début de son tour, le joueur peut cliquer sur un bouton pour lancer un seul dé, et un autre pour en lancer 2. Le jeu analyse automatiquement les cartes qui sont en jeu, et résout automatiquement leurs effets si le résultat du jet aléatoire correspond, tout en indiquant par texte ce qui s'est passé. Ensuite, le joueur peut choisir d'acheter une carte s'il possède suffisament de pièces, ou de passer son tour. Le jeu passe au joueur suivant, et répète l'opération.

Lorsqu'un joueur achète sa 5ème carte de type Monument, le jeu prend fin et affiche le Joueur Gagnant !

#### Résultat

Notre projet fut correctement noté. Certes, il n'était pas très élégant à regarder et nous n'avions pas reconstitué l'intégralité des cartes et leurs effets, mais nous avions tout de même un jeu fonctionnel. Il tournait sur un modèle "Métier, Vue et Controleur", et nous avons exploité tout ce que nous avions appris en Java pour avoir ce résultat. De plus, ce fut une excellente opportunité de pratiquer le travail de groupe, car notre équipe s'est répartie les tâches pour que chaque partie du modèle soit achevée dans les temps.
