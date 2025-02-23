<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AGE - Archivio Genetico Ereditario</title>
    <style>
        body {
            margin: 0;
            font-family: 'Orbitron', sans-serif;
            background: linear-gradient(135deg, #000428, #004e92);
            color: #00ffcc;
            text-align: center;
            overflow-x: hidden;
        }
        .container {
            padding: 50px;
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        h1 {
            font-size: 3.5em;
            text-shadow: 0 0 20px #00ffcc, 0 0 40px #00ffcc;
        }
        p {
            font-size: 1.3em;
            max-width: 700px;
            margin: auto;
            opacity: 0.9;
        }
        .cta-button {
            display: inline-block;
            margin-top: 30px;
            padding: 15px 35px;
            font-size: 1.4em;
            color: #000428;
            background: #00ffcc;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
            box-shadow: 0 0 20px #00ffcc;
        }
        .cta-button:hover {
            background: #009977;
            color: white;
        }
        .hero-image {
            width: 100%;
            max-height: 500px;
            object-fit: cover;
            border-bottom: 3px solid #00ffcc;
        }
        ul {
            list-style: none;
            padding: 0;
            margin-top: 30px;
        }
        ul li {
            font-size: 1.2em;
            margin: 10px 0;
            text-shadow: 0 0 10px #00ffcc;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
</head>
<body>
    <img src="Immagine WhatsApp 2025-02-22 ore 12.12.20_19b1d782.jpg" alt="AGE Futuristico" class="hero-image">
    <div class="container">
        <h1>Benvenuto in AGE</h1>
        <p>AGE - Archivio Genetico Ereditario collega il tuo DNA alla tua eredità digitale, permettendoti di lasciare un segno nel futuro.</p>
        <h2>Perché AGE è Innovativo?</h2>
        <p>AGE è la prima piattaforma che unisce dati genetici e archiviazione digitale, permettendoti di:</p>
        <ul>
            <li>🔹 Conservare ricordi e messaggi per le generazioni future.</li>
            <li>🔹 Creare un albero genealogico interattivo con foto e dati nel tempo.</li>
            <li>🔹 Notificare ai parenti eventuali malattie genetiche ereditarie.</li>
            <li>🔹 Garantire accesso sicuro solo ai tuoi discendenti tramite test del DNA.</li>
        </ul>
        <p>AGE rivoluziona il modo in cui pensiamo all'eredità e alla memoria digitale, garantendo un legame eterno tra passato, presente e futuro.</p>
        <a href="#" class="cta-button">Scopri di più</a>
    </div>
</body>
</html>
