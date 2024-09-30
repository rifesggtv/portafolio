<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio de Andrés Felipe Guerrero Sierra, artista plástico.">
    <title>Andrés Felipe Guerrero Sierra - Artista Plástico</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #d94f70;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        nav a:hover {
            color: #d94f70;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .biografia, .obras, .investigaciones, .contacto {
            padding: 20px 0;
            border-bottom: 1px solid #ddd;
        }
        h2 {
            color: #d94f70;
            font-size: 2em;
            margin-bottom: 10px;
        }
        p {
            line-height: 1.6;
        }
        .obras img {
            width: 100%;
            max-width: 400px;
            height: auto;
            margin: 10px;
            border: 2px solid #d94f70;
        }
        .obras div {
            margin-bottom: 20px;
        }
        .contacto ul {
            list-style-type: none;
            padding: 0;
        }
        .contacto ul li {
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }
        footer a {
            color: #d94f70;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Andrés Felipe Guerrero Sierra</h1>
        <p>Artista Plástico</p>
    </header>

    <nav>
        <a href="#biografia">Biografía</a>
        <a href="#obras">Obras</a>
        <a href="#investigaciones">Investigaciones</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="container">
        <section id="biografia" class="biografia">
            <h2>Biografía</h2>
            <p>Hola, soy Andrés Felipe Guerrero Sierra, un artista plástico con pasión por explorar la forma, el color y la textura a través de diversas técnicas. Mi trabajo se enfoca en la interacción entre el arte moderno y los elementos tradicionales.</p>
        </section>

        <section id="obras" class="obras">
            <h2>Obras</h2>
            <div>
                <img src="ruta/a/imagen1.jpg" alt="Obra 1">
                <p><strong>Nombre de la Obra 1:</strong> Descripción breve de la obra.</p>
            </div>
            <div>
                <img src="ruta/a/imagen2.jpg" alt="Obra 2">
                <p><strong>Nombre de la Obra 2:</strong> Descripción breve de la obra.</p>
            </div>
        </section>

        <section id="investigaciones" class="investigaciones">
            <h2>Investigaciones</h2>
            <p>Mi investigación artística se centra en la conexión entre el arte y la naturaleza, explorando cómo las formas orgánicas pueden integrarse en el espacio urbano. A través de mis investigaciones, busco entender cómo los materiales naturales pueden influir en las emociones humanas.</p>
        </section>

        <section id="contacto" class="contacto">
            <h2>Contacto</h2>
            <ul>
                <li><strong>Email:</strong> <a href="mailto:tuemail@example.com">tuemail@example.com</a></li>
                <li><strong>Facebook:</strong> <a href="https://www.facebook.com/profile.php?id=100007394686564" target="_blank">Mi perfil de Facebook</a></li>
                <li><strong>Instagram:</strong> <a href="https://www.instagram.com/traceur_art_hu/" target="_blank">Mi perfil de Instagram</a></li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Andrés Felipe Guerrero Sierra | Portafolio de Arte</p>
    </footer>

</body>
</html>
