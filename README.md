# tic_toc_toe
game
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <div id="toStartGame">
        <p>choose who is first</p>
        <button class="first" id="buttonStartX"> X</button>
        <button class="first" id="buttonStartCircle">O </button>

    </div>
    <div class="board " id="board">
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
      </div>
      <div class="winning-message" id="winningMessage">
        <div data-winning-message-text></div>
        <button id="restartButton">Restart</button>
      </div>
    <script src="script.js"></script>
      
</body>
</html>
