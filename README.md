# JessLau25.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <script src="p5.js"></script>
    <link href="style.css" rel="stylesheet" type="text/css">
    <link href="animation.css" rel="stylesheet" type="text/css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
<style>
    body {
        overflow: hidden;
    }
</style>
<script>
    let bimg
    let w = window.innerWidth
    let h = window.innerHeight
    function startgame() {
        location.href="level1start.html"
    }
    function preload() {
        bimg = loadImage('hipo.png');
    }
    function setup() {
        createCanvas(w, h);
    }
    function draw() {
        background(bimg)
    }
</script>
</head>
<body>
    <button id="title" onclick="startgame()">Level 1</button>
    <div id="level1intro">
        A couple of the paparazzi start to follow you and are trying to set you up for their next big story. They place banana peels on your usual path from home to the bus. In this first level, your goal is to avoid the peels while running to the bus! <br> Instructions: Use your space bar to jump
    </div>
</body>
</html>