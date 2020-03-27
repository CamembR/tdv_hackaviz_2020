# hackaviz 2020 : La célèbre équipe Brigade Camenbert

## TODO

- Viz en distinguant les jours par catégorie
- Classique
- WE
- Vendredi lundi
- Jour de semaines
- Entrées / Sorties
- Départ: Vendredi / Samedi
- Retour: Dimanche / Lundi
- Neutre: Autres jours
- Tester une vue lissée par mois
- Rassembler des départements
- Touristiques: 34, 66, 11
- Ruraux: 12, 
- Business: 31 
- Vacances
- Week-ends
- Ponts


# Le jeu de donnée et les outils

    access: https://toulouse-dataviz.fr/hackaviz-2020-telechargement-des-donnees
    nuitees : http://toulouse-dataviz.fr/hackaviz_2020/nuitees.xlsx
    par_origine : http://toulouse-dataviz.fr/hackaviz_2020/par_origines.xlsx
    capacites:  http://toulouse-dataviz.fr/hackaviz_2020/capacites.xlsx
geojson - http://toulouse-dataviz.fr/hackaviz_2020/capacites.zip
    complements : http://toulouse-dataviz.fr/hackaviz_2020/complements.xlsx
    le github:  https://github.com/CamembR/tdv_hackaviz_2020
    le pipeline devops en CI-CD (nan, je déconne)
    
# L'exploratoire

Github pages : https://camembr.github.io/tdv_hackaviz_2020/

# L'histoire à raconter

Nos departements ont chacun des typicités d'accueil de leurs touristes. On peut les distinguer quantitativement bien sûr, avec les départements du littoral subissant de fortes migration estivales <01-viz RidgeLines>, ou bien vis à vis du taux de remplissage relatif à leur capacité d'hébergement <01-Viz Ridgeline Pin Parasol>. Mais le plus intéressant est surtout de les distinguer par la typologie des migrations, et notemment par les jours d'arrivée et de départ des voyageurs. Le premier constat qui se dégage deja des deux premiers graphes, est que la Haute-Garonne provoque un comportement à part : Ce distinguo s'affine lorsqu'on separe la composante stucturelle (évolution lissée) de la composante hebdomadaire des nuitées. <02-Viz scatterplot avec annotation>
Nous voilà donc avec 3 regroupements thématiques : 
- Touristiques: 34, 66, 11
- Ruraux: 12, 
- Business: 31 



# Les beaux morceaux de viz à insérer

mettre les viz sur une carte : style  geo_facet : 

# Les idées en vrac

"On nous aurait menti : il y a des travailleurs cachés dans les voyageurs de ce dataset". Ils ne consomment pas (que) les hebergements dans la liste! pourquoi ?
- ce sont en fait des travailleurs
- ils vont dans leur maison de campagne
- ils font du Airb&B
- ils font du camping sauvage...
- ils font l'aller-retour dans la journée... 
- ils ont un peu resquillé sur les impots...

"Les 4 piliers du tourisme en Occ. : la plage, le ski, les festivals, la gastronomie, le tourisme vert, ..."
on peut faire des modèles pour extraire l'influence de la saisonnalité, ou un truc plus simple pour sortir les principaux...
on sort du piège de la carte des départements que personne ne connait... Mais c'est le parcours fléché par le dataset, donc on aura de la concurence...

"Comment sortir les 3 departements x,y,z de leur marasme touristique"
L'influence de la météo, les vacances scolaires,

"Comment étaler les vacanciers en dehors  de juillet-aout pour un tourisme plus durable
- les places libres
- les correlations (meme temperatures, les conges)
- les surcapacités et les moens de les 

"D'ou viennent-ils ?"
pour chaque département, on regroupe toutes les origines des voyageurs dans 5 categories, et on fait une carte de flux

"Mais ils sont aussi parti des departements d'ici"
il ne faut pas oublier de retrancher les départs des départements d'occitanie avec metropoles, 

# Les histoires à ne pas raconter


# Les beaux morceaux de viz à ne pas insérer (et les moches)

mettre les viz sur une carte : style  geo_facet : 
