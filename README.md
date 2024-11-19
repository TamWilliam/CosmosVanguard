# Cosmos Vanguard
Le projet consiste à créer un jeu sur Unity dans le thème "Space Invader-like" mais en 2D avec un twist : c'est en multijoueur (4 joueurs max).
On se retrouve dans l'espace avec nos 4 joueurs, tous placés à gauche de l'écran car ce sera en format paysage. La progression se fera de gauche à droite, à l'inverse des ennemies.
L'équipage sera doté d'une arme cannon (laser parce que c'est dans l'espace) ainsi que les ennemies.
Il y aura plusieurs difficultés :
- Le mode facile où les joueurs ne peuvent pas s'interférer entre eux (pas de collisions, pas de tirs alliés)
- Le mode intermédiaire où les vaissaux alliés peuvent rentrer en collision et par conséquent se gêner dans les manoeuvres de pilotage.
- Le mode difficule où les tirs alliés seront pris en compte en plus des collisions de vaisseaux
- Le mode hardcore qui englobe la difficulté en dessous, plus les ennemies sont plus rapides, l'effectif ennemie est augmenté et les collisions entre alliés peuvent tuer

## Flux
1 - Menu Principal
- Bouton pour jouer en solo
- Bouton pour héberger une partie
- Bouton pour rejoindre une partie
- Bouton tutoriel (affiche les touches)
- Bouton pour quitter le jeu

2 - Hébergeur
- Entrée du nom du vaisseau
- Bouton pour lancer la partie (minimum 2 joueurs)

3 - Invités
- Entrée du nom du vaisseau
- Bouton pour changer le statut prêt ou pas prêt

## UI
- Nombre de vaisseau restant (vie individuelle)
- Timer
- Score de la flotte
- Score individuel
