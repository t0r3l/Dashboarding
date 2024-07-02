# Dasboarding (En cours)
Quelle méthodologie aborder pour réaliser une analyse exploratoire dans le cadre de la conception d'un tableau de bord pour sythétiser des données?

C'est à cette problématique que tend à répondre ce projet à travers la lecture du livre "visual analytics for data scientists" du fichier "Sources"

"Analyse_exp_BSPP.Rmd" Est le fichier Rmarkdown expliquant la démarche de mon analyse exploratoire sur le jeu de données BSPP.csv (un jeu de données de la brigade des sapeurs pompiers de Paris). Il est en cours de progression.

Le fichier "BSPP.csv" contient les variables suivantes:

Intervention : un id d’intervention (non unique)
Id_engagement : un id correspondant à une sortie d’engin (unique)
Victime : 1 si l’engin a traité au moins une victime lors de son engagement, 0 sinon
Commune : la commune où a eu lieu l’intervention
Categorie : le type d’intervention
Id_engin : le n° de l’engin engagé
duree_engin_sur_intervention : le temps passé par l’engin sur l’intervention lors de son engagement
heure : l’heure d’engagement de l’engin
jour : le jour de la semaine

Le fichier "BSPP2.csv" est le fichier BSPP.csv après une première proposition de nettoyage des données.

Le fichier maping contient les coordonnées geojson des départements d'Île de France entre autres, dans un but de création de cartes interractives pour la visualisation des données.


