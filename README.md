### Salut à toi !
Je suis en train d'apprendre les languages C/C++.

Je bidouille beaucoup avec Arch Linux et essaie de mettre en place des petits serveurs variés. (bon, j'avoue que je galère)

Mon plus gros défi est d'arriver à coder un moteur de jeu 3D à partir de presque rien, voire rien du tout; qui respecte ces critères:
- Utilise l'API Vulkan
- Utilise C/C++
- Capable de tourner sur une variété de bidules donc:
  - Cross-Platform au maximum possible (Linux, Windows...)
  - Cross-Architecture au maximum possible (ARMv6, ARMv7, ARMv8, x86_64, RISC-V...)
  - Capable de tourner sur une patate

Premier objectif: afficher un piti cube qui tourne  
Deuxième objectif: appliquer des textures sur le cube  
Troisième objectif: charger d'autres modèles qu'un cube, ou plus généralement, n'importe quel modèle au format .obj  
Objectif final: faire un petit jeu avec le moteur 3D fonctionnel

Quêtes annexes: 
- Intégrer des librairies de compression variées pour optimiser le chargement et l'espace
- Faire tenir un petit jeu 3D sur une disquette 3 1⁄2" (1.44MB), juste pour le délire
- Faire tourner le jeu sur un Raspberry Pi Zero à un frame rate acceptable (à voir si le "driver" Vulkan tient suffisamment la route)
