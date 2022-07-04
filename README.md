# Gestion-projet


Sujet B2 Gestion de projet
Planification et ordonnancement des tâches avec utilisation des outils utilisés dans les ateliers
Contexte

Notre entreprise conçoit et fabrique une nouvelle collection de chaussures de sport haut de gamme. Elle souhaite un magasin en ligne, administrable, de sa nouvelle collection pour permettre aux clients de commander et de se faire livrer.

Votre rôle est de planifier ce projet et de coordonner le travail des développeurs. L’équipe qui vous accompagne est composée seulement d’un dev backend et un dev frontend.

Cahier des charges du projet
 Application web accessible uniquement sur authentification.
Deux rôles d'utilisateurs :
Clients. Il peuvent :
Parcourir la collection de chaussures.
Commander des produits.
Voir l'historique de leurs commandes.
Voir leur profil.
Administrateurs. En plus des droits des clients, il peuvent administrer toutes les entités :
Gestion CRUD des clients.
Gestion CRUD des produits.

Product Backlog
Voici toutes les actions nécessaires à la réalisation de notre projet :

backend - Initialisation de la BDD (8h)
backend - Initialisation du code du projet (3h)
frontend - Initialisation du code du projet (3h)
backend - routes API à produire :
Pour les clients
Verbe HTTP
Route HTTP
Action
Temps de réalisation
POST
/api/signin
Inscription sur l’app
12h
POST
/api/login
Connexion
8h
GET
/api/logout
Déconnexion
1h
GET
/api/products
Retourne liste des produits
8h
GET
/api/products/:id
Retourne un produit
3h
GET
/api/cart
Retourne le panier
3h
PUT
/api/cart
Ajoute un produit au panier
5h
PATCH
/api/cart
Modifie un produit du panier
5h
POST
/api/cart/checkout
Valide le panier
5h
GET
/api/orders
Retourne la liste des commandes
3h
GET
/api/orders/:id
Retourne une commande
5h
GET
/api/user/:id
Retourne le profil d’un utilisateur
3h
PATCH
/api/user/:id
Modifie mon profil utilisateur
5h
DELETE
/api/user/:id
Supprime mon compte utilisateur
5h


Pour les admins
Verbe HTTP
Route HTTP
Action
Temps de réalisation
POST
/api/products
Ajoute un produit
5h
PATCH
/api/products
Modifie un produit
5h
DELETE
/api/products
Supprime un produit
3h



frontend - Pages de l’application :

Route
Description
Temps de réalisation
/login
Authentification
8h
/
Barre de menu (+ logout)
5h
/
Accueil - liste tous les produits
5h
/error
Page 404
1h
/products/:id
Affiche une fiche produit
5h
/cart
Affiche le panier + gestion des articles
12h
/orders
Affiche la liste des commandes
3h
/orders/:id
Affiche le contenu d’une commande
3h
/profile
Affiche mon profil utilisateur
5h
/crud/users
Page de gestion CRUD des users
20h
/crud/products
Page de gestion CRUD des users
20h



Bonus des bonnes pratiques
Ajout de tests sur les routes api (nécessite 3h par route)
Ajout de tests end-to-end (nécessite 5h par page)


Livrables attendus :
Une planification des tâches pour la réalisation du projet
Un dépôt git avec chaque tâche représentée par un commit
Initialiser un dépôt git sur Github
Un membre de votre équipe sera le dev backend, un autre le dev frontend. Chaque dev devra pusher les commits relatifs à son rôle dans l’ordre de votre planification. En lisant le dépôt, l’ordre des commit représente le travail effectué par les dev dans l’ordre où vous l’avez planifié.
Un speach de 8 min devant un jury qui explique votre démarche et présente votre projet.
Chaque membre de l’équipe devra parler un minimum
Vous serez évalué sur :
Savoir-être : implication et travail d'équipe
Savoir-faire :
respect du cahier des charges
aboutissement du projet présenté.
Bon ordonnancement
Bonne utilisation de git
Pitch : expression orale , distribution de la parole dans le groupe, respect du timing, pertinence du pitch pour la présentation du projet et sa compréhension.
Explication des éventuels problèmes, fonctionnalités manquantes, améliorations souhaitées.

