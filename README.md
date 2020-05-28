# Docker_project
Project under guidance of Vimal daga sir in iiec rise campaign. 

First I installed docker on rhel 8 (Cli) on gcp
Then I pulled container image that have game deployed using cmd $docker pull nived15/mario-game
After that I installed that container using cmd $docker container run -d --name mario-game -p 80:80 nived15/mario-game
On port 80:80
<html> 
<head> 
<meta name = "viewport" content = "width = 1280" /> <title>Mario Maker</title> <link rel= "stylesheet" type="text/css" href="cs s/style.css"> <link rel="stylesheet" type="text/css" href = "cs s/reset.css"> </head> <body> <! -- main game <div class = "main-wrapper"> <canvas class="game -screen"></canvas> </div> <script src = "js/View.js"></script> <script src="js/GameUI.js"></script> <script src="js/mainGame/Game Sound.js"></script <script src='js/mainGame/Element.js"></script> <script src ="js/mainGame/PowerUp.js"></script> <script src="js/mainGame/Enemy.js"></script> <script src= "js/mainGame/Bullet.js'></script> <script src='js/mainGame/Mario.js"></script> <script src= "js/mainGame/Score.js"></script> <script src="js/mainGame/MarioGame, js"></script <script src = "js/levelEditor/Stor age.js"></scrip t> <script src ="js/levelEditor/Editor.js"></script <script src = "js/levelEditor/CreatedLevels.js">< /script> <script src="js/MarioMaker.js"></script> <script src ='js/Preloader.js"></ script> 
</body>

For checking game is running I used cmd $curl http://localhost

