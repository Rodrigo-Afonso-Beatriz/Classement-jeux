# Liste de jeux (1tm1-ephec)
# Présentation de l’équipe
- Afonso Beatriz Rodrigo
# Description du projet
Site qui permet d'ajouter les jeux que l'on souhait dans un tableau pour que l'utilisateur sache s'il a déjà fini celui-ci ou pas. L'utilisateur peut également donner une note au jeu pour qu'il sache s'il l'a apprécié ou pas.


# Aspect implémentés
 ## Frontend

Le formulaire HTML peut enregistrer de nouvelles données qui sera mis en forme via un fichier CSS.
Dans le JS, il y a plusieurs fonctionnalités. Ses fonctionnalités sont de pouvoir rechercher un jeu et en cliquant sur celui-ci, il peut accéder à une page internet pour avoir plus d'informations.
L'utilisateur peut choisir de trier par ordre croissant ou décroissant (jeu, note).

## Backend
Faire une base de données qui reprend toutes les informations (jeu, type de jeu, cote) via des tables d'adressages.
Il y a 2 webservices, un qui enregistre les données et l'autre qui récupère les données.

# détail api rest

## Webservice de Afonso Beatriz Rodrigo 
Le premier webservice se nomme "jeu" et permet via la procédure "getMontreJeu()" d'appeler la liste des jeux en JSON en faisant un select de la table "jeu".
Cette liste s'affichera sur la page HTML via JSON avec une fonction "initialisePage()".

# Diagramme ER



