# React + Vite

MyTree

Noms du binôme: DAMOUN Aya, DAHBI Mohamed Yasser

Fonctionnalités

Notre application permet aux utilisateurs de créer leur propre arbre généalogique.

Inscription et Connexion

    Inscription :
        L'utilisateur s'inscrit via la page d'inscription en ajoutant son nom, prénom, email et un mot de passe (qui sera ensuite hashé).
        Après l'inscription, l'utilisateur doit attendre la validation de son compte par un administrateur. L'administrateur peut accepter, refuser ou accorder des droits administratifs à l'utilisateur.

    Connexion :
        Une fois le compte validé, l'utilisateur peut se connecter en utilisant son email et son mot de passe.
        Après la connexion, un token valable 24 heures est généré et l'utilisateur est redirigé vers la page principale.

Création de l'Arbre Généalogique

Sur la page principale, l'utilisateur peut ajouter les membres de sa famille en suivant ces étapes :

    Ajout de l'ancêtre :
        Ajoutez d'abord l'ancêtre sans indiquer de Parent ID.
    Ajout des parents et de leur fratrie :
        Ajoutez les parents et leurs frères et sœurs en spécifiant l'ID de leur parent comme Parent ID.
    Ajout des générations suivantes :
        Ajoutez-vous, vos frères et sœurs, et les générations suivantes en suivant la même logique.

Une fois ces étapes complétées, l'utilisateur peut visualiser son arbre généalogique.
N.B: Les IDs doivent être nécessairement unique.
N.B: Back-end pas completement fonctionnel pour la version mobile.



Instructions d'Exécution:

npm install -g cordova

cordova platform add android

cordova build android

cordova run android (lier le téléphone android en mode développement au pc via un cable)

