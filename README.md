
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6f2;
            color: #d63384;
            padding: 50px;
        }
        #heart {
            font-size: 100px;
            cursor: pointer;
            color: #ff1493;
            transition: transform 0.2s;
        }
        #heart:hover {
            transform: scale(1.1);
        }
        #message {
            font-size: 24px;
            margin-top: 20px;
            display: none;
        }
    </style>
</head>
<body>
    <h1>Thème  Love</h1>
    <p>Clique sur le cœur !</p>
    <div id="heart">❤️</div>
    <div id="message">I love you !</div>

   <script>
        document.getElementById('heart').addEventListener('click', function() {
            document.getElementById('message').style.display = 'block';
        });
    </script>
</body>
</html>
