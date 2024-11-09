<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Article Right</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Estilos del contenedor principal */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }

        /* Contenedor con Flexbox */
        .container {
            display: flex;
            gap: 20px; /* Espacio entre barra lateral y el artículo */
            width: 80%;
            max-width: 1200px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Barra lateral */
        .sidebar {
            width: 30%;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }

        /* Contenido principal alineado a la derecha */
        .article {
            width: 70%;
            padding: 20px;
            background-color: #800;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Barra lateral -->
        <aside class="sidebar">
            <h2>Barra Lateral</h2>
            <p></p>
        </aside>

        <!-- Contenido principal alineado a la derecha -->
        <article class="article">
            <h1>Título del Artículo</h1>
            <p> </p>
            <p>Info</p>
        </article>
    </div>
</body>
</html>
