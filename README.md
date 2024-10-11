<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadeau pour Ma Princess Teorahau</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif; 
            background-image: linear-gradient(to bottom right, #ffcccb, #add8e6);
            color: black;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            height: 100%;
            animation: fadeIn 1.5s;
            overflow-x: hidden;
            padding-bottom: 50px;
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
            max-width: 600px;
            margin: 0 auto;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
        }

        .photo-frame {
            position: relative;
            width: 300px;
            height: 300px;
            border: 10px solid white;
            border-radius: 15px;
            margin-top: 20px;
            overflow: hidden;
            margin-bottom: 20px;
        }

        .photo-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .heart {
            position: absolute;
            width: 30px;
            height: 30px;
            background-color: lightblue;
            clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
            animation: float 4s infinite;
        }

        @keyframes float {
            0% {
                transform: translateY(0) scale(1);
            }
            50% {
                transform: translateY(-20px) scale(1.1);
            }
            100% {
                transform: translateY(0) scale(1);
            }
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
           Et je ne peux qu'être heureux. Je sais que ces derniers temps ça n'a pas été facile pour nous deux, 
           mais je sais que tu es forte et qu'ensemble nous pouvons tout surmonter. 
           Je crois en notre amour et je ne veux pas te perdre. Tu es celle qu'il me faut et je te veux, toi et personne d'autre ! 
           Je t'aime plus que tout, tu es l'amour de ma vie, et bien plus encore !
        </p>
    </div>

    <div class="photo-frame">
        <img src="https://i.imgur.com/mNNeqQY.jpeg" alt="Photo de nous deux">
    </div>

    <!-- Cœurs flottants -->
    <script>
        function scrollToMessage() {
            document.getElementById("message").style.display = "block";
            document.getElementById("message").scrollIntoView({ behavior: 'smooth' });
            document.querySelector('.button').style.display = 'none';
        }

        // Créer des cœurs flottants aléatoires
        for (let i = 0; i < 10; i++) {
            let heart = document.createElement('div');
            heart.classList.add('heart');
            heart.style.left = Math.random() * 100 + 'vw'; // position horizontale aléatoire
            heart.style.top = Math.random() * 100 + 'vh'; // position verticale aléatoire
            heart.style.animationDuration = Math.random() * 2 + 3 + 's'; // durée d'animation aléatoire
            document.body.appendChild(heart);
        }
    </script>
</body>
</html>

