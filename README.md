# viajesjovenes
Viajes que podrías hacer siendo joven con tu grupo de amigos
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Mi Portafolio</h1>
        <nav>
            <ul>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="proyectos">
        <h2>Mis Proyectos</h2>
        <div class="proyecto">
            <img src="proyecto1.jpg" alt="Proyecto 1">
            <h3>Proyecto 1</h3>
            <p>Descripción breve del proyecto 1.</p>
            <a href="enlace_al_proyecto_1">Ver proyecto</a>
        </div>
        <div class="proyecto">
            <img src="proyecto2.jpg" alt="Proyecto 2">
            <h3>Proyecto 2</h3>
            <p>Descripción breve del proyecto 2.</p>
            <a href="enlace_al_proyecto_2">Ver proyecto</a>
        </div>
        <!-- Agregar más proyectos aquí -->
    </section>
    
    <section id="habilidades">
        <h2>Mis Habilidades</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
            <!-- Agregar más habilidades aquí -->
        </ul>
    </section>
    
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarme en: <a href="mailto:correo@example.com">correo@example.com</a></p>
    </section>
    
    <footer>
        <p>&copy; 2023 Mi Portafolio</p>
    </footer>
</body>
</html>
/* Reset de estilos básicos */
body, h1, h2, h3, p, ul, li, a {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f7f7f7;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #222;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline-block;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

section {
    padding: 40px 0;
    text-align: center;
}

.proyecto {
    margin-bottom: 40px;
}

.proyecto img {
    max-width: 100%;
    height: auto;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #222;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
