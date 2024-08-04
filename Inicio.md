<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tesoros de Tunja</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #f2e8e1;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background: #8e735b;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        footer {
            background: #8e735b;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .description {
            text-align: center;
        }
        .description img {
            width: 100%;
            height: auto;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
        }
        .gallery img {
            width: 30%;
            margin-bottom: 20px;
        }
        section {
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tesoros de Tunja</h1>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="gastronomia.html">Gastronomía</a></li>
                <li><a href="cultura.html">Cultura</a></li>
                <li><a href="religioso.html">Religioso</a></li>
                <li><a href="academico.html">Académico</a></li>
                <li><a href="ambiental.html">Ambiental</a></li>
                <li><a href="equipo.html">Equipo</a></li>
                <li><a href="por-que-lo-hacemos.html">¿Por qué lo hacemos?</a></li>
                <li><a href="contactanos.html">Contáctanos</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <section id="inicio" class="description">
            <img src="tunja.jpg" alt="Imagen de Tunja">
            <p>Tunja, la capital del departamento de Boyacá, es una ciudad llena de historia, cultura y belleza natural. Descubre con nosotros los tesoros perdidos de esta encantadora ciudad y todo lo que tiene para ofrecer.</p>
        </section>
        <section class="gallery">
            <img src="tunja1.jpg" alt="Imagen de Tunja">
            <img src="tunja2.jpg" alt="Imagen de Tunja">
            <img src="tunja3.jpg" alt="Imagen de Tunja">
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Tesoros de Tunja. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

