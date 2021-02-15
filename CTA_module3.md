# amp classe A

==> classe A: toujours polarisé (resistace moyenne) + amplifie les 2 semi-cycles 


la resistance equivalente du transistor NPN doit être entre 1 et 1,5x celle de la resistance de collecteur. (la R Emisseur peut etre bcp plus faible).
On calcule la tension entre les 2 R et le transistor pour calculer la valeur des R de base.

On part de la tension de la R de Emissor + 0,6v pour avoir la tension de la base = entre le diviseur de tension de polarisation.
cela permet de choisir les 2 R de polarisation pour avoir cette tension.

avant l'entree du signal on met un capa d'acouplement qui maintient une tension fixe entre ses bornes comme si c'etait une batterie

quand la tension de base augmente la tension de collecteur est amplifiée et inversée

Le gain en tension de l'ampli classe A correspond au ratio de resistance Rcollecteur / R Emisseur


Configuration d'amplis:  collecteur commun: le collecteur se retrouve à la fois utilisé pour le signal d'entrée que de sortie.
On regarde par ou entre le signal et par ou il ressort, la patte restante est la patte "commune"


# Ampli Emissor commun: inversion de phase, amp tension et courant, mais basse freq
in-> base, out-> collecteur 
impedence d'entrée moyenne, sortie haute
avantage amp tension et courant en même temps, mais inversion de phase et donc impact capacité base collecteur en haute frequence qui fait court circuit et annule l'amplification

# Ampli Collecteur commun: Ampli Buffer: meme tension en entrée et en sortie mais capable de fournir un plus grand courant (phases egales)
In: base,  Out: emisseur
impedence d'entrée moyenne ou haute, sortie basse
collecteur relié directement à l'alimentation sans résistance, resistance uniquement à l'émisseur (et pour polariser la base)


# Ampli base commune, NPN: signal entre par l'emisseur et sort par le collecteur: utilisé en haute frequences

Lorsque l'une des jonctions du transistor est inversement polarisée il se forme une capacité de qqs picos aux bornes de cette jonction
ce condensateur est présent entre la base et l'émisseur et entre la base et le collecteur. Quand la fréquence augmente au dessus de l'audio, 
cette capacité rend le condensateur non opérationnel: capa parasite col-base

le signal entre par l'émisseur qui est toujours polarisé donc sans capacité, quand elle diminue, elle réduit la polarisation du transistor, ce qui s'observe à la tension au collecteur. Malgré la capacité qui existe tjrs entre base et collecteur, elle est maintenant utile car elle correspond à un condo de désacouplement.

le signal qui entre par l'émisseur fait varier la base et le collecteur dans le même sens donc il n'y a pas d'effet d'annulation avec la capacité collecteur base.

pas de gain de courant
imp entrée basse, sortie haute


## entrée audio: correcteur de niveaux pour micro a bobines:

les micros a bobines ont une baisse de niveau pour les frequences les plus hautes, donc on met un pont de resistances avec un condo en parallèle. le diviseurqui réduit le niveau à 70% quand la frequence est basse et laisse passer tout lorsque la freq est elevee.

## condensateur 47pf entre base et collecteur en préamp audio classe A:

objectif est de filtrer les freq supérieures à 20khz pour réduire le bruit

## condensateur entre émisseur et terre en parallèle de la résistance d'émisseur.

aide à amplifire l'amplification classe A, lorsque le 
