
# Cahier des charges - Refonte de l'application de livraison

## Mission

Refonte de notre application pour notre service de livraison.

## Contexte

LiVrai est une société de 150 employés. Nous proposons un service de livraison de marchandises en grande quantité pour les professionnels.

Afin de gérer nos clients et les livraisons, nous utilisons une application qui a été développée il y a plusieurs années.

Actuellement, chaque client passe par le service commercial pour établir un contrat de collaboration. C’est le service commercial qui crée un nouveau compte sur l’application, que le client pourra ensuite utiliser pour réserver des livraisons.

Suite à la forte croissance de notre activité, nous souhaitons désormais que nos clients puissent être autonomes pour utiliser le service de livraison. Seuls certains clients continueront à être gérés par le service commercial.

C’est pourquoi nous souhaitons refaire entièrement l’application.

## Exigences fonctionnelles

L'application devra comporter au minimum les fonctionnalités suivantes :

- Création de compte par les clients ou par notre service commercial ;
- Gestion des informations du client ;
- Commande et suivi des livraisons ;
- Gestion de la facturation ;
- Historique des livraisons.

## Types d'utilisateurs

L’application devra permettre l’accès à trois types d’utilisateurs :

- **Les clients** ;
- **Le service commercial**, qui doit pouvoir gérer certains clients et avoir accès à la facturation ;
- **Le service Livraisons**, qui doit pouvoir gérer les livraisons et avoir accès à la facturation.

## Exigences techniques

L'application devra respecter les exigences suivantes du service informatique :

- Le frontend devra être une SPA (Single-Page Application) développée en **Angular**, pour une application très interactive ;
- Le backend devra être développé en **Java**, en utilisant la **dernière version LTS** (Long-Term Support) ;
- Le déploiement en production se fera dans un environnement **Docker**, assuré par le service informatique. Le choix de l’hébergeur n’est pas encore défini.

## Points de vigilance

Nous portons une attention particulière à la **qualité** et à la **maintenabilité** de nos outils informatiques.

Nous demandons à nos prestataires de rédiger un **cahier des charges précis** décrivant les aspects fonctionnels et techniques de la future application, que nous validerons **avant le début du développement**.
