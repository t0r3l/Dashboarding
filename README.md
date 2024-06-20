# Dasboarding 
Ce projet est en cours.

Dashboarding pour test de recrutement de la brigade des sapeurs pompiers de Paris (BSPP).

Les consignes étaient les suivantes:

 .Réaliser un tableau de bord restituant une synthèse des données exploitées.
 

La question qui m'est alors venue était la suivante;
existe t-il une méthodologie pour répondre à la problématique posée?

J'ai déterminé qu'une analyse exploratoire était indispensable pour comprendre les données dans un premier avant de se lancer directement dans la réalisation d'un tableau de bord.

Seulement encore une fois qu'elle méthodologie aborder pour réaliser une analyse exploraoire?

Je détermine cette métodologie à travers la lecture du livre "visual analytics for data scientists" du fichier "Sources". Ce fichier contient aussi 1/3 du résumé de sa lecture dans le fichier "VADS_summary" même si je songe à changer prochaînement ma méthologie de façon à me servir du livre pendant mon analyse exploratoire et non en deux temps.

"Analyse_exp_BSPP.Rmd" Est le fichier Rmarkdown expliquant la démarche de mon analyse exploratoire sur le jeu de données BSPP.csv. Il est en cours de progression.

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


