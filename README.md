<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadeau pour my pretty Princess Teorahau</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-image: linear-gradient(to bottom right, #ffcccb, #add8e6); /* Dégradé de couleurs */
            color: black;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            height: 100vh;
            animation: fadeIn 1.5s;
            overflow: hidden; /* Pour éviter le défilement jusqu'à ce que ce soit nécessaire */
        }

        h1 {
            font-size: 4em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            margin-bottom: 20px;
        }

        .button {
            background-color: #ff69b4; /* Rose vif */
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.5em;
            border-radius: 25px;
            cursor: pointer;
            margin-top: 20px;
            transition: background-color 0.3s ease;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }

        .button:hover {
            background-color: #ff1493; /* Rose foncé au survol */
        }

        .message {
            display: none; /* Masqué par défaut */
            margin-top: 50px;
            font-size: 1.5em;
            max-width: 600px;
            margin: 0 auto;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8); /* Fond blanc semi-transparent */
            border-radius: 15px;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>FOREVER</h1>
    <button class="button" onclick="scrollToMessage()">Clique ici Babe 😌</button>
    
    <div id="message" class="message">
        <h2>À ma Prettty princess ❤️</h2>
        <p>
            Merci d'être à mes côtés et de rendre chaque jour spécial. 
            sa vas faire presque 1 ans et deux mois que nous partageons cette belle aventure. 
            Et je ne peut qu'etre mais vraiment heureux je sais que c'est dernier temps sa 
            na pas etait facile pour nous 2 mais je sais que tu et forte et que ensemble
            nous pouvons tout faire. je crois en n'otre amour et vraiment je ne peut que 
            me rejouir de t'avoir dans ma vie, je ne veut pas te perdre tu et celle au'il
            me faut et je te veut toi et aucune autre c'est compris ! Je t'aime plus que 
            tout tu et l'amour de ma vie et bien plus !
            You'r CUTIE ❤️
        </p>
    </div>

    <script>
        function scrollToMessage() {
            // Montre le message et défile vers le bas
            document.getElementById("message").style.display = "block"; // Affiche le message
            document.getElementById("message").scrollIntoView({ behavior: 'smooth' }); // Défile vers le message
        }
    </script>
</body>
</html>
