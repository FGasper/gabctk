gabc2mid
========

Conversion de gabc en midi.

Gabc
----

Le *gabc* est le langage utilisé par le logiciel [Gregorio](http://home.gna.org/gregorio/). Vous en trouverez la description [ici](http://home.gna.org/gregorio/gabc/).

Gabc2mid
--------

Ce script parcourt le code *gabc*, en extrait ce qui concerne la mélodie, et produit celle-ci sous la forme d'un fichier midi. Il peut aussi extraire le texte dans un fichier texte. La syntaxe est la suivante :

gabc2mid.py -i \</chemin/vers/le/fichier/source.gabc\> [-o \</chemin/vers/le/fichier/destination.mid\>] [-e \</chemin/vers/le/fichier/destination.txt\>] [-t tempo]

Le deuxième argument (fichier de destination) est optionnel : en son absence, gabc2mid produira un fichier midi dans le même dossier que la source, portant le même nom.

Le troisième est aussi optionnel, mais en son absence, aucun fichier texte ne sera produit.
