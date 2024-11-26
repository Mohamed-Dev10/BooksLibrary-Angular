
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Présentation de l'Application</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2 {
            text-align: center;
            color: #4CAF50;
        }
        .introduction {
            background: #ffffff;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .image-gallery {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .image-gallery img {
            max-width: 80%;
            margin: 15px 0;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .image-caption {
            font-style: italic;
            margin-bottom: 10px;
            color: #555;
        }
    </style>
</head>
<body>

    <h1>Présentation de l'Application de Gestion de Livres</h1>

    <div class="introduction">
        <p>L'application de gestion de livres est une plateforme moderne conçue pour offrir une expérience fluide aux utilisateurs souhaitant explorer, gérer et interagir avec une vaste bibliothèque numérique. Elle repose sur une architecture robuste et modulaire :</p>
        <ul>
            <li><strong>Back-end :</strong> Développé avec .NET Core, garantissant des performances élevées, une sécurité renforcée, et une extensibilité facile pour intégrer de nouvelles fonctionnalités.</li>
            <li><strong>Front-end :</strong> Créé avec Angular, fournissant une interface utilisateur réactive et dynamique, adaptée à tous les types de dispositifs.</li>
            <li><strong>Base de données :</strong> SQL Server est utilisé pour stocker et organiser efficacement les données des utilisateurs, des livres, des transactions et des interactions.</li>
        </ul>
    </div>

    <h2>Illustrations de l'Application</h2>
    <div class="image-gallery">
        <div class="image-caption">Page d'introduction</div>
        <img src="Captures/intro.PNG" alt="Intro Image">
        
        <div class="image-caption">Page de connexion</div>
        <img src="Captures/login.PNG" alt="Login Page">

        <div class="image-caption">Page d'inscription</div>
        <img src="Captures/Registration.PNG" alt="Registration Page">

        <div class="image-caption">Paramètres du compte</div>
        <img src="Captures/settings.PNG" alt="Settings Page">

        <div class="image-caption">Page d'accueil</div>
        <img src="Captures/home page.PNG" alt="Home Page">

        <div class="image-caption">Choix d'un livre</div>
        <img src="Captures/choose book.png" alt="Choose Book Page">

        <div class="image-caption">Détails du livre</div>
        <img src="Captures/detail book.PNG" alt="Book Details Page">

        <div class="image-caption">Lire un livre</div>
        <img src="Captures/Read book.png" alt="Read Book Page">

        <div class="image-caption">Afficher le livre PDF</div>
        <img src="Captures/Read book show pdf.PNG" alt="Read Book PDF Page">

        <div class="image-caption">Commentaires sur un livre</div>
        <img src="Captures/Comment book.PNG" alt="Comment Book Page">
    </div>

</body>
</html>
