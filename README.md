Jeu de Labyrinthe

Description

Le Jeu de Labyrinthe est un jeu en 2D basé sur Java, où le joueur navigue à travers des niveaux, évitant les ennemis et les obstacles, et collectant des points. Le jeu est conçu pour offrir un gameplay stimulant, avec des ennemis mobiles, des points spéciaux à collecter et un système de progression basé sur le temps.

Fonctionnalités

Mouvements du joueur : Contrôlés via les touches du clavier (flèches directionnelles).

Niveaux dynamiques : Plusieurs niveaux avec une difficulté croissante, présentant différentes configurations d'ennemis, de murs et de points à collecter.

Ennemis : Déplacements aléatoires que le joueur doit éviter.

Points et Points Spéciaux : Les points normaux augmentent le score, tandis que les points spéciaux ajoutent un bonus de temps.

Détection de collisions : Gestion précise des interactions entre le joueur, les ennemis, les murs et les points.

Jeu basé sur le temps : Les joueurs doivent terminer les niveaux avant que le temps ne soit écoulé.

Gameplay

Objectif : Collecter tous les points de chaque niveau tout en évitant les ennemis et en terminant avant la fin du temps imparti.

Conditions de fin de partie :

Toutes les vies du joueur sont perdues.

Le temps est écoulé.

Comment exécuter

Cloner le dépôt :

git clone https://github.com/Mezbushra04/game-project.git

Accéder au répertoire du projet :

cd game-project

Compiler les fichiers Java :

javac *.java

Lancer le jeu :

java Game

Aperçu des classes

Game : Classe principale qui gère la boucle de jeu, le rendu et la logique.

Player : Représente le personnage du joueur, gère les mouvements et les collisions.

Enemy : Représente les ennemis avec des mouvements aléatoires.

Point : Éléments collectables pour augmenter le score.

SpecialPoint : Éléments collectables qui ajoutent du temps supplémentaire.

Wall : Obstacles statiques bloquant le déplacement du joueur.

Obstacle : (Futur) Placeholders pour des défis supplémentaires.

Level : Gère le chargement et la configuration des niveaux.

TiledMapLoader : Analyse et charge les configurations de cartes à partir de fichiers.

Ressources et fichiers associés

labyrinthe.lua : Script Lua définissant les comportements ou configurations spécifiques des labyrinthes.

Fichiers .tmx (ex. labyrinthe.tmx, testmap.tmx) : Fichiers de configuration des niveaux créés avec l'éditeur Tiled.

tileset.png : Fichier graphique contenant les éléments visuels (textures) utilisés pour rendre les labyrinthes.

Images des labyrinthes : Les fichiers d'images, comme labyrinthes-vegetaux-de-france-et-dailleurs-017.jpg ou .png, peuvent servir d'inspiration ou d'arrière-plans pour le jeu.

Intégration des fichiers

Placez les fichiers .tmx et tileset.png dans le répertoire resources du projet.

Assurez-vous que le fichier TiledMapLoader.java est configuré pour charger correctement les fichiers .tmx.

Si nécessaire, modifiez labyrinthe.lua pour ajouter des comportements personnalisés.

Pour un projet avancé, vous pouvez intégrer les fichiers et bibliothèques fournis dans le répertoire TiledMapLoader-master pour une meilleure gestion des cartes avec l'éditeur Tiled. Ce dossier contient des fichiers comme Actions.cpp, Conditions.cpp et Expressions.cpp, qui définissent des fonctionnalités étendues pour la manipulation des cartes et des objets dans le jeu.

Contrôles

Flèches directionnelles :

Haut : Se déplacer vers le haut.

Bas : Se déplacer vers le bas.

Gauche : Se déplacer à gauche.

Droite : Se déplacer à droite.

Améliorations futures

Ajouter davantage de niveaux avec des dispositions uniques.

Introduire des power-ups et de nouveaux types d'ennemis.

Améliorer les graphismes avec des textures et des animations.

Implémenter une fonctionnalité multijoueur.

Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir des issues ou à soumettre des pull requests.

Licence

Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus de détails.
