<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SWAG House - Game Studio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #222;
            color: #fff;
        }

        header {
            background-color: #333;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
        }

        nav {
            text-align: center;
            margin-top: 20px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h2 {
            font-size: 24px;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        .games {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 40px;
        }

        .game {
            margin: 20px;
            padding: 20px;
            background-color: #444;
            border-radius: 10px;
            text-align: center;
            width: 300px;
        }

        .game img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background-color: #333;
            padding: 20px 0;
            text-align: center;
        }

        footer p {
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SWAG House - Game Studio</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Games</a>
            <a href="#">About Us</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <div class="container">
        <h2>Welcome to SWAG House</h2>
        <p>Experience the world of gaming like never before. We are dedicated to creating innovative and exciting games that will keep you entertained for hours.</p>

        <h2>Our Games</h2>
        <div class="games">
            <div class="game">
                <img src="game1.jpg" alt="Game 1">
                <h3>Game Title 1</h3>
                <p>Description of Game 1.</p>
            </div>
            <div class="game">
                <img src="game2.jpg" alt="Game 2">
                <h3>Game Title 2</h3>
                <p>Description of Game 2.</p>
            </div>
            <div class="game">
                <img src="game3.jpg" alt="Game 3">
                <h3>Game Title 3</h3>
                <p>Description of Game 3.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 SWAG House - Game Studio</p>
    </footer>
</body>
</html>
