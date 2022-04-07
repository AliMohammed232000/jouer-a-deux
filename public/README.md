# Projet-infoL2

Lien du jeu : https://abdulllahobad.github.io/Projet-infoL2/#

Dans le cadre de notre projet de deuxième année S4 nous avons développé un jeu de société "qui-est-ce?"
Ce jeu a été codé en JAVASCRIPT.
Afin de pouvoir tester le jeu avec plusieurs fichiers json (que nous avons écrit) il suffit de :

    - Ligne 1 changer le path du fichier json, exemple : var path_json = "js/jeu1.json"; devient var path_json = "js/jeu2.json";
        il existe trois fichier voici leurs paths : js/jeu1.json, js/jeu2.json, js/jeu3.json

Enfin, ouvrir le jeu avec l'extension LiveServer de vscode.
Et n'oubliez pas de lire les règles du jeu avant de commencer !

Bon jeu !



Ali


websocket.js:54 WebSocket connection to 'ws://localhost:3000/socket.io/?EIO=4&transport=websocket' failed:
l'extension McAfee® Web Boost empêche la connection....disable all extensions if passible

Failed to load resource: the server responded with a status of 404 (Not Found)
http://127.0.0.1:5500/favicon.ico".
Because your browser always looks for the favicon.ico even if you don't specify it within your HTML.
So I'd suggest just creating one and placing it in the root of your website.
solutio: <link rel="shortcut icon" href="#"> making default icon vide

problem personnage_choisi, the var was initlaised before the server chose the  personnage, and the game was reading all the page before even the request 'personage' comes
solution: dont let the rest of js client run before the personnage arrive, 
socket.on('Personnage',(n)=>{rest of js client});

add bootstrab to index2222
jquery <script type="text/javascript" src="https://code.jquery.com/jquery-latest.min.js"></script>


sweet alerts 
npm install sweetalert2
<script src="//cdn.jsdelivr.net/npm/sweetalert2@11"></script>
https://sweetalert2.github.io/