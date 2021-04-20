# Tuto Markdown

Le markdown est un language de balisage (comme le HTML). Sa structure est trés légère.

## Les titres

avec # on peu donner des titres de différents niveaux (comme les h1,h2 etc ... en HTML)

    # Titre de niveau 1
    ## Titre de niveau 2

## Les listes

On peut faire des listes de plusieurs niveaux :

Liste de course:

- tomates
  - 3 normales
  - une barquette de tomates cerise
- mozzarella
- parmesan
- huile d'olive

        Liste de course:
        - tomates
            - 3 normales
            - une barquette de tomates cerise
        - mozzarella
        - parmesan
        - huile d'olive

## Les liens

Pour creer un lien on utilise les crochets [] pour y mettre notre texte et les parenthéses pour indiquer le lien vers lequel il redirige  

[lien vers github](https://github.com/)

    [lien vers github](https://github.com/)

## Les images

On peut ajouter des images !

![alt text](https://images.unsplash.com/photo-1534447677768-be436bb09401?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1371&q=80 "Photo de Johannes Plennio")

    ![alt text](https://images.unsplash.com/photo-1534447677768-be436bb09401?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1371&q=80 "Photo de Johannes Plennio") 

## Les tableaux

| En-tête de colonne 1| En-tête de colonne 2|
|----------------------|----------------------|
| element colonne 1 ligne 1 | element colonne 2 ligne 1 |
| element colonne 1 ligne 2 | element colonne 2 ligne 2 |
| element colonne 1 ligne 3 | element colonne 2 ligne 3 |

    | En-tête de colonne 1| En-tête de colonne 2|
    |----------------------|----------------------|
    | element colonne 1 ligne 1 | element colonne 2 ligne 1 |
    | element colonne 1 ligne 2 | element colonne 2 ligne 2 |
    | element colonne 1 ligne 3 | element colonne 2 ligne 3 |

## Elements de texte

On peut mettre des éléments de texte en *italique*  

    On peut mettre des éléments de texte en *italique*

Ou en **gras**  

    Ou en **gras**

On peut inserer des lignes de code entre 3 backticks ` ou avec des tabulations

```html
    <!-- Jumbotron -->
    <div class="jumbotron jumbotron-fluid jumbo text-light">
        <div class="container">
            <h1 class="display-4">Jumbotron</h1>
            <p class="lead">Ceci est un jumbotron, je lui ai ajouter un effet qu'on appelle parallax. L'image de
                fond a
                été chargée dans le CSS</p>
            <a href="https://www.w3schools.com/howto/howto_css_parallax.asp" target="_blank"
                class="btn btn-outline-light">Plus d'info sur W3School</a>
        </div>
    </div>
```

Le markdown n'interprete pas le retour à la ligne comme les autres languages:  
On peut faire 
des 
retours  
à la ligne 
avec 2 espaces

        Le markdown n'interprete pas le retour à la ligne comme les autres languages:  
        On peut faire 
        des 
        retours  
        à la ligne 
        avec 2 espaces


