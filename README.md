# Création d'une application Express

Ce projet a pour but de vous faire construire une application Express
avec des routes de bases et des routes avec paramètres.

# But

Vous devez créer une application qui à des ressources à les adresses suivantes :

* /quotes - retourne un tableau des citations en JSON
* /quotes/id (où id est un nombre ex: /quotes/3 ou /quotes/10) - retourne la citation à l'indice id de la liste de citations en JSON
* /quotes/random - retourne une citation au hasard du tableau de citation en JSON

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

* L'application Express n'est pas fournie, c'est à vous de l'installer avec le express-generator.
* L'application express doit être dans un fichier `app.js`.