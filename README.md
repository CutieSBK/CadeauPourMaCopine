# CadeauPourMaCopine
Un petit site créé comme cadeau spécial pour ma copine ❤️
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forever</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-image: url('https://source.unsplash.com/1920x1080/?nature,love');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            overflow: hidden;
        }

        h1 {
            font-size: 4em;
            margin-top: 100px;
            animation: fadeIn 2s;
        }

        p {
            font-size: 1.5em;
            margin: 20px 40px;
            animation: fadeIn 2s;
            opacity: 0;
            animation-delay: 2s;
            animation-fill-mode: forwards;
            transition: opacity 0.5s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .flower {
            position: absolute;
            width: 150px;
            animation: float 5s infinite;
            z-index: -1;
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0); }
        }

        .flower1 {
            top: 30%;
            left: 10%;
            animation-delay: 0s;
        }

        .flower2 {
            top: 60%;
            right: 10%;
            animation-delay: 1s;
        }

        .flower3 {
            top: 20%;
            left: 50%;
            animation-delay: 2s;
        }

        .flower4 {
            top: 70%;
            right: 50%;
            animation-delay: 3s;
        }

        .flower5 {
            top: 50%;
            left: 30%;
            animation-delay: 4s;
        }
    </style>
</head>
<body>
    <h1>FOREVER</h1>
    <p>Mon amour, chaque jour à tes côtés est un cadeau précieux. 
       Je t'aime d'une manière qui transcende les mots, 
       et je souhaite que chaque instant passé avec toi soit éternel. 
       Ta beauté, ta gentillesse et ton rire illuminent ma vie comme 
       mille étoiles dans le ciel. Je suis si reconnaissant de t'avoir 
       dans ma vie et je promets de toujours chérir notre amour. 
       Ensemble, pour toujours.</p>

    <img class="flower flower1" src="https://source.unsplash.com/150x150/?flower" alt="Flower">
    <img class="flower flower2" src="https://source.unsplash.com/150x150/?flower" alt="Flower">
    <img class="flower flower3" src="https://source.unsplash.com/150x150/?flower" alt="Flower">
    <img class="flower flower4" src="https://source.unsplash.com/150x150/?flower" alt="Flower">
    <img class="flower flower5" src="https://source.unsplash.com/150x150/?flower" alt="Flower">
</body>
</html>
