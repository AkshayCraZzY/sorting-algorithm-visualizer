<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <link rel="shortcut icon" type="image/png" href="assets/favicon.ico">
    <title>Sorting Algorithm Visualizer</title>
</head>
<body>
    <div id="controls">
        <div id="buttons">
            <button class="control-button">SHUFFLE</button>
            <button class="control-button">BUBBLE</button>
            <button class="control-button">INSERTION</button>
            <button class="control-button">SELECTION</button>
            <button class="control-button">MERGE</button>
        </div>
        <input id="element-quantity" type="number" placeholder="ELEMENTS" value="250">
    </div>
    <canvas id="canvas"></canvas>
    <script src="functions.js"></script>
    <script src="sort.js"></script>
    <script src="script.js"></script>
</body>
</html>
