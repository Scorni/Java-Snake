# Projet Snake en Java

# Codeurs :
salut
- Brieuc Saillez 2TL1
- Maxence Scorniciel 2TL1
- Tom Varewyck 2TL1

# Règles et caractéristiques du jeu :

Les règles sont simples , restez en vie et avoir le plus de points à la fin de la partie.

- Une partie se joue a deux joueurs.
- Une partie dure 2 minutes.
- La taille du serpent est de 3. ( unité a définir )
- Un bonus apparait aléatoirement sur le terrain de jeu toutes les 8 à 12 secondes.
- Chaque bonus attrapé permet de gagner en taille ou de recevoir des points supplémentaires
- Il y a plusieurs types de bonus :
         
         - Un bonus donnant 1 point et 1 en taille. ( 60% de chance d'apparition )
         - Un bonus retirant 1 point et un de taille. ( 33% )
         - Un bonus donnant 5 points et 5 de tailles. ( 5% )
         - Un bonus donnant 2 points et perd 3 tailles. ( 2% )
     
- Si le serpent percute un mur , la partie se termine pour lui mais son cadavre reste à l'endroit de l'impact et forme un mur supplémentaires mais le joueur conserve les points recoltées tout au long de sa vie.
- Si le serpent percute un adversaire , le serpent meurt et son cadavre disparait du terrain de jeu. Dans ce cas ci le joueur perd tout ses points.
- Si un serpent ayant 3 de tailles ( taille à la creation ) recupère un bonus lui retirant 3 de tailles , le serpent meurt et garde ses points.
- Tout ceci sera affiché dans une interface GUI
