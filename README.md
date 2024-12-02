# ShawtyMessage
<html>
<head>
    <title>Creative Message</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Pacifico', cursive;
        }
        .message-container {
            text-align: center;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .message-container h1 {
            font-size: 4em;
            margin: 0;
            color: #ff6f61;
        }
        .message-container h2 {
            font-size: 2em;
            margin: 10px 0;
            color: #ffcc00;
        }
        .message-container .icon {
            font-size: 3em;
            margin-top: 20px;
            animation: bounce 2s infinite;
            color: #ff6f61;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-30px);
            }
            60% {
                transform: translateY(-15px);
            }
        }
    </style>
</head>
<body>
    <div class="message-container">
        <h1>Itot!</h1>
        <h2>Kupal kaba boss?</h2>
        <div class="icon">
            <i class="fas fa-heart"></i>
        </div>
    </div>
</body>
</html>
