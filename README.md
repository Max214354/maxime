<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Maxime</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    body { font-family: Arial; text-align:center; padding:20px; }

    #zoneImage {
      display: none; /* image cachée au début */
      margin-top: 30px;
    }

    img {
      max-width: 90%;
      border-radius: 10px;
    }

    a {
      font-size: 20px;
      text-decoration: none;
      color: blue;
    }
  </style>
</head>
<body>

  <h1>Salut les potos clique sur le lien en dessous</h1>

  <a href="#" onclick="afficher()">Clique ici pour faire apparaître l'image</a>

  <div id="zoneImage">
    <h2>L'image est belle non c'est Maxime hi hi hi :</h2>

    
 <img src="<img width="276" height="180" alt="image" src="https://github.com/user-attachments/assets/721c878b-c67a-428b-bd32-19d126731641" />
" alt="Maxime">


  <script>
    function afficher() {
      document.getElementById("zoneImage").style.display = "block";
      window.location = "#zoneImage"; // descend vers l'image
    }
  </script>

</body>
</html>




