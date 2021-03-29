## Workshop : Découverte du CSS

### Installation

La première étape du workshop est de cloner le repo est de lancer l’application React.js :

1. git clone https://github.com/cesar-vzc/workshop_css.git

2. cd workshop_css/




### Création du fichier CSS

Créer un fichier style.css et l’importer dans le header de notre page index.html :

```
<head>
	…
	<link rel="stylesheet" href="style.css">
</head>
```



### Stylisation d'une barre de navigation

Dans le fichier style.css, nous allons commencer la stylisation de la balise HTML <nav> qui permet de faire des barres de navigation.

 

Pour cela nous commençons par appeler la balise nav dans le fichier style.css et ouvrir des accolades :

```
* {
    margin: 0;
    padding: 0;
}

nav {
    …
}
```

Nous pouvons maintenant ajouter du style à notre barre de navigation :

```
nav {
    background-color: white;
    border-bottom: 1px solid black;
    top: 0;
    width: 100%;
    text-align: left;
    font-size: 100%;
    font-weight: bold;
    padding: 25px;
}
```

*Exemple de style pour une barre de navigation simple*



### Création d'une classe CSS

Nous allons maintenant découvrir comment créer des classes en CSS.

Pour cela, il suffit d’ajouter un ‘.’ devant le nom de votre classe :

```
.wrapper {
    display: flex;
    align-items: center;
    flex-direction: column; 
    justify-content: center;
    width: 100%;
    min-height: 100%;
}
```

*Exemple d’une classe nommé « wrapper » qui permet de centrer les balises HTML au centre de notre page*



Pour l’appeler dans notre code HTML, nous avons simplement besoin d’écrire :

```
<div class="wrapper">
	…
</div>
```



### Implémentation du CSS sur le body

Pour cette étape, vous devez appliquer du style sur votre <body> afin de changer la couleur du background (‘background-color’), la couleur du texte (‘color’), la taille du texte (‘font-size’).

 

Pour cela il vous faudra appeler la balise body (comme au préalable avec la balise nav) dans votre fichier style.css :

```
body {
	…
}
```



### Styliser la page

Pour ce dernier point, vous devrez styliser votre page HTML afin qu’elle ressemble le plus possible à celle-ci :

![](https://zupimages.net/up/21/13/3j4e.png)

*Le background ici présent est une image fournie dans le dossier assets/.*



N’hésitez pas à demander de l’aide !



### Merci d'avoir participé au workshop !

Présenté par César VENZAC