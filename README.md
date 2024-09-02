# MiamBox

## LE PROJET :

Créer un dispositif pour s’assurer que notre chien est bien nourri en mettant un boîtier à côté de sa gamelle. Cela permettra de suivre qui a nourri le chien et de s’assurer qu’il ne manque aucun repas.

## LES PRÉ-REQUIS :

### Un compteur par membre du foyer :
Pour éviter les disputes du type « C’est moi qui l’ai nourri la dernière fois ! » ou « Je suis le seul à le nourrir ! »
Un bouton physique par membre du foyer :
Pour incrémenter son propre compteur.
### Un feu tricolore :
Pour une indication visuelle facile à comprendre :
+ Feu rouge : Le chien vient d’être nourri, l’incrémentation du compteur est inactive.
+ Feu orange : Le chien peut être nourri, mais ce n’est pas encore tout à fait l’heure (2 heures avant l’heure H), l’incrémentation du compteur est active.
+ Feu vert : C’est l’heure de nourrir le chien, l’incrémentation du compteur est active.
### Un tableau de bord dans Home Assistant :
Affichage d’une carte ApexCharts pour visualiser qui nourrit le chien le plus souvent par semaine/mois, etc.

## LE BOÎTIER :

Utilisation de Fusion 360 et impression 3D. Voici le prototype :
![prototype](/docs/96a95cf00a6961c3a06991813392e723bbc3ace6.jpeg)

## LE HARDWARE :
Voici le schéma du montage prévu.
![le schéma du montage prévu](/docs/6f9bb969c072532362b816e7b4fe9392f020afbe_2_1035x526.jpeg)

### LE CALCUL DES RÉSISTANCES POUR LES LEDS :
![LED](/docs/LED.png)

### LE YAML pour ESP HOME :
À faire…

### Le 1er Prototype :
![PROTO](/docs/Image/PhotoProto1.jpg)
