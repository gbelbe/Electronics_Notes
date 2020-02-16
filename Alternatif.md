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

## valeur efficace Vrms

valeur de tension continue equivalente qui dissiperait la meme puissance moyenne avec la meme resistance

Vrms = Vp/ rac2   (rac2 =1,414)     

Vrms = Vp*0,707


