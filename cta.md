###Materiaux conducteurs / isolants / semiconducteurs
Atomes sont constitués d'un noyau composé de protons (charges positives) et d'électrons qui tournent autour sur plusieurs ellipses concentriques. La couche la plus éloignée du noyau détermine la "réceptivité" aux électrons. 8 electrons sur cette couche étant le max, les atomes qui en possèdent 3 ou moins sont très réceptifs à en recevoir d'autres (ils sont donc bons conducteurs), ceux qui en possèdent 5 ou plus sont considérés isolants. Ceux qui en possèdent 4 sont semi-conducteurs.
Ces derniers s'arrangent entre eux pour former des cristaux, très stables, pour en faire des semi conducteurs il faut les "doper" en insérant quelques atomes conducteurs ou isolants pour que le matériel devienne instable et possède les propriétés des semi conducteurs 


###Identification de problèmes par l'analyse des tensions

Quand on a un doute sur un probleme sur un groupe de resistances en parallèle (ou de condos). On compare leur chute de tension avec les autres résitstances en série et on infère quelle serait la resistance équivalente. On la compare ensuite avec le calcul pour vérifier si ça correspond et s’il n’y a pas de fugue ou d’altération.

###Calcul proportionnel des tensions sur des resistances en série: 

regarder combien de fois faut il multiplier "la resistance la plus faible" pour obtenir chacune des autres résistances. 
Remplacer ensuite la valeur de chacune de ces résistances par ce "multiplicateur". 1x pour la plus faible resistance qui a servi de base pour le calcul, et Nx pour chaque autre resistance.
On divise ensuite la tension totale par le nombre de x total de toutes les résistances. Ensuite on obtient chaque chute de tension en divisant la tension totale par le nombre de X de chaque resistance.

###Calcul proportionnel des tensions sur des résistances en parallèle

S'il n'y a que deux branches parallèles, on calcule d'abord la resistance totale sur chaque branche en ajoutant les res. en série. Puis, on observe les proportions entre les res eq de chaque branche: combiens de fois doit on multiplier la resistance la plus faible pour obtenir la plus grande?
Une fois que l'on a ces proportions, on obtient la res eq en divisant la resitance la plus forte par le nombre de propotions total.

Ex: 1 res de 1K une de 5k en parallèle: proportions: 1x et 5x. Nombre total de proportions: 5+1 = 6 ==> res eq = 5k / 6 = 833 ohms


s'il y a plus que deux branches parallèles, on prends les 2 premières pour calculer la resistance équivalente, une fois celle-ci calculée, on calcule la résistance equivalente entre la res. eq obtenue et une autre branche. De meme jusqu'à ce qu'il n'y ait plus de branche disponible.


###Lampes en série et conseils pratiques de réparation


Pour économiser la pointe d’un fer a souder et sa consommation, ajouter un interrupteur sur le fil ainsi qu’une diode en parallèle. Lorque l’interrupteur est ouvert, la diode ne laisse passer qu’un seul cycle du courant alternatif et réduit la consommation d’énergie, lorsqu’on allume de nouveau, le fer se réchauffe très rapidement.

Lampe série: 3x plus puissante que l’appareil testé. Ex: RL de l’appareil: 25w → ampoule de 75w; Lorsqu’on a besoin de tester un appareil puissant on place plusieurs ampoules en série pour atteindre la puissance désirée.Si l’on a besoin de plus de puissance on peut utiliser une résistance de grille pain ou de douche

###Disjoncteur différentiel:
Surveille qu’il n’y ait pas de fuite de courant par ex lorsqu’un fil de retour touche une carcasse métallique et que quelqu’un touche cette carcasse, il y a une fuite de courant par le sol. Les deux fils d’entrée et de sortie sont enroulés pour provoquer un champ magnétique du même sens et de même intensité. Si l’un des fils reçoit moins de courant (à cause d’une fuite), le champ magnétique est différent entre les deux fils et celà provoque l’actionnement d’un interrupteur. Reactance inductive / reactance capacitive. 

###Force electro magnétique

La force électro magnétique dépend du nombre de spires et du courant qui circule dans le circuit, ainsi que du noyau ferreux qui permet de concentrer le champs de forces
Cette force apparait en courant continu (elle varie en force et en polarité en courant alternative)

###Induction electro magnétique

L'induction electro magnétique apparait lorsque le courant varie dans un inducteur. Lors de ces variations une tension apparait dans une bobine placée à proximité de son champs électro magnétique.

Attention, même avec un courant continue, une tension importante apparait lorsque la bobine est mise sous tension, ou lorsqu'elle est coupée. La bobine "réagit" aux changement par une tension qui s'oppose à la variation de la tension.C'est ce principe qui est utilisé pour générer l'étincelle dans la bougie des moteurs à essence: on alimente une grosse bobine, puis on coupe le circuit d'alimentation avec un interrupteur qui transferre à une autre maille ou la bougie est placée. Le faible écart entre les deux bornes de la bougie provoque une étincelle avec la tension générée.

Lorsque le circuit secondaire du transfo est ouvert (rien n'est branché à ses bornes), quasiment aucun courant n'est consommé. Lorsqu'il est fermé, un courant circule, ce qui crée une variation de champs du secondaire vers le primaire et provoque une consommation de courant.

Un transformateur a des pertes environ 10% et une puissance max de fonctionnement. Pour savoir quel est le courant maxi, on doit connaitre sa puissance et sa tension de secondaire et de primaire. 
La tension et le courant entre primaire et secondaires sont proportionnelles aux nombre de spires de ces deux bobines. La puissance est la même des deux côtés (hors les pertes).




###reactance inductive et capacitive.

l'impedance d'un transformateur fait qu'il limite plus le courant que sa simple résistance laisserait penser.
Zl = R (res ohmique du transfo) + Xl (reactance inductive à 50Hz/60Hz courant alternatif 220V classique)

Reactance inductive, augmente avec la fréquence

Reactance capacitive diminue avec la fréquence

Impedance =  somme des resistance et reactances.

Pour connaitre la reactance sur un circuit avec diviseur de tension, simplement, on regarde avec l'oscillo entre la resistance et l'inductance ou le condensateur
et on observe la chute de tension entre les deux sinusoides. Elle correspond à la proportionalité entre la resistance et l'inductance pour une frequence donnée.

Xl = 2pi f L

Xc =  1 / 2pi f C

Si l'amplitude du générateur diminue lorsque la fréquence augmente, c'est que sa résistance interne devient plus importante au regard de la reactance. Lorsqu'on augmente la frequence, la reactance capacitive diminue, donc la résistance totale du circuit diminue, ce qui augmente proportionellement l'importance de la résistance interne du 
générateur et par conséquence fait diminuer l'amplitude de la tension du générateur.

L'inductance introduit une avance de phase dans la tension (la tension aux bornes de la bobine est maximum au début puis diminue progressivement), la capacitance introduit un retard de phase dans la tension, celle aux bornes du condo est nulle au départ (pendant qu'il se charge) puis augmente progressivement.


Dans une alimentation, les condensateurs electrolytiques ont leurs plaques enroulées en spirale, ce qui gère une inductance parasite importante. Pour réduire ce problème on place un condo ceramique de faible valeur en parallèle.


Attention lorsqu’on mesure un diviseur de tension avec de très hautes résistances (1MegOhm par ex) on a souvent un écart avec la réalité a cause de la resistance interne du multimètre.


###Polarisation de diode.

On regarde la tension dans les mailles sans la diode
si la ddp est supérieure a 0,6v et dans le bon sens de polarisation de la diode, on ajoute la diode et on recalcule les tensions, la diode force une tension de 0,6v.

Lorsqu'il n'y a pas de ddp entre les deux poles de la diode mais qu'on insère le multimètre, une tension apparait de 0,5v car la diode se polarise légèrement à travers le multimètre

Lorsque l'on mesure 0v sur le multimètre a un endroit non relié à la masse, on a certaines fois un numéro "flottant" qui bouge entre 0,0xx et -0,00xx celà indique que la mesure flotte et n'est pas reliée à la masse

Lorsqu'il y a une resistance en série avec une diode et que l'on a 0v entre les 2, pour savoir si c'est la résistance ou la diode ouverte, on mesure la tension entre les bornes de la résistance. Si la résistance est ouverte on aura un chemin pour le courant et la chute de tension sera de la tension d'origine - 0,6v, car la diode sera polarisée par la tension qui passe à travers le multimètre. 




