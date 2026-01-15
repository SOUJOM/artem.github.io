<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bitcoin Clicker Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <h1>Bitcoin Tycoon</h1>
        
        <div class="stats">
            <p>Біткоїни: <span id="balance">0</span> ₿</p>
            <p>Прибуток за клік: <span id="perClick">1</span></p>
        </div>
 
        <div class="click-area">
            <button id="clickBtn">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968260.png" alt="Bitcoin" width="150">
            </button>
        </div>
 
        <div class="shop">
            <h2>Магазин покращень</h2>
            <button class="upgrade-btn" id="buyUpgrade">
                Купити відеокарту (+5 до кліку) <br>
                Ціна: <span id="upgradeCost">50</span> ₿
            </button>
        </div>
    </div>
 
    <script src="script.js"></script>
</body>
</html>
