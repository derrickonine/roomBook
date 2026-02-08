RoomBook – Système de réservation des salles de réunion

1. Présentation du projet

RoomBook est une application web développée en Jakarta EE permettant la gestion des réservations
des salles de réunion et des équipements associés au sein d’une agence. 

L’objectif du projet est d’automatiser la réservation des salles, d’améliorer l’organisation
des réunions et de faciliter la gestion des ressources (salles et équipements).



2. Fonctionnalités principales

L’application est composée des modules suivants :

Front Office :
- Réservation des salles de réunion
- Recherche des réservations par salle ou par plage horaire
- Impression du calendrier des réservations

Back Office (Administration) :
- Gestion des salles de réunion
- Gestion des équipements
- Gestion des droits d’accès (Utilisateur / Administrateur)



3. Architecture et technologies

- Architecture MVC (Model – View – Controller)
- Backend : Jakarta EE (Servlets, JPA, Transactions)
- Frontend : JSP, HTML, CSS
- Serveur applicatif : WildFly
- Base de données : PostgreSQL
- Outils : IntelliJ IDEA, Git, GitHub


4. Base de données

La persistance des données est assurée par PostgreSQL.
Grâce à l’utilisation de JPA, l’application est indépendante du moteur de base de données,
ce qui permet un changement de SGBD sans modification majeure du code.


5. Démonstration vidéo

Une vidéo de démonstration présentant :
- le diagramme de cas d’utilisation
- le diagramme de classes
- la démonstration de l’application

est disponible via le lien suivant :

https://drive.google.com/file/d/1T_kB4ypzMwyqfoXMxzyvNaX3TSZ0GOHP/view?usp=sharing


6. Déploiement

L’application est packagée sous forme de fichier WAR et déployée sur un serveur WildFly.
Elle est accessible via un navigateur web.



7. Auteur

Nom Prénom
