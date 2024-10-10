<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gift for M'y Princess</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-image: linear-gradient(to bottom right, #ffcccb, #add8e6);
            color: black;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            animation: fadeIn 1.5s;
            overflow: hidden;
        }

        h1 {
            font-size: 4em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            margin-bottom: 20px;
        }

        .button {
            background-color: #ff69b4; 
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
            background-color: #ff1493; 
        }

        .message {
            display: none; 
            margin-top: 50px;
            font-size: 1.5em;
            max-width: 90%; /* Ajusté pour mobile */
            margin: 0 auto;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8); 
            border-radius: 15px;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Style pour les cœurs flottants */
        .heart {
            position: absolute;
            top: 100%;
            animation: float 6s infinite;
            font-size: 24px;
            color: red;
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-30px); }
            100% { transform: translateY(0); }
        }

        /* Styles pour le cadre de la photo */
        .photo-frame {
            margin-top: 20px;
            border: 5px solid #ff69b4; /* Couleur de la bordure */
            border-radius: 15px;
            overflow: hidden;
            width: 250px; /* Ajustez la largeur de l'image ici */
            height: 250px; /* Ajustez la hauteur de l'image ici */
        }

        .photo-frame img {
            width: 100%; /* L'image prend toute la largeur du cadre */
            height: 100%; /* L'image prend toute la hauteur du cadre */
            object-fit: cover; /* Garde le ratio d'aspect de l'image */
        }
    </style>
</head>
<body>
    <h1>FOREVER</h1>
    <button class="button" onclick="scrollToMessage()">Clique ici 🫶</button>
    
    <div id="message" class="message">
        <h2>À ma Prettty princess ❤️</h2>
        <p>
            Merci d'être à mes côtés et de rendre chaque jour spécial. 
            Ça va faire presque 1 an et deux mois que nous partageons cette belle aventure. 
            Et je ne peux qu'être vraiment heureux. Je sais que ces derniers temps ça 
            n'a pas été facile pour nous deux, mais je sais que tu es forte et qu'ensemble
            nous pouvons tout faire. Je crois en notre amour et vraiment je ne peux que 
            me réjouir de t'avoir dans ma vie. Je ne veux pas te perdre, tu es celle qu'il
            me faut et je te veux, toi et aucune autre. C'est compris ? Je t'aime plus que 
            tout, tu es l'amour de ma vie et bien plus !
            You are my CUTIE ❤️
        </p>
    </div>

    <!-- Cadre pour ajouter une photo -->
    <div class="photo-frame">
        <img src="https://imgur.com/d84gKtU" alt="Photo de nous">
    </div>

    <!-- Cœurs flottants -->
    <div class="heart" style="left: 10%;">❤️</div>
    <div class="heart" style="left: 20%;">❤️</div>
    <div class="heart" style="left: 30%;">❤️</div>
    <div class="heart" style="left: 40%;">❤️</div>
    <div class="heart" style="left: 50%;">❤️</div>
    <div class="heart" style="left: 60%;">❤️</div>
    <div class="heart" style="left: 70%;">❤️</div>
    <div class="heart" style="left: 80%;">❤️</div>
    <div class="heart" style="left: 90%;">❤️</div>

    <script>
        function scrollToMessage() {
            // Montre le message, défile vers le bas et cache le bouton
            document.getElementById("message").style.display = "block"; // Affiche le message
            document.querySelector('.button').style.display = 'none'; // Cache le bouton
            document.getElementById("message").scrollIntoView({ behavior: 'smooth' }); // Défile vers le message
        }
    </script>
</body>
</html>

