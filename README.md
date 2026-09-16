# Protolude - Sans issue
Sans issue est un jeu qui donne au joueur un besoin de chercher une solution, mais qui engendre quelques obstacles. Chaque terrain est de plus en sinistre, donnant une idée de jeu d'évasion.

### Les interactions
- Arrivé dans la deuxième partie du monde, le seul moyen d'ouvrir la porte est de rentrer en contact avec le feu en dessous des escalier pour avoir "la clé".
- Lorsqu'on a la clé et qu'on remonte les escalier, les portes tombent. La porte qui tombe est un objet autre que le personnage qui est affecté par la physique
- Monter les escaliers après avoir pris le feu, allume les torches petit à petit par des box colliders quand le joueur monte.
- Le contact entre la porte et le joueur lorsqu'elle tombe engendre un échec. 
- Lorsqu'on traverse la porte, un box collider un peu plus loin provoque un changement de scène qui montre la fin du jeu quand le joueur rentre dedans, mais laisse un suspence, ce qui fais un lien avec l'environnement de fin.

### L'échec

- Comme mentionné dans les intéractions, quand la porte touche le joueur lorsqu'elle tombe, ça recommence la scene.


### La réussite

- Lorsque le joueur rentre en contact avec le box collider après la porte, ça entraine à un changement de scène avec un message de fin
