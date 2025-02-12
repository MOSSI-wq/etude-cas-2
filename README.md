SIDIALI MOSLIM
BENJELOUN HIBA
Classe:5IIR7

Cette version du microservice permet de gérer les opérations CRUD sur l'entité "COMMANDE" avec une version mise à jour de la table "COMMANDE" :

La table "COMMANDE" (version 2) contient les colonnes suivantes : id, description, quantité, date, montant, id_produit.
Les microservices microservice-commandes et microservice-produit sont enregistrés auprès d’Eureka.
Une API Gateway est mise en place comme point d'accès unique à l'application.
Les fonctionnalités CRUD sont entièrement implémentées pour le microservice-commandes.
Un mécanisme de gestion de timeout est simulé entre les microservices, permettant de contourner les erreurs sans utiliser Hystrix.
