# ReadMe

Read me de Laura Kokonyange-Nkasei - Devoir Maison 1 CSS LPWM

Voici le lien du site, hebergé sur github : https://laurakonk.github.io/DMCSS1/
Ainsi que le lien du repository github du projet : https://github.com/LauraKoNk/DMCSS1

Afin de réaliser ce devoir maison, j’ai entièrement utilisé bootstrap pour la mise en page de mon site. 

## Le corps du code :

Il se situe à l’intérieur d’une div définie par `class=”container”` qui englobe toutes les informations et crée un conteneur avec une largeur fixe et un espacement automatique sur les côtés.

## La partie haute :

Dans cette partie, la balise  `<header>`, dans laquelle est contenue l’entête de la page, est définie par `class="row"` qui crée une rangée de conteneurs. 

À l’intérieur de cette balise : 

la première div est définie avec `class="col-12 col-md-9"`, ce qui signifie qu'elle occupe 12 colonnes sur les petites tailles d'écran (toutes les tailles d'écran) et 9 colonnes sur les écrans de taille moyenne, à partir de la taille medium définie par Bootstrap.

La seconde div est définie avec `class="col-12 col-md-3"`, ce qui signifie qu'elle occupe 12 colonnes sur toutes les tailles d'écran et 3 colonnes sur les écrans de taille moyenne et supérieure.

Il y a ensuite une balise <nav> dans laquelle se trouve la barre de navigation du site.

Pour chaque option de menu **`<li class="dropdown col-12 col-md-3">`**: 

- **`class="dropdown"`** : Indique que cet élément de liste est une liste déroulante.
- **`class="col-12 col-md-3"`** : Signifie que cet élément de liste occupera 12 colonnes sur toutes les tailles d'écran et 3 colonnes sur les écrans de taille moyenne et supérieure.

Enfin, il y a une balise **`<ul>`** avec **`class="lienAccueil d-flex”`  : I**ndique que les éléments de la liste doivent être disposés en tant que conteneur flex.

## La partie centrale :

Dans cette partie, la balise `<section>` est définie par `class="row mb-3”` : cette section possède une rangée de conteneurs , et elle a une marge inférieure de 3 unités. 

À l’intérieur de cette balise :

- une balise `<main>` définie par **`class="e1 col-md-8"`**, ce qui signifie qu'elle occupe 8 colonnes sur les écrans de taille moyenne et supérieure.
- une balise `<aside>` définie par **`class="col-md-4">`**, ce qui signifie qu'il occupe 4 colonnes sur les écrans de taille moyenne et supérieure et placé sur le côté droit de l’écran.

## La partie finale :

Dans cette partie se trouve le pied de page du site, dans la balise `<footer>` , qui est définie par `class="mb-3”` : ajoute une marge inférieure de 3 unités.

Dans cette balise : 

- **`<ul class="footer row p-4">`** : "row" Indique que les éléments de la liste seront disposés en ligne dans un système de grille Bootstrap. La classe "p-4" ajoute une marge de 4 unités à tous les côtés de la liste.
- **`<li class="col-12 col-md-1">` : L**a classe "col-12 col-md-1" signifie que cet élément occupera une colonne de largeur 12 sur les écrans de petite taille et une colonne de largeur 1 sur les écrans de taille moyenne.
- **`<li class="col-12 col-md-2">` :** Cet élément aura une largeur de 12 colonnes sur les écrans de petite taille et une largeur de 2 colonnes sur les écrans de taille moyenne.