<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Página de Investigación y Navegación</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background: #f9f9f9;
        }
        .container {
            max-width: 400px;
            margin: 100px auto;
            padding: 30px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        input[type="text"] {
            width: 80%;
            padding: 10px;
            margin-bottom: 10px;
        }
        button {
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Buscar en Google</h2>
        <form id="google-search" target="_blank" action="https://www.google.com/search" method="GET">
            <input type="text" name="q" placeholder="Escribe tu búsqueda aquí..." required>
            <button type="submit">Buscar</button>
        </form>
    </div>
</body>
</html>
