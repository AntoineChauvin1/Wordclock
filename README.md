# Wordclock
Horloge qui affiche l'heure en toute lettres

Fonctionne sous espHome qui qpelle une fonction.
Le code est dans la fonction


Modification 1

adaptation de la luminosité avec un capteur de presence et un capteur de luminosité

Quand une presence est detectée, un compteur se met en marche.
L'horloge a une luminosité suivant la table en annexe 1 tant que le compteur n'est pas à la limite définie.
quand le timer arrive a la limite définie, la luminosité passe a 0.

lux   luminosité

0-6        4

7-20       10

21-40      13

41-60      16

61-80      45

81-100     48

100-130    50

130-150    51

150-500    52
