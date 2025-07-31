<html>
<head>
    <meta charset="UTF-8">
    <title>Josip Tadić</title>
    <style>
        .naslov {
            background-color: blue;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .gumb-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 30px;
        }

        .gumb {
            width: 150px;
            height: 150px;
            background-color: #007BFF;
            color: white;
            font-size: 16px;
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .gumb:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <div class="naslov">
        <h1>Josip Tadić</h1>
    </div>
    
    <h2 style="text-align:center;">Magistar ekonomije</h2>
    <h3 style="text-align:center;">Dobrodošli na moju stranicu, nadam se da će vam se svidjeti!</h3>

    <div class="gumb-container">
        <a href="Josip_Tadić_Životopis.pdf" target="_blank"><button class="gumb">Životopis</button></a>
        <a href="Josip_Tadić_Motivacijsko_pismo_2.pdf" target="_blank"><button class="gumb">Motivacijsko pismo</button></a>
        <a href="https://www.linkedin.com/in/josip-tadi%C4%87-031588172/" target="_blank"><button class="gumb">LinkedIn profil</button></a>
        <a href="snimke.pdf" target="_blank"><button class="gumb">Ekranski prikaz</button></a>
    </div>
    
</body>
</html>
