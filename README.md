# InerciaZero
Gestión de deportes alternativos la motivación en la educación física
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>InerciaZero</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f2f2f2;
    }

    header {
      background-color: #1c2833;
      color: white;
      text-align: center;
      padding: 40px 20px 20px;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
    }

    header h2 {
      font-size: 1.5em;
      margin-top: 10px;
      color: #c0d6e4;
    }

.logo-upn {
      position: absolute;
      top: 20px;
      left: 20px;
      width: 80px;
      height: auto;
      z-index: 10;
    }

    .datos-personales {
      background-color: #ecf0f1;
      color: #2c3e50;
      text-align: center;
      padding: 20px;
    }

    .datos-personales h3 {
      margin: 0;
    }

    .datos-personales p {
      margin-top: 10px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    .datos-personales img {
      margin-top: 20px;
      width: 200px;
      border-radius: 10px;
    }

    .menu {
      text-align: center;
      background-color: #2980b9;
      padding: 10px 0;
    }

    .menu button {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 5px;
      cursor: pointer;
      border-radius: 5px;
      font-size: 1em;
      transition: background-color 0.3s;
    }

    .menu button:hover {
      background-color: #5dade2;
    }

    main {
      padding: 20px;
    }

    .contenido {
      display: none;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.5s ease, transform 0.5s ease;
    }

    .contenido.visible {
      display: block;
      opacity: 1;
      transform: translateY(0);
    }

    img {
      width: 100%;
      max-width: 600px;
      display: block;
      margin: 20px auto;
      border-radius: 10px;
    }

    footer {
      background-color: #1c2833;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo_upn.png" alt="Logo UPN" class="logo-upn">
    <h1>InerciaZero</h1>
    <h2>Gestión de Deportes Alternativos para una Autodeterminación</h2>
  </header>

    <h1>InerciaZero</h1>
    <h2>Gestión de Deportes Alternativos para una Autodeterminación</h2>
  </header>

  <section class="datos-personales">
    <h3>Diego Ortiz</h3>
    <p>Estudiante de Licenciatura en Educación Física en la Universidad Pedagógica Nacional de Colombia. Jugador de Ultimate Frisbee con más de 10 años de trayectoria. Representé a la Selección Colombia Sub17 en el año 2018. Me apasiona la creatividad, la innovación, la crítica constructiva, lo nuevo, las relaciones humanas y la competencia positiva.</p>

    <img src="diego_ortiz.jpg" alt="Foto de Diego Ortiz">
  </section>

  <div class="menu">
    <button onclick="mostrarSeccion('inicio')">Inicio</button>
    <button onclick="mostrarSeccion('deporte')">Deporte Escolar</button>
    <button onclick="mostrarSeccion('modelo')">Modelo Emancipador</button>
    <button onclick="mostrarSeccion('desarrollo')">Desarrollo a Escala Humana</button>
    <button onclick="mostrarSeccion('autodeterminacion')">Teoría de la Autodeterminación</button>
  </div>

  <main>
    <section id="inicio" class="contenido visible">
      <h2>Inicio</h2>
      <p><strong>InerciaZero</strong> no es solo un proyecto: es una invitación a repensar la educación física desde una mirada crítica, creativa y transformadora. Es un espacio que nace de la necesidad de romper con las prácticas tradicionales que limitan el potencial del movimiento humano, proponiendo en su lugar un enfoque donde la exploración, el juego y la autonomía sean protagonistas.</p>
<p>Creemos que los deportes alternativos no solo enriquecen la motricidad, sino que también son herramientas poderosas para el desarrollo personal y colectivo. Desde la Frisbee hasta el Kin-Ball, pasando por propuestas emergentes y autogestionadas, InerciaZero impulsa una educación física inclusiva, diversa y con sentido.</p>
<p>Nuestro objetivo es claro: construir experiencias motrices que despierten la curiosidad, el pensamiento crítico y el deseo de aprender desde el cuerpo. Aquí, cada estudiante es protagonista de su proceso, capaz de tomar decisiones, crear nuevas formas de jugar, y reflexionar sobre su lugar en el mundo a través del movimiento.</p>
<p>Con InerciaZero, la clase de educación física deja de ser un espacio repetitivo y se convierte en un laboratorio de posibilidades. Porque el cuerpo piensa, siente, se relaciona y transforma. Y cuando lo dejamos expresarse libremente, somos capaces de reinventar la educación.</p>

      <img src="inerciazero_inicio.jpg" alt="Imagen representativa de InerciaZero">
    </section>

    <section id="deporte" class="contenido">
      <h2>Deporte Escolar</h2>
      <section id="deporte" class="contenido">
  <h2>Deporte Escolar</h2>
  <iframe src="https://gamma.app/embed/atux61lg8yfdzxy" style="width: 700px; max-width: 100%; height: 450px;" allowfullscreen title="El Deporte Escolar según Blázquez: Una Visión Integral"></iframe>
      <img src="imagenes/deporte_escolar.jpg" alt="Imagen de deporte escolar">
    </section>

      <img src="imagenes/deporte_escolar.jpg" alt="Imagen de deporte escolar">
    </section>

    <section id="modelo" class="contenido">
      <h2>Modelo Emancipador</h2>
      <div style="position: relative; padding-bottom: 56.25%; height: 0;">
        <iframe src="https://view.genially.com/680581182a864e6d9137ebad" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen></iframe>
      </div>
      <img src="imagenes/modelo_emancipador.jpg" alt="Imagen del modelo emancipador">
    </section>

    <section id="desarrollo" class="contenido">
      <h2>Desarrollo a Escala Humana</h2>
      <iframe src="https://app.emaze.com/@ALFLFFWFF/desarrollo-a-escacla-humana" width="960" height="540" allowfullscreen></iframe>
      <img src="imagenes/desarrollo_humano.jpg" alt="Imagen sobre desarrollo a escala humana">
    </section>

    <section id="autodeterminacion" class="contenido">
      <h2>Teoría de la Autodeterminación</h2>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/CrhBdNYzC3E?si=fDlEi8xyCKZX6BJo" frameborder="0" allowfullscreen></iframe>
      <img src="imagenes/autodeterminacion.jpg" alt="Gráfico sobre teoría de la autodeterminación">
    </section>
  </main>

  <footer>
    <p>&copy; 2025 InerciaZero. Todos los derechos reservados.</p>
  </footer>

  <script>
    function mostrarSeccion(id) {
      const secciones = document.querySelectorAll('.contenido');
      secciones.forEach(sec => sec.classList.remove('visible'));
      const destino = document.getElementById(id);
      destino.classList.add('visible');
      destino.scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>

