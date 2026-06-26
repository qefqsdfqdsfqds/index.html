<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            max-width: 400px;
            width: 90%;
        }
        h1 {
            color: #ff4757;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        p {
            color: #57606f;
            font-size: 1.1rem;
            line-height: 1.6;
        }
        .cake {
            font-size: 4rem;
            margin: 20px 0;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        .btn {
            background-color: #ff4757;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 25px;
            font-size: 1rem;
            cursor: pointer;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #ff6b81;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="cake">🎂</div>
        <h1>Happy Birthday!</h1>
        <p>Wishing you a day filled with love, laughter, and endless happiness. Thank you for being such an awesome person!</p>
        <button class="btn" onclick="celebrate()">Click Me!</button>
    </div>

    <script>
        function celebrate() {
            alert("🎉 May all your wishes come true today and always! Have a blast! 🎉");
        }
    </script>

</body>
</html>
