Quand on a un doute sur un probleme sur un groupe de resistances en parallèle (ou de condos). On compare leur chute de tension avec les autres résitstances en série et on infère quelle serait la resistance équivalente. On la compare ensuite avec le calcul pour vérifier si ça correspond et s’il n’y a pas de fugue ou d’altération.

Pour économiser la pointe d’un fer a souder et sa consommation, ajouter un interrupteur sur le fil ainsi qu’une diode en parallèle. Lorque l’interrupteur est ouvert, la diode ne laisse passer qu’un seul cycle du courant alternatif et réduit la consommation d’énergie, lorsqu’on allume de nouveau, le fer se réchauffe très rapidement.

Lampe série: 3x plus puissante que l’appareil testé. Ex: RL de l’appareil: 25w → ampoule de 75w; Lorsqu’on a besoin de tester un appareil puissant on place plusieurs ampoules en série pour atteindre la puissance désirée.Si l’on a besoin de plus de puissance on peut utiliser une résistance de grille pain ou de douche

Disjoncteur différentiel:
Surveille qu’il n’y ait pas de fuite de courant par ex lorsqu’un fil de retour touche une carcasse métallique et que quelqu’un touche cette carcasse, il y a une fuite de courant par le sol. Les deux fils d’entrée et de sortie sont enroulés pour provoquer un champ magnétique du même sens et de même intensité. Si l’un des fils reçoit moins de courant (à cause d’une fuite), le champ magnétique est différent entre les deux fils et celà provoque l’actionnement d’un interrupteur. Reactance inductive / reactance capacitive. Impedance =  somme de resistance 

+ reactance inductive et capacitive.

Reactance inductive, augmente avec la fréquence

Reactance capacitive diminue avec la fréquence

Pour connaitre la reactance sur un circuit avec diviseur de tension, simplement, on regarde avec l'oscillo entre la resistance et l'inductance ou le condensateur
et on observe la chute de tension entre les deux sinusoides. Elle correspond à la proportionalité entre la resistance et l'inductance pour une frequence donnée.

Xl = 2pi f L

Xc =  1 / 2pi f C

Si l'amplitude du générateur diminue lorsque la fréquence augmente, c'est que sa résistance interne devient plus importante au regard de la reactance. Lorsqu'on augmente la frequence, la reactance capacitive diminue, donc la résistance totale du circuit diminue, ce qui augmente proportionellement l'importance de la résistance interne du 
générateur et par conséquence fait diminuer l'amplitude de la tension du générateur.

L'inductance introduit une avance de phase dans la tension (la tension aux bornes de la bobine est maximum au début puis diminue progressivement), la capacitance introduit un retard de phase dans la tension, celle aux bornes du condo est nulle au départ (pendant qu'il se charge) puis augmente progressivement.


Dans une alimentation, les condensateurs electrolytiques ont leurs plaques enroulées en spirale, ce qui gère une inductance parasite importante. Pour réduire ce problème on place un condo ceramique de faible valeur en parallèle.




Attention lorsqu’on mesure un diviseur de tension avec de très hautes résistances (1MegOhm par ex) on a souvent un écart avec la réalité a cause de la resistance interne du multimètre.


Polarisation de diode.

On regarde la tension dans les mailles sans la diode
si la ddp est supérieure a 0,6v et dans le bon sens de polarisation de la diode, on ajoute la diode et on recalcule les tensions, la diode force une tension de 0,6v.

Lorsqu'il n'y a pas de ddp entre les deux poles de la diode mais qu'on insère le multimètre, une tension apparait de 0,5v car la diode se polarise légèrement à travers le multimètre

Lorsque l'on mesure 0v sur le multimètre a un endroit non relié à la masse, on a certaines fois un numéro "flottant" qui bouge entre 0,0xx et -0,00xx celà indique que la mesure flotte et n'est pas reliée à la masse

Lorsqu'il y a une resistance en série avec une diode et que l'on a 0v entre les 2, pour savoir si c'est la résistance ou la diode ouverte, on mesure la tension entre les bornes de la résistance. Si la résistance est ouverte on aura un chemin pour le courant et la chute de tension sera de la tension d'origine - 0,6v, car la diode sera polarisée par la tension qui passe à travers le multimètre. 




