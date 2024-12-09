<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./style.css">
  <script src="./script.js" defer></script>
  <title>Simple Jump Game</title>
</head>
<body>
  <h1>Simple Jump Game</h1>
  <p>Нажмите <strong>Space</strong>, чтобы прыгать и избегать препятствий!</p>
  <div class="game">
    <div id="player"></div>
    <div id="damper"></div>
  </div>
  <button class="start">Start</button>
  <button class="restart" style="display: none;">Restart</button>
  <div class="score">Score: <span id="score">0</span></div>
</body>
</html>
