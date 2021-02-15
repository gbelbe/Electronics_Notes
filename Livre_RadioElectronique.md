# galvanometre

fil enroulé sur un cadre, avec un axe placé au milieu du champs magnétique d'un aimant. Quand un courant passe dans le fil, il se produit une force qui fait bouger le cadre sur lequel est placé une aiguille.

Un fil dans lequel passe un courant produit une force magnétique perpendiculaire à ce fil.

Très sensible, courant faible (50uA) pour le rendre efficace, on utilise des shunts:


# Alternateur:

tant que l'alternateur ne débite pas de courant, il n'y a qu'une tension (ddp) a ses bornes, et donc pas de courant qui circule dans la bobine, donc pas de champ magnétique, l'alternateur ne génère pas un champs qui s'oppose aux aimants et ne freine pas l'axe. Quand on consomme du courant, le courant circule et l'axe est freiné par l'action du champs opposé aux aimants.

# tension efficace = tension alternative qui fournirait la même puissance qu'une tension continue

Vmax = Racine(2) x Veff

Ueff = Vmax/ rac(2)   (RMS = racine de la moyenne des carrés)

# alternateurs: 

electro aimants avec un courant continu (qui permet de générer le champ magnétique) ce courant continue est variable en intensité en fonction de l'importance de la puissance à fournir. Celà s'appelle la puissance d'excitation de l'alternateur.
Petite dynamo branchée sur le même axe de l'alternateur qui sert à fournir son courant d'excitation.( petit alternateur à aimants , dont la tension
alternative est redressée.

Lorsque le champ magnétique varie à côté d'un conducteur, un courant est induit;
On peut faire varier ce champ magnétique en faisant bouger un aimant ou électro aimant à côté du conducteur, ou bien en faisant varier le courant qui passe
dans  une bobine, car la variation de ce courant génère également une variation du champ magnétique dans cette bobine.

==> Pour que des bobines soient bien couplées par induction mutuelles => variation de courant dans l'une transfert une variation de courant dans l'autre.
Elles doivent être proches l'une de l'autre dans le même axe.
==> Pour éviter un couplage par induction, on les éloigne ou on les places à 90° l'une de l'autre


# Oscillateurs a quartz

Une fine lame de quartz piezzoelectrique reliée par 2 electrodes résonne à une certaine frequence.
Un quartz possède deux fréquences de résonnance proches lorsqu'il est utilisé en série avec une impédance très faible
ou lorsqu'il est utilisé en parallèle avec une impédance plus forte;
Dans son utilisation en parallèle il est utilisé avec deux condensateur car il est équivalent à une inductance

# Oscillateur Colpitt

Un tank resonnant circuit est obtenu avec un inducteur et deux condos parallèles reliés à la masse. Les deux condos // agissent en diviseur de tension et permettent de renvoyer une partie du signal vers la base du transisteur pour qu'il soit amplifié et que l'oscillation soit maintenue.

Le fait de connecter les condos à la masse inverse le sens de leur charge et décharge, car chacun est connecté d'un côté et de l'autre de la masse. Celà permet d'obtenir une inversion de phase de 180 degrés et donc d'annuler l'inversion de phase en sortie de l'amplificateur. C'est important car si les phases sont opposées les tensions s'annulent et il n'y a pas d'amplification, et donc pas d'oscillation.

