# Présentation de l'Application de Gestion de Livres

L'application de gestion de livres est une plateforme moderne conçue pour offrir une expérience fluide aux utilisateurs souhaitant explorer, gérer et interagir avec une vaste bibliothèque numérique. Elle repose sur une architecture robuste et modulaire :

- **Back-end** : Développé avec .NET Core, garantissant des performances élevées, une sécurité renforcée, et une extensibilité facile pour intégrer de nouvelles fonctionnalités.
- **Front-end** : Créé avec Angular, fournissant une interface utilisateur réactive et dynamique, adaptée à tous les types de dispositifs.
- **Base de données** : SQL Server est utilisé pour stocker et organiser efficacement les données des utilisateurs, des books, des transactions et des interactions.

## Fonctionnalités principales

- **Authentification** : Les utilisateurs peuvent s'inscrire ou se connecter pour accéder à l'application.
- **Page d'accueil** : Après connexion, les utilisateurs sont redirigés vers une page d'accueil affichant la liste des books disponibles.
- **Détails du book** : Chaque book dispose d'une page dédiée avec des informations détaillées comme :
  - Une évaluation étoilée (note sur 5 étoiles).
  - Le nombre de téléchargements, de vues, et de pages.
  - La langue du book.
  - Une conclusion ou un résumé du contenu.
- **Téléchargement** : Les utilisateurs peuvent télécharger le book directement depuis sa page.
- **Lecture intégrée** :
  - Les utilisateurs peuvent lire un book directement dans l'application sans le télécharger.
  - **Condition** : Cette fonctionnalité est accessible uniquement aux adhérents ayant acheté au moins 5 books.
- **Favoris** : Possibilité d’ajouter un book à une liste de favoris pour un accès rapide.
- **Panneau d'achat** : Les utilisateurs peuvent ajouter des books à leur panier pour achat ultérieur.
- **Commentaires** :
  - Les utilisateurs peuvent commenter les books.
  - Discussions possibles entre utilisateurs dans les sections de commentaires.
  - Possibilité de modifier ou supprimer son propre commentaire.
- **Module "Join Us"** : Les utilisateurs peuvent postuler pour devenir contributeurs et publier leurs propres books sur la plateforme.
- **Gestion de compte** : Une page paramètres permet aux utilisateurs de modifier leurs informations personnelles (nom, email, mot de passe, etc.).

## Illustrations de l'Application

### Page d'introduction
<img src="Captures/intro.PNG" alt="Intro Image" width="600">

### Authentification
Les utilisateurs peuvent s'inscrire ou se connecter pour accéder à l'application.

#### Page de connexion
<img src="Captures/login.PNG" alt="Login Page" width="600">

#### Page d'inscription
<img src="Captures/Registration.PNG" alt="Registration Page" width="600">

### Gestion du compte
Une page paramètres permet aux utilisateurs de modifier leurs informations personnelles (nom, email, mot de passe, etc.).

<img src="Captures/settings.PNG" alt="Settings Page" width="600">

### Page d'accueil
Après connexion, les utilisateurs sont redirigés vers une page d'accueil affichant la liste des books disponibles.

<img src="Captures/home page.PNG" alt="Home Page" width="600">

### Choix d'un book
Les utilisateurs peuvent sélectionner un book pour afficher ses détails.

<img src="Captures/choose book.png" alt="Choose Book Page" width="600">

### Détails du book
Chaque book dispose d'une page dédiée avec des informations comme :
- Une évaluation étoilée (note sur 5 étoiles).
- Le nombre de téléchargements, de vues, et de pages.
- La langue du book.
- Une conclusion ou un résumé du contenu.

<img src="Captures/detail book.PNG" alt="Book Details Page" width="600">

### Lecture intégrée
Les utilisateurs peuvent lire un book directement dans l'application sans le télécharger (pour les adhérents ayant acheté au moins 5 books).

<img src="Captures/Read book.png" alt="Read Book Page" width="600">

#### Afficher le livre PDF
<img src="Captures/Read book show pdf.PNG" alt="Read Book PDF Page" width="600">

### Commentaires sur un livre
Les utilisateurs peuvent commenter les books et échanger leurs opinions dans des discussions.

<img src="Captures/Comment book.PNG" alt="Comment Book Page" width="600">
