# Interrogation Angular

Une fois votre devoir terminer, envoyer le moi par mail à l'adresse : ange.picard@pm.me.

**PENSEZ BIEN A SUPRRIMER LE DOSSIER .git ET node_modules**

> Pas la peine de faire de CSS, uniquement l'aspect fonctionnel sera pris en compte.

## Informations

Nom: GOKOL
Prenom: Semi

## Question ouvertes

Merci de répondre avec vos mots, même s'ils sont inexactes, je veux voir que vous avez compris, pas que vous savez faire un copier-coller.

### Qu'est qu'Angular et quel est son intérêt ?

```
C'est un framework Javascript front créé par Google, il est basé sur du TypeScript et une surcouche de Javascript, un framework de manière général facilite le développement et permet aussi d'avoir une certaine architecture pour cadrer le projet. Angular permet de gérer chaque composant indépendemment des autres je trouve que ça permet de travailler dans un environnement plus clair.
Angular est aussi connu pour pouvoir apporter une experience utilisateur très ergonomique généralement on retrouve tout sur une seule page.
```

### Qu'est-ce-qu'un composant

```
Un composant est un élément HTML de notre vuen une partie de notre vue, ça peut etre un tableau, un bouton, une liste, etc
```

### Comment est découper un composant dans Angular ?

```
Il est composé d'un template HTML/CSS/JS et un fichier typeScript qui contient la classe qui est lié à celui-ci.
```

### Pourquoi vaut-il mieux faire de petit composant ?

```
Cela permet d'améliorer la scalabilité, on pourra ré-utiliser les petits composants où l'on voudra etc, la maintenabilité sera bien meilleur.
```

### A quoi sert un service ?

```
C'est un autre type de composant entre guillemet, lorsque le composant lui va gérer sa logique interne qui lui est propre, le service va permettre de faire des actions plus globale on pourra l'appeler dans plusieurs composant, pour manipuler de la donnée etc, ça permettra de partager l'information entre les différents composants.
```

### Qu'est-ce-qu'un observable, et quel est son intérêt ?

```
Franchement j'ai pas bien compris.
```

## Exercice 1

- Créer un nouveau projet Angular
- Dans le AppComponent
    - Ajouter un input
    - Ajouter un span
    - Faire en sorte que quand l'utilisateur entre du contenu dans l'input, il soit également écrit dans le span. On voit la même chose dans le span et dans l'input.
    - Ajouter un bouton permettant de vider le contenu de l'input et du span
- Créer un composant ListComponent
    - L'ajouter dans le template du AppComponent
    - Afficher la liste qui suit dans ListComponent
        - ['Jean', 'Jacques', 'Martin']
- Ajouter un bouton "CACHER" dans le AppComponent
    - A chaque click, cacher ou afficher ListComponent

## Exercice 2

Cette partie de l'interrogation porte sur le projet PokeAdopt.

Pour l'instant l'application n'affiche que la première page de la liste de pokemon l'API.

- Ajouter un bouton précédent et suivant en haut de la liste
- Quand on clique sur précédent ou suivant, afficher la page précédente ou suivante de l'API
- Bonus: Griser le bouton précédent s'il n'y a pas de page précédente
- Bonus: Afficher le numéro de page entre les deux boutons (Page 1 / XXX)