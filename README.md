# le push qui tue

un petit TP pour expérimenter cette histoire de *push qui tue*, i.e. quand on n'arrive pas à pousser

## mise en place

* chacun doit avoir un identifiant github
* se mettre en équipes de 2 - ou 3 si nombre impair

## déroulement

### phase 1

* l'élève `A` crée un repo privé sur github
   * avec disons simplement un `README.md`
* il donne le droit d'accéder au reste de l'équipe

### phase 2

l'élève `A` est actif, l'élève `B` est passif:

* l'élève `A` publie une nouvelle version sur github
* l'élève `B` la récupère
* et on recommence...

que constatez-vous ? rencontrez-vous des difficultés particulières ?

### phase 3

chacun son tour: l'élève `B` devient actif, et `A` devient passif

* normalement à ce point les 3 repos sont synchrones (`A` et `B` et github)
* l'élève `B` publie une nouvelle version sur github
* l'élève `A` la récupère
* et on recommence...

mêmes questions

### phase 4

les deux ensemble

* normalement à ce stade les 3 repos sont synchrones
* `A` fait un changement dans un commit sur son ordi
* `B` fait un changement dans un commit sur son ordi  
  (arrangez-vous pour que les deux changements soint fusionnables !,  
  c'est-à-dire touchent des endroits distincts du fichier)
* `A` pousse sa modification
* `B` pousse sa modification

mêmes questions

arrangez-vous pour faire la fusion et vous retrouver 
dans l'état nominal où les 3 repos sont synchrones
