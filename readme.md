# BECODE - ANIMATION CSS

## Voyez le résultat ici : https://vieirahenrique.github.io/becode-animation-css/

---
Cet exercice fait partie du module "La prairie" de la formation WebDev Junior chez BeCode. Il est dédié à l'animation CSS.

Deux sortes d'animation y sont abbordées :
* la commande "transition"
* la commande "@keyframes"

---

## La fonction "transition"
La première consiste à établir que tout changement entre un état et l'autre d'un élément se passe de manière gradative.

Par exemple : si la couleur de fond d'un paragraphe change lors que la souris survole le paragraphe, cela normalement se fait de manière brusque, où l'état initial passe instantanément de A à B.

Avec la commande "transition", nous pouvons établir un temps de transition pour ce changement et également une fonction de vitesse.

Cette fonction de vitesse détermine si le changement dans le temps sera fait de manière linéaire ou exponentielle.

---
## La fonction @keyframes

La deuxième consiste à créer et personaliser une animation bien plus complexe. Notamment en changeant la position, la taille, la couleur, etc. d'un élément et ce, avec la possibilité de customiser dans le temps les différent états de l'animation.

Pour cela, nous créons des véritables petits "blocs" d'animation - un générateur d'animation, si vous voulez - où on établit qu'à 0% de l'animation nous serons à tel état, à 30% (par exemple), nous serons à un deuxième état, puis à 100% un état final.

Nous invoquons cette animation dans l'élément concerné, tout en indiquant combien de temps et avec quelle fonction de vitesse nous voulons performer l'animation.

---

Si l'animation dans une page web a longtemps été commandé par JavaScript, CSS aujourd'hui nous propose un puissant moteur d'animation par soi même. 

---

Voyez dans le fichier html [ici](https://vieirahenrique.github.io/becode-animation-css/) quelques exemples d'animations faites exclusivement avec CSS.