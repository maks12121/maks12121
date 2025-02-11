<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MTA Сервер</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #222;
            color: white;
        }
        .container {
            margin-top: 50px;
        }
        .btn {
            background-color: #ff4500;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            border-radius: 5px;
        }
        .btn:hover {
            background-color: #e03e00;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Ласкаво просимо на наш MTA сервер!</h1>
        <p>IP сервера: <strong>mtasa://127.0.0.1:22003</strong></p>
        <button class="btn" onclick="connectMTA()">Приєднатися</button>
    </div>
    <script>
        function connectMTA() {
            window.location.href = "mtasa://127.0.0.1:22003";
        }
    </script>
</body>
</html>
