# Scripts-utiles
## Git contenant un ensembles de scipts utiles

---
courbe-lattence  :
utilisation: courbe-lattence {URL} [nombre de mesures]

URL: obligatoire

nombre de mesures: non obligatoire: nombre de fois que la mesure sera effectuée

Donne un graphique effectué avec GNUPLOT

Necessite:

gnuplot
pareil2
est-nombre-entier
est-vide

Le fichier dans lequel la courbe de lattence est enregistrée est /tmp/courbe

----

montrer-for  et montrer-while

ecrit le nom de la commande
le nombre d'arguments
et liste les arguments passés en paramètre.
 
----

lister-repertoires {RepertoireDeDepart}

Necessite comme paramètre le repertoire de depart depuis lequel on liste les autres repertoire.

----

mkdire {repertoire}

crée un repertoire avec mkdir et y accède directement avec cd

----

lignesDeCode {Types de fichier}

Récupère ne nombre de lignes dans les fichiers dont le type est spécifié en paramètre.

Exemple: ligneDeCode c h
Donne le nombre de ligne dans les fichiers *.c et *.h du repertoire courant et le total.
