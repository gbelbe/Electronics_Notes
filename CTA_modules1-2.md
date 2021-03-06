
### Materiaux conducteurs / isolants / semiconducteurs
Atomes sont constitués d'un noyau composé de protons (charges positives) et d'électrons qui tournent autour sur plusieurs ellipses concentriques. La couche la plus éloignée du noyau détermine la "réceptivité" aux électrons. 8 electrons sur cette couche étant le max, les atomes qui en possèdent 3 ou moins sont très réceptifs à en recevoir d'autres (ils sont donc bons conducteurs), ceux qui en possèdent 5 ou plus sont considérés isolants. Ceux qui en possèdent 4 sont semi-conducteurs.
Ces derniers s'arrangent entre eux pour former des cristaux, très stables, pour en faire des semi conducteurs il faut les "doper" en insérant quelques atomes conducteurs ou isolants pour que le matériel devienne instable et possède les propriétés des semi conducteurs 


### Identification de problèmes par l'analyse des tensions

Une resistance peut altérer (valeur ohmique augmente) ou s'ouvrir. + Sa résistance est grande plus la pellicule de carbone qui la forme est fine et plus elle est fragile.

Quand on a un doute sur un probleme sur un groupe de resistances en parallèle (ou de condos). On compare leur chute de tension avec les autres résitstances en série et on infère quelle serait la resistance équivalente. On la compare ensuite avec le calcul pour vérifier si ça correspond et s’il n’y a pas de fugue ou d’altération.

### Calcul proportionnel des tensions sur des resistances en série: 

regarder combien de fois faut il multiplier "la resistance la plus faible" pour obtenir chacune des autres résistances. 
Remplacer ensuite la valeur de chacune de ces résistances par ce "multiplicateur". 1x pour la plus faible resistance qui a servi de base pour le calcul, et Nx pour chaque autre resistance.
On divise ensuite la tension totale par le nombre de x total de toutes les résistances. Ensuite on obtient chaque chute de tension en divisant la tension totale par le nombre de X de chaque resistance.

### Calcul proportionnel des tensions sur des résistances en parallèle

S'il n'y a que deux branches parallèles, on calcule d'abord la resistance totale sur chaque branche en ajoutant les res. en série. Puis, on observe les proportions entre les res eq de chaque branche: combiens de fois doit on multiplier la resistance la plus faible pour obtenir la plus grande?
Une fois que l'on a ces proportions, on obtient la res eq en divisant la resitance la plus forte par le nombre de propotions total.

Ex: 1 res de 1K une de 5k en parallèle: proportions: 1x et 5x. Nombre total de proportions: 5+1 = 6 ==> res eq = 5k / 6 = 833 ohms


s'il y a plus que deux branches parallèles, on prends les 2 premières pour calculer la resistance équivalente, une fois celle-ci calculée, on calcule la résistance equivalente entre la res. eq obtenue et une autre branche. De meme jusqu'à ce qu'il n'y ait plus de branche disponible.


### Lampes en série et conseils pratiques de réparation


Pour économiser la pointe d’un fer a souder et sa consommation, ajouter un interrupteur sur le fil ainsi qu’une diode en parallèle. Lorque l’interrupteur est ouvert, la diode ne laisse passer qu’un seul cycle du courant alternatif et réduit la consommation d’énergie, lorsqu’on allume de nouveau, le fer se réchauffe très rapidement.

Lampe série: 3x plus puissante que l’appareil testé. Ex: RL de l’appareil: 25w → ampoule de 75w; Lorsqu’on a besoin de tester un appareil puissant on place plusieurs ampoules en série pour atteindre la puissance désirée.Si l’on a besoin de plus de puissance on peut utiliser une résistance de grille pain ou de douche

### Disjoncteur différentiel:
Surveille qu’il n’y ait pas de fuite de courant par ex lorsqu’un fil de retour touche une carcasse métallique et que quelqu’un touche cette carcasse, il y a une fuite de courant par le sol. Les deux fils d’entrée et de sortie sont enroulés pour provoquer un champ magnétique du même sens et de même intensité. Si l’un des fils reçoit moins de courant (à cause d’une fuite), le champ magnétique est différent entre les deux fils et celà provoque l’actionnement d’un interrupteur. Reactance inductive / reactance capacitive. 

### Force electro magnétique

La force électro magnétique dépend du nombre de spires et du courant qui circule dans le circuit, ainsi que du noyau ferreux qui permet de concentrer le champs de forces
Cette force apparait en courant continu (elle varie en force et en polarité en courant alternative)

### Induction electro magnétique

L'induction electro magnétique apparait lorsque le courant varie dans un inducteur. Lors de ces variations une tension apparait dans une bobine placée à proximité de son champs électro magnétique.

Attention, même avec un courant continue, une tension importante apparait lorsque la bobine est mise sous tension, ou lorsqu'elle est coupée. La bobine "réagit" aux changement par une tension qui s'oppose à la variation de la tension.C'est ce principe qui est utilisé pour générer l'étincelle dans la bougie des moteurs à essence: on alimente une grosse bobine, puis on coupe le circuit d'alimentation avec un interrupteur qui transferre à une autre maille ou la bougie est placée. Le faible écart entre les deux bornes de la bougie provoque une étincelle avec la tension générée.

### Générateur

Aimant qui tourne sur un axe autour d'une bobine, ou bobine qui tourne sur un axe a côté d'un aimant.
Vrais aimants, ou électro aimants (bobine alimentée par une tension continue).

### Tension alternative

Générée par un générateur passe du + au - avec une certaine fréquence. Fréquence (Hz) =  1 / Période (en secondes)
Une tension alternative a une équivalence de tension moyenne (Root Mean Square) ==> 220v ou 110v par ex.
Pour obtenir sa tension max:  

Umax = Urms * 1,414
Urms =  Umax * 0,707


### Courant Triphasé

Pour avoir le meilleur rapport entre facilité de transport d'électricité (nombre de fils à utiliser sur les lignes) et maximisation du courant produit lors par les alternateurs (les centrales hydrolique, éolienne, nucléaire, thermique etc. utilisent tous des générateurs):
Lorsque le rotor fait 1 tour sur lui même, il passe devant trois aimants / bobines, et donc produit trois tensions sinusoidales décalées de 120 degrés. Celà permet de densifier la puissance produite par tous ces courants;

note: tension entre deux des trois cables du triphasé: 380vAC, tension entre un seul des cables et la terre: 220vAC
le transfo local passe du 13800v au 220v entre 2 fils du trifasé en introduisant un neutre au milieu. La taille du cable de sortie du transfo, est importante et généralement après ce transfo on tire plusieurs cables parallèles à chaque habitation pour éviter un gros cable sur une distance trop importante.

### Transformateur

Deux bobines de fil isolé l'une en face de l'autre ou cote à cote, (ou une seule bobine avec plusieurs sorties intermédiaires (auto transformateur). Couplage avec du matérieux ferreux (magnétique) pour concentrer les flux magnétiques et réduire les pertes.

Lorsque le circuit secondaire du transfo est ouvert (rien n'est branché à ses bornes), quasiment aucun courant n'est consommé. Lorsqu'il est fermé, un courant circule, ce qui crée une variation de champs du secondaire vers le primaire et provoque une consommation de courant.

Un transformateur a des pertes environ 10% et une puissance max de fonctionnement. Pour savoir quel est le courant maxi, on doit connaitre sa puissance et sa tension de secondaire et de primaire. 
La tension et le courant entre primaire et secondaires sont proportionnelles aux nombre de spires de ces deux bobines. La puissance est la même des deux côtés (hors les pertes).


### reactance inductive et capacitive.

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


### Polarisation de diode.

On regarde la tension dans les mailles sans la diode
si la ddp est supérieure a 0,6v et dans le bon sens de polarisation de la diode, on ajoute la diode et on recalcule les tensions, la diode force une tension de 0,6v.

Lorsqu'il n'y a pas de ddp entre les deux poles de la diode mais qu'on insère le multimètre, une tension apparait de 0,5v car la diode se polarise légèrement à travers le multimètre

### Défaults sur diodes 

Lorsque l'on mesure 0v sur le multimètre a un endroit non relié à la masse, on a certaines fois un numéro "flottant" qui bouge entre 0,0xx et -0,00xx celà indique que la mesure flotte et n'est pas reliée à la masse

Lorsqu'il y a une resistance en série avec une diode et que l'on a 0v entre les 2, pour savoir si c'est la résistance ou la diode ouverte, on mesure la tension entre les bornes de la résistance. Si la résistance est ouverte on aura un chemin pour le courant et la chute de tension sera de la tension d'origine - 0,6v, car la diode sera polarisée par la tension qui passe à travers le multimètre. 

Lorsqu'une diode a une chute de tension de 0,4v ou moins elle est en fugue.
Lorsque la ddp est supérieure à 0,7 elle peut être altérée.
(4 probs: en fugue, en court circuit, ouverte, altérée, fugue en polarisation inverse)

Diode en série avec une resistance et parallèle avec une autre resistance: on calcule la resistance eq. parallèle, et on ajoute un peu de tension (0,3v) pour tenir compte de la resistance.

Note: si une diode est en série avec une résistance et qu'il y a un défaut, si la ddp autour de la diode est de 0,6v, celà n'exclue pas que la résistance soit altérée

Si une diode est en série avec une resistance. Si un courant même très léger circule par la diode (ex: ddp de 0,5 sur la diode), on doit observer également une ddp légère sur la résistance.

Lorsqu'on a une maille série parallèle avec une diode zener ou plusieurs diodes sur l'une des branches, pour calculer la tension en dessus de la maille, on déplace toutes  les diodes vers la masse, puis on calcule la moyenne pondérée des tensions sur les résistances de chaque branche. Ca nous donne la tension moyenne que l'on peut utiliser comme base à la maille parallèle au dessus des diodes.

Moyenne pondérée des tensions.
On calcule la proportion des Req de chaque branche (1x / 3x par ex), puis on multiplie chaque proportion avec la tension de la branche opposée et on ajoute le tout, puis on divise par la somme des proportions.
On continue ensuite les calculs en se basant sur la tension moyenne obtenue comme base commune des resistances en parallèles au lieu de 0v.
Cette technique marche aussi pour des tensions négatives (ce qui compte c'est la DDP, une tension négative s'ajoute a une positive pour former une ddp totale plus importante).

Attention a bien vérifier le sens de circulation du courant qui n'est pas toujours bien explicite sur les schémas. Peu importe le schéma, le courant va toujours de la tension la plus haute à la plus basse.

### Diodes en circuit alternatif après transfo

Une diode située au secondaire d'un transfo élimine chaque demi cycle négatif, ne laissant passer que le cycle positif moins 0,6v de chute de tensions sur la diode.
20v alternatif, 19,4 vmax après la diode. On calcule la tension RMS sur ce demi cycle (70,7% de Vmax) = 13,7 v, puis on divise ce résultat par 2 car l'autre demi cycle est bloqué par la diode (0v), c'est pour celà qu'on obtient 6,8 V avec le multimètre en position courant continu.

Quand on mesure un circuit avec 1 diode et 2 resistances en série attachée au secondair d'un transfo et la ref terre entre les deux, lors du cycle positif, on a 20v aux bornes du secondaire et +10v et -10v entre chaque resistance (ref 0v entre les deux), et 0v et -20 v lors du semi cycle négatif ou la diode bloque le passage du courant. (c'est alors un circuit ouvert ou le courant ne passe pas, on a donc d'un coté une ref à -20v et 0v derrière la diode qui est comme un bouton ouvert).

Lorsqu'on mesure la tension AC au secondaire du transfo, le multimètre mesure la tension efficace et non de pic. (donc 70% de la tension de pic).
Lorsqu'on mesure la tension DC rectifiée après diode et avec un condensateur en parallèle, cette tension DC sera plus grande, car le condo se charge jusqu'à la tension de pic AC. (et non efficace)

Pour savoir le ripple d'une tension d'alim:
t = C.R (tau =  constante de decharge de 63% du condo, 3t = 95%, 5t = 99%)
freq 50hz => periode (50 cycles par seconde) combien de fois 50 dans 1000ms? => dans 100ms = 2x dans 1000 => 20x, periode = 20ms.
Temps que le condo doit supporter la charge tout seul (sans l'aide de la tension du transfo)==> temps entre le moment ou il est chargé au max (Vmax, milieu du semi cycle positif), et quelque part lors du début du semi cycle positif (moment ou la tension fournie par le transfo est égale à la tension aux bornes du condo.
20ms.
t = RC    pour RL = 1500 ohms et C = 4,7uF = 0,0000047 F
t = 1500 * 0,0000047 = 0,007 ==> 7ms jusqu'à ce qu'il ne reste plus que 30% de la charge du condo.

Lorsqu'on mesure un courant alternatif rectifié par une diode, à la borne du transfo qui est près de la diode, on observe une tension négative élevée lors du semi cycle bloqué par la diode. (le courant étant bloqué par la diode, il ne circule pas, il n'y a donc pas de chute de tension aux bornes des resistances mais simplement un pic de tension généré par la "pile" (les bornes du secondaire du transfo). 

Pour bien repérer le sens de circulation du courant à partir du secondaire d'un transfo, on le remplace par une pile ou une source DC de polarité définie. (on inverse la polarité pour imaginer ce qui se produit lors de l'autre phase).



### Circuit doubleur de tension

Lorsqu'on a 20 v au secondaire d'un transfo, rectifié en demi onde avec une diode, et intégré avec un condo, lorsque le demi cycle s'inverse, la diode bloque et l'on obtient 40 v momentanément à l'un des poles du secondaire du transfo (près de la diode qui bloque lorsque la tension s'inverse). (20v en sens contraire sur le transfo + 20 v qui provient du condo chargé).
Si on ajoute une diode suivie d'un condensateur, on laisse passer cette tension de 40v pour charger le condo et obtenir une tension continue de 40v.


### Vp Vpp Vdc-eq

Vp = tension de pic d'une onde. S'il s'agit d'un ripple qui a une faible variation mais arrive a un niveau de tension élevé, Vp correspont à la tension de pic la plus élevée au dessus de 0.
Vp, on prend la tension max a partir de la référence utilisée pour faire la mesure (Ref souvent 0). Vp est positive ou négative.


Vpp =  s'il s'agit d'un ripple, il y a une faible variation, Vpp correspond à la différence entre le point de plus faible tension et de plus haute tension de l'onde. Vpp peut être plus faible que Vp, par exemple pour une onde de ripple. La tension Vpp n'a pas de polarité.

Pour le calcul d'une tension DC moyenne equivalente, il faut observer la surface moyenne de l'onde et imaginer le niveau qui repartirait cette surface en deux parties de surfaces égales (en haut et en bas du trait)


### Diodes Zener

Une diode zener est ustilisée en polarisation inverse. Sa tension nominale peut varier légèrement (elle est inférieure si elle reçoit peu de courant / resistance élevée en série) ou tension inférieure si bcp de courant (faible resistance en série)
Vz (tension zener =  tension inverse)
Pmax (puissance max)

Note: circuits parallèles indépendants:
Si 2 circuits parallèles sont liés à l'alimentation, ils sont indépendants, car la source fournie une tension égale peu importe les circuits.
Si par contre il y  a une resistance en série avec ces deux branches parallèles, (ex resistance interne de la batterie), la consommation d'une des branches influe sur l'autre.

Lorsqu'on a une zener dans un circuit parlallèle, elle même en série avec une resistance, on place la zener en bas et on la retire du circuit pour calculer une moyenne pondérée.

Moyenne pondérée des tensions sert à trouver la tension moyenne à laquelle on va ajouter la tension équivalente.

Dans un circuit série avec des diodes zener ou non qui ne sont pas polarisées car leur tension dépasse la tension de la source, lorsque l'on introduit un multimètre entre les diodes, l'une d'elle peut être polarisée par le faible courant qui passe par la résistance élevée du multimètre (>1 Mohm) et formant un circuit parallèle directement connecté à la masse.
Attention, si une diode est inversement polarisée sur un circuit série, le fait de placer le multimètre pour mesurer une tension avant cette diode laissera passer un courant faible à travers le multimètre et montrera une chute de tension.

Si l'on ne sait pas la tension type d'une zener, on peut facilement la retrouver en la mettant en série avec une resistance de 10K sur une tension de 12v ou plus. On mesure au multimètre la tension à ses bornes.

### LED

Une led a une tension de polarisation généralement entre 1,5 et 3v certaines fois plus, en fonction de la couleur.
Pour polariser plusieurs diodes on peut les placer en série avec une résistance qui limite le courant en série.
Si l'on veut polariser plus de résistances on ne doit pas les placer en parallèles avec une résistance unique pour limiter le courant car si l'une des led s'ouvre, le courant sera supérieur sur toutes les autres branches parallèles. On préfèrera créer des circuits séries séparés, chacuns avec sa résistance.

### Transistor

Le transistor NPN ou PNP est composé de trois poles, Emissor (polarité avec la flèche) Collector et Base. 
Gain du transistor (ou Beta ou Hfe) correspond à Iec / Ibe. Il correspond au facteur de gain en courant entre le courant de base et Collecteur Emissor.
Si l'on veut utiliser un transistor comme un interrupteur (on doit "saturer" le transistor), il faut s'assurer que l'on envoie 30% de plus de courant que le courant de base nécessaire avec le Béta du transistor. De cette manière on est certain que le transistor sera complètement saturé et aura une résistance EC proche de zéro. Il faudra également s'assurer d'ajouter une résistance de protection à la base de celui-ci pour limiter le courant qui passera par celle-ci et éviter que le transistor ne crame.

Attention, lorsqu'on mesure un transistor avec un multimètre et que la base est ouverte, la tension mesurée ne sera pas nécessairement nulle car le multimètre a une résistance propre d'1 Mohm, qui sera donc placée en série avec la base et pourra générer une faible polarisation de la base du transistor. (la tension obtenue sera donc celle d'un circuit avec un diviseur formé par une eventuelle autre résistance, la jonction du transistor et la résistance du multimètre)

Un transistor possède également une tension Emissor Collector maximum, par sécurité on s'assurera qu'elle est au moins 30% supérieure à la tension nécessaire pour notre circuit. (on prend toujours une marge de 30% sur les maximums indiqués dans les specs)

Si le transistor doit alimenter un relai, il faudra mettre une diode en parallèle avec le relai car la tension inverse générée par la bobine sera haute lorque le transistor sera dépolarisé. Lorsque le transistor sera coupé, la tension aux bornes de la bobine aura un chemin pour circuler par la diode et circulera en boucle par la bobine jusqu'à ce qu'elle soit dispersée par effet joule.

Pour dimensionner le courant nécessaire pour le transistor:
- relai 12v 1A, il faudra qu'il y ait 1 A qui passe par le transistor.
- transistor Beta = 20, courant de base = 1/20 => 0,05 A, pour s'assurer d'une bonne polarisation on prendra 30% de plus de courant de base, donc 0,065A
- On choisira donc une résistance qui limitera le courant à 0,065 A.

### Protection contre les interferences électromagnétiques.

Attention : Lorsque le transistor est dépolarisé, on ne doit pas laisser la base "flottante" car les émissions électromagnétique (courant 60hz, ou moteur) peuvent générer un bruit qui va polariser le transistor aléatoirement. On ajoute donc une résistance qui reliera la base à la terre lorsque le transistor sera dépolarisé. Plus la valeur de la resistance est basse moins il sera sensible aux "bruits". Mais certaines fois il ne sera pas possible de mettre moins de 10k (car celà provoquera un diviseur de tension trop élevé)

Un autre moyen de lutter contre les interférences de haute fréquence est de placer un condensateur entre la base et le collecteur: celui-ci se charge avec la tension de collecteur. Lorsque la base capte une interférence, la base se polarise et fait baisser la tension de collecteur. Comme le condo était chargé, il transferre cette baisse de à la base (l'autre côté du condo). En chutant la tension dépolarise le transitor immédiatement. (et donc le protège contre les polarisations intempestives dues aux EFI). 




### Types de problèmes sur un transistor

Court circuit entre base et collecteur ou entre collecteur et emisseur

Manque de gain (le transistor a un gain plus faible que prévu, malgré une bonne polarisation)
Lorsqu'on est certain que le transistor reçoit une bonne polarisation (0,6v ou plus) mais que celui-ci ne sature pas complètement, (il y à une ddp de plusieurs volts à ses bornes) il a sans aucun doute un problème de défaut de gain.

Une fugue émisseur collecteur provoque une chute de tension indésirable aux bornes du transistor, même lorsqu'il est dépolarisé.

Une fugue base-emissor diminue la conduction collecteur-emisseur, et empêchera la transistor de se polariser correctement, même lorsqu'il existe suffisament de courant à sa base. (la chute de tension entre collecteur et emisseur diminue, ou sa resistnace equivalente augmente par rapport à la normale.)

Attention aux mesures près des semiconducteurs: Le multimètre est une resistance d'1 MegaOhm ou plus en série. Il a donc des effets sur le résultat de la mesure.

Ex: un transistor coupé (non polarisé par le circuit) devrait avori 0v sur sa base mais aura probablement O,5v lors de la mesure car le multimètre est en série avec celui-ci.

Lorsqu'un transistor travaille dans un circuit a haute frequence, saturant et ouvrant tres rapidement, la tension sur sa base sera de 0,3v (tension moyenne entre 0,6 et 0v).

Lorsque le transistor joue le role d'actionneur, il est normalement saturé (tension de 0V entre collecteur et emisseur). S'il ne l'est pas complètement de quelques milivolts à quelques volts entre E et C, celà n'est pas forcément un défaut, si celà n'empeche pas le circuit d'actionner correctement. C'est peut-être simplement un petit manque de courant en base ou une petite fugue.


Lorsqu'un transistor est polarisé par un autre, pour trouver le défaut, il faut bien observer en remontant la pente, si le transistor est bien polarisé par une tension suffisante, et observer les chutes de tensions dans les résistances en amont pour voir d'ou vient le courant. Si la chute de tension dans les résistances proches vont dans le sens opposés au normal, c'est probablement qu'il y a une fugue base emisseur ou base collecteur qui dévie le courant et le fait aller dans le "mauvais sens".

Attention: une fugue collecteur base va auto-polariser le transistor et donc faire passer une tension de 0,6 entre base et emisseur.
Il faut toujours regarder quelle est la polarisation du transistor et imaginer ce que celà devrait donner comme resistance / saturation du transistor. (0,7v à la jonction BE devrait normalement sature le transistor).
Pour savoir si c'est une fugue collecteur emisseur ou collecteur base, on regarde s'il y a du courant qui remonte par la base on non. (si oui c'est qu'il y a une fugue collecteur base qui polarise le transistor et laisse passer le reste du courant du collecteur vers la base en remontant sur la resistance de base.


### Circuit avec LDR / relai et transistor

Lorsque l'on veut retarder la polarisation du transistor par le diviseur de tension et la LDR, on peut ajouter un Transistor en parallèle avec la LDR et la masse. Il prendra un certain temps à se charger et retardera la polarisiation, ce qui evitera que le relai ne clignote lorsque le diviseur est proche de la tension de polarisation du transistor. (on prend t = RC (temps pour 66% de tension, 2t pour 90%) pour calculer la capacitance nécessaire en fonctio du temps de délai nécessaire)


### options différentes entre Base Emissor en fugue ou resistance de base ouverte:
La fugue base emissor entrainera une consommation de puissance élevée à travers la resistance de base, généralement de faible valeur, qui entrainera un dégagement de chaleur important sur le circuit. Si la résistance est ouverte, pas de courant, donc pas de dégagement de chaleur.

### transistor comme amplificateut de signal

On choisit sa valeur de resistance équivalente = 1,5 fois celle de la résistance de collector. On peut mettre une résistance d'émisseur de faible valeur.


### Alimentation stabilisée:

Une alimentation statbilisée est un diviseur de tension entre la charge et un transistor qui maintient toujours la même proportion entre les deux, peu importe la consommation de la charge. (+ la charge consomme, plus sa résistance interne diminue, et donc plus le transistor doit être polarisé pour maintenir la proportion du diviseur).

Une diode zener permet de maintenir la tension fixe, on calcule la résistance nécéssaire pour polariser la base du transistor avec juste suffisament de courant en sortie (après x par le Béta) pour qu'il y ait 1A qui passe par le transistor.
Si la diode zener fixe la base du NPN a 5,6v, la tension aux bornes de la charge sera fixée à 5v. Donc le courant qui passe par le transistor (1A) passera aussi par la charge.), il suffit de trouver le courant nécéssaire sur la base pour que le transistor renvoie 1A. Ce courant et la tension restante (tension totale - zener) determinera la résistance de polarisation de la base.
Attention à réduire un peu cette resistance pour permettre au courant de base de passer également par la diode zener et de maintenir sa polarisation. (si tout le courant venait a passer par le transistor, la diode zener n'en recevrait pas suffisament pour se polariser et ne pourrait jouer son role)

Attention, on doit vérifier que si l'on éteint la charge, la diode zener supportera le courant qui passera alors entièrement par elle. (on verifie sa puissance (p=UxI).

! 7809 entree doit être supérieur à la sortie d'au moins 30% pour que la reduction de tension soit correcte.


Si l'on a un courant trop important sur la diode zener, on peut ajouter un autre transistor directement connecté à la base du premier, pouar ajouter un étage d'amplification et réduire le courant max de la zener qui sera maintenant connectée à la base du second transistor.

Note: on effectue les calculs de resistances de polarisation en prenant le cas du courant maximum. A partir de ce courant on calcule la resistance de collecteur pour qu'elle soit légèrement inférieure à la resistance interne du transistor. La somme des deux devra être calculée pour le courant maxi. Donc on prendra 2/3 de la tension sur la resistance de collecteur par ex. L'idée est que comme on est sur le courant max, lorsque le courant diminura (moins de consommation de la charge) le transistor augmentera sa résistance interne. (on doit toujours choisir uen valeur de la résistance de collecteur de telle sorte à ce que le transistor reste en polarisation moyenne et ne soit jamais saturé ou coupé (sauf si l'on a retiré la charge du circuit).

### Choix des resistances alim stabilisée:

Attention à penser à trouver une résistance pas trop élevée pour laisser toujours un peu de courant polariser la diode zener et la jonction du transistor. Si la résistance ne permet pas suffisament de passage de courant pour polariser la zener, le circuit ne fonctionnera pas.

Penser aussi au cas ou rien n'est branché au circuit et donc tout le courant passe par la zener: important de voir quelle puissance elle absorbe pour choisir le bon composant 0,5w ou 1 w.

Attention aux montage réalisés en tension négative (-Vcc) les composants sont montés à l'envers

Attention à la mesure de tension: a partir de quelle reference mesure t'on la tension. La masse définie la référence. tout point avec un potentiel en dessous de la masse est négatif.

Attention, pour un transistor on prend dans les specs toujours la Hfe mini pour faire les calculs. Souvent les specs donnent une hfe mini et maxi comme elle varie selon les pièces, on veut garantir un courant minimum dans la base pour être certain que le transistor sera saturé, donc pour calculer la valeur de la resistance de base on prend en compte le gain mini du transistor

Régulateur 7805: attention, le circuit ne régulera la tension que pour une tension au minimum 30% supérieur à la tension de sortie spécifiée. Idem pour un circuit avec des composants discrets.

Pour calculer le dissipateur que l'on doit accrocher: regarder l'écart de tension à stabiliser (20 entrée 9 ens ortie => 11v de chute sur le régul), on multiplie par le courant qui passera dans le circuit et l'on a la puissance qui passe à travers le composant et la nécessité de dissipateur

Pour calculer le transistor nécessaire pour une alimentation stabilisée: on regarde ce que la "charge" nécéssite comme courant. On part toujours de la fin du circuit car le courant est "tiré" par la charge, et le reste du circuit doit lui fournir ce courant.
Ex: la charge a besoin de 5 A: le transistor devra laisser passer 5A, donc sa base devra être alimentée par 5/ Hfe min (gain mini du transistor) => une fois que l'on a le courant mini on peut en déduire la résistance de base en la prenant toujours légèrement supérieure pour polariser le zener.

Attention on doit choisir un transistor qui accepte au moins 30% de plus de courant que celui qui est nécessaire pour le circuit.

On commence toujours par travailler avec l'hypothèse de consommation maxi de la "charge". On traite après le cas ou la consommation est nulle.

Montage avec deux ou plusieurs transistors permet de diminuer la taille des composants.
calcul de la polarisation du transistor qui va polariser le transistor de puissance. On part du cas de consommation maxi pour déterminer le courant de base nécessaire.
Comme on est dans le cas de consommation maxi, on calcule une resistance faible du transistor de polarisation (mais mieux vaut ne pas le saturer car celà permettra d'être plus tolerant s'il y a consommation légèrement supérieure). On peut prendre l'hypothèse qu'en courant maxi la resistance de collector sera 2/3 superieur ou égale à la resistance du transistor de polarisation. On regarde ensuite la chute tension qui passe par le transistor et sa resistance de collecteur, et on divise par le courant nécessaire à la base du tr de puissance. ==> on en déduit la ddp sur la resistance et donc sa valeur.


# realimentation négative

circuit de régulation des alimentations stabilisées.

2 resistances reliées à un transistor npn par sa base, son emissor est connecté à la terre atravers de 2 diodes. La tension de seuil des 2 diodes + la jonction du transistor = 3x0,6v = 1,8v
a partir de 1,8v le transistor est polarisé. La tension sur la resistance du dessus => U => 1,8 pour une R de 10k  ==> Combien pour une R de 100K? ==> 10x1,8 ==> 18v




# notes transistors


Attention on dit que le collecteur est ouvert quand il y a polarisation de la base emissor mais pas de circulation de courant entre collecteur et emisseur

Manque de gain: polarisation entre base et emisseur de 0,7 et 0,8 mais pas de saturartion

si la jonction base emissor se coupe dans un transistor npn, la tension de base va augmenter fortement (elle ne sera plus contrainte par la tension de diode)

Attention quand faible polarisation d'un transistor, regarder les flux de tension avant le collecteur et après l'emisseur, si l'un d'eux est nul (pas de chute de tension dans l'une de ces résistances celà indique qu'il n'est pas polarisé.

Cas d'un transistor qui n'est pas polarisé mais ou les tensions de collecteur et d'emisseur sont différentes: il y a peut etre une fugue C-E. Mais regarder s'il y a chute de tension dans les résistances avant ou après le transistor. Si ce n'est pas le cas il n'y a pas de courant qui passe par le transistor. Dans ce cas un transistor qui parait polarisé par le premier est peut-être tout simplement en fugue collecteur base, une fugue qui fait polariser de lui même la base du transistor, sans courant qui circule dans la maille de la base.

Attention si la tension de sortie est faible, et que même en remontant les transistor elle n'atteint pas la tension de seuil du zener, celui ci ne sera pas activé et il ne maintiendra pas la tension à sa tension de seuil.
Lors d'un circuit d'alim stabilisé, veiller a regarder s'il n'y a pas un défaut de polarisation des transistors qui draine du courant et empêche la zener d'atteindre sa tension de seuil. Si tout parait normal c'est la zener qui est en fugue. 

Si le transistor chauffe: il y a du courant qui passe => donc il ne peut pas sagir d'un problème de manque de gain, mais plutot d'une fugue collector emissor.

Falta de ganho: malgré une bonne polarisation le transistor ne sature pas, ou a une résistance supérieure à ce qu'il devrait avoir. Mais : IL NE CHAUFFE PAS

Si il y a une fugue sur un condensateur, le condo en parallèle avec la charge fait baisser la tension et fait passer beaucoup de courant à travers le transistor qui s'échauffe fortement.

Chaleur ==> fort courant != problème de gain

Si c'est chaud: fort courant. Si la tension de base est correcte, transistor bien polarisé. Si la tension de sortie n'arrive pas à monter ==> resistance de charge trop basse ou fuite d'un capaciteur qui réduit la résistance equivalente de la charge


# réalimentation négative:

le principe est de stabiliser la tension de sortie d'une alimentation: On identifie une tension maximum autorisée en sortie.
Au niveau de la sortie on a un diviseur de tension connecté à la base d'un transistor NPN lui même relié par son émisseur à une diode zener.
Celà permet de polariser le transistor quand la différence de potentiel entre la tension au diviseur et celle de la zener est supérieure à 0,6v.
Dans ce cas, le NPN est polarisé et dévie le courant de la base du transistor principal de l'alimentation. En déviant le courant de la base du transistor principal, celà 
réduit la polarisation de celui-ci, qui conduit moins, et augmente sa résistance propre. Celà réduit donc la tension de sortie de l'alimentation jusqu'à ce que le diviseur 
de tension soit inférieur ou égal à 0,6v et que cette dépolarisation cesse.
Note: on alimente directement par une diode relié au + la diode zener pour s'arrurer de la stabilité de sa polarisation. (resistance relativement élevée pour ne pas consommer trop de courant)

Realimentation négative: se oppose à la variation. Va dans le sens inverse pour stabiliser.

## Detection de tension:
- la detection de courant se fait grâce à un diviseur de tension qui prend un échantillonage de la tension de sortie et la compare à une tension fixée par une diode zener (ou plusieurs diodes en série). Cette comparaison se fait entre la base et l'emisseur d'un transistor. l'emisseur à une tension fixée par la zener et le diviseur est relié à la base, plus la dif de tension est importante plus le courant sera important et plus le transistor sera polarisé. (comme la tension est fixée à 0,6v par la jonction du transistor.)

## Détection de courant:
Elle se fait en insérant une résistance de faible valeur entre base et emisseur d'un transistor qui servira à dévier le courant du circuit principal lorsque le courant dépasse une certaine valeur. En principe le transistor n'est pas polarisé mais lorsque le courant est suffisament important pour générer une chute de tension supérieure à 0,6v aux bornes de la résistance, celle ci polarise le transistor qui déviera le courant de la base du transistor principal, augmentant la résistance de celui ci et limitant le courant qui passe par la maille principale.

Plus grande chute de tension =  plus grand courant circulant = plus grande valeur de resistance:

# condensateur ceramique: fugue tres probable vs condo polyester fugue plus rare


# Note: 
quand deux résistances sont en série mais et entre les deux la base d'un PNP, il y aura un peu du courant de base qui passera par la résistance du bas.
Plus il y a de courant qui passe dans une résistance, plus sa DDP (tension entre les bornes augmente) U = R(fixe) x i (un peu plus de courant que celui du diviseur resistif car on ajouter celui de la base)

pour déterminer la polarisation d'un transistor en config d'ampli: on cherche sa tension de base (diviseur de tension + un peu de courant de base dans la R du bas)
on en déduis la tension à l'émisseur, puis on en déduit la DDP sur chaque résistance, et donc celle du transistor.
