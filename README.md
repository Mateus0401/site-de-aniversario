<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Aniversário!</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f9f9f9;
            margin: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1.happy-birthday {
            color: #ff6363;
        }
        .message {
            font-size: 1.2em;
            color: #333;
        }
        .custom-text {
            font-size: 1.2em;
            color: #555;
            margin: 20px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f7f7f7;
        }
        .button {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background: #ff6363;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1em;
        }
        .button:hover {
            background: #e55252;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="happy-birthday">Feliz Aniversário!</h1>
        <p class="message">"Feliz aniversário para o amor da minha vida e minha melhor amiga!
            É incrível como você consegue ser tudo para mim ao mesmo tempo: a pessoa que amo, a amiga com quem compartilho segredos e a parceira com quem quero construir um futuro.
            
            Você não é apenas minha namorada; você é minha confidente, minha parceira, meu sorriso nos dias difíceis e o motivo da minha felicidade todos os dias.
            
            Desejo que este novo ano traga para você tudo o que há de melhor no mundo, porque você merece cada pedacinho de alegria, amor e conquistas. Saiba que estou aqui, ao seu lado, para comemorar, apoiar e te amar em cada passo do caminho.
            
            Te amo mais do que palavras podem expressar. Que hoje seja tão especial quanto você é para mim!</p>
        
       
        </div>

        <!-- Botões -->
        <button onclick="playSound()">Clique para ouvir!</button>
        <a href="outra-pagina.html" class="button">Ir para outra página</a>
    </div>

    <audio id="birthday-sound" src="https://www.soundjay.com/button/beep-07.wav"></audio>

    <script>
        function playSound() {
            var sound = document.getElementById("birthday-sound");
            sound.play();
        }
    </script>
</body>
</html>


