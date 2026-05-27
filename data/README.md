## Données utilisées

Les données utilisées proviennent de la base nationale NAIADES dédiée au suivi de la qualité des eaux de surface en France.

Le projet repose sur plusieurs jeux de données environnementales :

### Base analyses
Contient les mesures de concentrations des résidus médicamenteux observées dans les stations de surveillance :
- concentrations mesurées ;
- molécules analysées ;
- dates de prélèvement ;
- codes stations ;
- informations analytiques.

### Base stations
Contient les informations géographiques et administratives des stations de mesure :
- stations de surveillance ;
- communes ;
- départements ;
- coordonnées géographiques.

### Documentation des données
Un dossier de documentation PDF a été utilisé afin de :
- comprendre la structure des variables ;
- interpréter les codes analytiques ;
- identifier les champs exploitables pour l’analyse.

### Construction de la base finale

Les bases analyses et stations ont été fusionnées sous Python afin de construire une base analytique consolidée regroupant :
- les concentrations des résidus médicamenteux ;
- les informations territoriales ;
- les dates de prélèvement ;
- les coordonnées des stations ;
- les variables nécessaires à l’analyse spatio-temporelle.

Après nettoyage des données :
- les analyses non exploitables ont été supprimées ;
- les données hors domaine de validité ont été exclues ;
- seules les mesures quantitatives exploitables ont été conservées.

La base finale a ensuite été exportée pour l’analyse et la visualisation sous Power BI.

## Accès aux données

Les données utilisées dans ce projet proviennent de la base nationale NAIADES dédiée au suivi de la qualité des eaux de surface.

### Jeux de données utilisés
- Base analyses des concentrations
- Base stations de surveillance
- Documentation des variables et métadonnées
- Base finale consolidée après nettoyage et fusion sous Python

Téléchargement des données :
[Accéder aux données du projet](https://drive.google.com/drive/folders/1GcUvx6RXx2SQ1tzLdt6da-_azr3hO-wn?usp=sharing)


