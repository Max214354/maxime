<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #f4f4f4;
    }

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

    .container {
        display: flex;
        height: calc(100vh - 120px);
    }

    .sidebar {
        width: 300px;
        background: #ffffff;
        padding: 20px;
        border-right: 2px solid #ddd;
        box-shadow: 3px 0 5px rgba(0,0,0,0.05);
        overflow-y: auto;
    }

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

    .description {
        margin-top: 5px;
        margin-bottom: 15px;
        font-size: 14px;
        color: #444;
        padding-left: 5px;
    }

    .content {
        flex: 1;
        padding: 20px;
        display: flex;
        flex-direction: column;
        align-items: center;
        background: #fff;
    }

    iframe {
        width: 90%;
        height: 80%;
        border: none;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
        margin-bottom: 20px;
    }

    .download-btn {
        background: #0080ff;
        color: white;
        padding: 12px 25px;
        border-radius: 8px;
        text-decoration: none;
        font-weight: bold;
        transition: 0.2s;
    }

    .download-btn:hover {
        background: #3399ff;
    }

</style>
</head>
<body>

<div class="header">
    Bibliothèque PDF
    <p>Choisis un document à gauche, il s’affichera ici à droite. Tu peux aussi le télécharger.Sur ce site ici tu va trouver des documents de cours des evals pleins de chose comme ca, regale toi mais la règle d'or ont ne cafte pas au profs que ici il y a toute les reponses.Bonne documentation</p>
</div>

<div class="container">

    <!-- Sidebar avec 25 boutons -->
    <div class="sidebar">

        <div class="btn" onclick="openPDF('https://raw.githubusercontent.com/Max214354/maxime/2cd38331887a4c94fe1ec1c50d3b306d1f333c31/G%C3%A9o%20Ch%209%20Bilan.pdf')">
            📄 Voir le document PDF 1
        </div>
        <div class="description">Géographie Chapitre 9 - Bilan</div>

        <!-- Les boutons 2 à 25 prêts à être remplacés par tes liens -->
       <div class="btn" onclick="openPDF('https://raw.githubusercontent.com/Max214354/Bonjour-Regaler-vous/refs/heads/main/Methode%20caluls%202025%20s%C3%A9rie%202.pdf')">
    📄 Voir le document PDF 2
</div>
<div class="description">Méthode calculs 2025 - Série 2</div>

        <div class="btn" onclick="openPDF('LIEN_3')">📄 Voir le document PDF 3</div>
        <div class="description">DESCRIPTION_3</div>

        <div class="btn" onclick="openPDF('LIEN_4')">📄 Voir le document PDF 4</div>
        <div class="description">DESCRIPTION_4</div>

        <div class="btn" onclick="openPDF('LIEN_5')">📄 Voir le document PDF 5</div>
        <div class="description">DESCRIPTION_5</div>

        <div class="btn" onclick="openPDF('LIEN_6')">📄 Voir le document PDF 6</div>
        <div class="description">DESCRIPTION_6</div>

        <div class="btn" onclick="openPDF('LIEN_7')">📄 Voir le document PDF 7</div>
        <div class="description">DESCRIPTION_7</div>

        <div class="btn" onclick="openPDF('LIEN_8')">📄 Voir le document PDF 8</div>
        <div class="description">DESCRIPTION_8</div>

        <div class="btn" onclick="openPDF('LIEN_9')">📄 Voir le document PDF 9</div>
        <div class="description">DESCRIPTION_9</div>

        <div class="btn" onclick="openPDF('LIEN_10')">📄 Voir le document PDF 10</div>
        <div class="description">DESCRIPTION_10</div>

        <div class="btn" onclick="openPDF('LIEN_11')">📄 Voir le document PDF 11</div>
        <div class="description">DESCRIPTION_11</div>

        <div class="btn" onclick="openPDF('LIEN_12')">📄 Voir le document PDF 12</div>
        <div class="description">DESCRIPTION_12</div>

        <div class="btn" onclick="openPDF('LIEN_13')">📄 Voir le document PDF 13</div>
        <div class="description">DESCRIPTION_13</div>

        <div class="btn" onclick="openPDF('LIEN_14')">📄 Voir le document PDF 14</div>
        <div class="description">DESCRIPTION_14</div>

        <div class="btn" onclick="openPDF('LIEN_15')">📄 Voir le document PDF 15</div>
        <div class="description">DESCRIPTION_15</div>

        <div class="btn" onclick="openPDF('LIEN_16')">📄 Voir le document PDF 16</div>
        <div class="description">DESCRIPTION_16</div>

        <div class="btn" onclick="openPDF('LIEN_17')">📄 Voir le document PDF 17</div>
        <div class="description">DESCRIPTION_17</div>

        <div class="btn" onclick="openPDF('LIEN_18')">📄 Voir le document PDF 18</div>
        <div class="description">DESCRIPTION_18</div>

        <div class="btn" onclick="openPDF('LIEN_19')">📄 Voir le document PDF 19</div>
        <div class="description">DESCRIPTION_19</div>

        <div class="btn" onclick="openPDF('LIEN_20')">📄 Voir le document PDF 20</div>
        <div class="description">DESCRIPTION_20</div>

        <div class="btn" onclick="openPDF('LIEN_21')">📄 Voir le document PDF 21</div>
        <div class="description">DESCRIPTION_21</div>

        <div class="btn" onclick="openPDF('LIEN_22')">📄 Voir le document PDF 22</div>
        <div class="description">DESCRIPTION_22</div>

        <div class="btn" onclick="openPDF('LIEN_23')">📄 Voir le document PDF 23</div>
        <div class="description">DESCRIPTION_23</div>

        <div class="btn" onclick="openPDF('LIEN_24')">📄 Voir le document PDF 24</div>
        <div class="description">DESCRIPTION_24</div>

        <div class="btn" onclick="openPDF('LIEN_25')">📄 Voir le document PDF 25</div>
        <div class="description">DESCRIPTION_25</div>

    </div>

    <div class="content">
        <iframe id="pdfFrame" src=""></iframe>
        <a id="downloadBtn" class="download-btn" href="" download>⬇️ Télécharger le PDF</a>
    </div>

</div>

<script>
function openPDF(link) {
    // Utiliser Google Docs Viewer pour afficher le PDF
    const viewer = 'https://docs.google.com/gview?url=' + encodeURIComponent(link) + '&embedded=true';
    document.getElementById("pdfFrame").src = viewer;
    document.getElementById("downloadBtn").href = link;
}
</script>

</body>
</html>
