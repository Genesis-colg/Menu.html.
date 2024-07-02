<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Funcional</title>
    <style>
        body {
            font-family: sans-serif;
        }
        #menu {
            background-color: #f2f2f2;
            padding: 20px;
            border-radius: 5px;
        }
        #menu ul {
            list-style: none;
            padding: 0;
        }
        #menu li {
            margin-bottom: 10px;
        }
        #menu a {
            text-decoration: none;
            color: #333;
            padding: 10px 20px;
            background-color: #ddd;
            border-radius: 5px;
            display: block;
            transition: background-color 0.3s;
        }
        #menu a:hover {
            background-color: #ccc;
        }
    </style>
</head>
<body>

    <div id="menu">
        <h2>Menú Principal</h2>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Productos</a></li>
            <li><a href="#">Servicios</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </div>

</body>
</html>
