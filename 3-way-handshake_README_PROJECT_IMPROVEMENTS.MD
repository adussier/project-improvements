# TWEB Project : Asteroïd Game Improvements


## Membres du groupe

Filipe Fortunato, Pierre Kohler & Jonathan Zaehringer

## First Improvement description 

Implémentation de rendu graphique en WebGL, via [threejs](https://threejs.org/).

Nous réimplémenterons dans un premier temps tout le fonctionnement des viewports, en implémentant un rendu avec three.js pour le canvas.
Au passage, le changement de moteur de rendu devrait nous permettre d'ajouter une esthétique plus élaborée encore à définir (dépend des possibilités offertes par three.js).
Un rendu 3D en perspective tout en conservant le gameplay 2D est envisagé.

## Second Improvement description

Concernant la seconde amélioration que nous souhaitons implémenter, il s'agirait d'améliorer le *gameplay*.
Cependant, comme nous n'avons actuellement aucune idée de la difficulté que représentera la réalisation de la première, nous souhaitons garder une certaine liberté sur la complexité de la seconde.

Les idées d'amélioration du gameplay ne manquent pas :

- Ajouter d'un status au joueur (vie, stamina, ...) et d'un HUV associé.
- Implémenter la sous-division des astéroids en éléments plus petit lors de la desctruction de ces dernières.
- Ajouter des modes de tires élaborés (tir multiple, tir puissant, tir explosif, ...)
