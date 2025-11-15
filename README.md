<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Maxime</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    body { 
      font-family: Arial; 
      text-align:center; 
      padding:20px;
    }

    #zoneImage {
      display: none; /* Au début l'image est cachée */
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
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h1>Salut les potos, clique sur le lien en dessous</h1>

  <a onclick="afficher()">Clique ici pour faire apparaître l'image</a>

  <div id="zoneImage">
    <h2>L'image est belle non ? 😄</h2>

    <!-- Ton image -->
    <img src="https://tse1.mm.bing.net/th?id=OIP.7lC8iBqC3gJaxk76a6JHkAHaE8&pid=Api&P=0&h=180" alt="Image paysage">
  </div>

  <script>
    function afficher() {
      document.getElementById("zoneImage").style.display = "block";
      window.location = "#zoneImage"; // descend vers l'image
    }
  </script>

</body>
</html>



