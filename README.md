
# G2:   PAC-MAN — README

###### TAWFIK Adam  - BELAL Anais 
###### DIRANI SAFAWI Hani - HEDIDAR Rayan 
###### KIRLOS Youssef - TABDELSADEK Abdallah

***

## Présentation du jeu

Notre projet est une ré-implémentation de `Pac-Man` en Java, jouable en 2D, avec génération aléatoire du labyrinthe à chaque partie, et plusieurs extensions : différents niveaux de difficulté, suivi du joueur par la caméra, et projectiles pour éliminer les fantômes.

* __But du jeu :__ Collecter toutes les pièces tout en évitant d’être tué par les fantômes pour remporter la partie.



## Lancement du jeu

1. **Choix de la difficulté et du mode**
   - Ouvrez le fichier `config.txt` disponible dans le répertoire du projet.

   - Sélectionnez la difficulté de jeu (`Easy` ou `Hard`) et le mode de carte (`tore` ou `non-tore`).


2. **Choix de la taille de la carte**
   - Ouvrez le fichier `MainTask3` dans le package `game`.
   - Choisissez la taille de la carte souhaitée (par défaut : `20x20`) ; le nombre de fantômes est proportionnel à la taille de la carte (par exemple, pour une carte 20x20 : 4 fantômes).

3. **Exécution du jeu**
   - Exécutez le fichier `MainTask3` pour lancer le jeu.



## Contrôles disponibles

| Touche                         | Action                                   |
|--------------------------------|------------------------------------------|
| `Flèches`       | Déplacer Pac-Man dans la direction choisie|
| `Shift` + `Flèche droite/gauche`   | Faire tourner Pac-Man sur place          |
| `F `                             | Activer / désactiver le mouvement continu|
| `Espace`                         | Tirer un projectile                      |
| `P`                              | Zoom avant (zoom in)                     |
| `M`                              | Zoom arrière (zoom out)                  |
| `=`                              | Réinitialiser le zoom                    |
| `Ctrl`                           | Afficher le mode debug (Grid, stats…)  |




## Répartition des tâches 

| Nom       | Tâches principales réalisées                                                                                      |
|-----------|------------------------------------------------------------------------------------------------------------------|
| __Abdallah__  | Générateur de labyrinthes, Avatars, Projectiles, Gestion des entités par case, Respawn des Ghosts , Affichage des Statistiques `[Debug Mode]`           |
| __Anais__     | Classes FSM, FleeingBot, Mouvements aléatoires (_Random_)                                                       |
| __Adam__      | Classes FSM, WanderingBot, WallFollowingBot, CollectorBot pour le Player                                         |
| __Hani__     | Classes FSM, ChaseBot                                                                                            |
| __Rayan__     | Gestion des conflits et merges _Git_, ChaseBot, gestion du menu `[Config File]`, Changement des Avatars                 |
| __Youssef__   | Gestion des morts du joueur et des fantômes (_PacGum, Projectiles_), fonctionnalité de zoom, Respawn des Ghosts , Affichage des Statistiques `[Debug Mode]` |

