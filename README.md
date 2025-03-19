<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>víctor</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap');

        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            color: black;
            text-align: center;
            padding: 30px;
        }

        h1 {
            font-size: 32px;
            font-weight: bold;
            text-transform: lowercase;
            margin-bottom: 10px;
        }

        p {
            font-size: 18px;
            font-style: italic;
            margin: 5px 0;
        }

        .shwrico {
            font-family: 'Great Vibes', cursive;
            font-size: 12px; /* Reduzido para ficar bem pequeno */
            margin-top: -5px;
        }

        button {
            margin-top: 15px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: black;
            color: white;
            border: none;
            border-radius: 20px;
            cursor: pointer;
        }

        button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>

    <h1>víctor</h1>
    <p>di$ciplina & $ucesso ./∞</p>
    <p class="shwrico">- 𝑠ℎ𝑤𝑟𝑖𝑐𝑜</p>

    <button onclick="copyLink()">Link copiado</button>

    <script>
        function copyLink() {
            navigator.clipboard.writeText(window.location.href);
            alert("Link copiado!");
        }
    </script>

</body>
</html>
