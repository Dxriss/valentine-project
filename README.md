<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentime!!</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="opening-screen" id="openingScreen">
        <div class="love-effect">
        </div> 
        </h1>Enter Your Name</h1>
        <input type="text" id="crushName" placeholder="Type name here..." />
        <button id="startbutton">Start</button>
    </div>

    <div class="container" id="mainContent" style="display: none;">
        <h1 class="animated-text">Happy Valentine Day, <span id="displayName"></span>! ❤️</h1>
        <div class="hearth" id="hearth"></div>
        <div id="messageContainer"></div>
        <button id="nextPageButton">Suprise</button>
    </div>

    <script src=script.js"></script>
  </body>
  </html>
