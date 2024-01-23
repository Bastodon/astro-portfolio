---
title: Twin Tin Bots (non officiel)
publishDate: 2020-11-12
img: /assets/stock-2.jpg
img_alt: Image vue du dessus du plateau de Twin Tin Bots
description: |
  Réadaptation du jeu Twin Tin Bots en Java
tags:
  - Jeu
  - Dev
  - Simulation
---

## Twin Tin Bots

> Les Hexagones, c'est quand même super classe !

Afin d'obtenir mon Bac+2, j'ai dû accomplir un dernier projet : encore un autre Jeu de Société à refaire en JAVA ! Tout comme Minivilles, c'était un bon exercice, mais cette-fois le niveau était un peu plus au dessus. Nous avions travaillés sur d'autres langages, et on attendait de nous une maîtrise plus avancée. Aussi, ce projet était à réaliser en solo, et allait compter énormément pour l'obtention de notre DUT.

### Le jeu

A première vue, Twin Tin Bots est moins compliqué que ne le fut Minivilles. Le but est de placer et déplacer stratégiquement des pions sur un plateau pour récolter des ressources. Cependant, pour déplacer ces fameux pions : les joueurs devaient entrer une combinaison d'ordres ("avance, va à gauche, attaque, ramasse, avance", par exemple), qui ne se résolvait qu'à la fin du tour. Mais ce qui fut le plus embêtant, c'était le plateau ! 

Jusqu'à maintenant, tous les jeux que nous avions créés ou refaits avaient un plateau composé de carrés, comme un damier, ou n'avait tout simplement pas de plateau. Ici, c'était différent : le plateau était composé d'hexagones, et n'avait clairement pas une forme carrées. C'est un choix sympathique, car les joueurs ont bien plus de possibilités de mouvements. Mais à émuler pour des débutants en Java, c'était une autre paire de manches !

### Le projet

Nous avions plusieurs semaines pour réaliser le projet, et nous allions en avoir besoin ! Le plateau était l'un des obstacles qui m'avait bloqué le plus, car il présentait beaucoup de restrictions et de risques d'erreurs pour le code. Mais d'un autre côté, nous n'étions pas évalués sur l'aspect "Graphique" du jeu. Et même si j'ai suivi un modèle "Métier, Vue et Contrôleur", l'aspect "Vue" fut vité réglé, et j'ai pu me focaliser sur le Métier.

Se déplacer sur les hexagones, prendre en compte les ordres de chaque pion et résoudre dans le respect des règles les conflits et les conditions de victoire. Voilà les objectifs sur lesquels je m'étais concentré. Et ainsi, bien que le jeu fut assez primitif en matière de visuel : il se montrait particulièrement exigeant quant à son fonctionnement.

#### Résultat

Ce ne fut pas facile, mais j'ai obtenu un retour positif de la part des évaluateurs. Bien que le jeu se présente comme n'étant rien de plus que des lettres se déplaçant dans un plateau mal dessiné, les pions ne pouvaient pas sortir du plateau et on pouvait les déplacer sans problèmes. Tout comme pour Minivilles, l'intégralité du jeu ne fut pas reproduit, et pour tout dire : c'était souvent le joueur qui commençait le premier qui gagnait toujours ! Mais il fonctionnait, et il ne plantait pas. Et par la suite : la note que j'ai obtenu
a grandement contribuée à l'obtention de mon DUT !
