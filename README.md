<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div></title>

    <style>

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f4f4;
        }

        /* Bandeau supérieur */
        .header {
            background: linear-gradient(90deg, #ff6a00, #ff9500);
            color: white;
            padding: 25px;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            box-shadow: 0 3px 10px rgba(0,0,0,0.2);
        }

        .header p {
            margin-top: 10px;
            font-size: 16px;
            font-weight: normal;
        }

        /* Layout général */
        .container {
            display: flex;
            height: calc(100vh - 120px);
        }

        /* Colonne gauche */
        .sidebar {
            width: 300px;
            background: #ffffff;
            padding: 20px;
            border-right: 2px solid #ddd;
            box-shadow: 3px 0 5px rgba(0,0,0,0.05);
            overflow-y: auto;
        }

        /* Boutons */
        .btn {
            display: block;
            background: #ff6a00;
            color: white;
            padding: 12px;
            text-align: center;
            text-decoration: none;
            margin-top: 12px;
            border-radius: 8px;
            font-size: 17px;
            font-weight: bold;
            transition: 0.2s;
            cursor: pointer;
        }

        .btn:hover {
            background: #ff8800;
            transform: scale(1.03);
        }

        /* Description sous les boutons */
        .description {
            margin-top: 5px;
            margin-bottom: 15px;
            font-size: 14px;
            color: #444;
            padding-left: 5px;
        }

        /* Zone PDF */
        .content {
            flex: 1;
            padding: 10px;
            background: #fff;
        }

        iframe {
            width: 100%;
            height: calc(100% - 60px);
            border: none;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .download-btn {
            margin-top: 10px;
            display: inline-block;
            background: #0080ff;
            color: white;
            padding: 12px 20px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }

    </style>

    <script>
        function openPDF(link) {
            document.getElementById("pdfFrame").src = link;
            document.getElementById("downloadBtn").href = link;
        }
    </script>

</head>
<body>

    <!-- Bandeau haut -->
    <div class="header">
        Documents PDF
        <p>Choisis un document à gauche, il s’affichera ici à droite. Tu peux aussi le télécharger.Sur ce site ici tu va trouver des documents de cours des evals pleins de chose comme ca, regale toi mais la règle d'or ont ne cafte pas au profs que ici il y a toute les reponses.Bonne documentation</p>
    </div>

    <div class="container">

        <!-- Colonne gauche avec les boutons -->
        <div class="sidebar">

            <div class="btn" onclick="openPDF(https://raw.githubusercontent.com/Max214354/maxime/2cd38331887a4c94fe1ec1c50d3b306d1f333c31/G%C3%A9o%20Ch%209%20Bilan.pdf
')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div>

            <div class="btn" onclick="openPDF('LIEN_2')">📄 Voir le document PDF 2</div>
            <div class="description">DESCRIPTION_2</div>

            <div class="btn" onclick="openPDF('LIEN_3')">📄 Voir le document PDF 3</div>
            <div class="description">DESCRIPTION_3</div>
          <div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div><div class="btn" onclick="openPDF('LIEN_1')">📄 Voir le document PDF 1</div>
            <div class="description">DESCRIPTION_1</div>

            <!-- Continue jusqu’à 20 boutons -->

        </div>

        <!-- Zone d'affichage PDF -->
        <div class="content">
            <iframe id="pdfFrame" src=""></iframe>

            <a id="downloadBtn" class="download-btn" href="" download>⬇️ Télécharger le PDF</a>
        </div>

    </div>

</body>
</html>



