<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kadir Gecesi</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: url('https://upload.wikimedia.org/wikipedia/commons/7/7b/Sultan_Ahmed_Mosque_%28Blue_Mosque%29_At_Night_%28Istanbul%2C_Turkey%29_%2826369164316%29.jpg') no-repeat center center/cover;
            text-align: center;
            color: white;
        }
        .overlay {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
        }
        .message {
            display: none;
            font-size: 24px;
            font-weight: bold;
        }
        .turkish-flag {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 100px;
            opacity: 0.8;
        }
        a {
            display: block;
            margin-top: 20px;
            font-size: 20px;
            color: yellow;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <img src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Flag_of_Turkey.svg" class="turkish-flag" alt="Drapeau de la Turquie">
    <div class="overlay">
        <a href="#" onclick="afficherMessage()">Cliquez ici pour voir le message</a>
        <p class="message" id="message">Kadir geceniz mübarek olsun, Şişman ailesi. Allah dualarınızı kabul etsin.</p>
    </div>

    <script>
        function afficherMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
