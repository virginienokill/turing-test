# Robot qui perds aux jeux

Ou aux dames ???
Est ce que ce serait pas plus simple de lui faire jouer au puissance 4, le nombre d'actions possibles à chaque tour étant peu nombreuses et toujours les mêmes quelque soit l'état du jeu (à part si une colonne de pions est remplie, ce qui pourrait être une erreur qu'il commet stupidement)

## Esthétique, allure du robot

Il n'est pas antropomorphe physiquement. C'est son comportement de mauvais perdant qui le rend "humain".

## Matériaux envisagés

Il est controlé par arduino

## Hypothèses de construction, description technique

### Scénario


Quand c'est à lui de jouer il pousse une pièce maladroitement sur le plateau.

Au bout de 4 coups joués, il en a marre et il fait valser le plateau.

### Modularité
Le robot recoit en entrée une information qu'il interprete comme "à toi de jouer". Ce signal doit être un standard du spectacle. Peut être le même que celui que puredata envoie à ognon pour dire, "image suivante".

La plus part du temps ça peut etre commandé par un bouton (ou une pédale sous la table ?)

## Moment envisagé pour la construction

?