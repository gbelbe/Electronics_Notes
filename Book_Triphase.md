# Nums complexes

j = Racine(-1)² ou j² = -1

forme cartésienne: z = a + jb (representee par un point sur 2 axes: a reel = abscisses, b imaginaire = ordonnées)

forme polaire: z = Z L 0(angle phi)  (Z = segment Oz qui part de l'origine jusqu'au point z, et 0(phi) l'angle entre abscisse et Z)

forme trigo: z = Z.cos0 + j.Zsin0
 
## pour transformer un complexe de la forme cartesienne a la polaire:

Z = racine (a² + b²)  ==> theoreme de pythagore Z² = a²+b²

O(angle phi) = atan(b/a)   
    - SohCahToa = tan = opposé sur adjacent, donc on fait atan pour retrouver l'angle phi)
    - on fait attention a corriger l'angle pour qu'il soit basé sur la partie positive de l'axe des abscisses

## pour transformer la forme polaire en cartesienne:

a = Z.cos0 (phi)   b = Z.sin0 

donc z peut s'écrire:

z = Zcos0 + j.Zsin0  ou  z = Z.(cos0 + jsin0)


# Opérations avec les complexes:

## somme et soustractions

forme cartesienne + les a et b

## x et :

forme polaire:

multiplication: x les modules et + les arguments (angles)

div:  : les modules et - les arguments



## conjugués:

z = a + jb   ==> conjugué z* = a - jb  ou z* = Z L -0

z.z* = a²+b²  (elimine la partie imaginaire


conjugué sert a diviser 2 complexes en cartesiens

1) on trouve le conjugué du denominateur
2) on le multiplie par le numerateur et le dénominateur


# signaux sinusoidaux

## representations

1. graphique sinusoide qui part de 0, soit en temporel: T soit en angulaire Pi

2. mathematique: 

w (omega, vitesse angulaire en radians/sec)  ==> w = 2pi.f

v(t) = Vp.sin(wt+0o)
v(0) = Vp.sin(0+0o)  0o= phase initiale, si >0 avance de phase, si <* 0 retard de phase

3. diagramme phasorial

cercle avec 2 axes et vit. angulaire anti horaire.
angle 0 = phase initiale
rayon = Vp
valeur v(t) = sin(0) = projection de P sur l'axe y.

on peut calculer simplement le décalage entre 2 signaux de meme frequence sur le meme diag phasorial.

4. par les nb complexes


v = Vp L 0o             forme polaire

v(t) = 15.sin(wt + 60)  forme trigo


# Opéraions

negatif 
- diag phasorial : on bouge le fasor de +-180 degres 
- en num complexes: polaire +-180 degres sur la phase, ou changer le signe des parties reelles et img


# tensoin et courants en circuits resistifs

i et v sont en alignement de phase: R n'a pas de phase, v(t) a un vecteur plus long qui i(t) mais ils sont alignés.
p = R.i²
p = u² / R

## p est pulsant et toujours positif car au meme moment i et u sont toutes les deux de meme signe
indépendant de la polarité, R se comporte comme un consommateur de puissance

freq P = 2 x freq v ou de i

!!! attention il n'existe pas de P rms, mais P moyenne = P pic / 2 ou Urms x I rms

## valeur efficace Vrms

valeur de tension continue equivalente qui dissiperait la meme puissance moyenne avec la meme resistance

Vrms = Vp/ rac2   (rac2 =1,414)     

Vrms = Vp*0,707

## fusibles: 
choisits pour valeur de pic d'intensité donc attention a convertir Vrms en Vpic


# transfo :  Vp/Vs = Np/Ns

# bobines:

quand le courant passe par les spires, celà genère un champs magnetique qui génère un courant électrique contraire force electromotrice auto induite

loi de lenz, cette fem autoinduite s'oppose au courant qui l'a créée.(**l'augmentation** du courant i dans la bobine)

- l'inducteur stocke le courant sous forme de champs magnetique
- il s'oppose aux variations de courant
- dans un inducteur le courant est en retard par rapport à la tension

au moment exact ou le circuit s'ouvre la tension auto induite s'ajoute à la tension de l'alim, il peut se produire un arc.

l'inductance L = capacité a stocker de l'énergie sous forme magnétique (H)

R s'oppose au passage du courant
L s'oppose aux variations de courant

Sur un inducteur, la tension est proportionnelle à la variation de courant à ses bornes.

v(t) = L x di(t)/dt


courant sinusoidal ==> i retardé de 90 degres / u

v(t) = Vp sin wt
i(t) = Ip sin (wt - 90)

## reactance inductive:

Xl ==> opposition au passage du courant d'une bobine:

Xl = 2.pi.f.L = w.L

plus l'inductance de la bobine est élevé, plus sa réactance est forte (nb de spires, noyau, longueur et diamètre de l'enroulement...)
plus la freq est élevée plus la réactance est forte.

En cc: inducteur = fil, en ca = résistance, si F, très élevé = circuit ouvert

Xl = v / i

Xl = V L 0  /  I L-90  ( V/I avec retard de phase de I de 90°)

divisions de nombres complexes = division des modules et somme des arguments ==> donc Xl = V/I L 90°  ou jXl

Si la tension a une phase initiale 0, alors le courant sur l'inducteur aura une phase 0 - 90°, la phase de la reactance inductive reste toujours de 90°


==> puissance: p(t) = v(t).i(t)  ==> dans un circuit purement inductif il n'y a pas de dissipation d'énergie, la puissance est positive puis négative, l'inducteur garde l'énergie puis la retransmet dans le circuit, il n'y a pas de dissipation sous forme de chaleur. L'énergie est échangée entre générateur et inducteur.

puissance active ou réelle
P = Vrms . Irms . cos(0phi) (Phi est le déphasage entre courant et tension = phase de la réactance) 

sur un circuit inductif pur: Cos(90)=0 donc P=0 (puissance nulle)

Puissance apparente (hypothénuse entre puissance réactive et puissance réelle) = en V.A.  ==> Papp = Vrms . Irms 

Puissance réelle ou active = consommée en watts ==> Papp.cos0 (phi)  ==> celà donne la partié "réelle" de la puissance donc résistive.

Puissance réactive pure ==> Papp.sin0 (partie imaginaire pure)

Le facteur de puissance = Préelle / Papparente  = phase du vecteur d'impédance (Z = R+jXl) ==> Cos0


Si le FP diminue, le courant transporté sur les fils augmente sans que la puissance réelle n'augmente, il faut donc "sur dimensionner" les fils qui transportent un courant plus important dont une bonne partie est renvoyé au circuit.
le courant consommé augmente en fonction que le FP baisse



#Reactance Inductive

Lorsqu'on a une inductance, on peut la séparer en une résistance en série avec une inductance pure.

Comme Vz = Vl + Vr, on a bien Zl = R + jXl avec Xl = 2pif.L avec un déphasage phi de 90 degrés

pour trouver la valeur d'une tension aux bornes d'un circuit reactif:

formule du diviseur de tensions en tensions complexes = 


Vl = v(Xl / R+Xl)

Dans une résistance, le courant est toujours en phase avec la tension.

Dans une bobine, le courant est en retard de 90 degrés par rapport à la tension

##Circuits RL série:

En série on a Z = R+jXl, donc Z est un vecteur sur le diagramme phasorial composé par R = Zcos0 et Xl=Zsin0
En série, U = Ur + Ul en vectoriel donc U = rac(Ur²+Ul²) et 0 = atan Ul/Ur
pour bien s'en rendre compte dessiner le diagramme phasorial et repérer que le vecteur Z

##Circuit RL en parallèle

attention en parallèle Z est différent de R + Xl, c'est 1/Z = 1/R + 1/L... ou Z = R.X / (R+X)

on sait par contre que les tensions I = Ir+Il donc en vectoriel I = rac(Ir²+Il²) et l'angle 0=atan(Il/Ir)

 


