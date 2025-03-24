# CharlyRobot-CRA4

# Carte de puissance

Analyse de la carte de puissance :

![Description Carte de puissance](/Photos/Carte_puissance_top_explications.JPG.jpg)

ALIM 1 :

 * Tension sortie transformateur : 23.6VAC
 * Tension sortie : 31VDC

ALIM 2 :

 * Tension sortie transformateur : 21VAC
 * Tension sortie : 28VDC

[Schématique](/carte_puissance/carte_puissance_schematique.pdf)

[PCB](/carte_puissance/carte_puissance_PCB.pdf)

# Indicateurs lumineux

![Témoins Lumineux](/Photos/temoins_lumineux.jpg)

Tension d'alimentation : 12VDC -> 32VDC
Courant : 
 * 6mA pour 12VDC
 * 20mA pour 30VDC

| Témoin | Couleur fil |
| ------------- | ------------- |
| Masse commune | Noir |
| Alimentation électrique | Rouge |
| Alarme | Jaune / Noir |
| STOP | Bleu / Gris |
| Broche / Spindle | Violet |
| Capteur Outil | Orange / Noir |
| X Ok | Marron |
| Y Ok | Vert |
| Z Ok | Bleu |

# Carte de commande

![commande_finie](/Photos/commande_finie.JPG)


La position des capteurs fin de course (1 seul par axe) :

![commande_finie](/Photos/position_fin_de_course.jpg)

## Drivers commande moteur pas à pas 

C'est des drivers TB6600.
4 microstep (donc 800 steps par tour).
3A pour X et Y , 2A pour Z

Positionnement des switch :

| Switch | Valeur |
| ------------- | ------------- |
| S1 | ON |
| S2 | OFF |
| S3 | OFF |
| S4 | Z : ON |
| S5 | Y et Y : ON |
| S6 | OFF |



