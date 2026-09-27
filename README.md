<!DOCTYPE html>
<html>
<head>
    <title>Happy Birthday Abahani</title>

    <style>
        body {
            text-align: center;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: Arial, sans-serif;
            padding-top: 80px;
        }

        h1 {
            color: #ff1493;
            font-size: 50px;
        }

        h2 {
            color: #800080;
            font-size: 35px;
        }

        p {
            font-size: 22px;
            color: #333;
        }

        button {
            padding: 15px 30px;
            font-size: 20px;
            background: #ff1493;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
        }

        #wish {
            display: none;
            margin-top: 30px;
            font-size: 25px;
            color: #c71585;
        }
    </style>
</head>

<body>

    <h1>🎂 Happy Birthday 🎂</h1>

    <h2>💖 Abahani 💖</h2>

    <p>Wishing you a very Happy Birthday!</p>

    <button onclick="showWish()">Click Here 🎁</button>

    <div id="wish">
        🎉 Happy Birthday Abahani! 🎉<br><br>
        May your day be filled with happiness,
        smiles and beautiful memories! 💕🎂✨
    </div>

    <script>
        function showWish() {
            document.getElementById("wish").style.display = "block";
        }
    </script>

</body>
</html