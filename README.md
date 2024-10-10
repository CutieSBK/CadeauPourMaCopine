# CadeauPourMaCopine
Un petit site créé comme cadeau spécial pour ma copine ❤️
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadeau pour ma copine</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-image: url('https://images.unsplash.com/photo-1544069992-3c0a5b493db5'); /* Fond floral */
            background-size: cover;
            background-repeat: no-repeat;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            height: 100vh;
            animation: fadeIn 1.5s;
        }

        h1 {
            font-size: 4em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            margin-bottom: 20px;
            animation: slideIn 1s ease forwards;
            opacity: 0;
        }

        p {
            font-size: 1.5em;
            max-width: 600px;
            margin: 0 auto;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
            opacity: 0;
            animation: fadeInText 1.5s ease forwards 0.5s; /* Légère animation */
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateY(-50px); }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes fadeInText {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .heart {
            font-size: 5em;
            color: #ff4d4d;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
    </style>
</head>
<body>
    <h1>FOREVER</h1>
    <div class="heart">❤️</div>
    <p>
        Mon amour, chaque jour passé à tes côtés est un cadeau précieux. Tu es la lumière de ma vie et je chéris chaque moment que nous partageons. Je t'aime plus que les mots ne peuvent l'exprimer.
    </p>
</body>
</html>
