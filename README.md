# My Clicker Game

## But du Jeu

Ces jeux ont un principe très simple : cliquer rapporte des points, qui peuvent être investis dans des moyens de production. Ces moyens de production rapportent des points à chaque seconde, qui pourront ensuite être réinvestis, créant une boucle infinie.

### Mise en place d'automatiseurs 

Ce sont des éléments du jeu qui permettent de gagner automatiquement de l'argent à intervalles réguliers (dans notre cas toutes les secondes).

### Mise en place des pirates 

Maintenant que notre gps fonctionne avec une valeur en brut, nous allons ajouter des Pirates qui vont augmenter le gps.
Chacun de ces Pirates aura ses propres caractéristiques, et plus ils seront chers plus ils seront productifs.

### Mise en place d'une boutique 

Maintenant il faut être capable d'acheter des pirates. Pour cela, il va vous falloir créer une boutique.

Il faudra une fonction qui prendra en paramètre un id. Elle devra chercher le pirates correspondant à cet id et en acheter une copie. L'achat signifie qu'il faut vérifier que le joueur ait les golds suffisants, et lui retirer.

Ne pas oublier de bien à mettre le gps à jour après l'achat, et à mettre les affichages à jour.

### Quelques améliorations

*  Lorsqu'un minion d'un certain type est acheté, le prochain va couter x1,15 plus cher. 
*  Tous les 50 minions achetés, la valeur du click double. 
*  Dès un joueur possède 25, 50, 100, 250 et 1000 minions d'un même type, ceux-ci vont produire 2x plus de gps. 

### Sauvegarde

Dernière étape pour notre petit clicker game, il faut avoir un semblant de sauvegarde ! Il faut que notre joueur puisse quitter le jeu, et reprendre sa partie ensuite.

Pour cela, il faut faire en sorte de pouvoir stocker toutes les données importantes au jeu dans le localStorage. Il faut que le joueur puisse reprendre sa partie sans aucune perte.





|         Lancement du jeu a 0         |
|:------------------------------------:|
|  ![](https://i.imgur.com/k4D2QPO.jpg)|


| Achat de différents Pirates, Nombres de pièces/secondes augmente |
|:---------------------------------------------------------------:|
|              ![](https://i.imgur.com/uf6upzs.jpg)               |

