# HTML : expertise et environnement de travail

## Devoir 2

Objectifs :

– maîtriser les règles de nommage de CSS pour des règles modulables et réutilisables ;

– savoir intégrer une page à l’aide d’un Framework ;

– générer du CSS à l’aide d’un préprocesseur.

Rendu :

Un fichier zippé contenant un dossier par exercice.

Ce dossier ne doit contenir que les éléments nécessaires à la visualisation, tels qu’on les retrouverait sur un site
statique en production.

## EXERCICE 1 : des CSS modulables et réutilisables

Voici une page HTML CSS dont les ciblages ont été réalisés il y a quelques années : annex/exercice-1

1. realiser une copie et la placer dans le docier : HT04-02exercice01

   Vous devez reprendre les codes HTML et CSS afin de rendre le code CSS réutilisable et modulable.

2. Ne pas modifer annex/exercie-1. Travailer sur le docier HT04-02exerce01; modifier les fichier index.html et style.css

   Vous ne devez pas modifier la structure du code HTML. Il s’agit uniquement de reprendre les noms de classes
   et les identifiants dans les fichiers HTML et CSS

3. Reprendre les noms de classes et les identifiants dans les fichiers HTML et CSS

   | class ou id</br>id remplacer par class | original        | modification:class |
   | :------------------------------------: | :-------------- | :----------------- |
   |                   id                   | wraper          | ...                |
   |              id => class               | header          | ...                |
   |               id=> class               | logo            | header_logo        |
   |                 class                  | clolonne        | ...                |
   |              id => class               | pub             | heard_pub          |
   |                 class                  | clear           | ...                |
   |                  ---                   | ---             | ---                |
   |                ajouter                 | nav +++         | nav                |
   |              id => class               | menu_horizontal | nav_menu           |
   |                ajouter                 | li +++          | liste_item         |
   |                ajouter                 | a +++           | item               |
   |          survole: .item:hover          | .item:hover     | .item:hover        |
   |                  ---                   | ---             | ---                |
   |              id => class               | contenu         | ...                |
   |              id => class               | contenu_gauche  | col_gauche         |
   |                 class                  | bloc            | ...                |
   |                 class                  | date            | ...                |
   |              id => class               | contenu_centre  | ...                |
   |                 class                  | align_droite    | ...                |
   |              id => class               | vignettes       | ...                |
   |                 class                  | vignette        | ...                |
   |              id => class               | contenu_droite  | ...                |
   |              id => class               | actulites       | ...                |
   |              id => class               | footer          | ...                |

4. N’envoyez que la version retravaillée pour la correction.
