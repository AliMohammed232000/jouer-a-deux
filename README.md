# jouer-a-deux
deploying the game on Heroku

nous avons mit le jeu online dans le cloud de Heroku, pour que le jeu soit disponible online

donc il y a deux possibilité pour tester le jeu
1) tester le jeu derictement online, 
    Lien du jeu hebérgé dans le cloud :https://jouer-a-deux.herokuapp.com/
2)tester le jeu en localhost
   a) afin de tester le jeu en localhost, vous devez téléchager node.js
   b) aussi nous avos utilisé les sweetalert2 pour gérer les alerts dans notre code javascript
      donc il faut le télécharger....npm install sweetalert2 (windows)
   c) dès que vous avez téléchargé node.js et les sweetalerts2, localisez vous dans le repertoir du jeu et    tapez node server
   d) vous aller remarquer dans le terminale que le serveur écoute le port (lestning on) 3000, donc tout     marche bien
   e) ouverez un navigateur et tapez http://127.0.0.1:3000/
