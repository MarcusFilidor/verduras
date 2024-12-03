<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Verdulería - Verduras</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #FFD700; /* Amarillo */
            padding: 20px;
            text-align: center;
            font-size: 24px;
            color: #000;
        }

        .content {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .vegetable-card {
            background-color: #808080; /* Gris */
            padding: 20px;
            border-radius: 10px;
            width: 200px;
            text-align: center;
            color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .vegetable-card h3 {
            margin: 10px 0;
        }

        .vegetable-card p {
            font-size: 18px;
            margin: 5px 0;
        }

        footer {
            background-color: #000; /* Negro */
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        .back-to-home {
            margin-top: 20px;
            background-color: #FFD700;
            color: #000;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .back-to-home:hover {
            background-color: #e6b800;
        }
    </style>
</head>
<body>

<header>
    Verdulería - Verduras
</header>

<div class="content">
    <div class="vegetable-card">
        <h3>Zanahoria</h3>
        <p>Perfecta para ensaladas o guisos</p>
    </div>
    <div class="vegetable-card">
        <h3>Lechuga</h3>
        <p>Fresca y crujiente para tus ensaladas</p>
    </div>
    <div class="vegetable-card">
        <h3>Tomate</h3>
        <p>Ideal para salsas y ensaladas</p>
    </div>
    <div class="vegetable-card">
        <h3>Brócoli</h3>
        <p>Rico en nutrientes, ideal para cocer al vapor</p>
    </div>
    <div class="vegetable-card">
        <h3>Papa</h3>
        <p>Versátil para todo tipo de platos</p>
    </div>
</div>

<footer>
    <a href="index.html" class="back-to-home">Volver al Inicio</a>
</footer>

</body>
</html>
