# Création d'une application Express

Ce projet a pour but de vous faire construire une application Express
avec des routes de bases et des routes avec paramètres et une application
React avec des éléments dynamiques.

# But - Express

Vous devez créer une application Express qui à des ressources à l'adresse suivante :

* /quotes/id1-id2 (où id1 et id2 sont des nombres ex: /quotes/3-7 ou /quotes/10-45) - retourne un tableau des citations aux id données

# But - React

Vous devez créer une application React qui à les fonctionnalités suivantes :

* Un `input` et un `button` qui permet d'entrer un ID.
* Quand on entre un ID et pèse sur le bouton, affiche le quotes de l'ID sélectionné.

# Élément fourni

* Le fichier quotes.json des citations.

Le code suivant permet d'importer les citations dans votre application Express:

```js
// La variable quotes sera un tableau d'objet avec les clés "quote" et "author"
// Le fichier quotes.json doit être dans le même dossier que l'application express.
const quotes = require('./quotes');

// Exemple d'utilisation des quotes
console.log(quotes[4].author) // Affiche Robert Frost
```

# Requis technique

* L'application Express/React n'est pas fournie, c'est à vous de l'installer avec le express-generator/create-react-app.
* L'application Express/React doit être dans un fichier `app.js/App.js`.
