<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Proyecto Final</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo.jpg" alt="Mi Logo" class="logo">
        <nav>
            <ul>
                <li><a href="#about">Acerca de mí</a></li>
                <li><a href="#experience">Experiencia</a></li>
                <li><a href="#projects">Proyectos</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="showcase">
            <h1>Bienvenido a mi Web</h1>
            <p>Esta es una página creada como parte de mi proyecto final.</p>
            <button id="projects-button">Proyectos</button>
        </section>

        <section id="about">
            <h2>Acerca de mí</h2>
            <p>Hola, soy estudiante de tecnología. Me encanta aprender sobre desarrollo web.</p>
        </section>

        <section id="experience">
            <h2>Mi Experiencia</h2>
            <ul>
                <li>2025 - Desarrollador Frontend en una empresa innovadora.</li>
                <li>2028 - Diseñador UX/UI trabajando en proyectos internacionales.</li>
                <li>2035 - CTO en una startup tecnológica de éxito.</li>
                <li>2040 - fui al espacio ya que fui astronauta</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Proyectos Escolares</h2>
            <div class="project">
                <img src="proyecto-1.jpg" alt="Proyecto 1">
                <p>Proyecto de robótica educativa.</p>
                <button onclick="window.location.href='https://scratch.mit.edu/'">Ver Proyecto</button>
            </div>
            <div class="project">
                <img src="proyecto-2.png" alt="Proyecto 2">
                <p>Desarrollo de una aplicación móvil con una web sobre la app.</p>
                <button onclick="window.location.href='https://segredonocastelo.godaddysites.com/'">Ver Proyecto</button>
            </div>
            <div class="project">
                <img src="proyecto-3.jpg" alt="Proyecto 3">
                <p>Video narrativo de la final del mundial.</p>
                <button onclick="window.location.href='https://www.youtube.com/watch?v=FA1sR2SZAlY'">Ver Proyecto</button>
            </div>
        </section>

        <section id="contact">
            <h2>Contacto</h2>
            <p>Teléfono: 123-456-7890</p>
            <p>Email: hectorgutierrezinsua@gmail.com</p>
            <button onclick="window.location.href='https://www.instagram.com/hector.gutierreez/'">Mi Instagram</button>
            <button id="hidden-button" onclick="window.location.href='https://www.tiktok.com/@2021donpollo/video/7204591936492129579?is_from_webapp=1&sender_device=pc&web_id=7438893679298790945'">¡Secreto!</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Mi Proyecto Final. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
