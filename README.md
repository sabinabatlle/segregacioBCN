# segregacioBCN
Visualització de la segregació urbana als barris de la ciutat de Barcelona.

## Objectiu
L'objectiu de la visualització és posar en relleu la segregació urbana als barris de Barcelona. El dataviz permet interactuar amb un seguit de característiques sociodemogràfiques per veure com es distribueixen els grups de població en la superfície urbana.

## Descripció
La visualització consta de quatre parts: la secció d'entrada de variables, el mapa, un petit quadrat informatiu sobre els barris i finalment una breu explicació del concepte de segregació urbana i de com s'han aconseguit i tractat les dades. 
L'apartat interactiu permet a l'usuari de seleccionar entre diverses opcions les variables que s'utilitzaran per renderitzar el mapa. Aquestes opcions corresponen a característiques sociodemogràfiques de la població barcelonina, que s'utilitzen com a filtre per a seleccionar les dades utilitzades per dissenyar el mapa. Aquest representa els barris de Barcelona en una gamma de quatre colors segons si és més o menys probable que una persona amb les característiques seleccionades hi visqui. El valor que representa aquesta possibilitat es calcula amb el teorema de Bayes, assumint -malgrat que no sigui exactament així- que les variables són independents. Les categories utilitzades per escollir els colors dels barris són els quartils de la distribució dels resultats d'aquest càlcul.
