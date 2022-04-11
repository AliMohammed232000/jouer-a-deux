# Projet-infoL2


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